---
title: splwow64.exe | Print driver host for applications
excerpt: What is splwow64.exe?
---

# splwow64.exe 

* File Path: `C:\Windows\splwow64.exe`
* Description: Print driver host for applications

## Hashes

Type | Hash
-- | --
MD5 | `09EC082A13633BAEDE8FF155A0ACCF9E`
SHA1 | `2D962BA8E740C70FFEC00FEED2E2DC3D02729CB1`
SHA256 | `F00450B2DCEA43504642C00C4D5B725003E23AD00928BE0A5AD381E920561EA7`
SHA384 | `B16F937170FABBC81CA538AC7081F6559E26BAF4B30EBEAD4543FD570D641AE8F9E5374AF6CF6B2290B6F7A8CC1886BD`
SHA512 | `3A818D8B26BBCAAAE4DA456AF64A67746AF4E670513E4DC2E03AA6E951B351F3DAF8A569429D91BF2D156B987D6E2B720C7549C2F082EFCE2327DC7CE72B958C`
SSDEEP | `3072:xMvRNJWRNsoGlAi+iKJKUZsQgV1HQbPRyZ2pPTc:mvRNJyNsoGlAid4sF78AZ2`
IMP | `260422772873DF4417E4B473F68B1ADE`
PESHA1 | `787F42EF194F2A9687F8B1F18DB58FA030E94170`
PE256 | `CD22F48C381844D9E6D063BC4B81B54F1507990CF623F21E7E3BB505FFAFE19E`

## Runtime Data

### Open Handles:

Path | Type
-- | --
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
C:\Windows\splwow64.exe |
C:\Windows\System32\ADVAPI32.dll |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\System32\msvcrt.dll |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\RPCRT4.dll |
C:\Windows\System32\sechost.dll |
C:\Windows\System32\USER32.dll |


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: splwow64.exe
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.685 (WinBuild.160101.0800)
* Product Version: 10.0.19041.685
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/76
* VirusTotal Link: https://www.virustotal.com/gui/file/f00450b2dcea43504642c00c4d5b725003e23ad00928be0a5ad381e920561ea7/detection

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\WINDOWS\splwow64.exe](splwow64.exe-906E1DFC3A3A64D3452C5BA124AC9A4C.md) | 41
[C:\Windows\splwow64.exe](splwow64.exe-93A8D365CB20A105CB97FF41451B85D5.md) | 40
[C:\Windows\splwow64.exe](splwow64.exe-9FCD31635CC99F1DAFB64AB3F963E0C1.md) | 72
[C:\Windows\splwow64.exe](splwow64.exe-AA4138C0FBC6D41F9EBC5C4EFE20ECCA.md) | 72
[C:\Windows\splwow64.exe](splwow64.exe-B626F1C0194C73D55529E729A63209A2.md) | 41
[C:\Windows\splwow64.exe](splwow64.exe-B73202D296AE4FDB8ECC29CC97F8A444.md) | 44
[C:\Windows\splwow64.exe](splwow64.exe-BD86784ABDA6C4FD8ACFD3912AC192E9.md) | 43
[C:\windows\splwow64.exe](splwow64.exe-BE96C8815DE31A42E93A3BE09C2EECCC.md) | 49
[C:\Windows\system32\PrintIsolationHost.exe](PrintIsolationHost.exe-95E50C824C9C9B4362AA3522B8449E29.md) | 47
[C:\Windows\system32\PrintIsolationHost.exe](PrintIsolationHost.exe-A7BF96D6CC09A5012C1EA0F990D65567.md) | 50
[C:\Windows\system32\PrintIsolationHost.exe](PrintIsolationHost.exe-B59C716809F72A87CF72C66AB7BD5082.md) | 44

## Possible Misuse

*The following table contains possible examples of `splwow64.exe` being misused. While `splwow64.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_splwow64.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_splwow64.yml) | `title: Suspicious Splwow64 Without Params`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_splwow64.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_splwow64.yml) | `description: Detects suspicious Splwow64.exe process without any command line parameters`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_splwow64.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_splwow64.yml) | `Image\|endswith: '\splwow64.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_splwow64.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_splwow64.yml) | `CommandLine\|endswith: 'splwow64.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020-2021 Strontic.


