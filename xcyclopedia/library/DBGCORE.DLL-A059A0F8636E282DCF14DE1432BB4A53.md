---
title: DBGCORE.DLL | Windows Core Debugging Helpers
excerpt: What is DBGCORE.DLL?
---

# DBGCORE.DLL 

* File Path: `C:\Program Files (x86)\Microsoft Office\root\Office16\DBGCORE.DLL`
* Description: Windows Core Debugging Helpers

## Hashes

Type | Hash
-- | --
MD5 | `A059A0F8636E282DCF14DE1432BB4A53`
SHA1 | `797ADAA6987890E14A69CAC39233719649610052`
SHA256 | `3147513B5B3DDFA690F305E9509AD935259773B7C90E359991D66B0F7C962706`
SHA384 | `69ED7E1C16C00F8D57463B5C0C89E18341D66ABEACDBB42E4BBB231BB157A251D70CFBB2E1979E5717FA57BE7B6B747D`
SHA512 | `F83BBC90633B3B198F76190F3080F0D2516C3B82573220EDF446FC0BCFA89372DE6CD3CEB392597A2F12C576CEA7D42FF1A4C59920BAF200263A5695FBAB3325`
SSDEEP | `3072:maQASh0NdRoQOxTcNmz3gC5q8wabIXmarr5LZ/lHTRmW6DZIeXVnWG:YASh0NdT4q8wabytrNhlzRP6BFnV`
IMP | `A7AE4A8159842082BE9CED109E340F42`
PESHA1 | `38046787CF4B683255635CC4609411E5289A6DFF`
PE256 | `E8EF9088D12B12C72A0214A8D279F0083016E85E507C81CBA95EFF87E9618447`

## DLL Exports:

Function Name | Ordinal | Type
-- | -- | --
`MiniDumpWriteDump` | 2 | Exported Function
`MiniDumpReadDumpStream` | 1 | Exported Function


## Signature

* Status: Signature verified.
* Serial: `33000001B24A37C6C97E0168860001000001B2`
* Thumbprint: `A380D6A21D68FA9B52D2405B36C712BAFA57632B`
* Issuer: CN=Microsoft Code Signing PCA, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Corporation, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: DBGCORE.DLL
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.17763.1 (WinBuild.160101.0800)
* Product Version: 10.0.17763.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/71
* VirusTotal Link: https://www.virustotal.com/gui/file/3147513b5b3ddfa690f305e9509ad935259773b7c90e359991d66b0f7c962706/detection/

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Program Files (x86)\Windows Kits\10\Debuggers\x86\dbgcore.dll](dbgcore.dll-844F24E2DE8C9E585D310450FFC2FBDC.md) | 49
[C:\Program Files (x86)\Windows Kits\10\Debuggers\x86\srcsrv\dbgcore.dll](dbgcore.dll-5E5EFBC2FF0880AE227863015F8FBBBC.md) | 49
[C:\Windows\SysWOW64\dbgcore.dll](dbgcore.dll-4A77035E26FA131A2F639CEA80E89773.md) | 50

## Possible Misuse

*The following table contains possible examples of `DBGCORE.DLL` being misused. While `DBGCORE.DLL` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_suspicious_dbghelp_dbgcore_load.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/image_load/sysmon_suspicious_dbghelp_dbgcore_load.yml) | `title: Load of dbghelp/dbgcore DLL from Suspicious Process` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_suspicious_dbghelp_dbgcore_load.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/image_load/sysmon_suspicious_dbghelp_dbgcore_load.yml) | `description: Detects the load of dbghelp/dbgcore DLL (used to make memory dumps) by suspicious processes. Tools like ProcessHacker and some attacker tradecract use MiniDumpWriteDump` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_suspicious_dbghelp_dbgcore_load.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/image_load/sysmon_suspicious_dbghelp_dbgcore_load.yml) | `API found in dbghelp.dll or dbgcore.dll. As an example, SilentTrynity C2 Framework has a module that leverages this API to dump the contents of Lsass.exe and` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_suspicious_dbghelp_dbgcore_load.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/image_load/sysmon_suspicious_dbghelp_dbgcore_load.yml) | `- '\dbgcore.dll'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_lsass_memdump.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_access/sysmon_lsass_memdump.yml) | `description: Detects process LSASS memory dump using procdump or taskmgr based on the CallTrace pointing to dbghelp.dll or dbgcore.dll for win10` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_lsass_memdump.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_access/sysmon_lsass_memdump.yml) | `- '*dbgcore.dll*'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020 Strontic.


