---
title: verclsid.exe | Extension CLSID Verification Host
excerpt: What is verclsid.exe?
---

# verclsid.exe 

* File Path: `C:\WINDOWS\SysWOW64\verclsid.exe`
* Description: Extension CLSID Verification Host

## Hashes

Type | Hash
-- | --
MD5 | `62DF4183B426B5B91A4662DEA1B8012A`
SHA1 | `86AFC4C63EE5F5300338B9365FCC88AFEF58EB85`
SHA256 | `29E65E002297C3E4358354965E062C3A4EB421A7A72C3E8E5AD9982B770AE16E`
SHA384 | `CE18A05DAA450654F7A6A68A68BBF8538AB34C5C6E23D3C6D1CC8EB13896F320618581FB7721E315EEF4FCF185C44B1F`
SHA512 | `09AC400D11E0C4894B1C7F40DC293193D69B5C0650375CEE69F4478B8361EE7B5B95C2B4DE992898F7E56050998DDB186B140B3C539C7B01B79372D260F1757E`
SSDEEP | `192:/1kSl1oRrErsjucqEnDoD1MJVRAqnWnNW:tSmrsjucqEcDWJESWnNW`

## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: verclsid.exe
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.18362.1 (WinBuild.160101.0800)
* Product Version: 10.0.18362.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.



## Possible Misuse

*The following table contains possible examples of `verclsid.exe` being misused. While `verclsid.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_malware_verclsid_shellcode.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_access/sysmon_malware_verclsid_shellcode.yml) | `title: Malware Shellcode in Verclsid Target Process`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_malware_verclsid_shellcode.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_access/sysmon_malware_verclsid_shellcode.yml) | `description: Detects a process access to verclsid.exe that injects shellcode from a Microsoft Office application / VBA macro`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_malware_verclsid_shellcode.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_access/sysmon_malware_verclsid_shellcode.yml) | `TargetImage\|endswith: '\verclsid.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [process_creation_lolbins_by_office_applications.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/process_creation_lolbins_by_office_applications.yml) | `- 'verclsid'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [process_creation_lolbins_with_wmiprvse_parent_process.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/process_creation_lolbins_with_wmiprvse_parent_process.yml) | `- 'verclsid'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [process_creation_office_from_proxy_executing_regsvr32_payload.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/process_creation_office_from_proxy_executing_regsvr32_payload.yml) | `- 'verclsid'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [process_creation_office_from_proxy_executing_regsvr32_payload2.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/process_creation_office_from_proxy_executing_regsvr32_payload2.yml) | `- '*verclsid*'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_verclsid_runs_com.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_verclsid_runs_com.yml) | `title: Verclsid.exe Runs COM Object`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_verclsid_runs_com.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_verclsid_runs_com.yml) | `description: Detects when verclsid.exe is used to run COM object via GUID`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_verclsid_runs_com.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_verclsid_runs_com.yml) | `- https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Verclsid.yml`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_verclsid_runs_com.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_verclsid_runs_com.yml) | `Image\|endswith: '\verclsid.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Verclsid.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Verclsid.yml) | `Name: Verclsid.exe`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Verclsid.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Verclsid.yml) | `- Command: verclsid.exe /S /C {CLSID}`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Verclsid.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Verclsid.yml) | `- Path: C:\Windows\System32\verclsid.exe`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Verclsid.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Verclsid.yml) | `- Path: C:\Windows\SysWOW64\verclsid.exe`{:.highlight .language-yaml} | 
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [index.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Indexes-Markdown/index.md) | - T1218.012 Verclsid [CONTRIBUTE A TEST](https://atomicredteam.io/contributing) | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [windows-index.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Indexes-Markdown/windows-index.md) | - T1218.012 Verclsid [CONTRIBUTE A TEST](https://atomicredteam.io/contributing) | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [matrix.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Matrices/matrix.md) | \|  \|  \|  \|  \| Verclsid [CONTRIBUTE A TEST](https://atomicredteam.io/contributing) \|  \|  \|  \|  \|  \|  \|  \| | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [windows-matrix.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Matrices/windows-matrix.md) | \|  \|  \|  \|  \| Verclsid [CONTRIBUTE A TEST](https://atomicredteam.io/contributing) \|  \|  \|  \|  \|  \|  \|  \| | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)



MIT License. Copyright (c) 2020-2021 Strontic.


