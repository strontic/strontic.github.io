
# expand.exe 

* File Path: `C:\Windows\system32\expand.exe`
* Description: LZ Expansion Utility
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `700328EA375572AA173E72932AAC389E`
SHA1 | `068EA7377D30066A4340F9F7525C56B32F7AA202`
SHA256 | `83EA7A5C7634EEA15F4460417658120E1B2FC2C706B0D3468231FD47266086FC`
SHA384 | `CD8103889FC4597313F764538B665C88FAA138ACEFB64C431D9075A49E212376C244061D21C447D3E802F2807A07E1A7`
SHA512 | `31F03FF8F42F3719BE40EA48B3A68E3D1979A492236C346FC2D8C324F07647AE67E9631799ACDD93E0B3AB4DF8F1C3013E14281DA26B6DE5103EE09EF9ECE146`
SSDEEP | `1536:zXf4VOsHS2ENfKm1TFcdK5fHuYHwrBDn:TQHSHNH1TyeuJn`

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
[C:\Windows\system32\tzutil.exe](tzutil.exe-F152E16FC4FE1EDF606D9DFAD92C5242.md) | 32


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


