---
title: backgroundTaskHost.exe | Background Task Host
excerpt: What is backgroundTaskHost.exe?
---

# backgroundTaskHost.exe 

* File Path: `C:\WINDOWS\system32\backgroundTaskHost.exe`
* Description: Background Task Host

## Hashes

Type | Hash
-- | --
MD5 | `AFFD26BF186915A32218A855976E6697`
SHA1 | `F0EE8131431D48F4ACD31463882D55826706AB11`
SHA256 | `3974CCC64FAA92230554D21D1292FA8587DBC55F9D4A2EF2B8EE16F552AAA812`
SHA384 | `A4456428BE70C5CAAF6D00A1EEAF40FB563E12C762ECD2198DE5694148C56DFDA145890C38BBF96920859BF01B885149`
SHA512 | `6EB5DB5E6CE8D5DEED050DD729F6DD8CC721403F5D9CA93F8FB81397C2D805BFDB562B131A3A54D2C4BFE62AB89278FC30E467948BCDDA62532D239297F8785F`
SSDEEP | `384:zp+STdJdBBCqwIHTDWBGWiDBRJ7oJ/AlGs7pYJL:1+oBcIHTKa1P7c/xI+JL`
IMP | `DC601E2593053A84A6989DE251407AA7`
PESHA1 | `B8C46915388ACC218282948776DB936B2AA624EC`
PE256 | `82390C5D23EB4AA5B6CB226F7538C3569ABF3DC33CFAB9918B88F8B97C12859D`

## Runtime Data

### Child Processes:
backgroundTaskHost.exe WerFault.exe

### Open Handles:

Path | Type
-- | --
(RW-)   C:\Windows\System32 | File
\BaseNamedObjects\__ComCatalogCache__ | Section
\BaseNamedObjects\C:\*ProgramData\*Microsoft\*Windows\*Caches\*{6AF0698E-D558-4F6E-9B3C-3716689AF493}.2.ver0x0000000000000001.db | Section
\BaseNamedObjects\C:\*ProgramData\*Microsoft\*Windows\*Caches\*{DDF571F2-BE98-426D-8288-1A9A39C3FDA2}.2.ver0x0000000000000001.db | Section
\BaseNamedObjects\C:\*ProgramData\*Microsoft\*Windows\*Caches\*cversions.2.ro | Section
\Sessions\2\BaseNamedObjects\NLS_CodePage_1252_3_2_0_0 | Section
\Sessions\2\BaseNamedObjects\NLS_CodePage_437_3_2_0_0 | Section


### Loaded Modules:

Path |
-- |
C:\WINDOWS\system32\backgroundTaskHost.exe |
C:\WINDOWS\System32\KERNEL32.DLL |
C:\WINDOWS\System32\KERNELBASE.dll |
C:\WINDOWS\System32\msvcrt.dll |
C:\WINDOWS\SYSTEM32\ntdll.dll |


## Signature

* Status: Signature verified.
* Serial: `33000002ED2C45E4C145CF48440000000002ED`
* Thumbprint: `312860D2047EB81F8F58C29FF19ECDB4C634CF6A`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: backgroundTaskHost.exe
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.22000.1 (WinBuild.160101.0800)
* Product Version: 10.0.22000.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/73
* VirusTotal Link: https://www.virustotal.com/gui/file/3974ccc64faa92230554d21d1292fa8587dbc55f9d4a2ef2b8ee16f552aaa812/detection

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\WINDOWS\system32\icsunattend.exe](icsunattend.exe-D4B94D62AD95291F1C61D312B6B22044.md) | 40
[C:\WINDOWS\SysWOW64\backgroundTaskHost.exe](backgroundTaskHost.exe-1A79FA2EC172EC30F985348A51C9105E.md) | 50

## Possible Misuse

*The following table contains possible examples of `backgroundTaskHost.exe` being misused. While `backgroundTaskHost.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_abusing_azure_browser_sso.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/image_load/sysmon_abusing_azure_browser_sso.yml) | `- BackgroundTaskHost.exe`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020-2021 Strontic.


