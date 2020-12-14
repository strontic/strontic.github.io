---
title: MsMpEng.exe | Antimalware Service Executable
excerpt: What is MsMpEng.exe?
---

# MsMpEng.exe 

* File Path: `C:\Program Files\Windows Defender\MsMpEng.exe`
* Description: Antimalware Service Executable

## Hashes

Type | Hash
-- | --
MD5 | `CEDC4E5155D9D48F2922C21EC02419B7`
SHA1 | `82E7FFB4E780BF16F3C42D52E2C6B0A4EF48732C`
SHA256 | `B147CC9A14B92E224C7755D41E0453506F983E7874573F1DF79F3EBF27BED090`
SHA384 | `2C228AF83455013F00172BDD6B3CAACC40BC85CAA37CFC81A2DCBBF4FB4B108348D08DDEC711455356EFA0937B194FC0`
SHA512 | `9B4B23C5C8053526AAA4C85182B88E0CD8BFC8B4F09BBE264E6CD900061F10E77C339072116B6ECE87D2B6BFAC4CAE1211BC93143A766448F5913F12F9F2FFA4`
SSDEEP | `3072:GggdXEoTjiYxqS/Gn35KTen6tk5knppQslDt:GlZEgGYBoFVynpplDt`
IMP | `D3CAE088864F29A1BAAAC62FAD45C882`
PESHA1 | `D959A2A519132A5B0F59ECE03761F8FF07B94EEE`
PE256 | `52AFDDDFF99112215DA2F99EC282948F0792753D760F9FE6D73EA6A9BEB01172`

## Signature

* Status: Signature verified.
* Serial: `33000001C422B2F79B793DACB20000000001C4`
* Thumbprint: `AE9C1AE54763822EEC42474983D8B635116C8452`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: MsMpEng.exe
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 4.18.1807.18075 (GitEnlistment(winpbld).180719-0853)
* Product Version: 4.18.1807.18075
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/70
* VirusTotal Link: https://www.virustotal.com/gui/file/b147cc9a14b92e224c7755d41e0453506f983e7874573f1df79f3ebf27bed090/detection/


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


