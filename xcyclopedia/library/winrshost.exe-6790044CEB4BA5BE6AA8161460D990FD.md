---
title: winrshost.exe | Host Process for WinRM's Remote Shell plugin
excerpt: What is winrshost.exe?
---

# winrshost.exe 

* File Path: `C:\Windows\system32\winrshost.exe`
* Description: Host Process for WinRM's Remote Shell plugin

## Hashes

Type | Hash
-- | --
MD5 | `6790044CEB4BA5BE6AA8161460D990FD`
SHA1 | `F8DA634CFF92D525B98D99E91A6551020B3F5C0C`
SHA256 | `047427E1ECC1D5758A9553F0E819A9536D9D56D279BA81F707FE377FA1433318`
SHA384 | `CA1DE62A16D55DA5E7CBD99388F413894461DD0CD56CF3A2A0CB36F9D77582C29EA6F2B0404C68476931662661EC43F9`
SHA512 | `E52F5D34069AE471B41A20B7F71D8EC3219F1BD2848AF1EDC5FC976C55106BBBDEF76A8A2DC26F66087DFFBC3178CCBB53A7FE542BD5F81343E90DA61CA6F4C9`
SSDEEP | `768:sb+k5T4Bpg6zDHkIabua14BVkB4x8/07spU:M+k54wSEIaKa14BVkk8/07spU`
IMP | `94B88BB1A488481A09FB94AE3B531ED2`
PESHA1 | `9C4A5996EB1355105B5A316202D1E91C98528033`
PE256 | `5721D76D71D34C9D116808654F8C0B13D88E04DA3F68E56B8AF46B40AC09E02A`

## Runtime Data

### Child Processes:
conhost.exe

### Open Handles:

Path | Type
-- | --
(R-D)   C:\Windows\System32\en-US\user32.dll.mui | File
(RW-)   C:\Users\user | File
\BaseNamedObjects\__ComCatalogCache__ | Section
\BaseNamedObjects\C:\*ProgramData\*Microsoft\*Windows\*Caches\*{6AF0698E-D558-4F6E-9B3C-3716689AF493}.2.ver0x0000000000000002.db | Section
\BaseNamedObjects\C:\*ProgramData\*Microsoft\*Windows\*Caches\*{DDF571F2-BE98-426D-8288-1A9A39C3FDA2}.2.ver0x0000000000000002.db | Section
\BaseNamedObjects\C:\*ProgramData\*Microsoft\*Windows\*Caches\*cversions.2 | Section
\BaseNamedObjects\NLS_CodePage_1252_3_2_0_0 | Section
\BaseNamedObjects\NLS_CodePage_437_3_2_0_0 | Section
\Sessions\1\Windows\Theme1175649999 | Section
\Windows\Theme601709542 | Section


### Loaded Modules:

Path |
-- |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\System32\msvcrt.dll |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\system32\winrshost.exe |


## Signature

* Status: Signature verified.
* Serial: `330000026551AE1BBD005CBFBD000000000265`
* Thumbprint: `E168609353F30FF2373157B4EB8CD519D07A2BFF`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: winrshost.exe
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/74
* VirusTotal Link: https://www.virustotal.com/gui/file/047427e1ecc1d5758a9553f0e819a9536d9d56d279ba81f707fe377fa1433318/detection


## Possible Misuse

*The following table contains possible examples of `winrshost.exe` being misused. While `winrshost.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_in_memory_powershell.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/image_load/sysmon_in_memory_powershell.yml) | `- '\winrshost.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020-2021 Strontic.


