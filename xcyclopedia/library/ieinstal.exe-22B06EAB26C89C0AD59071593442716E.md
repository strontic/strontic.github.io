---
title: ieinstal.exe | Internet Explorer Add-on Installer
excerpt: What is ieinstal.exe?
---

# ieinstal.exe 

* File Path: `C:\Program Files (x86)\Internet Explorer\ieinstal.exe`
* Description: Internet Explorer Add-on Installer

## Hashes

Type | Hash
-- | --
MD5 | `22B06EAB26C89C0AD59071593442716E`
SHA1 | `1DFE3E2B0BDAC0E4B8C62652D1749E0190058268`
SHA256 | `AD5DCBE9F92C6DA4CA09226C93B570F918014D7FB596A7AE402459AB32EA3658`
SHA384 | `5876754005614D54FF17C94B490074CCB4265732221341383E5F7213D6F149689930BE909C744199E48704796D22D4A3`
SHA512 | `B7525FC23EF95F7F509F2C0558747497D7542E7385B01641AD2D24D41183EA567880848D9B9FB6ED13AD2F027ED3751203B23A64B9DB63E6FD7C49930A0C3CB2`
SSDEEP | `6144:WkzBUBwEw1rOt9pdYamXnrdbMKw7w1rOt9pdYamXnrdbMKww:WkNdn5OLpdNIrd4Ds5OLpdNIrd4Dw`
IMP | `9F36C0AED915A5B7F4A6DB6667FCB4C6`
PESHA1 | `AE23A867503593DE30E163B0A2F7A3ECCBA52A1D`
PE256 | `D3E108BA141FB42BB59C6AEC4AE14B4CB924B1329CA8498088B6EBFABC2280B5`

## Runtime Data

### Loaded Modules:

Path |
-- |
C:\Program Files (x86)\Internet Explorer\ieinstal.exe |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\wow64.dll |
C:\Windows\System32\wow64cpu.dll |
C:\Windows\System32\wow64win.dll |


## Signature

* Status: Signature verified.
* Serial: `33000001C422B2F79B793DACB20000000001C4`
* Thumbprint: `AE9C1AE54763822EEC42474983D8B635116C8452`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: ieinstal.exe.mui
* Product Name: Internet Explorer
* Company Name: Microsoft Corporation
* File Version: 11.00.17763.1 (WinBuild.160101.0800)
* Product Version: 11.00.17763.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/69
* VirusTotal Link: https://www.virustotal.com/gui/file/ad5dcbe9f92c6da4ca09226c93b570f918014d7fb596a7ae402459ab32ea3658/detection/

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Program Files (x86)\Internet Explorer\ieinstal.exe](ieinstal.exe-7871873BABCEA94FBA13900B561C7C55.md) | 85
[C:\Program Files (x86)\Internet Explorer\ielowutil.exe](ielowutil.exe-650FE7460630188008BF8C8153526CEB.md) | 60
[C:\Program Files (x86)\Internet Explorer\ielowutil.exe](ielowutil.exe-CE5D25E64B5CB96681659196EB6147E9.md) | 58
[C:\Program Files\internet explorer\ieinstal.exe](ieinstal.exe-58646B0C0417C0E01BECB6C922C0C10A.md) | 82
[C:\Program Files\Internet Explorer\ieinstal.exe](ieinstal.exe-C9EDD394EB4D0996EE43CB67563DF50C.md) | 83
[C:\Program Files\internet explorer\ielowutil.exe](ielowutil.exe-97484E82D101785A7BE817FCF9C4CBD3.md) | 57
[C:\Program Files\Internet Explorer\ielowutil.exe](ielowutil.exe-D831180F7596E0D2BB87B2CC57ECFCA2.md) | 57

## Possible Misuse

*The following table contains possible examples of `ieinstal.exe` being misused. While `ieinstal.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_uac_bypass_ieinstal.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/file_event/sysmon_uac_bypass_ieinstal.yml) | `title: UAC Bypass Using IEInstal - File`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_uac_bypass_ieinstal.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/file_event/sysmon_uac_bypass_ieinstal.yml) | `description: Detects the pattern of UAC Bypass using IEInstal.exe (UACMe 64)`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_uac_bypass_ieinstal.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/file_event/sysmon_uac_bypass_ieinstal.yml) | `Image: 'C:\Program Files\Internet Explorer\IEInstal.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_uac_bypass_ieinstal.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_uac_bypass_ieinstal.yml) | `title: UAC Bypass Using IEInstal - Process`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_uac_bypass_ieinstal.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_uac_bypass_ieinstal.yml) | `description: Detects the pattern of UAC Bypass using IEInstal.exe (UACMe 64)`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_uac_bypass_ieinstal.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_uac_bypass_ieinstal.yml) | `ParentImage\|endswith: '\ieinstal.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020-2021 Strontic.


