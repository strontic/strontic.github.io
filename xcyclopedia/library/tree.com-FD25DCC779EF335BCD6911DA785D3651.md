---
title: tree.com | Tree Walk Utility
excerpt: What is tree.com?
---

# tree.com 

* File Path: `C:\Windows\SysWOW64\tree.com`
* Description: Tree Walk Utility

## Hashes

Type | Hash
-- | --
MD5 | `FD25DCC779EF335BCD6911DA785D3651`
SHA1 | `89242671C7407F8D31E885013F0EF746266E579D`
SHA256 | `C0A2D6B70C92214727DD022DCF0BD80EA2C1DD282EC000F09BC120675817FE3E`
SHA384 | `7370AC0E91503981C81990329AB2BB6EA28C64BC28EC84D045D60493CACCBBF00D16428164A4895C178C3239510717DE`
SHA512 | `3AA6B0338E2C8924441533352949788E743CFA2812EF284DB5C2B03FD2BE486060264896EEBC946DB3E96B42308008492716C79F9EA468D2E44AF0B8298DD141`
SSDEEP | `192:khCd29lqA75yFeyIwHKjvb8mA5vALKW3uL1xkcWcyWekJ:kwwgMAHtHK8mA52KcvcWcyWFJ`
IMP | `70A2F6E664F57CFD7B5D15C3D92CF60F`
PESHA1 | `6D512E80790CB2CFB06BEB76084AA8DD799BE78A`
PE256 | `8E285558D4C1CA7B85536E092C366E61F2E615B035F302514BA6F48FD6761A4C`

## Runtime Data

### Usage (stdout):
```cmhg
Graphically displays the folder structure of a drive or path.

TREE [drive:][path] [/F] [/A]

   /F   Display the names of the files in each folder.
   /A   Use ASCII instead of extended characters.


```

### Loaded Modules:

Path |
-- |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\wow64.dll |
C:\Windows\System32\wow64cpu.dll |
C:\Windows\System32\wow64win.dll |
C:\Windows\SysWOW64\tree.com |


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: TREE.COM
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/76
* VirusTotal Link: https://www.virustotal.com/gui/file/c0a2d6b70c92214727dd022dcf0bd80ea2c1dd282ec000f09bc120675817fe3e/detection



## Additional Info*

**The information below is copied from [MicrosoftDocs](https://github.com/MicrosoftDocs/windowsserverdocs), which is maintained by [Microsoft](https://opensource.microsoft.com/codeofconduct/). Available under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) license.*

---

## tree

Displays the directory structure of a path or of the disk in a drive graphically. The structure displayed by this command depends upon the parameters that you specify at the command prompt. If you don't specify a drive or path, this command displays the tree structure beginning with the current directory of the current drive.

### Syntax

```
tree [<drive>:][<path>] [/f] [/a]
```

#### Parameters

| Parameter | Description |
|--|--|
| `<drive>:` | Specifies the drive that contains the disk for which you want to display the directory structure. |
| `<path>` | Specifies the directory for which you want to display the directory structure. |
| /f | Displays the names of the files in each directory. |
| /a | Specifies to use text characters instead of graphic characters to show the lines that link subdirectories. |
| /? | Displays help at the command prompt. |

### Examples

To display the names of all the subdirectories on the disk in your current drive, type:

```
tree \
```

To display, one screen at a time, the files in all the directories on drive C, type:

```
tree c:\ /f | more
```

To print a list of all the directories on drive C, type:

```
tree c:\ /f  prn
```

### Additional References

- [Command-Line Syntax Key](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/command-line-syntax-key.md)

---



MIT License. Copyright (c) 2020-2021 Strontic.


