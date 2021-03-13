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
MD5 | `620CBF4C26A1E8871F1767C5F00F96E1`
SHA1 | `10E81F33D3DDB1E7A318FA020E5000E58FDD89F8`
SHA256 | `62E620AB5AD80E8E9A9424F776A4F745024591A9F92A7284889E48EBAE597342`
SHA384 | `EFA5A023E535C16F617C01A0AD66D92759621E9C9A8AD3CD4AED82A194CD524A27625DE8012F0178C3B00F2D55982CFE`
SHA512 | `BD67F0560196154AE63F6F28689D9E61E635B38038298CA19E507030C0E15C74CB1F9D22017C829EB7D9313D74E716780B3116F1DCF81D55B890FD634E93AC9A`
SSDEEP | `384:ZBbTa6lzIQJ2bmEl5TpJYxpQU5Rs+U9ixUzeESb9eVKl2RNGLr/PyboQinL7uKW8:ZBvyV5H8ZRs+ClSokl0NGLrqbBiLaVS`

## Runtime Data

### Open Handles:

Path | Type
-- | --
(R-D)   C:\Windows\System32\en-US\user32.dll.mui | File
(RW-)   C:\Users\user | File
\BaseNamedObjects\__ComCatalogCache__ | Section
\BaseNamedObjects\C:\*ProgramData\*Microsoft\*Windows\*Caches\*{6AF0698E-D558-4F6E-9B3C-3716689AF493}.2.ver0x0000000000000002.db | Section
\BaseNamedObjects\C:\*ProgramData\*Microsoft\*Windows\*Caches\*{DDF571F2-BE98-426D-8288-1A9A39C3FDA2}.2.ver0x0000000000000001.db | Section
\BaseNamedObjects\C:\*ProgramData\*Microsoft\*Windows\*Caches\*cversions.2.ro | Section
\BaseNamedObjects\NLS_CodePage_1252_3_2_0_0 | Section
\BaseNamedObjects\NLS_CodePage_437_3_2_0_0 | Section
\Sessions\1\BaseNamedObjects\C:\*ProgramData\*Microsoft\*Windows\*Caches\*{F79646A6-8BE5-443B-A98F-AD03D667F646}.2.ver0x0000000000000001.db | Section
\Sessions\1\BaseNamedObjects\SessionImmersiveColorPreference | Section
\Sessions\1\Windows\Theme1149834063 | Section
\Windows\Theme2597483563 | Section


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
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.


## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Windows\system32\wsmprovhost.exe](wsmprovhost.exe-345926C1D6E692E0054E1B2A61E202EC.md) | 96

## Possible Misuse

*The following table contains possible examples of `wsmprovhost.exe` being misused. While `wsmprovhost.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [powershell_remote_powershell_session.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/powershell/powershell_remote_powershell_session.yml) | `HostApplication\|contains: 'wsmprovhost.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_mimikatz_trough_winrm.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_access/sysmon_mimikatz_trough_winrm.yml) | `description: Detects usage of mimikatz through WinRM protocol by monitoring access to lsass process by wsmprovhost.exe.`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_mimikatz_trough_winrm.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_access/sysmon_mimikatz_trough_winrm.yml) | `SourceImage: 'C:\Windows\system32\wsmprovhost.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_remote_powershell_session_process.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_remote_powershell_session_process.yml) | `description: Detects remote PowerShell sections by monitoring for wsmprovhost as a parent or child process (sign of an active ps remote session)`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_remote_powershell_session_process.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_remote_powershell_session_process.yml) | `- Image\|endswith: '\wsmprovhost.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_remote_powershell_session_process.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_remote_powershell_session_process.yml) | `- ParentImage\|endswith: '\wsmprovhost.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020-2021 Strontic.


