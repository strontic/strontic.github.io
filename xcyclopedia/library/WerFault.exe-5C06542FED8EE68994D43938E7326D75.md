---
title: WerFault.exe | Windows Problem Reporting
excerpt: What is WerFault.exe?
---

# WerFault.exe 

* File Path: `C:\Windows\system32\WerFault.exe`
* Description: Windows Problem Reporting

## Hashes

Type | Hash
-- | --
MD5 | `5C06542FED8EE68994D43938E7326D75`
SHA1 | `DD5F35048D912997EDB108F80C9D2CE47E3B684A`
SHA256 | `DF42A4557521BACAE0D4982ED804762A2815DC157723725A19304632D9B49204`
SHA384 | `9205394C0D5F7304ABC26F9B8F5FBFB73D1E06519CCEA7BC6BBB52AEF82EF986B0C01FB97A612C6018DE35FC7CCB0896`
SHA512 | `329D8CCA981C4F64DF112830D69166AA3915C14BE794238BCDE363127B437C7B149AE91F372AC63F5B772C7D2B1B7591D288E9C2A3EC334839E8466E960EAB19`
SSDEEP | `12288:kuTjYVUewBKx4hwCbEpr2TOzvRENc2Hyw9:kyon/xqlOzvRwcyh9`
IMP | `A8411DCFB6906C782549D77E5571DC7E`
PESHA1 | `A6A51413C08802CB40F962B306ABAF514E6D7338`
PE256 | `A34A1543617C036B489D4CAAA68EDEDF707C2402A81BECB30C21B38A1EC4F730`

## Runtime Data

### Loaded Modules:

Path |
-- |
C:\Windows\System32\combase.dll |
C:\Windows\system32\CRYPTSP.dll |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\System32\msvcp_win.dll |
C:\Windows\System32\msvcrt.dll |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\OLEAUT32.dll |
C:\Windows\System32\RPCRT4.dll |
C:\Windows\System32\ucrtbase.dll |
C:\Windows\system32\WerFault.exe |


## Signature

* Status: Signature verified.
* Serial: `33000002EC6579AD1E670890130000000002EC`
* Thumbprint: `F7C2F2C96A328C13CDA8CDB57B715BDEA2CBD1D9`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: WerFault.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/73
* VirusTotal Link: https://www.virustotal.com/gui/file/df42a4557521bacae0d4982ed804762a2815dc157723725a19304632d9b49204/detection


## Possible Misuse

*The following table contains possible examples of `WerFault.exe` being misused. While `WerFault.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_suspicious_werfault_connection_outbound.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/builtin/win_suspicious_werfault_connection_outbound.yml) | `title: Suspicious Werfault.exe Network Connection Outbound`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_suspicious_werfault_connection_outbound.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/builtin/win_suspicious_werfault_connection_outbound.yml) | `description: Adversaries can migrate cobalt strike/metasploit/C2 beacons on compromised systems to legitimate werfault.exe process to avoid detection.`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_suspicious_werfault_connection_outbound.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/builtin/win_suspicious_werfault_connection_outbound.yml) | `Image: 'werfault.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_cve_2021_26857_msexchange.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/sysmon_cve_2021_26857_msexchange.yml) | `- 'WerFault.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_bad_opsec_sacrificial_processes.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_bad_opsec_sacrificial_processes.yml) | `description: 'Detects attackers using tooling with bad opsec defaults e.g. spawning a sacrificial process to inject a capability into the process without taking into account how the process is normally run, one trivial example of this is using rundll32.exe without arguments as a sacrificial process (default in CS, now highlighted by c2lint), running WerFault without arguments (Kraken - credit am0nsec), and other examples.'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_bad_opsec_sacrificial_processes.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_bad_opsec_sacrificial_processes.yml) | `Image\|endswith: '\WerFault.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_bad_opsec_sacrificial_processes.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_bad_opsec_sacrificial_processes.yml) | `CommandLine\|endswith: '\WerFault.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_exploit_cve_2020_1350.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_exploit_cve_2020_1350.yml) | `- '\System32\werfault.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_lsass_dump.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_lsass_dump.yml) | `Image\|endswith: '\werfault.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_uac_bypass_consent_comctl32.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_uac_bypass_consent_comctl32.yml) | `Image\|endswith: '\werfault.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_wmiprvse_spawning_process.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_wmiprvse_spawning_process.yml) | `- '\WerFault.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020-2021 Strontic.


