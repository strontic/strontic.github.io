---
title: xwizard.exe | Extensible Wizards Host Process
---

# xwizard.exe 

* File Path: `C:\windows\system32\xwizard.exe`
* Description: Extensible Wizards Host Process
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `10B8BDC83EF7CFBBD344F2587453AD29`
SHA1 | `AFB419905F2CB4A48714836C5D3D5527A8FD6B80`
SHA256 | `B0C08A32F7F9FF3696DFEB67924D873604F20D7561A0800F39148C7B82552710`
SHA384 | `3E23BB960B5C2378CE90F9C6938ABF10F65AEBD8EEF4DE3709B0149B65D5D4D20C1BAC4BB6393566F04FF7015A44B1D8`
SHA512 | `53CB82832ABA22AAAD8CB7CA8FECBD87A1BA0FED5FEB2C4D87FF56B1C992B1B38D83A32D570A5B06CE26014B05BAAEF44611C1E2509481106441CA4B41C239B4`
SSDEEP | `1536:Cpc6rrqCnPKFuT9lt53gbi1SCDURDoq4OZZZLlCIib:Ca6nhnPmuB53H1BoRD68wb`

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
* Serial: `33000001C422B2F79B793DACB20000000001C4`
* Thumbprint: `AE9C1AE54763822EEC42474983D8B635116C8452`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: xwizard.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.17763.1 (WinBuild.160101.0800)
* Product Version: 10.0.17763.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Windows\system32\ComputerDefaults.exe](ComputerDefaults.exe-3F032A1BDF4D7DF2F43FE7C0410AC175.md) | 52
[C:\WINDOWS\system32\ComputerDefaults.exe](ComputerDefaults.exe-495F18535BBBA007A18EC5EE708318FE.md) | 46
[C:\Windows\system32\ComputerDefaults.exe](ComputerDefaults.exe-AC4C3945A3E6DFFF98145096DA4EDA93.md) | 47
[C:\windows\system32\ComputerDefaults.exe](ComputerDefaults.exe-C18B586CA8F414A47D9CBA263361692B.md) | 60
[C:\Windows\system32\ComputerDefaults.exe](ComputerDefaults.exe-D25A9E160E3B74EF2242023726F15416.md) | 44
[C:\windows\system32\xwizard.exe](xwizard.exe-2AFA70B713D8AF4279C9FDAE7AD08A9D.md) | 52
[C:\Windows\system32\xwizard.exe](xwizard.exe-30C784340F42DB44A84C7958C240E394.md) | 44
[C:\WINDOWS\system32\xwizard.exe](xwizard.exe-30D89280E86DFB29C2F232194642125E.md) | 55
[C:\Windows\system32\xwizard.exe](xwizard.exe-C0CCC55F9E988ACB8B624EFD0EC8B92B.md) | 47
[C:\windows\SysWOW64\ComputerDefaults.exe](ComputerDefaults.exe-1A506E36A76AD897490E77313CD3259A.md) | 57
[C:\WINDOWS\SysWOW64\ComputerDefaults.exe](ComputerDefaults.exe-455CCBB47F4BEF02A9E0034859CE59E2.md) | 47
[C:\Windows\SysWOW64\ComputerDefaults.exe](ComputerDefaults.exe-4A007FCF54D0379B75D1FA50F840D62B.md) | 54
[C:\Windows\SysWOW64\ComputerDefaults.exe](ComputerDefaults.exe-CFA65B13918526579371C138108A7DDB.md) | 47
[C:\Windows\SysWOW64\ComputerDefaults.exe](ComputerDefaults.exe-FF2E0EABBB610CD9D4F06C8C0E33B92F.md) | 46
[C:\Windows\SysWOW64\xwizard.exe](xwizard.exe-3C70F039EE4C07511ABD82B5664FB91B.md) | 54
[C:\Windows\SysWOW64\xwizard.exe](xwizard.exe-759CF84292251AB50E1791CBC0C4E8C5.md) | 54
[C:\windows\SysWOW64\xwizard.exe](xwizard.exe-7E421CBAF3DB19860413EC55C5B03F61.md) | 52
[C:\Windows\SysWOW64\xwizard.exe](xwizard.exe-8581F29C5F84B72C053DBCC5372C5DB6.md) | 47
[C:\WINDOWS\SysWOW64\xwizard.exe](xwizard.exe-CB72CA2B130AA4B776FAF32E18453CF6.md) | 52

## Possible Misuse

*The following table contains possible examples of `xwizard.exe` being misused. While `xwizard.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Xwizard.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Xwizard.yml) | `Name: Xwizard.exe` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Xwizard.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Xwizard.yml) | `  - Command: xwizard RunWizard {00000001-0000-0000-0000-0000FEEDACDC}` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Xwizard.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Xwizard.yml) | `    Description: Xwizard.exe running a custom class that has been added to the registry.` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Xwizard.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Xwizard.yml) | `  - Command: xwizard RunWizard /taero /u {00000001-0000-0000-0000-0000FEEDACDC}` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Xwizard.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Xwizard.yml) | `    Description: Xwizard.exe running a custom class that has been added to the registry. The /t and /u switch prevent an error message in later Windows 10 builds.` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Xwizard.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Xwizard.yml) | `  - Path: C:\Windows\System32\xwizard.exe` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Xwizard.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Xwizard.yml) | `  - Path: C:\Windows\SysWOW64\xwizard.exe` | 



MIT License. Copyright (c) 2020 Strontic.


