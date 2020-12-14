---
title: TSTheme.exe | TSTheme Server Module
excerpt: What is TSTheme.exe?
---

# TSTheme.exe 

* File Path: `C:\Windows\system32\TSTheme.exe`
* Description: TSTheme Server Module

## Hashes

Type | Hash
-- | --
MD5 | `C0AB057D87EB804E79F3540F0AC1AC37`
SHA1 | `1E1EC63ED702B6BB96DE0A99C793103B4CA96129`
SHA256 | `31114F153F14D9AABD425D75A0F3F87D68A3A4C30E6185D9C040B86AE6470CEE`
SHA384 | `7174073AF10D2DCEE152459BE41C7274D065F4154273F92E45A305786B8488F11E3443D4E954CD18B5396F3E8C354B91`
SHA512 | `76C7EAAD1A3F5DDA5F2F037C7AEFCB560BE063A77CD925B61F124D5B4401283FD345F0037A396642CF7D6CAF8BBF2D4D2693A2D9D36EF31D9308268181997F09`
SSDEEP | `1536:V6TIIfttRqCLNvA3glLTsRe774HrPU8wIBS0s+rPjundilyq//v2:4sWD36YTUe774HrM8JBA+DjudicI/+`
IMP | `C12F529C6B4328A6103FC0A0C6285568`
PESHA1 | `45080E43D23C13B9202A239E666AA620C8FC03E1`
PE256 | `DE422F6B69C692D2075DA996C0510C87BEEA442279AAD3246F5B74120CCA7D29`

## Runtime Data

### Open Handles:

Path | Type
-- | --
(R-D)   C:\Windows\System32\en-US\TSTheme.exe.mui | File
(RW-)   C:\Users\user | File
\BaseNamedObjects\__ComCatalogCache__ | Section
\BaseNamedObjects\C:\*ProgramData\*Microsoft\*Windows\*Caches\*{6AF0698E-D558-4F6E-9B3C-3716689AF493}.2.ver0x0000000000000002.db | Section
\BaseNamedObjects\C:\*ProgramData\*Microsoft\*Windows\*Caches\*{DDF571F2-BE98-426D-8288-1A9A39C3FDA2}.2.ver0x0000000000000002.db | Section
\BaseNamedObjects\C:\*ProgramData\*Microsoft\*Windows\*Caches\*cversions.2 | Section
\BaseNamedObjects\NLS_CodePage_1252_3_2_0_0 | Section
\BaseNamedObjects\NLS_CodePage_437_3_2_0_0 | Section


### Loaded Modules:

Path |
-- |
C:\Windows\System32\ADVAPI32.dll |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\System32\msvcrt.dll |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\RPCRT4.dll |
C:\Windows\System32\sechost.dll |
C:\Windows\system32\TSTheme.exe |


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: TSThemeS.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/76
* VirusTotal Link: https://www.virustotal.com/gui/file/31114f153f14d9aabd425d75a0f3f87d68a3a4c30e6185d9c040b86ae6470cee/detection


## Possible Misuse

*The following table contains possible examples of `TSTheme.exe` being misused. While `TSTheme.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_suspicious_remote_thread.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/sysmon/sysmon_suspicious_remote_thread.yml) | `- '\tstheme.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020 Strontic.


