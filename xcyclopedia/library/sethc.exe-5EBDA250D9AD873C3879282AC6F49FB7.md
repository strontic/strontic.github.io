﻿---
title: sethc.exe | Accessibility shortcut keys
---

# sethc.exe 

* File Path: `C:\windows\SysWOW64\sethc.exe`
* Description: Accessibility shortcut keys
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `5EBDA250D9AD873C3879282AC6F49FB7`
SHA1 | `4D1E70C0C8507794E6239EEE16C54C310C3C5AA6`
SHA256 | `10FB638DC9C7E7D0961ACE87320A0BD7CA48918BBB818038AC807B1172033C36`
SHA384 | `73A7CEDAA9AE10B958EB76D32321E443751763413332504A77794351B0814704E556ED2B7CCA4C112DE6A078EE016CCB`
SHA512 | `73F6FCC46FF0C84CBB3561718E3C2F28894AE203E42EE179701B14D3835FD76F19DF4595E3E55658BC0B3E1D1E97A3F1D9EB1FCDC99544A1A399A297AF625397`
SSDEEP | `6144:5XzrCPOj+jC6uFz2LJGRg4kLNnei36cw:QwFCdUc`

## Runtime Data

### Usage (stdout):
```Batchfile

```

### Usage (stderr):
```Batchfile

```

### Child Processes:


## Signature

* Status: The file C:\windows\SysWOW64\sethc.exe is not digitally signed. You cannot run this script on the current system. For more information about running scripts and setting execution policy, see about_Execution_Policies at http://go.microsoft.com/fwlink/?LinkID=135170
* Serial: ``
* Thumbprint: ``
* Issuer: 
* Subject: 

## File Metadata

* Original Filename: sethc.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 6.3.9600.16384 (winblue_rtm.130821-1623)
* Product Version: 6.3.9600.16384
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\windows\system32\EaseOfAccessDialog.exe](EaseOfAccessDialog.exe-1EF5808E2ADC8AD7892E45551CE5C5CF.md) | 82
[C:\Windows\system32\EaseOfAccessDialog.exe](EaseOfAccessDialog.exe-6CF3E7D021A16A86178F840D787F2E4C.md) | 80
[C:\Windows\system32\EaseOfAccessDialog.exe](EaseOfAccessDialog.exe-9A846ED516E009A8409800B19402EF39.md) | 63
[C:\Windows\system32\sethc.exe](sethc.exe-0D68CE0D6D390F926B4ECE77E44D4E30.md) | 79
[C:\windows\system32\sethc.exe](sethc.exe-EE69991DCEA4CA4189F42DEEE5D7666A.md) | 82
[C:\Windows\system32\sethc.exe](sethc.exe-F00FAB17E7FE21D930AA4A6CABD2381F.md) | 63
[C:\Windows\SysWOW64\EaseOfAccessDialog.exe](EaseOfAccessDialog.exe-1913FD496CAFF87B409FAC35CD876274.md) | 74
[C:\windows\SysWOW64\EaseOfAccessDialog.exe](EaseOfAccessDialog.exe-69D795102CADA9D5FEC1089138DA48AF.md) | 77
[C:\Windows\SysWOW64\EaseOfAccessDialog.exe](EaseOfAccessDialog.exe-C5897612D16810BE94A68C5EB6950598.md) | 65
[C:\Windows\SysWOW64\sethc.exe](sethc.exe-406DBF91AAFCBA4331AA0B487D578E33.md) | 65
[C:\Windows\SysWOW64\sethc.exe](sethc.exe-9FE388226A8EF1B085441E21A3B0A57D.md) | 74

## Possible Misuse

*The following table contains possible examples of `sethc.exe` being misused. While `sethc.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_install_reg_debugger_backdoor.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_install_reg_debugger_backdoor.yml) | `            - '*\CurrentVersion\Image File Execution Options\sethc.exe*'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_stickykey_like_backdoor.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/registry_event/sysmon_stickykey_like_backdoor.yml) | `            - '*\SOFTWARE\Microsoft\Windows NT\CurrentVersion\Image File Execution Options\sethc.exe\Debugger'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_stickykey_like_backdoor.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/registry_event/sysmon_stickykey_like_backdoor.yml) | `            - '*cmd.exe sethc.exe *'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_stickykey_like_backdoor.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/sysmon/sysmon_stickykey_like_backdoor.yml) | `            - '*\SOFTWARE\Microsoft\Windows NT\CurrentVersion\Image File Execution Options\sethc.exe\Debugger'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_stickykey_like_backdoor.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/sysmon/sysmon_stickykey_like_backdoor.yml) | `            - '*cmd.exe sethc.exe *'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1546.008.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1546.008/T1546.008.md) | Two common accessibility programs are <code>C:\Windows\System32\sethc.exe</code>, launched when the shift key is pressed five times and <code>C:\Windows\System32\utilman.exe</code>, launched when the Windows + U key combination is pressed. The sethc.exe program is often referred to as "sticky keys", and has been used by adversaries for unauthenticated access through a remote desktop login screen. (Citation: FireEye Hikit Rootkit) | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1546.008.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1546.008/T1546.008.md) | \| parent_list \| Comma separated list of system binaries to which you want to attach each #{attached_process}. Default: "osk.exe" \| String \| osk.exe, sethc.exe, utilman.exe, magnify.exe, narrator.exe, DisplaySwitch.exe, atbroker.exe\| | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)



MIT License. Copyright (c) 2020 Strontic.

