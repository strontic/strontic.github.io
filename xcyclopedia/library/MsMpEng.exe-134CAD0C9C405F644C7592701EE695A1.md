---
title: MsMpEng.exe | Antimalware Service Executable
excerpt: What is MsMpEng.exe?
---

# MsMpEng.exe 

* File Path: `C:\ProgramData\Microsoft\Windows Defender\Platform\4.18.2008.9-0\MsMpEng.exe`
* Description: Antimalware Service Executable

## Hashes

Type | Hash
-- | --
MD5 | `134CAD0C9C405F644C7592701EE695A1`
SHA1 | `9D014808CBA7A33B6FA58576734B1074D2301260`
SHA256 | `98F2679F37260CDDBCE40CEFDC2A6F26450B1DD1271F2F43311D61A4A8229C96`
SHA384 | `B84E85BE5D2F1ED5584C470ABE6260858FC67BE5F723713B57646392DF7E715AC8FAE066024258EC13D78A49C993CF7E`
SHA512 | `7B2F5C72521047628C48C00D8B2AB46B657F0815288248A008180DA2967590B81FEFFB2547DC8C3A18FC2F2E127901016A666D7350F9B2D7CF17B37DB737843F`
SSDEEP | `3072:l9vYfT+Tb7MJx/iB+5KTeEr8kHhlqCwRF:lhYb+TbOo4+phPQ`
IMP | `2DFE2B101E95D9803D7B3F7C3C2C42BE`
PESHA1 | `72A65AE6E168471B5934509A67D0411D39AAA6D7`
PE256 | `A671B51F49239EDB0A645F30B5036FD23D4D809237820576D5BAD6B0F49944EB`

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
* File Version: 4.18.2008.9 (WinBuild.160101.0800)
* Product Version: 4.18.2008.9
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/68
* VirusTotal Link: https://www.virustotal.com/gui/file/98f2679f37260cddbce40cefdc2a6f26450b1dd1271f2f43311d61a4a8229c96/detection/

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\ProgramData\Microsoft\Windows Defender\Platform\4.18.2009.7-0\MsMpEng.exe](MsMpEng.exe-F54E7E584C472FFF2B741C05F8CDC766.md) | 77

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


