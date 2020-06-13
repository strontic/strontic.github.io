
# expand.exe 

* File Path: `C:\WINDOWS\SysWOW64\expand.exe`
* Description: LZ Expansion Utility
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `8C2235852F8C2659EB6CA4A0C6B3B3F1`
SHA1 | `A4EC9636DF0A27EE5CBCD360EE17755B3686F026`
SHA256 | `FAC091FDD81D75056CB923A6781E6CCF70693ED7A45CC260AD8B6F29C41D7A71`
SHA384 | `98858AD7224C53B7BD3254351AB737B90A97749CD991E65363CE6CD991E7289AC5B3EF8BA328043D3FEFD9453BA8526D`
SHA512 | `0543F270CCBB0E6E1D09BED03D0510A5E018CF2E795D3A8D03AB71B6DD0BC2D73CE04D3D3A9523C428E063335326D7B56B91EB60A8692BC0DA35312165CA5AE4`
SSDEEP | `768:9FkdwuRjSBialKHjiPg7wI5TadLrai73h/uuVULR/e9jDUnI7J:9FYwuRNHeo7wIZQrt73h/8V/CjDUnI1`

## Runtime Data

### Usage (stdout):
```Batchfile
Microsoft (R) File Expansion Utility
Copyright (c) Microsoft Corporation. All rights reserved.

Expands one or more compressed files.

EXPAND [-R] Source Destination
EXPAND -R Source [Destination]
EXPAND -I Source [Destination]
EXPAND -D Source.cab [-F:Files]
EXPAND Source.cab -F:Files Destination

  -R		Rename expanded files.
  -I		Rename expanded files but ignore directory structure.
  -D		Display list of files in source.
  Source	Source file specification.  Wildcards may be used.
  -F:Files	Name of files to expand from a .CAB.
  Destination	Destination file | path specification.
		Destination may be a directory.
		If Source is multiple files and -r is not specified,
		Destination must be a directory.

```

### Usage (stderr):
```Batchfile

```

### Child Processes:


## Signature

* Status: Signature verified.
* Serial: `330000023241FB59996DCC4DFF000000000232`
* Thumbprint: `FF82BC38E1DA5E596DF374C53E3617F7EDA36B06`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: expand
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 5.00 (WinBuild.160101.0800)
* Product Version: 5.00
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.


## Additional Info

*Source: [MicrosoftDocs](https://github.com/MicrosoftDocs/windowsserverdocs) by [Microsoft](https://opensource.microsoft.com/codeofconduct/), available under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) license. Some links modified.*

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


