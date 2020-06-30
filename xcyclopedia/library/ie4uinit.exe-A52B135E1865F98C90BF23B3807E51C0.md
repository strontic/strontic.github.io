---
title: ie4uinit.exe | IE Per-User Initialization Utility
---

# ie4uinit.exe 

* File Path: `C:\Windows\system32\ie4uinit.exe`
* Description: IE Per-User Initialization Utility
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `A52B135E1865F98C90BF23B3807E51C0`
SHA1 | `BF142E7FA17591BAF7D97E342781C8BCA8545C63`
SHA256 | `46A3D721ADB36114A5141E5795E4DFC02644FDF8F6C602BCCFDC057784F29DB0`
SHA384 | `5AA92BCDD9D69BC129DE2444F3CEDCBE9F9E548C0238A7112B83BC87EF120123F60A7BA228F9C5301D04AAF76617B6A5`
SHA512 | `E97A8803B343677A15D2F84E161AA0A2C1C424FC973E933273768C5EB9F21C354F506AF396879C4B59145CFF83E28F0636446A11AB61A240AE36335DC47584E2`
SSDEEP | `6144:2wFUGsVC9US0r+ELOC2esAfxd4beLQ+V5h6X:2wuhVw01OCtfz4bexy`

## Runtime Data

### Usage (stdout):
```Batchfile

```

### Usage (stderr):
```Batchfile

```

### Child Processes:


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: IE4UINIT.EXE.MUI
* Product Name: Internet Explorer
* Company Name: Microsoft Corporation
* File Version: 11.00.17763.1 (WinBuild.160101.0800)
* Product Version: 11.00.17763.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.


## Possible Misuse

*The following table contains possible examples of `ie4uinit.exe` being misused. While `ie4uinit.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Ie4uinit.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Ie4uinit.yml) | `Name: Ie4uinit.exe` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Ie4uinit.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Ie4uinit.yml) | `  - Command: ie4uinit.exe -BaseSettings` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Ie4uinit.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Ie4uinit.yml) | `    Description: Executes commands from a specially prepared ie4uinit.inf file.` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Ie4uinit.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Ie4uinit.yml) | `  - Path: c:\windows\system32\ie4uinit.exe` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Ie4uinit.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Ie4uinit.yml) | `  - Path: c:\windows\sysWOW64\ie4uinit.exe` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Ie4uinit.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Ie4uinit.yml) | ` - IOC: ie4uinit.exe loading a inf file from outside %windir%` | 
[malware-ioc](https://github.com/eset/malware-ioc) | [nukesped_lazarus](https://github.com/eset/malware-ioc/blob/master/nukesped_lazarus/README.adoc) | `.`IE4UINIT.exe`` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)



MIT License. Copyright (c) 2020 Strontic.


