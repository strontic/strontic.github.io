---
title: WerFault.exe | Windows Problem Reporting
excerpt: What is WerFault.exe?
---

# WerFault.exe 

* File Path: `C:\Windows\SysWOW64\WerFault.exe`
* Description: Windows Problem Reporting

## Hashes

Type | Hash
-- | --
MD5 | `40A149513D721F096DDF50C04DA2F01F`
SHA1 | `60B3F112E9869B8EFE6FC074C1D8C3355091F7B7`
SHA256 | `4906290168DAD75AF6513D93B80CE09692D5285CCDA384E55085D9B5FB46FCF8`
SHA384 | `6FD184FC62A201505C8F76C798A4AAF55C508EB0043E19C0BA828A341C7808CA8E928BDE0128308BED5380FF74A04CD1`
SHA512 | `CC6578D931402A1C2765DC5757D68F6D9CC4AA56C15ACB4DD684547B1C460D08508C0EA6C7BA8B352337F570816A6A66A541C3C4373B3600D476B0CDED0A2882`
SSDEEP | `12288:tJUYE9KZ5RRDECvgQ+I0cY6rDmuyX3Oevt4c2Hyw4tnU4:DUYE9iHRIYgQ+IXXf6X3Oevt4cyh4tU4`
IMP | `C8DD8BDD184BD81C95776BD2A73DCF11`
PESHA1 | `5525A2E8FD8CB8DC9AC05DF9A600DFB4E48C1BFF`
PE256 | `5F6A8E5B251C1EBE2B12692446AFED5EF93DCB1DC5EEAEE846B33ADE807BE553`

## Runtime Data

### Loaded Modules:

Path |
-- |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\wow64.dll |
C:\Windows\System32\wow64cpu.dll |
C:\Windows\System32\wow64win.dll |
C:\Windows\SysWOW64\WerFault.exe |


## Signature

* Status: Signature verified.
* Serial: `33000002EC6579AD1E670890130000000002EC`
* Thumbprint: `F7C2F2C96A328C13CDA8CDB57B715BDEA2CBD1D9`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: WerFault.exe
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1081 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1081
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/73
* VirusTotal Link: https://www.virustotal.com/gui/file/4906290168dad75af6513d93b80ce09692d5285ccda384e55085d9b5fb46fcf8/detection


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


