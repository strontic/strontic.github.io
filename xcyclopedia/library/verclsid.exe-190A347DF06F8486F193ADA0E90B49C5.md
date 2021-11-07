---
title: verclsid.exe | Extension CLSID Verification Host
excerpt: What is verclsid.exe?
---

# verclsid.exe 

* File Path: `C:\Windows\SysWOW64\verclsid.exe`
* Description: Extension CLSID Verification Host

## Hashes

Type | Hash
-- | --
MD5 | `190A347DF06F8486F193ADA0E90B49C5`
SHA1 | `A2C097DB996DCAB5AC01D11DF4DDEEBC7D0F04B6`
SHA256 | `5F6FD0BC72EB2E71918241213E97DCD8FD0DE2887A36BE58B769E8C5A4FF8598`
SHA384 | `4B0FA5DAD679A62173E0D00C5FD5FDE5C8C446991957B830B9F25EDD49A1FBBDAC28157BBA03AF450D77A96503D564B8`
SHA512 | `B7FFC21A13CA5A1C3520F3F1A41E35F313819A58D66F52EF78F7919945C6EB875992FA3C732F8A0E853E90AF32AE59AFF7D65F3CCF5DBF9D91679707A3E2D131`
SSDEEP | `192:K91EQfrn8bEjcTu8qknDtD1MJvgzNq/WSNWEN:KfTbnjcTu8qk5DWJoZSWSNWE`
IMP | `BDC7940F5DE0DB2F5978F34E0BD82FF0`
PESHA1 | `304A8E030B188F081983B5C73B6D79A899F872F7`
PE256 | `06CA864E0F3B2596D7A68FC6748CF6917537DCE0CED0CE9A3445C1A5628635AA`

## Runtime Data

### Loaded Modules:

Path |
-- |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\wow64.dll |
C:\Windows\System32\wow64cpu.dll |
C:\Windows\System32\wow64win.dll |
C:\Windows\SysWOW64\verclsid.exe |


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
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/75
* VirusTotal Link: https://www.virustotal.com/gui/file/5f6fd0bc72eb2e71918241213e97dcd8fd0de2887a36be58b769e8c5a4ff8598/detection


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


