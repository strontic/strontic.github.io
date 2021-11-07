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
MD5 | `7871873BABCEA94FBA13900B561C7C55`
SHA1 | `4A8F6571E59ADC7F7EA8911CA9AB2F1FDA5A13B8`
SHA256 | `A71004C20ABC2216D52137A41B72703841DA8BAB3A97A60EEDF77A37E951609F`
SHA384 | `B36AAC777940925EFB143CB5ECB993042DD5774468826E7414D33E65A66C595CB0BC0A184D1D09BAF2F9ED1C7FF954F8`
SHA512 | `06F8686A7D89A3E1957FA74439CA22743ABFE0994042D082DD24C1BAB7FB5FCC62355C16DF0C216BEB5A007A6087E6AA771428AFE907467F4DC6CF900B58418E`
SSDEEP | `6144:LDYHL0vyBwHw1rOt9pdYamXnrdbMKw7w1rOt9pdYamXnrdbMKwwR:LDGL6Q5OLpdNIrd4Ds5OLpdNIrd4DwR`
IMP | `1CCE32FED1758051BAFEFBB6EF77244E`
PESHA1 | `CB2D46AE9C513316417041D76FC42D8C2C48384A`
PE256 | `A2059A8151910B43E8C48848EC2488820331BD4E3D8D958C2EFA7706953F2658`

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
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: ieinstal.exe.mui
* Product Name: Internet Explorer
* Company Name: Microsoft Corporation
* File Version: 11.00.19041.1 (WinBuild.160101.0800)
* Product Version: 11.00.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/69
* VirusTotal Link: https://www.virustotal.com/gui/file/a71004c20abc2216d52137a41b72703841da8bab3a97a60eedf77a37e951609f/detection/

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Program Files (x86)\Internet Explorer\ieinstal.exe](ieinstal.exe-22B06EAB26C89C0AD59071593442716E.md) | 85
[C:\Program Files (x86)\Internet Explorer\ielowutil.exe](ielowutil.exe-650FE7460630188008BF8C8153526CEB.md) | 57
[C:\Program Files (x86)\Internet Explorer\ielowutil.exe](ielowutil.exe-CE5D25E64B5CB96681659196EB6147E9.md) | 55
[C:\Program Files\internet explorer\ieinstal.exe](ieinstal.exe-58646B0C0417C0E01BECB6C922C0C10A.md) | 82
[C:\Program Files\Internet Explorer\ieinstal.exe](ieinstal.exe-C9EDD394EB4D0996EE43CB67563DF50C.md) | 80
[C:\Program Files\internet explorer\ielowutil.exe](ielowutil.exe-97484E82D101785A7BE817FCF9C4CBD3.md) | 54
[C:\Program Files\Internet Explorer\ielowutil.exe](ielowutil.exe-D831180F7596E0D2BB87B2CC57ECFCA2.md) | 54

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


