---
title: autoconv.exe | Auto File System Conversion Utility
excerpt: What is autoconv.exe?
---

# autoconv.exe 

* File Path: `C:\Windows\SysWOW64\autoconv.exe`
* Description: Auto File System Conversion Utility

## Hashes

Type | Hash
-- | --
MD5 | `A705C2ACED7DDB71AFB87C4ED384BED6`
SHA1 | `2BB020F0AD627AD58F9B944356B626B01F4D8CDB`
SHA256 | `9E03F82B733908FF583EC767F2F7FFBC705F01C5E451FA5B6E603FF1B6261F0C`
SHA384 | `CE4685FF24503AB80746A32CF877C91986174A7FEF7EB2975176E14186449E61141CAFBC2497176031D5AD92D5158E48`
SHA512 | `4FD560FAB8863BC056AF811A3F0A30FC2C45FC00375BD59EDEE58DD22967EF8707AAACC113E2EA41CFFC828112A37C7A1699C4E2262329CFC545EF84DB7F1859`
SSDEEP | `24576:zZXvJieMO3wHxKb1aAQPbLdZEVNdU5s4b3:FBMLRiIAQT0TO5s4b`
IMP | `0A22CD34204D8F58411816B6E287736C`
PESHA1 | `D745C7F84FF6C80B5583B3F969ED7745BA7365FC`
PE256 | `E4D81F814C7962F2EDAAAA3790979D7E6AB0013FD76495E04AFD884D0AD11007`

## Signature

* Status: Signature verified.
* Serial: `33000002EC6579AD1E670890130000000002EC`
* Thumbprint: `F7C2F2C96A328C13CDA8CDB57B715BDEA2CBD1D9`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: AUTOCONV.EXE
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1266 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1266
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/73
* VirusTotal Link: https://www.virustotal.com/gui/file/9e03f82b733908ff583ec767f2f7ffbc705f01c5e451fa5b6e603ff1b6261f0c/detection



## Additional Info*

**The information below is copied from [MicrosoftDocs](https://github.com/MicrosoftDocs/windowsserverdocs), which is maintained by [Microsoft](https://opensource.microsoft.com/codeofconduct/). Available under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) license.*

---

## autoconv

>Applies to: Windows Server 2022, Windows Server 2019, Windows Server 2016, Windows Server 2012 R2, Windows Server 2012

Converts file allocation table (Fat) and Fat32 volumes to the NTFS file system, leaving existing files and directories intact at startup after **autochk** runs. volumes converted to the NTFS file system cannot be converted back to Fat or Fat32.

> [!IMPORTANT]
> You can't run **autoconv** from the command-line. This can only run at startup, if set through **convert.exe**.

### Additional References

- [Command-Line Syntax Key](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/command-line-syntax-key.md)

- [autochk command](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/autochk.md)

- [convert command](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/convert.md)

---



MIT License. Copyright (c) 2020-2021 Strontic.


