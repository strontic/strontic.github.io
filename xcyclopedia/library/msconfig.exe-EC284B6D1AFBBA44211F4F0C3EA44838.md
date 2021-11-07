---
title: msconfig.exe | System Configuration Utility
excerpt: What is msconfig.exe?
---

# msconfig.exe 

* File Path: `C:\WINDOWS\system32\msconfig.exe`
* Description: System Configuration Utility

## Screenshot

![msconfig.exe](screenshots/msconfig.exe-FA81544250A477790C003D6D88256078-1.png)

## Hashes

Type | Hash
-- | --
MD5 | `EC284B6D1AFBBA44211F4F0C3EA44838`
SHA1 | `109198C4AE353AF8DA0979491C5E975C199F045B`
SHA256 | `E8A61E948E6E3F072BA33E2D5AB1133667646C52E51471C7022B72FF0592DEFB`
SHA384 | `96418B6C0ACDCEF8060C66D8C75C2E58D92A97D0D874B0025739B64291E4EEE1169DBC0FFC84F7EB96D9E0DBBC90D8BF`
SHA512 | `80732EC1F7E211CE984BAF32C0480189384AA2C76E95E1AFC0446F04CA35EB48AF98CB4FED6B30F48B2970CA8A8BE353FFB1EB27D9B253628CBC5A3606D4A5E7`
SSDEEP | `3072:4Y4vQ82v8NLxkoUoi95DQ9oVrBfUd0/HlGJRA1i:ngQV0FkoUoi95c9ofUdSGJRW`

## Signature

* Status: Signature verified.
* Serial: `330000023241FB59996DCC4DFF000000000232`
* Thumbprint: `FF82BC38E1DA5E596DF374C53E3617F7EDA36B06`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: msconfig.EXE.MUI
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.18362.1 (WinBuild.160101.0800)
* Product Version: 10.0.18362.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.


## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Windows\system32\msconfig.exe](msconfig.exe-39009536CAFE30C6EF2501FE46C9DF5E.md) | 47
[C:\windows\system32\msconfig.exe](msconfig.exe-9115A4002D040BF7F16AC1E29F353FB9.md) | 44
[C:\Windows\system32\msconfig.exe](msconfig.exe-C39148DD0D650E2C49095237998218F2.md) | 44
[C:\Windows\system32\msconfig.exe](msconfig.exe-EA390568A41C03B6327AAE1873664B45.md) | 47
[C:\Windows\system32\msconfig.exe](msconfig.exe-FA81544250A477790C003D6D88256078.md) | 43

## Possible Misuse

*The following table contains possible examples of `msconfig.exe` being misused. While `msconfig.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_uac_bypass_msconfig_gui.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/file_event/sysmon_uac_bypass_msconfig_gui.yml) | `title: UAC Bypass Using MSConfig Token Modification - File`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_uac_bypass_msconfig_gui.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/file_event/sysmon_uac_bypass_msconfig_gui.yml) | `description: Detects the pattern of UAC Bypass using a msconfig GUI hack (UACMe 55)`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_uac_bypass_msconfig_gui.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_uac_bypass_msconfig_gui.yml) | `title: UAC Bypass Using MSConfig Token Modification - Process`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_uac_bypass_msconfig_gui.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_uac_bypass_msconfig_gui.yml) | `description: Detects the pattern of UAC Bypass using a msconfig GUI hack (UACMe 55)`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_uac_bypass_msconfig_gui.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_uac_bypass_msconfig_gui.yml) | `CommandLine: '"C:\Windows\system32\msconfig.exe" -5'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Msconfig.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Msconfig.yml) | `Name: Msconfig.exe`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Msconfig.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Msconfig.yml) | `Description: MSConfig is a troubleshooting tool which is used to temporarily disable or re-enable software, device drivers or Windows services that run during startup process to help the user determine the cause of a problem with Windows`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Msconfig.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Msconfig.yml) | `- Command: Msconfig.exe -5`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Msconfig.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Msconfig.yml) | `Usecase: Code execution using Msconfig.exe`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Msconfig.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Msconfig.yml) | `- Path: C:\Windows\System32\msconfig.exe`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Msconfig.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Msconfig.yml) | `- IOC: msconfig.exe executing`{:.highlight .language-yaml} | 
[malware-ioc](https://github.com/eset/malware-ioc) | [nukesped_lazarus](https://github.com/eset/malware-ioc/blob/master/nukesped_lazarus/README.adoc) | `.`msconfig.exe``{:.highlight .language-cmhg} | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)



MIT License. Copyright (c) 2020-2021 Strontic.


