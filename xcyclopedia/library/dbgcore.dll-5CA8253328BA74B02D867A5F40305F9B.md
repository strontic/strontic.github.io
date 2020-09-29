---
title: dbgcore.dll | Windows Core Debugging Helpers
excerpt: What is dbgcore.dll?
---

# dbgcore.dll 

* File Path: `C:\Windows\system32\dbgcore.dll`
* Description: Windows Core Debugging Helpers

## Hashes

Type | Hash
-- | --
MD5 | `5CA8253328BA74B02D867A5F40305F9B`
SHA1 | `11FC2A42BC9904B3AA4DDBEA8A52C5E14662551F`
SHA256 | `CE76D374BF58239F7F4A16AEA2E6152537437AF8AA3C83C59CCCC88DAFFCCC85`
SHA384 | `653460B2B2457CC6423525DCE9295D55DB1ABEC04DA2A111FB8D9035AB5DB0867312D9E5708F0DA37975EE894DAC27B8`
SHA512 | `EFC1003BF0E0AB4A58483292E75951F5E9DD441D6911ABD22E1D56C50BE2B7AF19819E8E960DFBEACB063A329D59EAF81C7283417EDD20839B78AC76BDE9C96B`
SSDEEP | `3072:aEqbGcbEWcgmPtELNGmpbg04HhpEXWpINKKASB0ddOMYgOxTsvmbmr1V:aEqdEWqtCNG6gNBwWpeASB0ddOm1`
IMP | `1931C583747A3AFF6555664A0BEA87DD`
PESHA1 | `95FF51B808527EE83BD3122ABC4540A96C19BC8A`
PE256 | `A03E2287F371B5A69C37DD875AA8446FA93C1758DCF4F8EF2077075BD2E95FF4`

## DLL Exports:

Function Name | Ordinal | Type | Address | Relative Address
-- | -- | -- | -- | --
`MiniDumpReadDumpStream` | 1 (0x1) | Exported Function | 0x0000000180006d70 | 0x00006d70
`MiniDumpWriteDump` | 2 (0x2) | Exported Function | 0x0000000180006a80 | 0x00006a80


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: DBGCORE.DLL
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/65
* VirusTotal Link: https://www.virustotal.com/gui/file/ce76d374bf58239f7f4a16aea2e6152537437af8aa3c83c59cccc88daffccc85/detection/


## Possible Misuse

*The following table contains possible examples of `dbgcore.dll` being misused. While `dbgcore.dll` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_suspicious_dbghelp_dbgcore_load.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/image_load/sysmon_suspicious_dbghelp_dbgcore_load.yml) | `title: Load of dbghelp/dbgcore DLL from Suspicious Process` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_suspicious_dbghelp_dbgcore_load.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/image_load/sysmon_suspicious_dbghelp_dbgcore_load.yml) | `description: Detects the load of dbghelp/dbgcore DLL (used to make memory dumps) by suspicious processes. Tools like ProcessHacker and some attacker tradecract use MiniDumpWriteDump` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_suspicious_dbghelp_dbgcore_load.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/image_load/sysmon_suspicious_dbghelp_dbgcore_load.yml) | `API found in dbghelp.dll or dbgcore.dll. As an example, SilentTrynity C2 Framework has a module that leverages this API to dump the contents of Lsass.exe and` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_suspicious_dbghelp_dbgcore_load.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/image_load/sysmon_suspicious_dbghelp_dbgcore_load.yml) | `- '\dbgcore.dll'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_lsass_memdump.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_access/sysmon_lsass_memdump.yml) | `description: Detects process LSASS memory dump using procdump or taskmgr based on the CallTrace pointing to dbghelp.dll or dbgcore.dll for win10` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_lsass_memdump.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_access/sysmon_lsass_memdump.yml) | `- '*dbgcore.dll*'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020 Strontic.


