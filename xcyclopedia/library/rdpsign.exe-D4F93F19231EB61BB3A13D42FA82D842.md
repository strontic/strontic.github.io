---
title: rdpsign.exe | Remote Desktop Session Host Server Sign Tool
---

# rdpsign.exe 

* File Path: `C:\Windows\system32\rdpsign.exe`
* Description: Remote Desktop Session Host Server Sign Tool

## Hashes

Type | Hash
-- | --
MD5 | `D4F93F19231EB61BB3A13D42FA82D842`
SHA1 | `86593DFC765698F3339EA3CF9047EA4F35F96ACA`
SHA256 | `B75813377FD6FF39421158DD1E1EF7B5AEE175F427D516596410534006BD369A`
SHA384 | `4FB6BDE3ECB408B83521820FF72147B06874C67D601A007E94C7A52FDD509BB39B0D5538D2A9266532470DA2B14FC9DD`
SHA512 | `9AB365C956B1CC295C23BAC6C39E0B289EFFC7F4871F31A089907FCAC1C8051C2D5E991EA731AD76D9922FDAB1C2CA44F2F5284646F71087C578015B4233B47C`
SSDEEP | `1536:i1gg2lY1dflxnezx0Xr4mnLPnu/UQqKklhNVg68XPU1PTbg0sO80DhGBNqS:Lg2lQdn1Xr4mLPyUQmVsPURXg0580DU3`

## Runtime Data

### Usage (stdout):
```Batchfile
All rdp file(s) have been succesfully signed.

```

### Usage (stderr):
```Batchfile
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
* Serial: `33000000BCE120FDD27CC8EE930000000000BC`
* Thumbprint: `E85459B23C232DB3CB94C7A56D47678F58E8E51E`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: TSSignTool.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.14393.0 (rs1_release.160715-1616)
* Product Version: 10.0.14393.0
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.



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



MIT License. Copyright (c) 2020 Strontic.


