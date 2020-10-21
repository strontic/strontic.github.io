---
title: subst.exe | Subst Utility
excerpt: What is subst.exe?
---

# subst.exe 

* File Path: `C:\Windows\SysWOW64\subst.exe`
* Description: Subst Utility

## Hashes

Type | Hash
-- | --
MD5 | `1CD4F787762A6A3688F02A346F6D5178`
SHA1 | `EA9A28875EF01A07BDC95946305624B427786E7B`
SHA256 | `7825146856DEFE9D7D240585117330A3D6B3BC8E4023FFA94C351CDE6FEB2F39`
SHA384 | `206A561E12D11CC98537056C09689F64169423F7196EFECD54E3DD9EE72DBA73CA64C3F7C126B144D889906CA4BB4DE1`
SHA512 | `C6AFCD8ACF0052BF1DAB22E5FD12FD6855C0E3A085B7484E932D2C1126785F4C222D60F8D0CDFC25B18B7577BD6D6117FFCBAEFABC34E8E52F9796B9E2277B86`
SSDEEP | `192:jGLQZcd/5MFs8B72LItJ6pkhEd3MtcnkxVRXkZWYGWju:rZc55MFbh2A6pkhm3oEuUZWYGWju`
IMP | `7DD76573763F447C2EF4E1C30B281996`
PESHA1 | `09C3D7CF5CD6B26BA6A4D8D2ADB0F5025186C6E2`
PE256 | `9DC542AC72840F389EB0221778253301D6CC06DBAD38AEAEED746080CCB1D8B0`

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
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\wow64.dll |
C:\Windows\System32\wow64cpu.dll |
C:\Windows\System32\wow64win.dll |
C:\Windows\SysWOW64\subst.exe |


## Signature

* Status: Signature verified.
* Serial: `33000001C422B2F79B793DACB20000000001C4`
* Thumbprint: `AE9C1AE54763822EEC42474983D8B635116C8452`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: Subst.Exe
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.17763.1 (WinBuild.160101.0800)
* Product Version: 10.0.17763.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/71
* VirusTotal Link: https://www.virustotal.com/gui/file/7825146856defe9d7d240585117330a3d6b3bc8e4023ffa94c351cde6feb2f39/detection/

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\WINDOWS\SysWOW64\subst.exe](subst.exe-940B29797E1759E5B304C15ED332730B.md) | 47


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


