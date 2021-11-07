---
title: wsmprovhost.exe | Host process for WinRM plug-ins
excerpt: What is wsmprovhost.exe?
---

# wsmprovhost.exe 

* File Path: `C:\Windows\system32\wsmprovhost.exe`
* Description: Host process for WinRM plug-ins

## Hashes

Type | Hash
-- | --
MD5 | `FEC31C1BE115BA365D9C10A3F5816F58`
SHA1 | `40D93028788EDE9F982029518E995B966D0055A4`
SHA256 | `F7938766E9BC8363C4A3AC7B1693446849815ECA4E34A240F75C9760151A69B3`
SHA384 | `104EEECC6C948959456F913AAA242B115AB55F67135BAB390388870250C0F6B50AEEEC6995DEA9C83C0DA758CDD150B6`
SHA512 | `DFFD0A85E9050A544F385CC73695C41F333AA82D43E7761D3CE232AD16E352B709B47749A41120D03EC544AA4D71D83731BCDEFD543D9285BB38BE74965E874F`
SSDEEP | `768:R/2ZtZXqoRs+CJrHpHl0NJs59qbBi/0aD3:R/2ZHqoRs+CLH+Py90BisaD`
IMP | `E54118702A5DA1E2A145713FB7D6A53B`
PESHA1 | `3B65D5602B2C8667BEBF14287BFE50FAEAB060F5`
PE256 | `97D29D596920619E8B9326459C58ACD0CD0DB674B1984CF8540278B3595FF2BE`

## Runtime Data

### Open Handles:

Path | Type
-- | --
(R-D)   C:\Windows\System32\en-US\user32.dll.mui | File
(RW-)   C:\Users\user | File
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
C:\Windows\System32\combase.dll |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\System32\msvcrt.dll |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\RPCRT4.dll |
C:\Windows\System32\ucrtbase.dll |
C:\Windows\system32\wsmprovhost.exe |
C:\Windows\system32\WsmSvc.DLL |


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
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/73
* VirusTotal Link: https://www.virustotal.com/gui/file/f7938766e9bc8363c4a3ac7b1693446849815eca4e34a240f75c9760151a69b3/detection


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


