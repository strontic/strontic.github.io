---
title: Procmon.exe | Process Monitor
excerpt: What is Procmon.exe?
---

# Procmon.exe 

* File Path: `C:\SysinternalsSuite\Procmon.exe`
* Description: Process Monitor

## Hashes

Type | Hash
-- | --
MD5 | `EB2A0D7AC44B9B66E884EE5087305ACC`
SHA1 | `BBF29C66AF4CA33B4F18F0B577A7D4E6DD9EB41A`
SHA256 | `92BAA0C5CD23911CFE3C028344524B570288FBEEAB1D2E5233B022841257ADB0`
SHA384 | `69A5CDE443EEA7EC0B1F8C71272EB7568424D9054E35BD99DCCD1945C8E7449A7ABE1C59B4ECD6802BEBC692874AEDB6`
SHA512 | `0B58D1FF1447731FBF35787A653E5140E596ADD06CA762B29C5587EC6FF2BEB3A7D67A4E0722FF39DE99A5004B4FC77F82E94E3F911EC1B36F4C780A4A029658`
SSDEEP | `49152:MWx2ZPsp8QLVMeGZsvdVcSuPgBptM1tt+z9:EPCphNdVcnIBDF`
IMP | `B40205CE8E5F99279FA70374DE4753D1`
PESHA1 | `ED3DC778BBE845475FE6E1DD27B99DE1955A26D8`
PE256 | `9B8569F2D002E635FF44D491EEE3D470D74963F54ED6307336FD285E6975E453`

## Runtime Data

### Child Processes:
Procmon64.exe

### Open Handles:

Path | Type
-- | --
(R-D)   C:\Windows\Fonts\StaticCache.dat | File
(R-D)   C:\Windows\System32\en-US\propsys.dll.mui | File
(R-D)   C:\Windows\SystemResources\imageres.dll.mun | File
(RW-)   C:\Windows | File
(RW-)   C:\Windows\WinSxS\x86_microsoft.windows.common-controls_6595b64144ccf1df_6.0.19041.488_none_11b1e5df2ffd8627 | File
(RW-)   C:\xCyclopedia | File
\BaseNamedObjects\__ComCatalogCache__ | Section
\BaseNamedObjects\C:\*ProgramData\*Microsoft\*Windows\*Caches\*{6AF0698E-D558-4F6E-9B3C-3716689AF493}.2.ver0x0000000000000002.db | Section
\BaseNamedObjects\C:\*ProgramData\*Microsoft\*Windows\*Caches\*{DDF571F2-BE98-426D-8288-1A9A39C3FDA2}.2.ver0x0000000000000002.db | Section
\BaseNamedObjects\C:\*ProgramData\*Microsoft\*Windows\*Caches\*cversions.2 | Section
\BaseNamedObjects\NLS_CodePage_1252_3_2_0_0 | Section
\BaseNamedObjects\NLS_CodePage_437_3_2_0_0 | Section
\BaseNamedObjects\windows_shell_global_counters | Section
\Sessions\1\BaseNamedObjects\SessionImmersiveColorPreference | Section
\Sessions\1\BaseNamedObjects\UrlZonesSM_user | Section
\Sessions\1\BaseNamedObjects\windows_shell_global_counters | Section


### Loaded Modules:

Path |
-- |
C:\SysinternalsSuite\Procmon.exe |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\wow64.dll |
C:\Windows\System32\wow64cpu.dll |
C:\Windows\System32\wow64win.dll |


## Signature

* Status: Signature verified.
* Serial: `3300000187721772155940C709000000000187`
* Thumbprint: `2485A7AFA98E178CB8F30C9838346B514AEA4769`
* Issuer: CN=Microsoft Code Signing PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Corporation, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: Process Monitor
* Product Name: Sysinternals Procmon
* Company Name: Sysinternals - www.sysinternals.com
* File Version: 3.60
* Product Version: 3.60
* Language: English (United States)
* Legal Copyright: Copyright  1996-2020 Mark Russinovich
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/70
* VirusTotal Link: https://www.virustotal.com/gui/file/92baa0c5cd23911cfe3c028344524b570288fbeeab1d2e5233b022841257adb0/detection/

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\SysinternalsSuite\Procmon64.exe](Procmon64.exe-39899AFCF9F1B338AE97B7B407951BEA.md) | 71

## Possible Misuse

*The following table contains possible examples of `Procmon.exe` being misused. While `Procmon.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_user_driver_loaded.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/builtin/win_user_driver_loaded.yml) | `- '*\procmon.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_susp_procexplorer_driver_created_in_tmp_folder.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/file_event/sysmon_susp_procexplorer_driver_created_in_tmp_folder.yml) | `- '*\procmon.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_susp_service_installed.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/registry_event/sysmon_susp_service_installed.yml) | `- '*\procmon.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[stockpile](https://github.com/mitre/stockpile) | [7a6ba833-de40-466a-8969-5c37b13603e0.yml](https://github.com/mitre/stockpile/blob/master/data/abilities/defense-evasion/7a6ba833-de40-466a-8969-5c37b13603e0.yml) | `"procmon",`{:.highlight .language-yaml} | [Apache-2.0](https://github.com/mitre/stockpile/blob/master/LICENSE)



MIT License. Copyright (c) 2020-2021 Strontic.


