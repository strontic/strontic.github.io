---
title: winrshost.exe | Host Process for WinRM's Remote Shell plugin
excerpt: What is winrshost.exe?
---

# winrshost.exe 

* File Path: `C:\Windows\SysWOW64\winrshost.exe`
* Description: Host Process for WinRM's Remote Shell plugin

## Hashes

Type | Hash
-- | --
MD5 | `9EB3371F7B80A434CC9F468B330A9928`
SHA1 | `B207B1D5B81B812F909F2434DADE79E8D9472877`
SHA256 | `233E8EA78906FB63E306DD5FFDBE07716DAA9144A2B4715B0EF9C2C990EF60C0`
SHA384 | `58EEE2B460AF981CE97611AD6E9BDCDDA73169BA2088E4BADCBFA2E3CEE5DAB34E9343D8D13DF7FFD9D4D91826932169`
SHA512 | `DA32424F31950736471FB31D35DDA40B2DFF7CF568A8E1FF777C50D072CBF6479ED303390240E21947FD763A50B71367A2A2B17F776C7BBB478B4E4B19D0ED9D`
SSDEEP | `384:qCLwubRl9FlrAjArVdl8wEhUfDTW3ap/vFWscEW:brbD9FlrprVdgcaKp/vE`
IMP | `84E8D0734E85FF07FA62BE51BF7504A9`
PESHA1 | `106387CB5156F49300C0A02249BD73174E8F0BCF`
PE256 | `FDF329ED11AD473BFEF6D2C25E7032E7B64CCA6C9A60FC6B0A0271F4EF36BF2D`

## Runtime Data

### Child Processes:
conhost.exe

### Open Handles:

Path | Type
-- | --
(R-D)   C:\Windows\SysWOW64\en-US\user32.dll.mui | File
(RW-)   C:\Users\user | File
(RW-)   C:\Windows | File
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
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\wow64.dll |
C:\Windows\System32\wow64cpu.dll |
C:\Windows\System32\wow64win.dll |
C:\Windows\SysWOW64\winrshost.exe |


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
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
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/73
* VirusTotal Link: https://www.virustotal.com/gui/file/233e8ea78906fb63e306dd5ffdbe07716daa9144a2b4715b0ef9c2c990ef60c0/detection


## Possible Misuse

*The following table contains possible examples of `winrshost.exe` being misused. While `winrshost.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_in_memory_powershell.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/image_load/sysmon_in_memory_powershell.yml) | `- '\winrshost.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020-2021 Strontic.


