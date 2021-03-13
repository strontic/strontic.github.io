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
MD5 | `AD6A0951757BBDFE781DF92C6CD8B7CD`
SHA1 | `33B6E8749390BF7EDC3C07E8855F585281B1CFCD`
SHA256 | `BFE7DC2AB8C610FBA1339A86C7E3C0D8D574A82F17670C31C32C11558000C54E`
SHA384 | `6235D5F5637FCB3827C39E52728E12FE1C6E85D9B1FF30C24037669CB71F561302205891556D11985CC59291514F9FCB`
SHA512 | `FFC44F79878F1244A7F7E91D32257548000742962D640113EB657116C0852BE7DB7A2D7FF10DEE741AF3CC0B5F586CEA9CDA75FDEB88522AB464A8CC677F081B`
SSDEEP | `24576:BT24NzkbRbXN07U7n4xrZND06NfD0wcy6H0zMV:ZzkFG7U7n4xrZlNbcy6UzMV`
IMP | `135495E54FD99DE3B1B5BAD0EB1B49C4`
PESHA1 | `29AF6D9ED0DA50890FDAE5107E80C60F2DC87C99`
PE256 | `D2370649F6794FBFBC021060DB64DC3654C1149F883EE8D250F310982095BB4E`

## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: AUTOCONV.EXE
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.17763.1490 (WinBuild.160101.0800)
* Product Version: 10.0.17763.1490
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: Unknown



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



MIT License. Copyright (c) 2020-2021 Strontic.


