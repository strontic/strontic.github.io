﻿---
title: pcwrun.exe | Program Compatibility Troubleshooter Invoker
excerpt: What is pcwrun.exe?
---

# pcwrun.exe 

* File Path: `C:\Windows\system32\pcwrun.exe`
* Description: Program Compatibility Troubleshooter Invoker

## Hashes

Type | Hash
-- | --
MD5 | `2CED4FEAA29CCFBE376B8BC31C9E2D68`
SHA1 | `27A241E12CA18C5B8FC504D04B9AE2E9D584A727`
SHA256 | `68BBE7B9F1C6B87B5A73EDF9CF74A3BA0781307BFC08E61CD09C8D14BA3ABC18`
SHA384 | `55891104C0E75D140C68FEC01AEFBCF877ACA9C00A876F7E78766C8A37872511378BB1BECAF58F3CF242DB2D70620F4B`
SHA512 | `C2FF9D51B492ED0A72F5CA5A411D9260744AC6849F3364AB4E68DF7F19B986932126B3C1703BDF1EE760821845209D7662AFD8F4AEF77681E1A458DB973B8682`
SSDEEP | `192:q9UhMD/2g7+qsOUWPmOSXMKDS6gLRHJAD13JOynSdFwC7JAm0WTgW:qIMD/2qAOU5OSXDShLJTySHFl0WTgW`

## Runtime Data

### Child Processes:
msdt.exe

## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: pcwrun.exe
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.14393.0 (rs1_release.160715-1616)
* Product Version: 10.0.14393.0
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.



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


