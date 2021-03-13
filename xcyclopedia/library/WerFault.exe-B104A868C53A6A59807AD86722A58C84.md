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
MD5 | `B104A868C53A6A59807AD86722A58C84`
SHA1 | `4F396329A5406584058E344452957322DA65A157`
SHA256 | `49FC3B1FEBD3F56466D930E35B1CB5BE76113CFEE92D721923EC2C8034C8DCF0`
SHA384 | `332AAC70D8EAC240FAA405E631309878037C1C8DC7A36E1C568F31E93C1A39D2CE84303A874EFB179872798E5021845A`
SHA512 | `2E535F27A283CA84A38DB722F4ACC3E3934E260C264C08E81D447200A493E46EF0A3266518511AB0665783DC80133D3C45BB7B476EBC2DC0407CC0E6914EC78B`
SSDEEP | `12288:zcGGEOQ1w6uJeIcxsDKHZ1L8ZzbcUUOevJec2Hyw3QWL:gGGE7S6IbcxsDshibcHOevJecyh3V`
IMP | `C8DD8BDD184BD81C95776BD2A73DCF11`
PESHA1 | `71B6D3B02DDC9723EB1CE61205DE5126C186DED2`
PE256 | `B0F6F41D9103830124235D3D9889D1A32FF1D66A6A45E7F16D179A40A6703387`

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
* File Version: 10.0.19041.572 (WinBuild.160101.0800)
* Product Version: 10.0.19041.572
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/75
* VirusTotal Link: https://www.virustotal.com/gui/file/49fc3b1febd3f56466d930e35b1cb5be76113cfee92d721923ec2c8034c8dcf0/detection

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Windows\SysWOW64\WerFault.exe](WerFault.exe-449DAAB4CBDB9298FF841FE24B00A927.md) | 85

## Possible Misuse

*The following table contains possible examples of `WerFault.exe` being misused. While `WerFault.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_exploit_cve_2020_1350.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_exploit_cve_2020_1350.yml) | `- '\System32\werfault.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_lsass_dump.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_lsass_dump.yml) | `Image\|endswith: '\werfault.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_wmiprvse_spawning_process.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_wmiprvse_spawning_process.yml) | `- '\WerFault.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020-2021 Strontic.


