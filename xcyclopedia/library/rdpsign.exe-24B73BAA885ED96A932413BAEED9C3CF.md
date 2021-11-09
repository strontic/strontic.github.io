---
title: rdpsign.exe | Remote Desktop Session Host Server Sign Tool
excerpt: What is rdpsign.exe?
---

# rdpsign.exe 

* File Path: `C:\WINDOWS\system32\rdpsign.exe`
* Description: Remote Desktop Session Host Server Sign Tool

## Hashes

Type | Hash
-- | --
MD5 | `24B73BAA885ED96A932413BAEED9C3CF`
SHA1 | `0E61046D8DE74C493FE9FFD82C03149E6647D920`
SHA256 | `97F3872AB311A5B05419602E0E761F60A25240BE41F275763969DDFB889A1B92`
SHA384 | `B9B13EF9386CDC77D3471FD9295A1A12D168B957A1D38D4A52856B38AD9A6E2132AE0B616788808BFE11A05FCD5A3261`
SHA512 | `25E19B17F2AC434C4165077466D25D3ABBED63275D7D499FA7BDFDAEE63CAB7E2E64CD115BF789D73699B61BB2D0B64706035C3B862AEFE157A5D0CE47EBDC9B`
SSDEEP | `3072:42sSnMmrUfKEtIp8HiRXQyInZQNinkVye8jg7+dG8Eha5pF:4OrCKEap8HiRgfZQNinkVye8jg7MGraL`
IMP | `4543F04476DD9127780628735CE6C490`
PESHA1 | `22741929D2E718D2638E12B4AEFD162566F097B8`
PE256 | `FB4B57415F5F4D26B8F81FAB853DC77542C5865D4E96FB4213A4877C8F450984`

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
C:\WINDOWS\System32\KERNEL32.DLL |
C:\WINDOWS\System32\KERNELBASE.dll |
C:\WINDOWS\SYSTEM32\ntdll.dll |
C:\WINDOWS\system32\rdpsign.exe |


## Signature

* Status: Signature verified.
* Serial: `33000002ED2C45E4C145CF48440000000002ED`
* Thumbprint: `312860D2047EB81F8F58C29FF19ECDB4C634CF6A`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: TSSignTool.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.22000.1 (WinBuild.160101.0800)
* Product Version: 10.0.22000.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/73
* VirusTotal Link: https://www.virustotal.com/gui/file/97f3872ab311a5b05419602e0e761f60a25240be41f275763969ddfb889a1b92/detection



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


