---
title: dbgcore.dll | Windows Core Debugging Helpers
excerpt: What is dbgcore.dll?
---

# dbgcore.dll 

* File Path: `C:\Program Files (x86)\Windows Kits\10\Debuggers\arm\srcsrv\dbgcore.dll`
* Description: Windows Core Debugging Helpers

## Hashes

Type | Hash
-- | --
MD5 | `D92B372FF16F45DC99880849EADBFBD0`
SHA1 | `C213B71B984AFC6F7934CBF2DC73949EC5D11ABD`
SHA256 | `1E1C6F4292DA8AE9E2A70A809125507ACD936BD8B5F1BA95A8D75730B5C2CA7B`
SHA384 | `7306C5CD8DCCE246035A3588CD103CDF2FC445D969A00A33CDBEB5E5D2C1643E293EF83D9AFAB8CB1654F4FA00D1DF94`
SHA512 | `932A2ADE422FF81F5DB2C5A3C976FB0241A3F35D0085B347C7BA6D111F68C46F92B09FFB5C9D6AB9B492F8F5EDA9F4203653802EB3B5E76FF05F98541421F028`
SSDEEP | `3072:Pa9ASx0NdOnoQOxTcImz3rMLQHnS1P38cEPxarABe6UJksJux8M5Ap6GNhlwg3qE:0ASx0NdOeLqFb5qGeTJhSAggjGeR`
IMP | `A1A9F77ED03D39B171C0A02E15991E97`
PESHA1 | `627CEC08AF53287A48E443834BE40046F58A496F`
PE256 | `3721D889A7558918C1CA7C585CC0836507D160EBC39C63DDB9F43D05D20500BE`

## DLL Exports:

Function Name | Ordinal | Type
-- | -- | --
`MiniDumpWriteDump` | 2 | Exported Function
`MiniDumpReadDumpStream` | 1 | Exported Function


## Signature

* Status: Signature verified.
* Serial: `33000002B7E8E007A82AEF13150000000002B7`
* Thumbprint: `5A68625F1A516670A744F7EF919500A479D32A5B`
* Issuer: CN=Microsoft Code Signing PCA 2010, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows Kits Publisher, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: DBGCORE.DLL
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 452

## File Scan

* VirusTotal Detections: Unknown
* VirusTotal Link: n/a

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Program Files (x86)\Windows Kits\10\Debuggers\arm\dbgcore.dll](dbgcore.dll-EA56C2C6CC1846310DA69F14C7C26883.md) | 97

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


