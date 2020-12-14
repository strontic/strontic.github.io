---
title: Taskmgr.exe | Task Manager
excerpt: What is Taskmgr.exe?
---

# Taskmgr.exe 

* File Path: `C:\Windows\system32\Taskmgr.exe`
* Description: Task Manager

## Screenshot

![Taskmgr.exe](screenshots/Taskmgr.exe-BE497D144DBC4F9689AA9846033D2A95-1.png)

## Hashes

Type | Hash
-- | --
MD5 | `44E41BABF9676B9296D8A5719A9ACECC`
SHA1 | `10D7BAAA772F31B8E3B1F63CD2C8FA71492B5D23`
SHA256 | `793CA2ED06301D0AE8BB590254380E71A91E0EFDEDCE825FB9367D31D02B1D27`
SHA384 | `5D1B1CAF2F55D81DA2FAA08F63CF843BFABCC1A14E542BE6286A07E15EA44647479FD10F1D3B591941C1E57105BC15CD`
SHA512 | `758F3375B300F1D77BEED95A0A3A7120932A089072C28828C39B3C2D44F4DB8192F2173EDEBE321A83E48D580D8A9E4BF10607DDD1E16958826C130C55980730`
SSDEEP | `24576:JdUilwcPxRSPydIY+SaYLoitMvIIYxBopASEfGJ8Q21dgb25:owxRS6dIYdLIIIYxBUEfGJB21dg`
IMP | `9905CD1DB600EE86C64A86E4F49A7378`
PESHA1 | `56FFD129EF621E8049052DF788F6D3C60560BDA9`
PE256 | `54E2986865F1A3B91882F5A5ABE4B2B8B7332246949956C94657D7D7EA5802DF`

## Runtime Data

### Window Title:
Task Manager

### Open Handles:

Path | Type
-- | --
(R-D)   C:\Windows\apppatch\DirectXApps_FOD.sdb | File
(R-D)   C:\Windows\Fonts\StaticCache.dat | File
(R-D)   C:\Windows\System32\en-US\oleaccrc.dll.mui | File
(R-D)   C:\Windows\System32\en-US\propsys.dll.mui | File
(R-D)   C:\Windows\System32\en-US\Taskmgr.exe.mui | File
(R-D)   C:\Windows\SystemResources\Taskmgr.exe.mun | File
(RW-)   C:\Users\user | File
(RW-)   C:\Windows\WinSxS\amd64_microsoft.windows.common-controls_6595b64144ccf1df_6.0.19041.488_none_ca04af081b815d21 | File
(RWD)   C:\Users\user\AppData\Local\Microsoft\Windows\Explorer\iconcache_16.db | File
(RWD)   C:\Users\user\AppData\Local\Microsoft\Windows\Explorer\iconcache_idx.db | File
\BaseNamedObjects\__ComCatalogCache__ | Section
\BaseNamedObjects\C:\*ProgramData\*Microsoft\*Windows\*Caches\*{6AF0698E-D558-4F6E-9B3C-3716689AF493}.2.ver0x0000000000000002.db | Section
\BaseNamedObjects\C:\*ProgramData\*Microsoft\*Windows\*Caches\*{DDF571F2-BE98-426D-8288-1A9A39C3FDA2}.2.ver0x0000000000000002.db | Section
\BaseNamedObjects\C:\*ProgramData\*Microsoft\*Windows\*Caches\*cversions.2 | Section
\BaseNamedObjects\NLS_CodePage_1252_3_2_0_0 | Section
\BaseNamedObjects\NLS_CodePage_437_3_2_0_0 | Section
\Sessions\1\BaseNamedObjects\C:\*Users\*user\*AppData\*Local\*Microsoft\*Windows\*Caches\*{3DA71D5A-20CC-432F-A115-DFE92379E91F}.3.ver0x0000000000000009.db | Section
\Sessions\1\BaseNamedObjects\C:\*Users\*user\*AppData\*Local\*Microsoft\*Windows\*Caches\*cversions.3.ro | Section
\Sessions\1\BaseNamedObjects\SessionImmersiveColorPreference | Section
\Sessions\1\BaseNamedObjects\windows_shell_global_counters | Section
\Sessions\1\Windows\Theme1175649999 | Section
\Windows\Theme601709542 | Section


### Loaded Modules:

Path |
-- |
C:\Windows\System32\combase.dll |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\System32\msvcp_win.dll |
C:\Windows\System32\NSI.dll |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\OLEAUT32.dll |
C:\Windows\SYSTEM32\powrprof.dll |
C:\Windows\System32\RPCRT4.dll |
C:\Windows\system32\Taskmgr.exe |
C:\Windows\System32\ucrtbase.dll |


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: Taskmgr.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.662 (WinBuild.160101.0800)
* Product Version: 10.0.19041.662
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/74
* VirusTotal Link: https://www.virustotal.com/gui/file/793ca2ed06301d0ae8bb590254380e71a91e0efdedce825fb9367d31d02b1d27/detection


## Possible Misuse

*The following table contains possible examples of `Taskmgr.exe` being misused. While `Taskmgr.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_alert_lsass_access.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/builtin/win_alert_lsass_access.yml) | `- Some Taskmgr.exe related activity` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_lsass_dump_generic.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/builtin/win_susp_lsass_dump_generic.yml) | `- '\taskmgr.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_creation_system_file.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/file_event/sysmon_creation_system_file.yml) | `- '*\Taskmgr.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_creation_system_file.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/file_event/sysmon_creation_system_file.yml) | `- '*\taskmgr.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_cred_dump_lsass_access.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_access/sysmon_cred_dump_lsass_access.yml) | `- '\taskmgr.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_lsass_memdump.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_access/sysmon_lsass_memdump.yml) | `description: Detects process LSASS memory dump using procdump or taskmgr based on the CallTrace pointing to dbghelp.dll or dbgcore.dll for win10` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_lsass_memdump.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_access/sysmon_lsass_memdump.yml) | `- https://blog.menasec.net/2019/02/threat-hunting-21-procdump-or-taskmgr.html` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_taskmgr_localsystem.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_taskmgr_localsystem.yml) | `title: Taskmgr as LOCAL_SYSTEM` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_taskmgr_localsystem.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_taskmgr_localsystem.yml) | `description: Detects the creation of taskmgr.exe process in context of LOCAL_SYSTEM` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_taskmgr_localsystem.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_taskmgr_localsystem.yml) | `Image: '*\taskmgr.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_taskmgr_parent.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_taskmgr_parent.yml) | `title: Taskmgr as Parent` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_taskmgr_parent.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_taskmgr_parent.yml) | `ParentImage: '*\taskmgr.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_taskmgr_parent.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_taskmgr_parent.yml) | `- '*\taskmgr.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_system_exe_anomaly.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_system_exe_anomaly.yml) | `- '*\Taskmgr.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[signature-base](https://github.com/Neo23x0/signature-base) | [crime_cn_campaign_njrat.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/crime_cn_campaign_njrat.yar) | $a3 = "taskkill /f /im taskmgr.exe" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [gen_cn_hacktools.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/gen_cn_hacktools.yar) | $s2 = "Kiwi Taskmgr no-gpo" fullword wide | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [thor_inverse_matches.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/thor_inverse_matches.yar) | description = "Anomaly rule looking for certain strings in a system file (maybe false positive on certain systems) - file taskmgr.exe" | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [thor_inverse_matches.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/thor_inverse_matches.yar) | $s1 = "taskmgr.chm" fullword | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [thor_inverse_matches.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/thor_inverse_matches.yar) | ( filename == "taskmgr.exe" or filename == "Taskmgr.exe" ) and not 1 of ($s*) and not WINDOWS_UPDATE_BDC | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)



MIT License. Copyright (c) 2020 Strontic.


