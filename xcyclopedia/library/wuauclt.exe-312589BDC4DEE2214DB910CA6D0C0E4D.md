﻿---
title: wuauclt.exe | Windows Update
excerpt: What is wuauclt.exe?
---

# wuauclt.exe 

* File Path: `C:\WINDOWS\system32\wuauclt.exe`
* Description: Windows Update

## Hashes

Type | Hash
-- | --
MD5 | `312589BDC4DEE2214DB910CA6D0C0E4D`
SHA1 | `A585051E833098A3DC04E6A471A4B3B6BCE08172`
SHA256 | `62AFF13B933C69C3CF2DBC4D29FE2D7C19E15226D65652455726B08BE66AD94C`
SHA384 | `93082F4A65005E51D3BF659670A98E2C99ACCC87D6A1594A2192511A3549F97497580CB5B7B6F499434988796DC321A2`
SHA512 | `FF470D99B190A7E691367AB7E5A0D6513B669BD214360B958F79ED0704DD9F3612537F4CE1B2BD4038A064B46748A6915C1A23255D8210864C974A36195DA593`
SSDEEP | `768:/Ul/9UyG1qzF8vHPP12MTnKXKh16KwdOjOvixrH6KRUQGFMP0GasceHTMixx44zU:/e/9DYvdt17i0Dep2c7WNVexfNR+3EPJ`

## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: wuauclt.exe
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.18362.836 (WinBuild.160101.0800)
* Product Version: 10.0.18362.836
* Language: Language Neutral
* Legal Copyright:  Microsoft Corporation. All rights reserved.



## Possible Misuse

*The following table contains possible examples of `wuauclt.exe` being misused. While `wuauclt.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_wuauclt_network_connection.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/network_connection/sysmon_wuauclt_network_connection.yml) | `title: Wuauclt Network Connection`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_wuauclt_network_connection.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/network_connection/sysmon_wuauclt_network_connection.yml) | `description: Detects the use of the Windows Update Client binary (wuauclt.exe) to proxy execute code and making a network connections. One could easily make the DLL spawn a new process and inject to it to proxy the network connection and bypass this rule.`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_wuauclt_network_connection.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/network_connection/sysmon_wuauclt_network_connection.yml) | `- https://dtm.uk/wuauclt/`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_wuauclt_network_connection.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/network_connection/sysmon_wuauclt_network_connection.yml) | `Image\|contains: wuauclt`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_wuauclt_network_connection.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/network_connection/sysmon_wuauclt_network_connection.yml) | `- Legitimate use of wuauclt.exe over the network.`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_proxy_execution_wuauclt.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/sysmon_proxy_execution_wuauclt.yml) | `title: Proxy Execution via Wuauclt`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_proxy_execution_wuauclt.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/sysmon_proxy_execution_wuauclt.yml) | `description: Detects the use of the Windows Update Client binary (wuauclt.exe) to proxy execute code.`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_proxy_execution_wuauclt.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/sysmon_proxy_execution_wuauclt.yml) | `- https://dtm.uk/wuauclt/`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_proxy_execution_wuauclt.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/sysmon_proxy_execution_wuauclt.yml) | `- Image\|contains: wuauclt`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_proxy_execution_wuauclt.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/sysmon_proxy_execution_wuauclt.yml) | `- OriginalFileName: wuauclt.exe`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_lolbas_execution_of_wuauclt.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_lolbas_execution_of_wuauclt.yml) | `title: Monitoring Wuauclt.exe For Lolbas Execution Of DLL`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_lolbas_execution_of_wuauclt.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_lolbas_execution_of_wuauclt.yml) | `description: Adversaries can abuse wuauclt.exe (Windows Update client) to run code execution by specifying an arbitrary DLL.`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_lolbas_execution_of_wuauclt.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_lolbas_execution_of_wuauclt.yml) | `- https://dtm.uk/wuauclt/`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_lolbas_execution_of_wuauclt.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_lolbas_execution_of_wuauclt.yml) | `CommandLine\|re: '(?i)wuauclt\.exe.*\/UpdateDeploymentProvider.*\/Runhandlercomserver'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_spoolsv_child_processes.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_spoolsv_child_processes.yml) | `- \wuauclt.exe`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_wuauclt.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_wuauclt.yml) | `description: Detects code execution via the Windows Update client (wuauclt)`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_wuauclt.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_wuauclt.yml) | `- https://dtm.uk/wuauclt/`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_wuauclt.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_wuauclt.yml) | `- '\wuauclt.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Wuauclt.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Wuauclt.yml) | `Name: wuauclt.exe`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Wuauclt.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Wuauclt.yml) | `- Command: wuauclt.exe /UpdateDeploymentProvider <Full_Path_To_DLL> /RunHandlerComServer`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Wuauclt.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Wuauclt.yml) | `- Path: C:\Windows\System32\wuauclt.exe`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Wuauclt.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Wuauclt.yml) | `- IOC: wuauclt run with a parameter of a DLL path`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Wuauclt.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Wuauclt.yml) | `- Link: https://dtm.uk/wuauclt/`{:.highlight .language-yaml} | 
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_putterpanda.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_putterpanda.yar) | $x0 = "WUAUCLT.EXE" fullword wide /* PEStudio Blacklist: strings */ /* score: '20.01' */ | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)



MIT License. Copyright (c) 2020-2021 Strontic.


