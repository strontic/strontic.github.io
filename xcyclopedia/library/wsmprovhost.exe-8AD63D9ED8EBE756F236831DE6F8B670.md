---
title: wsmprovhost.exe | Host process for WinRM plug-ins
excerpt: What is wsmprovhost.exe?
---

# wsmprovhost.exe 

* File Path: `C:\WINDOWS\system32\wsmprovhost.exe`
* Description: Host process for WinRM plug-ins

## Hashes

Type | Hash
-- | --
MD5 | `8AD63D9ED8EBE756F236831DE6F8B670`
SHA1 | `E6B1E0A3737ACFD4F6881623A2A223B8A8FD2D26`
SHA256 | `814BAEB715C2A74C5CCD5E09DE1154A33FED899F8C45B783F254E8963AFE0EBF`
SHA384 | `91D67FBBB66A85C51CC26E8A9C1D78F70AB303EDACE890B6C6BA91E461CB89C87732E6294628E65DEE1AC87F6B971CC8`
SHA512 | `9A40D1A9C3C64C4A1F53D07316742229BB94C2FD9A83B73BBFBF8004A9825518ADC9B326A94EE1867121BE9923185177BDEA54F26804729C0F89A09F8583F2D7`
SSDEEP | `384:h1fSl04cQWS80PMXwxBh6b1Alkimhn4ol0Bl2RNUhjCu+yboQin5dkLWW7VfWasf:ffdHS/bh6JAy14i0Bl0NyCuxbBiELZC`

## Signature

* Status: Signature verified.
* Serial: `330000023241FB59996DCC4DFF000000000232`
* Thumbprint: `FF82BC38E1DA5E596DF374C53E3617F7EDA36B06`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: wsmprovhost.exe
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.18362.693 (WinBuild.160101.0800)
* Product Version: 10.0.18362.693
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.



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


