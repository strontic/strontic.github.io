---
title: MicrosoftEdgeSH.exe | Microsoft Edge Web Platform
excerpt: What is MicrosoftEdgeSH.exe?
---

# MicrosoftEdgeSH.exe 

* File Path: `C:\WINDOWS\system32\MicrosoftEdgeSH.exe`
* Description: Microsoft Edge Web Platform

## Hashes

Type | Hash
-- | --
MD5 | `CCC1B1B80190934832DDD8E518F4CCA9`
SHA1 | `E2AEC2F15BF3863AADAC8F56A766AA3DECE4651B`
SHA256 | `BC6EF07260624E303AAC107D388D87CE85FD0D545EFBE57DA5F59433C2BACAE3`
SHA384 | `7C387CEC0D05F81C247CFD51C79C93F69F8110A4EC60499D522E5873B48CF634278A9CE0733EF4ED28590857868E028C`
SHA512 | `D9C181E397D3285BC2B370397BB5EC730B8320750BB6FD2CF6C7C635B9048CA467F71E7E2D72B5266FEF19422C507F72663B4A413E2C1E3EAD68E2133301A60C`
SSDEEP | `1536:4WIBAwglPk935NfxVOmQGUvIiToe9x+wO95xUm:sBS89LjOVtToe9kwO5xr`
IMP | `4F297C9CDCE9606A6D53083F755D899C`
PESHA1 | `C6640132073E425B979A3519100CCB947DB13D5D`
PE256 | `60BF6A4F5F759027BB2CDE15DE1269D0DFED6A052FED0A145A95296E60F5DF7E`

## Runtime Data

### Child Processes:
MicrosoftEdgeSH.exe WerFault.exe

### Loaded Modules:

Path |
-- |
C:\WINDOWS\System32\KERNEL32.DLL |
C:\WINDOWS\System32\KERNELBASE.dll |
C:\WINDOWS\system32\MicrosoftEdgeSH.exe |
C:\WINDOWS\SYSTEM32\ntdll.dll |
C:\WINDOWS\System32\ucrtbase.dll |


## Signature

* Status: Signature verified.
* Serial: `33000002ED2C45E4C145CF48440000000002ED`
* Thumbprint: `312860D2047EB81F8F58C29FF19ECDB4C634CF6A`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: MicrosoftEdgeSH.exe
* Product Name: Microsoft Edge Web Platform
* Company Name: Microsoft Corporation
* File Version: 11.00.22000.1 (WinBuild.160101.0800)
* Product Version: 11.00.22000.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/73
* VirusTotal Link: https://www.virustotal.com/gui/file/bc6ef07260624e303aac107d388d87ce85fd0d545efbe57da5f59433c2bacae3/detection


## Possible Misuse

*The following table contains possible examples of `MicrosoftEdgeSH.exe` being misused. While `MicrosoftEdgeSH.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_powershell_parent_process.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_powershell_parent_process.yml) | `- "MicrosoftEdgeSH.exe"`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020-2021 Strontic.


