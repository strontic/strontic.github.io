---
title: autoconv.exe | Auto File System Conversion Utility
excerpt: What is autoconv.exe?
---

# autoconv.exe 

* File Path: `C:\Windows\system32\autoconv.exe`
* Description: Auto File System Conversion Utility

## Hashes

Type | Hash
-- | --
MD5 | `0FAE9437F45C390F9896B108450771E7`
SHA1 | `C47BFC979C7A231F865ECC4B51FE2F7222AD737F`
SHA256 | `E6C20451167B160C70BD03F7FFF6B40B20E69BE567CDDBCFC48A7AA7365FBAA1`
SHA384 | `60F45FDD519831316DDD7FCC2619483AFC730878F054B8D3657C6F4A63F7875423F2FDF9905FE44BDDA1ED29AB37C89D`
SHA512 | `6CD051D47042B47547124F89C92C631D43CE26129E83D0B74CA2B84CBECB9024ABFB873A541A85A4249EC69DECA16282E513AAA776F1EB3BADEFC4436F80CE32`
SSDEEP | `12288:ysM6usYU5/OuoRbd8htoCDYP1zqU9B+FMHpSbqnkq7hgblcE+3r:yL6mPpRbd8gCUP1mUn+FwJgpob`
IMP | `76CB0DCE1BF280D1E33241F6979DFDF6`
PESHA1 | `9097258A8546F37D2EC560136C7AF80784F1500D`
PE256 | `CDD6C944477F22C3F2DA927C559C74FE8CA0FC0001FD93D116AC365815D4347D`

## Signature

* Status: Signature verified.
* Serial: `33000002EC6579AD1E670890130000000002EC`
* Thumbprint: `F7C2F2C96A328C13CDA8CDB57B715BDEA2CBD1D9`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: AUTOCONV.EXE.MUI
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1023 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1023
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/68
* VirusTotal Link: https://www.virustotal.com/gui/file/e6c20451167b160c70bd03f7fff6b40b20e69be567cddbcfc48a7aa7365fbaa1/detection



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


