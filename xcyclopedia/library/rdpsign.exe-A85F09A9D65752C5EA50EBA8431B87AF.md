---
title: rdpsign.exe | Remote Desktop Session Host Server Sign Tool
excerpt: What is rdpsign.exe?
---

# rdpsign.exe 

* File Path: `C:\Windows\system32\rdpsign.exe`
* Description: Remote Desktop Session Host Server Sign Tool

## Hashes

Type | Hash
-- | --
MD5 | `A85F09A9D65752C5EA50EBA8431B87AF`
SHA1 | `578655A959ACB372602B6715E6589DED4AD45032`
SHA256 | `8CB8A09B32C56C8E1C7BCA6B2EF24C9705FB494EC2CA834256B56EC378C90159`
SHA384 | `1F4E7CC7D4C33956489D66202E8527D9885C103989662BB86CB9D2A3BD472D6CC3370AFEBEC08FCD34AFFE726EDF0971`
SHA512 | `781ACB6BBD7FE53A2C6E80839C4C7168A1F0919DF06D296953F7A4F25C891C346041F82F4517941B0C4CAC976A91697002E5A441AAB012674CED8343FD80DC2D`
SSDEEP | `3072:vTzgYNQDMn7EX6T43qmxkr/eQYGYp+d282H/aBKj:XgaQDS7EXl3qmKL5aM2vaB`
IMP | `E3919B702EC45B7A5C0DE4EED6F36CF0`
PESHA1 | `9B8A54EC50BDE2398AEFC0D3DB21D724180C2A0A`
PE256 | `E34646FEEFA5DB332D4D9C5AD536E7A5ED528AD277B6E7293DDBFA93A269BB7B`

## Runtime Data

### Usage (stdout):
```cmhg
All rdp file(s) have been succesfully signed.

```

### Usage (stderr):
```cmhg
NAME

rdpsign [options] [items to sign]

OPTIONS

  /sha256 HASH
       Specified the SHA256 hash of the signing certificate.
  /q
       Quiet mode:  No output when success, minimal output when failed.
  /v
       Verbose mode:  Display all warnings, messages, and status.
  /l
       Test signing and output results without actually replacing any of the inputs.  Ignores when input files are on stdin.



```

### Loaded Modules:

Path |
-- |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\system32\rdpsign.exe |


## Signature

* Status: Signature verified.
* Serial: `33000002EC6579AD1E670890130000000002EC`
* Thumbprint: `F7C2F2C96A328C13CDA8CDB57B715BDEA2CBD1D9`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: TSSignTool.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/74
* VirusTotal Link: https://www.virustotal.com/gui/file/8cb8a09b32c56c8e1c7bca6b2ef24c9705fb494ec2ca834256b56ec378c90159/detection



## Additional Info*

**The information below is copied from [MicrosoftDocs](https://github.com/MicrosoftDocs/windowsserverdocs), which is maintained by [Microsoft](https://opensource.microsoft.com/codeofconduct/). Available under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) license.*

---

## rdpsign

>Applies to: Windows Server 2022, Windows Server 2019, Windows Server 2016, Windows Server 2012 R2, Windows Server 2012

Enables you to digitally sign a Remote Desktop Protocol (.rdp) file.

> [!NOTE]
> To find out what's new in the latest version, see [What's New in Remote Desktop Services in Windows Server](/previous-versions/windows/it-pro/windows-server-2012-r2-and-2012/dn283323(v=ws.11)).

### Syntax

```
rdpsign /sha1 <hash> [/q | /v |] [/l] <file_name.rdp>
```

#### Parameters

| Parameter | Description |
|--|--|
| /sha1 `<hash>` | Specifies the thumbprint, which is the Secure Hash Algorithm 1 (SHA1) hash of the signing certificate that is included in the certificate store. Used in Windows Server 2012 R2 and older. |
| /sha256 `<hash>` | Specifies the thumbprint, which is the Secure Hash Algorithm 256 (SHA256) hash of the signing certificate that is included in the certificate store. Replaces /sha1 in Windows Server 2016 and newer. |
| /q | Quiet mode. No output when the command succeeds and minimal output if the command fails. |
| /v | verbose mode. Displays all warnings, messages, and status. |
| /l | Tests the signing and output results without actually replacing any of the input files. |
| `<file_name.rdp>` | The name of the .rdp file. You must specify the .rdp file (or files) to sign by using the full file name. Wildcard characters are not accepted. |
| /? | Displays help at the command prompt. |

##### Remarks

- The SHA1 or SHA256 certificate thumbprint should represent a trusted .rdp file publisher. To obtain the certificate thumbprint, open the **Certificates** snap-in, double-click the certificate that you want to use (either in the local computer's certificates store or in your personal certificates store), click the **details** tab, and then in the **Field** list, click **Thumbprint**.

    > [!NOTE]
    > When you copy the thumbprint for use with the rdpsign.exe tool, you must remove any spaces.

- The signed output files overwrite the input files.

- If multiple files are specified, and if any of the .rdp files can't be read or written to, the tool continues to the next file.

#### Examples

To sign an .rdp file named *file1.rdp*, navigate to the folder where you saved the .rdp file, and then type:

```
rdpsign /sha1 hash file1.rdp
```

> [!NOTE]
> The *hash* value represents the SHA1 certificate thumbprint, without any spaces.

To test whether digital signing will succeed for an .rdp file without actually signing the file, type:

```
rdpsign /sha1 hash /l file1.rdp
```

To sign multiple .rdp files that are named, *file1.rdp*, *file2.rdp*, and *file3.rdp*, type (including the spaces between file names):

```
rdpsign /sha1 hash file1.rdp file2.rdp file3.rdp
```

### See Also

- [Command-Line Syntax Key](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/command-line-syntax-key.md)

- [Remote Desktop Services (Terminal Services) Command Reference](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/remote-desktop-services-terminal-services-command-reference.md)

---



MIT License. Copyright (c) 2020-2021 Strontic.


