---
title: subst.exe | Subst Utility
excerpt: What is subst.exe?
---

# subst.exe 

* File Path: `C:\Windows\system32\subst.exe`
* Description: Subst Utility

## Hashes

Type | Hash
-- | --
MD5 | `4BFB2ED4A3F52E323F3AE31F3C3A08AC`
SHA1 | `BB8D85B8CE05AF67A0CDA65F25EFD86748E3E1FF`
SHA256 | `899A5E7E86B1B9F63A1D5E8C63F93C28565528B25EB6C7199B85A0FD69D79AD1`
SHA384 | `E67D1DB36DB9BB60BDA1F2D6C9F62D57084A1505332ED3CBDBABA27DE258BFC750D2B52FFBA486EBA5B74C7F003050BA`
SHA512 | `1D262C243E47E9DCF2FBFA176E7D397D8E1E11CEA240198C37B5BFC853C2444B1D4A6A5A5D9672BF337D9171590DDDF9F106CC9C027A8364E20E7D066C16543B`
SSDEEP | `192:aL9CaXjtsVIoPNPeXj2UC32DWtKayvOc1OCS+3SFzGGVj4/iqmpWYGW:s9B2siUwy7lvp1Viz/jFnpWYGW`
IMP | `657724BEF967C549A066ECF72A628438`
PESHA1 | `D886FA8AEB4CD5FE8F2C9C2DCC91B526F312B347`
PE256 | `BED605200A2F5E035F06850AFBC5F8CA3C974BF6F1F57393D45686EF2A19AB5F`

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

### Loaded Modules:

Path |
-- |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\system32\subst.exe |


## Signature

* Status: Signature verified.
* Serial: `33000001C422B2F79B793DACB20000000001C4`
* Thumbprint: `AE9C1AE54763822EEC42474983D8B635116C8452`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: Subst.Exe.MUI
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.17763.1 (WinBuild.160101.0800)
* Product Version: 10.0.17763.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/68
* VirusTotal Link: https://www.virustotal.com/gui/file/899a5e7e86b1b9f63a1d5e8c63f93c28565528b25eb6c7199b85a0fd69d79ad1/detection/

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\WINDOWS\system32\subst.exe](subst.exe-E34A0B167101310F0949BCA9BC2DD9EE.md) | 52


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



MIT License. Copyright (c) 2020 Strontic.


