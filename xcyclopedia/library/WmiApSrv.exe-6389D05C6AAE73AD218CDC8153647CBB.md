---
title: WmiApSrv.exe | WMI Performance Reverse Adapter
excerpt: What is WmiApSrv.exe?
---

# WmiApSrv.exe 

* File Path: `C:\Windows\system32\wbem\WmiApSrv.exe`
* Description: WMI Performance Reverse Adapter

## Hashes

Type | Hash
-- | --
MD5 | `6389D05C6AAE73AD218CDC8153647CBB`
SHA1 | `E593A6EF16D400B761800BDEE37A4D6364AFCF1D`
SHA256 | `2A05EA2653CE6EE43E02B1CC26530D3292D314BE8D31A4641DE333FA6B093CCA`
SHA384 | `AC1A7C23D9E38500609240045443E30DA2833B181AD63380AB0D0AFD9BEB16F5F2CEB283C750FEDBC7C0C852DADE6E14`
SHA512 | `7109FCB3B640D6B4C8B266FF13D4927CAAA5523155264417404D21DA9A4069E988265F88DBB9A9FB0A696D6B543001AB04923B1BD7DB8D596D39A901927CAF3A`
SSDEEP | `3072:lAiSyaIRNc6IQqHNOQpwLs2Z0PpEXcjZl+7aTnbJUORZp2:lwyaIRNcLDtOPo2Z0Ryc1lhn6ORZp`
IMP | `E91C5A3E92623E396D79A8A599CF25A9`
PESHA1 | `5C6B9931F1C020ECB882B820B43E7767192E8D04`
PE256 | `1D7A0138D99CDB361C769ACA8FE3067003E8102C85874FB61CA558F43EC54593`

## Runtime Data

### Loaded Modules:

Path |
-- |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\System32\msvcrt.dll |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\RPCRT4.dll |
C:\Windows\System32\sechost.dll |
C:\Windows\system32\wbem\WmiApSrv.exe |
C:\Windows\SYSTEM32\wbemcomn.dll |


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: WmiApSrv.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/76
* VirusTotal Link: https://www.virustotal.com/gui/file/2a05ea2653ce6ee43e02b1cc26530d3292d314be8d31a4641de333fa6b093cca/detection


## Possible Misuse

*The following table contains possible examples of `WmiApSrv.exe` being misused. While `WmiApSrv.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_wmi_module_load.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/image_load/sysmon_wmi_module_load.yml) | `- '\WmiAPsrv.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020-2021 Strontic.


