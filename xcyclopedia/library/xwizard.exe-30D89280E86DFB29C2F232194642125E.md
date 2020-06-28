---
title: xwizard.exe | Extensible Wizards Host Process
---

# xwizard.exe 

* File Path: `C:\WINDOWS\system32\xwizard.exe`
* Description: Extensible Wizards Host Process
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `30D89280E86DFB29C2F232194642125E`
SHA1 | `1E437EB24F067A666ED911F40AB459943728752C`
SHA256 | `E3AB3499ADD8BE055DF9741DA2DC5E21C6B00F9A8344999808FDDF48025DF031`
SHA384 | `3C4AAD4D57720840FE01BE440538B988772137CB20CEAD4B9B1B9171F1B26CDC215E0096EA5488631E7F20AE68DD3B5D`
SHA512 | `EE64AFF2EEF4B42FF1D8BD49E820D38265BCAACF400DABCF3C9E4682FBF7E2E0861616EB10A1DA8EBE637C0C8A4E335593201DCD84B5BF747EC90CF3709CDA6F`
SSDEEP | `1536:aQqwlcECPKwnjoF3bVnLVn3g3iBzndURDoq4OZZZLlCIib:aQqrHP9jib3TBznSRD68wb`

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
* Serial: `330000023241FB59996DCC4DFF000000000232`
* Thumbprint: `FF82BC38E1DA5E596DF374C53E3617F7EDA36B06`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: xwizard.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.18362.1 (WinBuild.160101.0800)
* Product Version: 10.0.18362.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Windows\system32\ComputerDefaults.exe](ComputerDefaults.exe-3F032A1BDF4D7DF2F43FE7C0410AC175.md) | 50
[C:\WINDOWS\system32\ComputerDefaults.exe](ComputerDefaults.exe-495F18535BBBA007A18EC5EE708318FE.md) | 50
[C:\Windows\system32\ComputerDefaults.exe](ComputerDefaults.exe-D25A9E160E3B74EF2242023726F15416.md) | 43
[C:\Windows\system32\xwizard.exe](xwizard.exe-30C784340F42DB44A84C7958C240E394.md) | 41
[C:\Windows\system32\xwizard.exe](xwizard.exe-C0CCC55F9E988ACB8B624EFD0EC8B92B.md) | 47
[C:\WINDOWS\SysWOW64\ComputerDefaults.exe](ComputerDefaults.exe-455CCBB47F4BEF02A9E0034859CE59E2.md) | 44
[C:\Windows\SysWOW64\ComputerDefaults.exe](ComputerDefaults.exe-4A007FCF54D0379B75D1FA50F840D62B.md) | 54
[C:\Windows\SysWOW64\ComputerDefaults.exe](ComputerDefaults.exe-CFA65B13918526579371C138108A7DDB.md) | 52
[C:\Windows\SysWOW64\xwizard.exe](xwizard.exe-3C70F039EE4C07511ABD82B5664FB91B.md) | 50
[C:\Windows\SysWOW64\xwizard.exe](xwizard.exe-8581F29C5F84B72C053DBCC5372C5DB6.md) | 47
[C:\WINDOWS\SysWOW64\xwizard.exe](xwizard.exe-CB72CA2B130AA4B776FAF32E18453CF6.md) | 55

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


