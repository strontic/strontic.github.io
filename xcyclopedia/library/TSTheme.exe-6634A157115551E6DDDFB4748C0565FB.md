---
title: TSTheme.exe | TSTheme Server Module
excerpt: What is TSTheme.exe?
---

# TSTheme.exe 

* File Path: `C:\Windows\SysWOW64\TSTheme.exe`
* Description: TSTheme Server Module

## Hashes

Type | Hash
-- | --
MD5 | `6634A157115551E6DDDFB4748C0565FB`
SHA1 | `37578D8599729B648F828755C6A2FAC1A77125D4`
SHA256 | `D574A6CA42D1A50B3115A916E62A4CC5AB92833DFF4A3F2CCF85A2EA2512A6F3`
SHA384 | `230A869A6A88F786CE9D0A52BDBB686E254E2011CD0EF67114C3FCCFA23C40308D28621BE62C3F7895F875137968BE72`
SHA512 | `F7C4FA6B2C4591E54812EADC27D55868E793B551AF89B889F5956580E86B9F65FB26817FFD3B4A02E0B033D754DD3C795580EE4A3AA07124F249BEEAE23A53D8`
SSDEEP | `1536:H+7ffgEx3Jrst6bnH8jeVsWfsGbQpqyqd5jaz:H+DfgExBst6L8GxfsMGXW52`
IMP | `C059327BB81F9769B552D03F94C4F1A1`
PESHA1 | `40EFAB91ECF729C8AAD19AEE116F656C48B675A1`
PE256 | `02288DB58D2A7D1F0D8FE700AFD6FCB3FEDF81FDEEC58E4BA97F597AD30BA302`

## Runtime Data

### Open Handles:

Path | Type
-- | --
(R-D)   C:\Windows\System32\en-US\TSTheme.exe.mui | File
(RW-)   C:\Users\user | File
(RW-)   C:\Windows | File
\BaseNamedObjects\__ComCatalogCache__ | Section
\BaseNamedObjects\C:\*ProgramData\*Microsoft\*Windows\*Caches\*{6AF0698E-D558-4F6E-9B3C-3716689AF493}.2.ver0x0000000000000002.db | Section
\BaseNamedObjects\C:\*ProgramData\*Microsoft\*Windows\*Caches\*{DDF571F2-BE98-426D-8288-1A9A39C3FDA2}.2.ver0x0000000000000002.db | Section
\BaseNamedObjects\C:\*ProgramData\*Microsoft\*Windows\*Caches\*cversions.2 | Section
\BaseNamedObjects\NLS_CodePage_1252_3_2_0_0 | Section
\BaseNamedObjects\NLS_CodePage_437_3_2_0_0 | Section


### Loaded Modules:

Path |
-- |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\wow64.dll |
C:\Windows\System32\wow64cpu.dll |
C:\Windows\System32\wow64win.dll |
C:\Windows\SysWOW64\TSTheme.exe |


## Signature

* Status: Signature verified.
* Serial: `33000002EC6579AD1E670890130000000002EC`
* Thumbprint: `F7C2F2C96A328C13CDA8CDB57B715BDEA2CBD1D9`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: TSThemeS.exe
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.746 (WinBuild.160101.0800)
* Product Version: 10.0.19041.746
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/74
* VirusTotal Link: https://www.virustotal.com/gui/file/d574a6ca42d1a50b3115a916e62a4cc5ab92833dff4a3f2ccf85a2ea2512a6f3/detection


## Possible Misuse

*The following table contains possible examples of `TSTheme.exe` being misused. While `TSTheme.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_suspicious_remote_thread.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/create_remote_thread/sysmon_suspicious_remote_thread.yml) | `- '\tstheme.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020-2021 Strontic.


