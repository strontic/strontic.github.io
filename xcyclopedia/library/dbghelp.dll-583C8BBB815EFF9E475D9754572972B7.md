---
title: dbghelp.dll | Windows Image Helper
excerpt: What is dbghelp.dll?
---

# dbghelp.dll 

* File Path: `C:\Program Files (x86)\Windows Kits\10\Debuggers\arm64\dbghelp.dll`
* Description: Windows Image Helper

## Hashes

Type | Hash
-- | --
MD5 | `583C8BBB815EFF9E475D9754572972B7`
SHA1 | `1932EA91BFF5C3DADBFBB8A0A77E116065000B45`
SHA256 | `0652DF4C785B4E9BFC5D7B7FEDA32EC595E6FC73F708DE9A3C51E89BB56EA51E`
SHA384 | `AE734A22E0568AF253066ABDAF4294DB8423EFFDAB05F598B2E9FE8E12348C48A430B36E946CB4908E31817D77168643`
SHA512 | `FB4B6CEEA725A918BBEB4FEE7DB72DAFAE55AB620CB74A3B96D797705F3DFC801181D191FDDEC561A458A62B1FCF54E3D8ABED98767EB9FD8EA0AFD2C71D50DD`
SSDEEP | `12288:Dqex9w3k8tTxXD1rS8xXnGGRdUKAkBM1k3JTs4YeTljofVQuVJotAZxF/B2HtsDW:bP8thD3pCvdeYinGuSus7lIXVZ`
IMP | `F75CAB32CF727D7F502502606D380E8E`
PESHA1 | `0E4F11B0E100E377B3B5E5F47391A8E8CB7A6AEB`
PE256 | `819F0DDFE945F234FC137E0CCE5FFFD9230684F40264BAC6EEE1F6ABECCB7AA2`


## Signature

* Status: Signature verified.
* Serial: `33000002CF6D2CC57CAA65A6D80000000002CF`
* Thumbprint: `1A221B3B4FEF088B17BA6704FD088DF192D9E0EF`
* Issuer: CN=Microsoft Code Signing PCA 2010, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Corporation, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: DBGHELP.DLL
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit ARM

## File Scan

* VirusTotal Detections: Unknown
* VirusTotal Link: n/a

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Program Files (x86)\Windows Kits\10\Debuggers\arm64\srcsrv\dbghelp.dll](dbghelp.dll-D8D713C0FDBEAB65FA6AD9F245030B45.md) | 97

## Possible Misuse

*The following table contains possible examples of `dbghelp.dll` being misused. While `dbghelp.dll` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_suspicious_dbghelp_dbgcore_load.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/image_load/sysmon_suspicious_dbghelp_dbgcore_load.yml) | `title: Load of dbghelp/dbgcore DLL from Suspicious Process` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_suspicious_dbghelp_dbgcore_load.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/image_load/sysmon_suspicious_dbghelp_dbgcore_load.yml) | `description: Detects the load of dbghelp/dbgcore DLL (used to make memory dumps) by suspicious processes. Tools like ProcessHacker and some attacker tradecract use MiniDumpWriteDump` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_suspicious_dbghelp_dbgcore_load.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/image_load/sysmon_suspicious_dbghelp_dbgcore_load.yml) | `API found in dbghelp.dll or dbgcore.dll. As an example, SilentTrynity C2 Framework has a module that leverages this API to dump the contents of Lsass.exe and` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_suspicious_dbghelp_dbgcore_load.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/image_load/sysmon_suspicious_dbghelp_dbgcore_load.yml) | `- https://www.pinvoke.net/default.aspx/dbghelp/MiniDumpWriteDump.html` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_suspicious_dbghelp_dbgcore_load.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/image_load/sysmon_suspicious_dbghelp_dbgcore_load.yml) | `- '\dbghelp.dll'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_lsass_memdump.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_access/sysmon_lsass_memdump.yml) | `description: Detects process LSASS memory dump using procdump or taskmgr based on the CallTrace pointing to dbghelp.dll or dbgcore.dll for win10` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_lsass_memdump.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_access/sysmon_lsass_memdump.yml) | `- '*dbghelp.dll*'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_donotteam_ytyframework.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_donotteam_ytyframework.yar) | $s9 = "dbghelp.dll" wide fullword | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)



MIT License. Copyright (c) 2020 Strontic.


