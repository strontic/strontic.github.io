---
title: dbgcore.dll | Windows Core Debugging Helpers
excerpt: What is dbgcore.dll?
---

# dbgcore.dll 

* File Path: `C:\Program Files (x86)\Windows Kits\10\Debuggers\arm64\dbgcore.dll`
* Description: Windows Core Debugging Helpers

## Hashes

Type | Hash
-- | --
MD5 | `E0E1571F0E3CF5F55A40575DC0958271`
SHA1 | `AB62912BD51037264ACD6D6D7B89D4DB0EADB985`
SHA256 | `DE927FBCD3F8ECE16EF13067BA7FE1C9C6C2731FFCF86CBE858B752A3B7B16B8`
SHA384 | `017BB6E9BBD1FD2F4B21E54DB61DE49CCDFD823BFDA6872F9887D5F0F3556568358A12E66B061A0BAE6C09769F624461`
SHA512 | `F5939864864A4D1173A62CFA60EF09A6B1749D10326A26BC7EACE3D43D092D8AEA05C22265C0F165C309C3424181D9FC592D0EDEA47FF9377E4E5652A43372FF`
SSDEEP | `3072:wEVY9LNBeRSV8zVU2zqH/gNHHFjyItCDPU6KgASB0ddOyYgOxTsombAay8kY:wywX0SVW6LH/gNFjZCDPzASB0ddO3aye`
IMP | `226ECB2A33EFE15D0F17C78CA601BDEB`
PESHA1 | `CD05AC5C586B4F128A66570E6078AD20B23B060A`
PE256 | `59324828EB48D13876669EF8898D6B24E724433F0FE44B75BFE20C6C80D4E6DA`


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
* Machine Type: 64-bit ARM

## File Scan

* VirusTotal Detections: Unknown
* VirusTotal Link: n/a

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Program Files (x86)\Windows Kits\10\Debuggers\arm64\srcsrv\dbgcore.dll](dbgcore.dll-50F6AF4FE83736A5EEEFB4CCE33D187C.md) | 96
[C:\Program Files (x86)\Windows Kits\10\Debuggers\x64\dbgcore.dll](dbgcore.dll-DC40CB46D05EF450684E1A1A09C0CFE3.md) | 40
[C:\Program Files (x86)\Windows Kits\10\Debuggers\x64\srcsrv\dbgcore.dll](dbgcore.dll-89A977B69952BC8941F5600C4B24022F.md) | 40
[C:\Windows\system32\dbgcore.dll](dbgcore.dll-5CA8253328BA74B02D867A5F40305F9B.md) | 40

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


