---
title: subst.exe | Subst Utility
excerpt: What is subst.exe?
---

# subst.exe 

* File Path: `C:\WINDOWS\SysWOW64\subst.exe`
* Description: Subst Utility

## Hashes

Type | Hash
-- | --
MD5 | `940B29797E1759E5B304C15ED332730B`
SHA1 | `AA3A3FDB3F04561F641E72D40578C8EAE7039997`
SHA256 | `917140098ADF2E6EAEC3ADEAB430FF72E7B0879DCEC9B01245E07373D25A7A0E`
SHA384 | `99E2A0D8354F4E9876F7B5095C1F280FC934AFBCF0964BC60C45A353DF54CBA6F6BEA3B2E92D51A37A89BA5270C91551`
SHA512 | `BD4C44DFFBD3FEE5BC63EA629262F777175DCEC499E07310C97C9E0153FDA05C7C8CCC71025AE0AE41B4CB35DA2BD7D11868A58D1D8A284E6E550F4FABA04621`
SSDEEP | `192:DuXlcd//+t9lePB2WAYtkGpFB0d3MtcnkKVRXkJWeGWNAaX:DMlc5/+tf+4J5GpFBW3oEdUJWeGW5`

## Runtime Data

### Usage (stdout):
```cmhg
Associates a path with a drive letter.

SUBST [drive1: [drive2:]path]
SUBST drive1: /D

  drive1:        Specifies a virtual drive to which you want to assign a path.
  [drive2:]path  Specifies a physical drive and path you want to assign to
                 a virtual drive.
  /D             Deletes a substituted (virtual) drive.

Type SUBST with no parameters to display a list of current virtual drives.

```

## Signature

* Status: Signature verified.
* Serial: `330000023241FB59996DCC4DFF000000000232`
* Thumbprint: `FF82BC38E1DA5E596DF374C53E3617F7EDA36B06`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: Subst.Exe
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.18362.1 (WinBuild.160101.0800)
* Product Version: 10.0.18362.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.


## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Windows\SysWOW64\subst.exe](subst.exe-1CD4F787762A6A3688F02A346F6D5178.md) | 47


## Additional Info*

**The information below is copied from [MicrosoftDocs](https://github.com/MicrosoftDocs/windowsserverdocs), which is maintained by [Microsoft](https://opensource.microsoft.com/codeofconduct/). Available under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) license.*

---

## subst

Associates a path with a drive letter. If used without parameters, **subst** displays the names of the virtual drives in effect.

### Syntax

```
subst [<drive1>: [<drive2>:]<path>]
subst <drive1>: /d
```

#### Parameters

| Parameter | Description |
|--|--|
| `<drive1>:` | Specifies the virtual drive to which you want to assign a path. |
| `[<drive2>:]<path>` | Specifies the physical drive and path that you want to assign to a virtual drive. |
| /d | Deletes a substituted (virtual) drive. |
| /? | Displays help at the command prompt. |

### Remarks

- The following commands don't work and must not be used on drives specified in the **subst** command:

  - [chkdsk command](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/chkdsk.md)

    [diskcomp command](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/diskcomp.md)

    [diskcopy command](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/diskcopy.md)

    [format command](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/format.md)

    [label command](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/label.md)

    [recover command](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/recover.md)

- The `<drive1>` parameter must be within the range that is specified by the **lastdrive** command. If not, **subst** displays the following error message: `Invalid parameter - drive1:`

### Examples

To create a virtual drive z for the path b:\user\betty\forms, type:

```
subst z: b:\user\betty\forms
```

Instead of typing the full path, you can reach this directory by typing the letter of the virtual drive followed by a colon as follows:

```
z:
```

### Additional References

- [Command-Line Syntax Key](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/command-line-syntax-key.md)

---



MIT License. Copyright (c) 2020-2021 Strontic.


