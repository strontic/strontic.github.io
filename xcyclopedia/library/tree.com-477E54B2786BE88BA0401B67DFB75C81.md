---
title: tree.com | Tree Walk Utility
excerpt: What is tree.com?
---

# tree.com 

* File Path: `C:\Windows\system32\tree.com`
* Description: Tree Walk Utility

## Hashes

Type | Hash
-- | --
MD5 | `477E54B2786BE88BA0401B67DFB75C81`
SHA1 | `E1D7C0CF42370B07134D658E555860F08EED5BA6`
SHA256 | `FC306B15135C7A9DDB55C1157ED462C03E2588974FEA3764C89B83E759635AEF`
SHA384 | `D31EF38774DDAF51157B632E4CB26819F660270A9C587B0B4942CC69A89D5E101B41AEB243627CF3D29794FF4865722E`
SHA512 | `E14EE0A46A23D816894388F206EA615907789AB8D877C3854B8B794AC98F73F3121129E1B0541310714F47C41B81704CEC5F817B2CF998DE369670BFADB9D9D4`
SSDEEP | `384:WWeoaloC/n0jSVG0ceRueOtNcI4ywK3bIEWcyW:WVCCM/ZWu5ldzIK`
IMP | `319D2E1D16C6598457BAAED4EC069CE8`
PESHA1 | `ACAEE008B27B25F40DEA78B2CC37DF559BA53DBD`
PE256 | `16D68FC0DD7F60B816FDB39796B279FED26D3AE1EF11F08120CB356CEDC8E89A`

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
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\system32\tree.com |


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
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/76
* VirusTotal Link: https://www.virustotal.com/gui/file/fc306b15135c7a9ddb55c1157ed462c03e2588974fea3764c89b83e759635aef/detection



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


