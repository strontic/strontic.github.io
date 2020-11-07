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
MD5 | `E9862685F483002916436CDE77965076`
SHA1 | `C9E03E349DEDE305A5E23E38101BF296EFE3B836`
SHA256 | `4E87E4C2C71B519B402E1D6FBD818AB2EAAB712BFDC61AC741EA9ED8850E7C27`
SHA384 | `83EC7BF54BDA63C2B48CBDD8B22EDF5FCD3D56707A4AA0E0DA73A775A2036AB924F7E4B203F3304FF55D4546AE2EF106`
SHA512 | `703615810AAA4C9BAA5501628D844C4CC17C66FC0B45C398E24E6AD53FEF576357B6FE293473038BBFF12EBE9A75423EC4C32691C9676C5372EF5D5AAF9A0B90`
SSDEEP | `12288:wE2ecBg7D/qSvd889Oe5X+F/LexR1GOIn8Xc2Hyw4:fKBg7D/qSFf9Oe5yS/1GOIn8Xcyh4`
IMP | `DB2005AFC3C908C50B9371AF6F31CE8D`
PESHA1 | `C9AE5E6F43196DB619489952D543F93ED317F7DF`
PE256 | `3205C8776E74751EF82975A2E2D718A791B34B0B10324C69D5041CE3B2E0A7E3`

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
* File Version: 10.0.17763.1518 (WinBuild.160101.0800)
* Product Version: 10.0.17763.1518
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/61
* VirusTotal Link: https://www.virustotal.com/gui/file/4e87e4c2c71b519b402e1d6fbd818ab2eaab712bfdc61ac741ea9ed8850e7c27/detection/


## Possible Misuse

*The following table contains possible examples of `WerFault.exe` being misused. While `WerFault.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_exploit_cve_2020_1350.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_exploit_cve_2020_1350.yml) | `- '\System32\werfault.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_lsass_dump.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_lsass_dump.yml) | `Image\|endswith: '\werfault.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_wmiprvse_spawning_process.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_wmiprvse_spawning_process.yml) | `- '\WerFault.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020 Strontic.


