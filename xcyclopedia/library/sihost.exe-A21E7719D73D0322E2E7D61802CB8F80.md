---
title: sihost.exe | Shell Infrastructure Host
excerpt: What is sihost.exe?
---

# sihost.exe 

* File Path: `C:\Windows\system32\sihost.exe`
* Description: Shell Infrastructure Host

## Hashes

Type | Hash
-- | --
MD5 | `A21E7719D73D0322E2E7D61802CB8F80`
SHA1 | `5310BA14A05256E4D93E0B04338F53B4E1D680CB`
SHA256 | `8EE21A0BA8849D31C265B4090A9E2EBE8BA66F58A8F71D4E96509E8A78F7DB00`
SHA384 | `F26C177FE978D5A83E5837A9F1747CD7420165492B6F763C0C8C4327F1DCDA95C0CBA51D09AF0DCD52235DB984D09DF6`
SHA512 | `E78793B58C358DAFA0EECF3D2E7582186DF0BBBC13D96A5475342C371946219CA544CF49EF3DD60D078C2ED0BBB614727F25774B84BDDCF5A77A4181FCBA184C`
SSDEEP | `3072:Y8JFdMPmFAXIf/9odiof3UWAWktyEyc6Lh7:YaPQy/9odio/UHyc6Lh`
IMP | `9FFE8029F721BD904F419F82A63D59A2`
PESHA1 | `7C8600351D050A684D8553503884AA16E21795B3`
PE256 | `76157225DD6E8AC1D711CF6C16874708D7A5EC8EE502BAA2AFAEE30ED33E704F`

## Runtime Data

### Child Processes:
explorer.exe

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
C:\Windows\System32\combase.dll |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\System32\msvcp_win.dll |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\system32\sihost.exe |
C:\Windows\System32\ucrtbase.dll |


## Signature

* Status: Signature verified.
* Serial: `33000002EC6579AD1E670890130000000002EC`
* Thumbprint: `F7C2F2C96A328C13CDA8CDB57B715BDEA2CBD1D9`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: sihost.exe
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.746 (WinBuild.160101.0800)
* Product Version: 10.0.19041.746
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/73
* VirusTotal Link: https://www.virustotal.com/gui/file/8ee21a0ba8849d31c265b4090a9e2ebe8ba66f58a8f71d4e96509e8a78f7db00/detection


## Possible Misuse

*The following table contains possible examples of `sihost.exe` being misused. While `sihost.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_creation_system_file.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/file_event/sysmon_creation_system_file.yml) | `- '\sihost.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_system_exe_anomaly.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_system_exe_anomaly.yml) | `- '\sihost.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020-2021 Strontic.


