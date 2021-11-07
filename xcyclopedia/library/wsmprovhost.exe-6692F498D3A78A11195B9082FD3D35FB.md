---
title: wsmprovhost.exe | Host process for WinRM plug-ins
excerpt: What is wsmprovhost.exe?
---

# wsmprovhost.exe 

* File Path: `C:\Windows\SysWOW64\wsmprovhost.exe`
* Description: Host process for WinRM plug-ins

## Hashes

Type | Hash
-- | --
MD5 | `6692F498D3A78A11195B9082FD3D35FB`
SHA1 | `A5EBCF2C1DCAE8A354E9139C34249657957E44D3`
SHA256 | `519EA677F7F3169121693901DE546B3978DB63203AB96035C9F3FA50C6EA564A`
SHA384 | `1516A00A5C532D6A3EF0C44182D3A50D18FCABB989DB505F07996A0360B9381D09CF48F5A8E7AADA812F4DFD4AFD3D52`
SHA512 | `08C7DC0D7DDEE10C8B3BE1D8B6605DA3F66BF936DC65648968BAC8E8A9A67B9FC2F7773AFA60011B58A02E73BD5BB7FCC09F51E70B11E9979E4A6DC4C07A4214`
SSDEEP | `384:UsKmx9ygrKG3Jrh0qAvqa3FFi6GIBW4brMlphhmW2KymnbxizpOW7OfWI6He:UlU9BK0J8qa3r1G8OhhmW9hn9i1Cl`
IMP | `85FC9DC7C929E91AD67D98751023E144`
PESHA1 | `CE6AA2A11ADD024226FCF29F68DBC1F0961BE1B5`
PE256 | `24236ECC69BEBBDAEE2F51A60BE37BD494099D093E2EDBEEF4B13565C8FF3056`

## Runtime Data

### Open Handles:

Path | Type
-- | --
(R-D)   C:\Windows\SysWOW64\en-US\user32.dll.mui | File
(RW-)   C:\Users\user | File
(RW-)   C:\Windows | File
\BaseNamedObjects\__ComCatalogCache__ | Section
\BaseNamedObjects\C:\*ProgramData\*Microsoft\*Windows\*Caches\*{6AF0698E-D558-4F6E-9B3C-3716689AF493}.2.ver0x0000000000000002.db | Section
\BaseNamedObjects\C:\*ProgramData\*Microsoft\*Windows\*Caches\*{DDF571F2-BE98-426D-8288-1A9A39C3FDA2}.2.ver0x0000000000000002.db | Section
\BaseNamedObjects\C:\*ProgramData\*Microsoft\*Windows\*Caches\*cversions.2 | Section
\BaseNamedObjects\NLS_CodePage_1252_3_2_0_0 | Section
\BaseNamedObjects\NLS_CodePage_437_3_2_0_0 | Section
\Sessions\1\Windows\Theme449731986 | Section
\Windows\Theme1396518710 | Section


### Loaded Modules:

Path |
-- |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\wow64.dll |
C:\Windows\System32\wow64cpu.dll |
C:\Windows\System32\wow64win.dll |
C:\Windows\SysWOW64\wsmprovhost.exe |


## Signature

* Status: Signature verified.
* Serial: `33000002EC6579AD1E670890130000000002EC`
* Thumbprint: `F7C2F2C96A328C13CDA8CDB57B715BDEA2CBD1D9`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: wsmprovhost.exe
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1202 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1202
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/73
* VirusTotal Link: https://www.virustotal.com/gui/file/519ea677f7f3169121693901de546b3978db63203ab96035c9f3fa50c6ea564a/detection

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Windows\SysWOW64\wsmprovhost.exe](wsmprovhost.exe-05997300509B65EF3C3BB7AC0FCCA97F.md) | 91
[C:\Windows\SysWOW64\wsmprovhost.exe](wsmprovhost.exe-8167AB7B0D7E8C5FEC4C2A1806C774F9.md) | 91

## Possible Misuse

*The following table contains possible examples of `wsmprovhost.exe` being misused. While `wsmprovhost.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_in_memory_powershell.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/image_load/sysmon_in_memory_powershell.yml) | `- '\wsmprovhost.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_susp_adfs_namedpipe_connection.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/pipe_created/sysmon_susp_adfs_namedpipe_connection.yml) | `- 'wsmprovhost.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [powershell_classic_remote_powershell_session.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/powershell/powershell_classic/powershell_classic_remote_powershell_session.yml) | `HostApplication\|contains: 'wsmprovhost.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [powershell_remote_powershell_session.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/powershell/powershell_module/powershell_remote_powershell_session.yml) | `- 'wsmprovhost.exe'      #  HostApplication\|contains: 'wsmprovhost.exe' french  Application hôte = `{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_mimikatz_trough_winrm.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_access/sysmon_mimikatz_trough_winrm.yml) | `description: Detects usage of mimikatz through WinRM protocol by monitoring access to lsass process by wsmprovhost.exe.`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_mimikatz_trough_winrm.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_access/sysmon_mimikatz_trough_winrm.yml) | `SourceImage: 'C:\Windows\system32\wsmprovhost.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_shell_spawn_from_winrm.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_access/win_susp_shell_spawn_from_winrm.yml) | `ParentImage: '*\wsmprovhost.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_remote_powershell_session_process.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_remote_powershell_session_process.yml) | `description: Detects remote PowerShell sections by monitoring for wsmprovhost (WinRM host process) as a parent or child process (sign of an active PowerShell remote session).`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_remote_powershell_session_process.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_remote_powershell_session_process.yml) | `- Image\|endswith: '\wsmprovhost.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_remote_powershell_session_process.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_remote_powershell_session_process.yml) | `- ParentImage\|endswith: '\wsmprovhost.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020-2021 Strontic.


