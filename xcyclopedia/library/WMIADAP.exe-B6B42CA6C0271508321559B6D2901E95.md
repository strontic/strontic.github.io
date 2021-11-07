---
title: WMIADAP.exe | WMI Reverse Performance Adapter Maintenance Utility
excerpt: What is WMIADAP.exe?
---

# WMIADAP.exe 

* File Path: `C:\Windows\SysWOW64\wbem\WMIADAP.exe`
* Description: WMI Reverse Performance Adapter Maintenance Utility

## Hashes

Type | Hash
-- | --
MD5 | `B6B42CA6C0271508321559B6D2901E95`
SHA1 | `FF78F05E59E65E3E20C3DAED043EF8FE48577248`
SHA256 | `999113AEE6783853D56F3AA40BD524FC567DF553AEC310C797193704219930D7`
SHA384 | `08E35027B3181A3247C077EEF79E7DDE7013367CB8A3CBC12BAE3A46253FA3E7DDD303357A1444961625DE267786642E`
SHA512 | `7CE5B9E93F80FEE2C8C694B5CC12103539675AF6B1FA12953E65123BA647E0B1C7E6B2121B57C1B19846C99DAC6B153E6E257BD92AFCA1913F633E206B6A5BA9`
SSDEEP | `3072:zp++AOVdnU7EEZ8+NNPyQ3fwyHSZ3du+LLC:zqOVMBrNP/33yZ3duEm`
IMP | `CF3EAAFDB564A5CFF2518D8921F5BC72`
PESHA1 | `66FC617DD2612E02E76F58B2A186A2FCE45BED72`
PE256 | `08C171FA6CAC88FE38924FBC56DFEB144FF311F4FE6FECDE50475F74885B88DD`

## Runtime Data

### Loaded Modules:

Path |
-- |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\wow64.dll |
C:\Windows\System32\wow64cpu.dll |
C:\Windows\System32\wow64win.dll |
C:\Windows\SysWOW64\wbem\WMIADAP.exe |


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: wmicookr.dll
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.17763.1 (WinBuild.160101.0800)
* Product Version: 10.0.17763.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/72
* VirusTotal Link: https://www.virustotal.com/gui/file/999113aee6783853d56f3aa40bd524fc567df553aec310c797193704219930d7/detection/


## Possible Misuse

*The following table contains possible examples of `WMIADAP.exe` being misused. While `WMIADAP.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_wmi_module_load.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/image_load/sysmon_wmi_module_load.yml) | `- '\windows\system32\wbem\WMIADAP.exe'  # https://github.com/SigmaHQ/sigma/issues/1871`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020-2021 Strontic.


