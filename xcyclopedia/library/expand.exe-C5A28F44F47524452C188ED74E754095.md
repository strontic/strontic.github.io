
# expand.exe 

* File Path: `C:\Windows\SysWOW64\expand.exe`
* Description: LZ Expansion Utility
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `C5A28F44F47524452C188ED74E754095`
SHA1 | `A53EAB93D544C278BA065C3DA26508C80E8AAB6E`
SHA256 | `8082B8A2CE8DFCA365A669CE94C439E91D2D5291A513702C0FC93273F2CF9C9C`
SHA384 | `CC6F43831944FB07710AAD447200B3BDF22E18FA1962CAEF86EE0F482832CD66CE58960A49E8FFD7AAEFE457FCFF503F`
SHA512 | `EB593B53D8F3D08472246563E3804926368A2F5689F11EEE35FCC8F8545D5C45CFACFE4D758722784D15FADA66DAD785996DF5EED67608B07C578BDB018620CB`
SSDEEP | `768:bvLfPdgShY2ialKHTiPgnwJIxOaCIVCiGRORizS91PDnyw:bvLndg6YbHOonwJIsJIsa9Dny`

## Runtime Data

### Usage (stdout):
```Batchfile
Microsoft (R) File Expansion Utility
Copyright (c) Microsoft Corporation. All rights reserved.

No destination specified for: help.

```

### Usage (stderr):
```Batchfile

```

### Child Processes:


## Signature

* Status: Signature verified.
* Serial: `33000000BCE120FDD27CC8EE930000000000BC`
* Thumbprint: `E85459B23C232DB3CB94C7A56D47678F58E8E51E`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: expand
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 5.00 (rs1_release.160715-1616)
* Product Version: 5.00
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Windows\SysWOW64\CertEnrollCtrl.exe](CertEnrollCtrl.exe-E24D3DC4B70286411ED6A972A0CA4900.md) | 32
[C:\Windows\SysWOW64\tzutil.exe](tzutil.exe-E2A285FBF3BEB083A8A1336C28197195.md) | 38


## Additional Info*

**The information below is copied from [MicrosoftDocs](https://github.com/MicrosoftDocs/windowsserverdocs), which is maintained by [Microsoft](https://opensource.microsoft.com/codeofconduct/). Available under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) license.*

---

# expand

> Applies to: Windows Server (Semi-Annual Channel), Windows Server 2019, Windows Server 2016, Windows Server 2012 R2, Windows Server 2012

Expands one or more compressed files. You can also use this command to retrieve compressed files from distribution disks.

The **expand** command can also run from the Windows Recovery Console, using different parameters. For more information, see [Windows Recovery Environment (WinRE)](https://docs.microsoft.com/windows-hardware/manufacture/desktop/windows-recovery-environment--windows-re--technical-reference).

## Syntax

```
expand [/r] <source> <destination>
expand /r <source> [<destination>]
expand /i <source> [<destination>]
expand /d <source>.cab [/f:<files>]
expand <source>.cab /f:<files> <destination>
```

### Parameters

| Parameter | Description |
| --------- | ----------- |
| /r | Renames expanded files. |
| source | Specifies the files to expand. *Source* can consist of a drive letter and colon, a directory name, a file name, or a combination of these. You can use wildcards (**&#42;** or **?**). |
| destination | Specifies where files are to be expanded.<p>If *source* consists of multiple files and you don't specify **/r**, the *destination* must be a directory. *Destination* can consist of a drive letter and colon, a directory name, a file name, or a combination of these. Destination `file | path` specification. |
| /i | Renames expanded files but ignores the directory structure. |
| /d | Displays a list of files in the source location. Doesn't expand or extract the files. |
| /f:`<files>` | Specifies the files in a cabinet (.cab) file that you want to expand. You can use wildcards (**&#42;** or **?**). |
| /? | Displays help at the command prompt. |

## Additional References

- [Command-Line Syntax Key](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/command-line-syntax-key.md)

---


MIT License. Copyright (c) 2020 Strontic.


