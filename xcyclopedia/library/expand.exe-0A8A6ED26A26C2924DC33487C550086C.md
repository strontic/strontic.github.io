
# expand.exe 

* File Path: `C:\WINDOWS\system32\expand.exe`
* Description: LZ Expansion Utility
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `0A8A6ED26A26C2924DC33487C550086C`
SHA1 | `07262F304A0C8D14EAF93BADEE25D52C322BABDB`
SHA256 | `71D931442AA51E3FECB3C014D189E9125E210507BA8ACF8ABE83E5C9F6810FE2`
SHA384 | `E81DB65302882341A1E4D4EF01737159329C05D73F29DF7CA0D49A779BC4E70451E94024583A2C47C186A44AFDEB9DD4`
SHA512 | `F9F14EF5D37B83862DF607E2884673CB35A1C121110BED310C689E581C2E70D67BA24F4C6CC7F25FBD5E26E68B46BE039EE25797B4CA1B65D1C8610407030979`
SSDEEP | `1536:RSmjX43XNNnOeC0c6sIJAo6HuYbwklXKUn:/X0dhOeU4a1lXbn`

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


## Additional Info*

**The information below is copied from [MicrosoftDocs](https://github.com/MicrosoftDocs/windowsserverdocs) by [Microsoft](https://opensource.microsoft.com/codeofconduct/), available under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) license. Some links modified.*

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


