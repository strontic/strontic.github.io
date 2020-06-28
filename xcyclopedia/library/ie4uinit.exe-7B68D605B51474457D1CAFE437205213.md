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
MD5 | `7B68D605B51474457D1CAFE437205213`
SHA1 | `2DAA37A12BA96B6990418460F1D30869E432F125`
SHA256 | `6F83621ED34B61CA0BBAFF5A5FD158FEECA364DE52EEC38E1CC2295A82A7BD5C`
SHA384 | `96D0EEAD8C04662AD3CB5DF188C881292FA28AED20491B039B7C269D05FA5DCAA9898988381AD63ADB74935635E06F02`
SHA512 | `616873A3BCC7A1E78441A9040FD37DFA5F6648347685C1B4198841B64F8E553F82CC28288215B6016602071F5C854D43EFFE0898C552F3A1B6D183479612264F`
SSDEEP | `6144:U3scA4efnKKCR/o6e8cnz/eXTsrqAxWl/s5ZMyQ:U8cAjKd7I7UAx+`

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
* File Version: 11.00.19041.1 (WinBuild.160101.0800)
* Product Version: 11.00.19041.1
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


