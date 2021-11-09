---
title: rdrleakdiag.exe | Microsoft Windows Resource Leak Diagnostic
excerpt: What is rdrleakdiag.exe?
---

# rdrleakdiag.exe 

* File Path: `C:\WINDOWS\SysWOW64\rdrleakdiag.exe`
* Description: Microsoft Windows Resource Leak Diagnostic

## Hashes

Type | Hash
-- | --
MD5 | `07428F1C3BDD83F75455BC2525DDD16A`
SHA1 | `4DAEF04474C71FEBAC9E3EE15F71BAE14F0505BB`
SHA256 | `FA188D19E59304FD1968FC14CEC679238D569FB535679BD067130EAF29164B5B`
SHA384 | `5AF068D49E3FCEA5354EA5649263E6BBDF59EE0976CA0573AE95C16E0450826CAE93BA64F10EA71097C6CFDA5B809722`
SHA512 | `E399145104578EBF947834A6A194944DA8965E97FEB8A71F1ACEF01C115B1324FB2D809381F3A7D019770AC761B169DB404783020E6A3B99B5963B9A74795EF8`
SSDEEP | `768:ewv/jBpLXQh2kr0LZjMJ/GmfYHdQ3aT48GtVA5LrgIDtD+4a2GcD06oNDo2NcVsJ:e1hZ+Zc/Gsgbda2X46oNcVdky`
IMP | `F719B5A96668840690D2133A9C4444EC`
PESHA1 | `47DF8882C5F498B2A1082705E5C4BD622E910811`
PE256 | `9EE3A3BD265B06C02F5C50E17FED15B9D5562823C0DF7EC7187603F505D544FB`

## Runtime Data

### Loaded Modules:

Path |
-- |
C:\WINDOWS\SYSTEM32\ntdll.dll |
C:\WINDOWS\System32\wow64.dll |
C:\WINDOWS\System32\wow64base.dll |
C:\WINDOWS\System32\wow64con.dll |
C:\WINDOWS\System32\wow64win.dll |
C:\WINDOWS\SysWOW64\rdrleakdiag.exe |


## Signature

* Status: Signature verified.
* Serial: `33000002ED2C45E4C145CF48440000000002ED`
* Thumbprint: `312860D2047EB81F8F58C29FF19ECDB4C634CF6A`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: RdrLeakDiag.exe
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.22000.1 (WinBuild.160101.0800)
* Product Version: 10.0.22000.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/74
* VirusTotal Link: https://www.virustotal.com/gui/file/fa188d19e59304fd1968fc14cec679238d569fb535679bd067130eaf29164b5b/detection


## Possible Misuse

*The following table contains possible examples of `rdrleakdiag.exe` being misused. While `rdrleakdiag.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_process_dump_rdrleakdiag.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_process_dump_rdrleakdiag.yml) | `title: Process Dump via RdrLeakDiag.exe`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_process_dump_rdrleakdiag.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_process_dump_rdrleakdiag.yml) | `description: Detects a process memory dump performed by RdrLeakDiag.exe`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_process_dump_rdrleakdiag.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_process_dump_rdrleakdiag.yml) | `OriginalFileName: RdrLeakDiag.exe`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020-2021 Strontic.


