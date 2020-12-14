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
MD5 | `345926C1D6E692E0054E1B2A61E202EC`
SHA1 | `B1A32230391B6D87D255053DE0FD262C8329DDB8`
SHA256 | `0FBB9BE7CA2AAFDE4ED8614A3A9DEF68E5AF1A2CB2E15D6CBCBF7B72F4DCD3B6`
SHA384 | `00677AA6CE6EB666B2032BC7D8AA8F9D2B5C0ACB69E294F53EE51CACFDAFF19E969B7E5054330D3890FF822CDDB9A759`
SHA512 | `6F569BA2E9F9E8ECD4162B1D649B29E5AD74466AF2EDE8DCF24EA0E209F66307C962D450EDEC5D1F213A62665624578F0A156106AE86C66D8322F1E046170544`
SSDEEP | `384:CBbTa6lzIQJ2bmEl5TpJYxpQU5Rs+U9ixUzeESb9eVKl2RNGLr/PyboQinL7ueW0:CBvyV5H8ZRs+ClSokl0NGLrqbBiLaAj`
IMP | `E54118702A5DA1E2A145713FB7D6A53B`
PESHA1 | `B844888BCF722E0CB82AF20E448B060A40B80891`
PE256 | `7EFFEAC7EACF591FB2AF21C40C758FEEC27950BA0E34B0A597F282B3FDD3991A`

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
\Sessions\1\Windows\Theme1175649999 | Section
\Windows\Theme601709542 | Section


### Loaded Modules:

Path |
-- |
C:\Windows\System32\combase.dll |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\System32\msvcp_win.dll |
C:\Windows\System32\msvcrt.dll |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\OLEAUT32.dll |
C:\Windows\System32\RPCRT4.dll |
C:\Windows\System32\ucrtbase.dll |
C:\Windows\system32\wsmprovhost.exe |
C:\Windows\system32\WsmSvc.DLL |


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: wsmprovhost.exe
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.488 (WinBuild.160101.0800)
* Product Version: 10.0.19041.488
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/76
* VirusTotal Link: https://www.virustotal.com/gui/file/0fbb9be7ca2aafde4ed8614a3a9def68e5af1a2cb2e15d6cbcbf7b72f4dcd3b6/detection

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Windows\system32\wsmprovhost.exe](wsmprovhost.exe-620CBF4C26A1E8871F1767C5F00F96E1.md) | 96

## Possible Misuse

*The following table contains possible examples of `wsmprovhost.exe` being misused. While `wsmprovhost.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [powershell_remote_powershell_session.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/powershell/powershell_remote_powershell_session.yml) | `HostApplication\|contains: 'wsmprovhost.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_mimikatz_trough_winrm.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_access/sysmon_mimikatz_trough_winrm.yml) | `description: Detects usage of mimikatz through WinRM protocol by monitoring access to lsass process by wsmprovhost.exe.` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_mimikatz_trough_winrm.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_access/sysmon_mimikatz_trough_winrm.yml) | `SourceImage: 'C:\Windows\system32\wsmprovhost.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_remote_powershell_session_process.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_remote_powershell_session_process.yml) | `description: Detects remote PowerShell sections by monitoring for wsmprovhost as a parent or child process (sign of an active ps remote session)` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_remote_powershell_session_process.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_remote_powershell_session_process.yml) | `- Image\|endswith: '\wsmprovhost.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_remote_powershell_session_process.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_remote_powershell_session_process.yml) | `- ParentImage\|endswith: '\wsmprovhost.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020 Strontic.


