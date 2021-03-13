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
MD5 | `B5A7F34701B56588E883679DFFF94974`
SHA1 | `692695B128435BD941D19B2241EF6121803966E7`
SHA256 | `D58172FFC44BC94722C950984D056919739FDFF69EAB646A06F499CB137204F6`
SHA384 | `92AE9C45B04040700DEF13C18EAF0F9C51FA185420EE048601FA3E9771E83F3531C7636D865782BF62785ACA6B53174D`
SHA512 | `A31CDB09B153516658017D5D7541EF8169BC168F413C82FF7C345706CC9233072AA0E9752A18C30A08AB5A4D95C1B0642B9224E06BC3170CB941084FC046264C`
SSDEEP | `1536:zLw3MR+4Owb0KL4cVr89b8u6XI52CLV1Ss3Nisj18XFf+tLt1wO8fHlXi2Wcn:oMg+oLbA452M1SqL1WmFl8fHE2W8`
IMP | `93E7CBA8D80F69855D2E770C0795E77F`
PESHA1 | `265974455178D3D40EB7637E666D1045036D1BC5`
PE256 | `60053A42B9A993A92C53C1D45165863A322AFD4860C21A44308139A25F01F77D`

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

## Signature

* Status: Signature verified.
* Serial: `33000001C422B2F79B793DACB20000000001C4`
* Thumbprint: `AE9C1AE54763822EEC42474983D8B635116C8452`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: TSSignTool.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.17763.1 (WinBuild.160101.0800)
* Product Version: 10.0.17763.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/72
* VirusTotal Link: https://www.virustotal.com/gui/file/d58172ffc44bc94722c950984d056919739fdff69eab646a06f499cb137204f6/detection/



## Additional Info*

**The information below is copied from [MicrosoftDocs](https://github.com/MicrosoftDocs/windowsserverdocs), which is maintained by [Microsoft](https://opensource.microsoft.com/codeofconduct/). Available under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) license.*

---

## rdpsign

> Applies to: Windows Server (Semi-Annual Channel), Windows Server 2019, Windows Server 2016, Windows Server 2012 R2, Windows Server 2012

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


