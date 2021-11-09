---
title: pcwrun.exe | Program Compatibility Troubleshooter Invoker
excerpt: What is pcwrun.exe?
---

# pcwrun.exe 

* File Path: `C:\WINDOWS\system32\pcwrun.exe`
* Description: Program Compatibility Troubleshooter Invoker

## Hashes

Type | Hash
-- | --
MD5 | `F403498CD4CCAD1D23B19639E9AE39C3`
SHA1 | `9285D28787CD0C3767EBDC2D2BC15C3598C490AA`
SHA256 | `3087F9AA4EA61FB0AC46E23721BDA1F688919684F88B32CA6A37E5115094E5DC`
SHA384 | `0C3F5AB4FC7065987B85169A6B64EA5A87D326905FFF79113BDF963CBB8504C508B310AA541C05A6264D1AD264BEC634`
SHA512 | `F02FEDD8EB176312A812BD509420442AE3A53A6DCC905AA9DFD5F42648396E3A274CC57D40EAF22C8E98E13CB278615E91C3DE566DDEF45FAF78C988C6337164`
SSDEEP | `192:oI2fS2y9cq15HvBomH2bAqy+ChtqeAhEx3yZKoOg8OmcWzgW:oI26z9/1rNWb35vExcODLcWzgW`
IMP | `F377D135D63E07ADC800E6F236499A9F`
PESHA1 | `CCFF489103A148D7D4A550BBAC0B7A88705A42B5`
PE256 | `05D54964AAA22F088E6A21C2C0E22EF57F289CBEE9D284C09F37514001B41588`

## Runtime Data

### Child Processes:
msdt.exe

### Loaded Modules:

Path |
-- |
C:\WINDOWS\System32\KERNEL32.DLL |
C:\WINDOWS\System32\KERNELBASE.dll |
C:\WINDOWS\SYSTEM32\ntdll.dll |
C:\WINDOWS\system32\pcwrun.exe |


## Signature

* Status: Signature verified.
* Serial: `33000002ED2C45E4C145CF48440000000002ED`
* Thumbprint: `312860D2047EB81F8F58C29FF19ECDB4C634CF6A`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: pcwrun.exe
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.22000.1 (WinBuild.160101.0800)
* Product Version: 10.0.22000.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/73
* VirusTotal Link: https://www.virustotal.com/gui/file/3087f9aa4ea61fb0ac46e23721bda1f688919684f88b32ca6a37e5115094e5dc/detection


## Possible Misuse

*The following table contains possible examples of `pcwrun.exe` being misused. While `pcwrun.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_indirect_cmd_compatibility_assistant.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_indirect_cmd_compatibility_assistant.yml) | `description: Detect indirect command execution via Program Compatibility Assistant pcwrun.exe`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_indirect_cmd_compatibility_assistant.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_indirect_cmd_compatibility_assistant.yml) | `- https://lolbas-project.github.io/lolbas/Binaries/Pcwrun/`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_indirect_cmd_compatibility_assistant.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_indirect_cmd_compatibility_assistant.yml) | `ParentImage\|endswith: '\pcwrun.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Pcwrun.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Pcwrun.yml) | `Name: Pcwrun.exe`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Pcwrun.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Pcwrun.yml) | `- Command: Pcwrun.exe c:\temp\beacon.exe`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Pcwrun.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Pcwrun.yml) | `- Path: C:\Windows\System32\pcwrun.exe`{:.highlight .language-yaml} | 



MIT License. Copyright (c) 2020-2021 Strontic.


