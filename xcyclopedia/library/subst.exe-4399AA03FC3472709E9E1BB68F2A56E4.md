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
MD5 | `4399AA03FC3472709E9E1BB68F2A56E4`
SHA1 | `2467CD11C3E8672B0509641CCDD4A32792B9B76A`
SHA256 | `BF91A26C040417656E389188F291C9FCC8C7BEB4F1A00067D3D3623EF8F3C03C`
SHA384 | `85C5C3FB1B0EE5D186D6E71976446B16187B62014060E01D6FDE7B98668BD8D1AAF8FE9AD9232932FEB3ED6F2CC9A9A5`
SHA512 | `A761ACBFEB619236DA44C222D59834D531E4778764D03ADB0B46307891D9ACBF9D2514227B942A28E07DD82510C6D7111B0D328E3F298D58A0099805415547E0`
SSDEEP | `384:iDqh05jngc5eIJz3owju9M5lsDEJbZWzGW:BS5bgwe8LCmbQERa`
IMP | `657724BEF967C549A066ECF72A628438`
PESHA1 | `22D95BB6A2205E74572BDAC8568A9E6EE366AF33`
PE256 | `A297A81A32129D94FCE4D5B50ADCBA870B631D2761C4A9DEA57041A0CDF52705`

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
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: Subst.Exe.MUI
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/74
* VirusTotal Link: https://www.virustotal.com/gui/file/bf91a26c040417656e389188f291c9fcc8c7beb4f1a00067d3d3623ef8f3c03c/detection



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


