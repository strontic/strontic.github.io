---
title: sethc.exe | Accessibility shortcut keys
---

# sethc.exe 

* File Path: `C:\WINDOWS\SysWOW64\sethc.exe`
* Description: Accessibility shortcut keys
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `0E6CDF17D71D663ECA4659AAA94735DB`
SHA1 | `7BF5163B0F870AD28B6C60B5EEDF6E667990B356`
SHA256 | `408E8B6C66411A1F3E05E5FD330B1B921E63FE3DBDF436C17F9670FE72BA76B6`
SHA384 | `84DF2514C33622078577E40717B9A24A41B4EA404C33E898756EA35E3D1B28CF3716395833C55724EA46DF6AE02BBDDE`
SHA512 | `D1AE02BC7D8BA87836B31DCB5DFE069A80ED87617127198A6FEA9594D2941F56CA19EC095EDA765177501A52DFB9DF4E997F768ADBCD5AA490C5E04E4A3C2504`
SSDEEP | `1536:P+a0Kgw4XuTQD4gyB0HN5g5r1qzWO0vmTZB1+hKW/Gzg30:f0K2+T0Kut5g5lAg30`

## Runtime Data

### Usage (stdout):
```Batchfile

```

### Usage (stderr):
```Batchfile

```

### Child Processes:


## Signature

* Status: Signature verified.
* Serial: `330000023241FB59996DCC4DFF000000000232`
* Thumbprint: `FF82BC38E1DA5E596DF374C53E3617F7EDA36B06`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: sethc.exe
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.18362.449 (WinBuild.160101.0800)
* Product Version: 10.0.18362.449
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Windows\SysWOW64\EaseOfAccessDialog.exe](EaseOfAccessDialog.exe-E3F4970C45200284908BF474D26FCF3E.md) | 47
[C:\WINDOWS\SysWOW64\EaseOfAccessDialog.exe](EaseOfAccessDialog.exe-E76BBB4FA720040460D84005E90D2585.md) | 43
[C:\Windows\SysWOW64\sethc.exe](sethc.exe-79B368594321417E6BF79FB308DD9DF3.md) | 50

## Possible Misuse

*The following table contains possible examples of `sethc.exe` being misused. While `sethc.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_install_reg_debugger_backdoor.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_install_reg_debugger_backdoor.yml) | `            - '*\CurrentVersion\Image File Execution Options\sethc.exe*'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_stickykey_like_backdoor.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/registry_event/sysmon_stickykey_like_backdoor.yml) | `            - '*\SOFTWARE\Microsoft\Windows NT\CurrentVersion\Image File Execution Options\sethc.exe\Debugger'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_stickykey_like_backdoor.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/registry_event/sysmon_stickykey_like_backdoor.yml) | `            - '*cmd.exe sethc.exe *'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1546.008.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1546.008/T1546.008.md) | Two common accessibility programs are <code>C:\Windows\System32\sethc.exe</code>, launched when the shift key is pressed five times and <code>C:\Windows\System32\utilman.exe</code>, launched when the Windows + U key combination is pressed. The sethc.exe program is often referred to as "sticky keys", and has been used by adversaries for unauthenticated access through a remote desktop login screen. (Citation: FireEye Hikit Rootkit) | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1546.008.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1546.008/T1546.008.md) | \| parent_list \| Comma separated list of system binaries to which you want to attach each #{attached_process}. Default: "osk.exe" \| String \| osk.exe, sethc.exe, utilman.exe, magnify.exe, narrator.exe, DisplaySwitch.exe, atbroker.exe\| | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)



MIT License. Copyright (c) 2020 Strontic.


