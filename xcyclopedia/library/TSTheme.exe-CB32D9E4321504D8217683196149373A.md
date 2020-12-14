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
MD5 | `CB32D9E4321504D8217683196149373A`
SHA1 | `509F20BFE552800EBDFE0A37B6189B4343D99A94`
SHA256 | `0A827CB624FB1DD5743DD5706A60FFED477988D4E939C6876BBCE398F2574065`
SHA384 | `2EDEA61F7141C2F107FAB28F0752719FA91F71FC3544FEA227F547A661BB8868D3F6B15A0B570E7C189A607152509CD9`
SHA512 | `5CFDDB139F254607D81F0E9ADDD0AB7D5FEC46FE8FACFC8F69BF789DA5DF7C0809A808144EC0A32CC841240F3C74DFC541C9BF9A24A33C57B3E4D2C9A88B2D9A`
SSDEEP | `1536:Y+7fA8LgWp8jweDL+l0YW2iwpjyrH/jak:Y+DAmgWEDL+zrim+L/2k`
IMP | `C059327BB81F9769B552D03F94C4F1A1`
PESHA1 | `86126C61838F7F598E55482173F646ADCEECDCDC`
PE256 | `879F25E8E0304DC678BE79520EEF9FD22464DCD01C99758C896A9C11D9AFBD0B`

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
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: TSThemeS.exe
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/75
* VirusTotal Link: https://www.virustotal.com/gui/file/0a827cb624fb1dd5743dd5706a60ffed477988d4e939c6876bbce398f2574065/detection


## Possible Misuse

*The following table contains possible examples of `TSTheme.exe` being misused. While `TSTheme.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_suspicious_remote_thread.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/sysmon/sysmon_suspicious_remote_thread.yml) | `- '\tstheme.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020 Strontic.


