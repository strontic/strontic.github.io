---
title: wuauclt.exe | Windows Update
excerpt: What is wuauclt.exe?
---

# wuauclt.exe 

* File Path: `C:\Windows\system32\wuauclt.exe`
* Description: Windows Update

## Hashes

Type | Hash
-- | --
MD5 | `95E303BF80AECA5A296E519C61F42427`
SHA1 | `B523E0CD46B3E5F6CDCD6F99E8CC9932D9585B9E`
SHA256 | `AC52D02086B83A2FA92E305E1EACD490101D08BE6C47210989BAA192E030DC06`
SHA384 | `9C899FC7C606C6A2B9BF926510CBE2A902F82DAE7496BEBF83A844C066107C44BE2F01D8CBEF3B8F6952D63F4F3E5FEB`
SHA512 | `884A18F68FE328958AD7B0EBA5A13515C517992423CF123DC81D44D0EAC5988771F7958D877997E9BFCA74427F99E2B87EFBCA8A44132164A6928E0368D3F125`
SSDEEP | `1536:HK0TzC8tY6HAqCsd56ncymh7TpkwsZYm+P/:HKE+8tY6H/FPRkLYm+n`

## Runtime Data

### Loaded Modules:

Path |
-- |
C:\Windows\System32\combase.dll |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\RPCRT4.dll |
C:\Windows\System32\ucrtbase.dll |
C:\Windows\system32\wuauclt.exe |


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
* File Version: 10.0.19041.423 (WinBuild.160101.0800)
* Product Version: 10.0.19041.423
* Language: Language Neutral
* Legal Copyright:  Microsoft Corporation. All rights reserved.


## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Windows\system32\wuauclt.exe](wuauclt.exe-11F337850E397E473B3666AFB7AC1D44.md) | 88
[C:\Windows\system32\wuauclt.exe](wuauclt.exe-42B8C692B9A93F2224CA4BA56B99FC37.md) | 68
[C:\Windows\system32\wuauclt.exe](wuauclt.exe-C96893183EBD19B9AE8630EA0FF21B77.md) | 68
[C:\Windows\system32\wuauclt.exe](wuauclt.exe-E97B13E82F4E1ED5918A6C0466E19748.md) | 90

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


