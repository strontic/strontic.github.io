---
title: dbgcore.dll | Windows Core Debugging Helpers
excerpt: What is dbgcore.dll?
---

# dbgcore.dll 

* File Path: `C:\Program Files (x86)\Windows Kits\10\Debuggers\x64\dbgcore.dll`
* Description: Windows Core Debugging Helpers

## Hashes

Type | Hash
-- | --
MD5 | `DC40CB46D05EF450684E1A1A09C0CFE3`
SHA1 | `D7A177C8BDD217BC2EC4A56714EA289D837AF465`
SHA256 | `4AA03E8A3A89835D2FE52375F2032002D5FC468A38A885BA306EB1F154E2251F`
SHA384 | `8AEBC803A80F7247086B36DA6B25DAF6D32411BE8A1455B03E626ACDFC9A1C2FE4F5790C1B47E8FFF35BFD680232DEEF`
SHA512 | `F6B3B81F0E12FEFE526B8D4C404D485E15FD96AB52ADF4C8CBC7AB43A84BA3F15E190419E095C58582C7DAE571FE7813CF241AC48179D775ACD5C800A8CDF8EE`
SSDEEP | `3072:zEqbGcbEWcgmPtELNGmpbg04HhpEXWpINKKASB0ddOMYgOxTsvmbmr1VH:zEqdEWqtCNG6gNBwWpeASB0ddOm1`
IMP | `1931C583747A3AFF6555664A0BEA87DD`
PESHA1 | `95FF51B808527EE83BD3122ABC4540A96C19BC8A`
PE256 | `A03E2287F371B5A69C37DD875AA8446FA93C1758DCF4F8EF2077075BD2E95FF4`

## DLL Exports:

Function Name | Ordinal | Type
-- | -- | --
`MiniDumpWriteDump` | 2 | Exported Function
`MiniDumpReadDumpStream` | 1 | Exported Function


## Signature

* Status: Signature verified.
* Serial: `33000002CF6D2CC57CAA65A6D80000000002CF`
* Thumbprint: `1A221B3B4FEF088B17BA6704FD088DF192D9E0EF`
* Issuer: CN=Microsoft Code Signing PCA 2010, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Corporation, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

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

* VirusTotal Detections: 0/76
* VirusTotal Link: https://www.virustotal.com/gui/file/4aa03e8a3a89835d2fe52375f2032002d5fc468a38a885ba306eb1f154e2251f/detection

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Program Files (x86)\Windows Kits\10\Debuggers\arm64\dbgcore.dll](dbgcore.dll-E0E1571F0E3CF5F55A40575DC0958271.md) | 40
[C:\Program Files (x86)\Windows Kits\10\Debuggers\arm64\srcsrv\dbgcore.dll](dbgcore.dll-50F6AF4FE83736A5EEEFB4CCE33D187C.md) | 38
[C:\Program Files (x86)\Windows Kits\10\Debuggers\x64\srcsrv\dbgcore.dll](dbgcore.dll-89A977B69952BC8941F5600C4B24022F.md) | 99
[C:\Windows\system32\dbgcore.dll](dbgcore.dll-5CA8253328BA74B02D867A5F40305F9B.md) | 99

## Possible Misuse

*The following table contains possible examples of `dbgcore.dll` being misused. While `dbgcore.dll` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_suspicious_dbghelp_dbgcore_load.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/image_load/sysmon_suspicious_dbghelp_dbgcore_load.yml) | `title: Load of dbghelp/dbgcore DLL from Suspicious Process` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_suspicious_dbghelp_dbgcore_load.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/image_load/sysmon_suspicious_dbghelp_dbgcore_load.yml) | `description: Detects the load of dbghelp/dbgcore DLL (used to make memory dumps) by suspicious processes. Tools like ProcessHacker and some attacker tradecract use MiniDumpWriteDump` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_suspicious_dbghelp_dbgcore_load.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/image_load/sysmon_suspicious_dbghelp_dbgcore_load.yml) | `API found in dbghelp.dll or dbgcore.dll. As an example, SilentTrynity C2 Framework has a module that leverages this API to dump the contents of Lsass.exe and` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_suspicious_dbghelp_dbgcore_load.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/image_load/sysmon_suspicious_dbghelp_dbgcore_load.yml) | `- '\dbgcore.dll'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_lsass_memdump.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_access/sysmon_lsass_memdump.yml) | `description: Detects process LSASS memory dump using procdump or taskmgr based on the CallTrace pointing to dbghelp.dll or dbgcore.dll for win10` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_lsass_memdump.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_access/sysmon_lsass_memdump.yml) | `- '*dbgcore.dll*'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020 Strontic.


