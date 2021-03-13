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
MD5 | `449DAAB4CBDB9298FF841FE24B00A927`
SHA1 | `195477A0E2238F56C396C9D43863B6D2BCA54182`
SHA256 | `83A761B12295B06047BE6CA13A142E2B944F7394D6BAEC64956612DC1CE64461`
SHA384 | `A7C963B8A8FAC6110D693EAA3F7434594E221730C66CCCCE74F6270E3E428C8CE04C4289E2E71AA7352956CB966C8B01`
SHA512 | `543EFC28CA37AEF8D66B3044F025267E7AF9D539AF9908EC205B1927D1458722F307B916ED5D8241C58195EE62AA1F79AB347AF7A540F3EE84A860E42F05296C`
SSDEEP | `12288:vwGGEy0sw6uJeIcxsDKHZ1L8ZzbcUUOevJec2HywPQWt:oGGE3l6IbcxsDshibcHOevJecyhPz`
IMP | `C8DD8BDD184BD81C95776BD2A73DCF11`
PESHA1 | `4654A2B36F79610DE03764C5578E97A652F96430`
PE256 | `F99823C97D5BDF51DAEE52131E0C99443EB6B2436B02C36C60B427D8C1337F85`

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
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: WerFault.exe
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.630 (WinBuild.160101.0800)
* Product Version: 10.0.19041.630
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/76
* VirusTotal Link: https://www.virustotal.com/gui/file/83a761b12295b06047be6ca13a142e2b944f7394d6baec64956612dc1ce64461/detection

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Windows\SysWOW64\WerFault.exe](WerFault.exe-B104A868C53A6A59807AD86722A58C84.md) | 85

## Possible Misuse

*The following table contains possible examples of `WerFault.exe` being misused. While `WerFault.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_exploit_cve_2020_1350.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_exploit_cve_2020_1350.yml) | `- '\System32\werfault.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_lsass_dump.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_lsass_dump.yml) | `Image\|endswith: '\werfault.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_wmiprvse_spawning_process.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_wmiprvse_spawning_process.yml) | `- '\WerFault.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020-2021 Strontic.


