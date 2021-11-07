---
title: NisSrv.exe | Microsoft Network Realtime Inspection Service
excerpt: What is NisSrv.exe?
---

# NisSrv.exe 

* File Path: `C:\ProgramData\Microsoft\Windows Defender\Platform\4.18.2007.8-0\NisSrv.exe`
* Description: Microsoft Network Realtime Inspection Service

## Hashes

Type | Hash
-- | --
MD5 | `091538ABE1B2C0BEFE53EB5DB3BAED89`
SHA1 | `B45833242E79AFDBD77DA9FF01CCE001F9F8516B`
SHA256 | `3AB68DDD04335ED4F5A69EC3ADB56CC80E2F2AB849394C07A21D66BDCBD67FF5`
SHA384 | `C50347F203C0340F6659B679119CA2C7BFE9C58909B0103252AA31665F2E06C8288A528577F3A1F43CDD8183AB0D207F`
SHA512 | `83449B31CEC68981B6000FB11171A47AB6381881596431B90E6177D3E319B8E9CB1D2E8F5120E5F6FBC307D5C99CA6F42A6828872800EC71E5CA17E9B0E7E8EA`
SSDEEP | `49152:mrWcaibdxQ1OHz8Z9SzZ1AAAyQolOM5JeeE2:tKb2Z/2`
IMP | `49CCF316E37B15E05F835D2FCF6BBE52`
PESHA1 | `F3375886A77E6A0504FE6DA142E21A76C4A4CC79`
PE256 | `25995C4F9B21F202D580D58B556FB366A58DAB4B7386CC0900254F230E218FE2`

## Runtime Data

### Loaded Modules:

Path |
-- |
C:\ProgramData\Microsoft\Windows Defender\Platform\4.18.2007.8-0\NisSrv.exe |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\SYSTEM32\ntdll.dll |


## Signature

* Status: Signature verified.
* Serial: `330000024A0E8AFDF15C662D2B00000000024A`
* Thumbprint: `96384A7F5F1C438F32E2454697DC6D312A74517B`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows Publisher, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: NisSrv.exe
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 4.18.2007.8 (WinBuild.160101.0800)
* Product Version: 4.18.2007.8
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/70
* VirusTotal Link: https://www.virustotal.com/gui/file/3ab68ddd04335ed4f5a69ec3adb56cc80e2f2ab849394c07a21d66bdcbd67ff5/detection/


## Possible Misuse

*The following table contains possible examples of `NisSrv.exe` being misused. While `NisSrv.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_reg_disable_sec_services.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_reg_disable_sec_services.yml) | `- '\NisSrv'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020-2021 Strontic.


