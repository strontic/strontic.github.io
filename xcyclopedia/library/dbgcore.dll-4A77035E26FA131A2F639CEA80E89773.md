---
title: dbgcore.dll | Windows Core Debugging Helpers
excerpt: What is dbgcore.dll?
---

# dbgcore.dll 

* File Path: `C:\Windows\SysWOW64\dbgcore.dll`
* Description: Windows Core Debugging Helpers

## Hashes

Type | Hash
-- | --
MD5 | `4A77035E26FA131A2F639CEA80E89773`
SHA1 | `07F8E5E58D5C2A65CA250249353B42BF9C6CDB20`
SHA256 | `C6B895F9D45F733EA753AD5E59A60213F2CE2291C8038194A809EA5D09D774A3`
SHA384 | `9B2FF8A9B501F460F800C297B6D976A8845C3779DBE434B89E0E69E62019BD76006BAC2F86736B4E9972019B37B5F6CA`
SHA512 | `90E4E075B29DEA4B7546B2FB2D2CDB6634DA3C628A1797049B0F22B6724C5AB451AA41B71F2E6948D9953BB75A8E675974B4B98174516C322BA34CE378A3B83B`
SSDEEP | `3072:qmaQASh0NdONoQOxTcdmz3QCAalrN3qnKs31pD4AlR3AqXDzePXsE:dASh0NdO3CA6Z3qKw12AlR3AqXG9`
IMP | `6B4C359DDEE8D04B59FFFFE32DA056B2`
PESHA1 | `ECF515823A251A0B088B41735D810BC0463677F0`
PE256 | `BA228BFC09DB6AD4DD4CB80BC449D9E3AE4AE630A61039BBF9B71408871D8545`

## DLL Exports:

Function Name | Ordinal | Type
-- | -- | --
`MiniDumpReadDumpStream` | 1 | Exported Function
`MiniDumpWriteDump` | 2 | Exported Function


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
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/67
* VirusTotal Link: https://www.virustotal.com/gui/file/c6b895f9d45f733ea753ad5e59a60213f2ce2291c8038194a809ea5d09d774a3/detection/


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


