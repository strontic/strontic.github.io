---
title: WMIADAP.exe | WMI Reverse Performance Adapter Maintenance Utility
excerpt: What is WMIADAP.exe?
---

# WMIADAP.exe 

* File Path: `C:\WINDOWS\SysWOW64\wbem\WMIADAP.exe`
* Description: WMI Reverse Performance Adapter Maintenance Utility

## Hashes

Type | Hash
-- | --
MD5 | `02D133350FB8468E36E7A2EA37F31158`
SHA1 | `CB078EBD050F4FEC2513AABCCC024D5A00DCE5BC`
SHA256 | `ECEDF979F721786ACCD9B6238212CE5E0FC2702CEA46D25A3F4C7D0A859A44D4`
SHA384 | `7431D57A1D6B33017FD4FB063E90D66FC24BF02D6FFD1C6889F74627C8258DF010C2270B1361BDC61A5FC08775BE5AD4`
SHA512 | `1451AE8C7C1B58320CBCA99E53D4A397192A7D358D658DCA88BA5AADD79BD0F30D6FFD67CEAC0B5DC5859D4EAA4FCD0E094029F71F346D2B96EF2E916681C1FE`
SSDEEP | `3072:Z03iJru+4GyLOjDSbbO0cnvl3X2oeQh2yZ5osAyPN:iku/LQe3nyXDiyZ5os7PN`
IMP | `26C0A363865F31DAE002A17462FEE792`
PESHA1 | `DF6D935BE02931A4029CFDDBDAED4317A39DA09F`
PE256 | `86BCEC7DADF47AEC9F0B41250E3765AD30757C37C09B3EB29F8E80D7BEFFD43C`

## Runtime Data

### Loaded Modules:

Path |
-- |
C:\WINDOWS\SYSTEM32\ntdll.dll |
C:\WINDOWS\System32\wow64.dll |
C:\WINDOWS\System32\wow64base.dll |
C:\WINDOWS\System32\wow64con.dll |
C:\WINDOWS\System32\wow64cpu.dll |
C:\WINDOWS\System32\wow64win.dll |
C:\WINDOWS\SysWOW64\wbem\WMIADAP.exe |


## Signature

* Status: Signature verified.
* Serial: `33000002ED2C45E4C145CF48440000000002ED`
* Thumbprint: `312860D2047EB81F8F58C29FF19ECDB4C634CF6A`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: wmicookr.dll
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.22000.1 (WinBuild.160101.0800)
* Product Version: 10.0.22000.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/73
* VirusTotal Link: https://www.virustotal.com/gui/file/ecedf979f721786accd9b6238212ce5e0fc2702cea46d25a3f4c7d0a859a44d4/detection


## Possible Misuse

*The following table contains possible examples of `WMIADAP.exe` being misused. While `WMIADAP.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_wmi_module_load.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/image_load/sysmon_wmi_module_load.yml) | `- '\windows\system32\wbem\WMIADAP.exe'  # https://github.com/SigmaHQ/sigma/issues/1871`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020-2021 Strontic.


