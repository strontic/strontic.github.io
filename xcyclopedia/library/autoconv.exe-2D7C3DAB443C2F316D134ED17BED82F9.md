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
MD5 | `2D7C3DAB443C2F316D134ED17BED82F9`
SHA1 | `93BBC8180D0B8354EA00D73E514CBDE41F631EF5`
SHA256 | `9DDA6341087E07B7C50E3C1816B7076C2D7B2BE7D281C231F99144FC144A11A4`
SHA384 | `C5AA282ABE821FD84708D478904A02466EE1EE8A984AFE537B7D7667CDBF6E19BE643F138A4504501F45EAB19455F2DA`
SHA512 | `34FD16816438B58FC1B7DD7A6194A0DD602DF1B5DA66F155F63B95DCC34E72270ADE4F48C23887DD4EFBB227DD9F91AC87FC5802CF6AD36FD7CCB2CF84102DB3`
SSDEEP | `24576:fqDKn0C4VusZpMZFHB0JIX0/RtWh48U8R3:fKCN4SvHBu7/RYhBU8R3`
IMP | `AC2AA7C2A531F2F88A81ABC0EB309F2A`
PESHA1 | `36301B4911DEC8A9F363E730998132CE5410BC5E`
PE256 | `E72D3C41537B03460ED8A9AB685F43D0BF8374331434A104740E9498F98781FC`

## Signature

* Status: Signature verified.
* Serial: `330000026551AE1BBD005CBFBD000000000265`
* Thumbprint: `E168609353F30FF2373157B4EB8CD519D07A2BFF`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: AUTOCONV.EXE
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/71
* VirusTotal Link: https://www.virustotal.com/gui/file/9dda6341087e07b7c50e3c1816b7076c2d7b2be7d281c231f99144fc144a11a4/detection/



## Additional Info*

**The information below is copied from [MicrosoftDocs](https://github.com/MicrosoftDocs/windowsserverdocs), which is maintained by [Microsoft](https://opensource.microsoft.com/codeofconduct/). Available under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) license.*

---

## autoconv

> Applies to: Windows Server (Semi-Annual Channel), Windows Server 2019, Windows Server 2016, Windows Server 2012 R2, Windows Server 2012

Converts file allocation table (Fat) and Fat32 volumes to the NTFS file system, leaving existing files and directories intact at startup after **autochk** runs. volumes converted to the NTFS file system cannot be converted back to Fat or Fat32.

> [!IMPORTANT]
> You can't run **autoconv** from the command-line. This can only run at startup, if set through **convert.exe**.

### Additional References

- [Command-Line Syntax Key](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/command-line-syntax-key.md)

- [autochk command](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/autochk.md)

- [convert command](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/convert.md)

---



MIT License. Copyright (c) 2020 Strontic.


