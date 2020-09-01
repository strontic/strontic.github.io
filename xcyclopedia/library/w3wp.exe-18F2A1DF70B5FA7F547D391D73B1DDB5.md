---
title: w3wp.exe | IIS Worker Process
---

# w3wp.exe 

* File Path: `C:\windows\SysWOW64\inetsrv\w3wp.exe`
* Description: IIS Worker Process

## Hashes

Type | Hash
-- | --
MD5 | `18F2A1DF70B5FA7F547D391D73B1DDB5`
SHA1 | `DF775D31C3ABBDA6BF9FD6AD35610D179CD6357B`
SHA256 | `BBECEB8DBEB159152B1D1B63AA4A23BB97A93EE7E63271213C181D3064F2DDF3`
SHA384 | `F00DB7AB22FD187DFF74A10BA8AD20E9A62DB73AE4D804DC78EF6224A0671A9EE9214D65A70BB4387B956D11988DF3BA`
SHA512 | `005797943BC340E5ED4CA0BB7D18EDE1A42706A6511E2E4B75AEE9944CD16353AC86A36265492D8462F8C083CF4A8E485A578E6124C44A8BBE6480072D3DD966`
SSDEEP | `384:aaI3JPdnZePRLWX5GpSMJGjG4kvvWSubaIXe:RAJPxZePRHSPjRkvFme`

### Loaded Modules:

Path |
-- |
C:\Windows\SYSTEM32\ntdll.dll |


## Signature

* Status: The file C:\windows\SysWOW64\inetsrv\w3wp.exe is not digitally signed. You cannot run this script on the current system. For more information about running scripts and setting execution policy, see about_Execution_Policies at http://go.microsoft.com/fwlink/?LinkID=135170
* Serial: ``
* Thumbprint: ``
* Issuer: 
* Subject: 

## File Metadata

* Original Filename: w3wp.exe.mui
* Product Name: Internet Information Services
* Company Name: Microsoft Corporation
* File Version: 8.5.9600.16384 (winblue_rtm.130821-1623)
* Product Version: 8.5.9600.16384
* Language: Language Neutral
* Legal Copyright:  Microsoft Corporation. All rights reserved.


## Possible Misuse

*The following table contains possible examples of `w3wp.exe` being misused. While `w3wp.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [godmode_sigma_rule.yml](https://github.com/Neo23x0/sigma/blob/master/other/godmode_sigma_rule.yml) | `            - '\w3wp.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_csc_folder.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_csc_folder.yml) | `            - '*\w3wp.exe'  # https://twitter.com/gabriele_pippi/status/1206907900268072962` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_powershell_parent_process.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_powershell_parent_process.yml) | `            - '\w3wp.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_webshell_detection.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_webshell_detection.yml) | `            - '*\w3wp.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_webshell_recon_detection.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_webshell_recon_detection.yml) | `            - '*\w3wp.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_webshell_spawn.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_webshell_spawn.yml) | `            - '*\w3wp.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_suspicious_remote_thread.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/sysmon/sysmon_suspicious_remote_thread.yml) | `            - '\w3wp.exe*'       ` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020 Strontic.


