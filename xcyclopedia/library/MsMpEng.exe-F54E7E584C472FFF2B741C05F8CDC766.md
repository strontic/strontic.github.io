---
title: MsMpEng.exe | Antimalware Service Executable
excerpt: What is MsMpEng.exe?
---

# MsMpEng.exe 

* File Path: `C:\ProgramData\Microsoft\Windows Defender\Platform\4.18.2009.7-0\MsMpEng.exe`
* Description: Antimalware Service Executable

## Hashes

Type | Hash
-- | --
MD5 | `F54E7E584C472FFF2B741C05F8CDC766`
SHA1 | `17AC1041F0AF35F7FF6823C326D0AA8F20CD71AA`
SHA256 | `03D99B46FFF022D7B8BDCDF52D25AB21B30F2346E3B388E22804EF5D6E1AE08F`
SHA384 | `BB607F2AD89EC0EAD9DEE8BDBB2357DBE722E7DB5724C9AA6015B7BE8EEBC795AD6DD78C451A49BEFB641A7C5FECE6DE`
SHA512 | `4B7C88FADF7FC989F9C691220EB475C9959A70DA91BD6DE8B16836AB6A52E06A543104380D59B0004E365CB51C92A12846315022A2BCA2143271AD7E886BAB3F`
SSDEEP | `3072:x9vYfT+Tb7MJx/iB+uKTe4BkHhlqCTWaByo:xhYb+TbOo4qhPd`
IMP | `2DFE2B101E95D9803D7B3F7C3C2C42BE`
PESHA1 | `D07319ECEB6750512972B52184717CB4A7250F35`
PE256 | `ACC2D1B7C10FA1ACFAAC9ABA4A808B4092B9E78BF232F3DA4B2AFB78A6719B97`

## Signature

* Status: Signature verified.
* Serial: `330000024A0E8AFDF15C662D2B00000000024A`
* Thumbprint: `96384A7F5F1C438F32E2454697DC6D312A74517B`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows Publisher, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: MsMpEng.exe
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 4.18.2009.7 (WinBuild.160101.0800)
* Product Version: 4.18.2009.7
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/70
* VirusTotal Link: https://www.virustotal.com/gui/file/03d99b46fff022d7b8bdcdf52d25ab21b30f2346e3b388e22804ef5d6e1ae08f/detection/

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\ProgramData\Microsoft\Windows Defender\Platform\4.18.2008.9-0\MsMpEng.exe](MsMpEng.exe-134CAD0C9C405F644C7592701EE695A1.md) | 77

## Possible Misuse

*The following table contains possible examples of `MsMpEng.exe` being misused. While `MsMpEng.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_msmpeng_crash.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/builtin/win_susp_msmpeng_crash.yml) | `- '*MsMpEng.exe*'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_msmpeng_crash.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/builtin/win_susp_msmpeng_crash.yml) | `- MsMpEng.exe can crash when C:\ is full` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_plugx_susp_exe_locations.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_plugx_susp_exe_locations.yml) | `Image: '*\MsMpEng.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_proc_wrong_parent.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_proc_wrong_parent.yml) | `- '*\Windows Defender\\*\MsMpEng.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_svchost.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_svchost.yml) | `- '*\MsMpEng.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_op_cloudhopper.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_op_cloudhopper.yar) | $s1 = "MsMpEng.exe" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)



MIT License. Copyright (c) 2020 Strontic.


