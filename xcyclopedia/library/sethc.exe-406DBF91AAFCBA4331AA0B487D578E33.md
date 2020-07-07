---
title: sethc.exe | Accessibility shortcut keys
---

# sethc.exe 

* File Path: `C:\windows\SysWOW64\sethc.exe`
* Description: Accessibility shortcut keys
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `406DBF91AAFCBA4331AA0B487D578E33`
SHA1 | `D0F39007C0E9BA21B62D7BE40EE7EFCC9B1C2189`
SHA256 | `708DCEEDC93B0DA05583E0320FBD36B952E1DBA1F5C896CCAC2FBF1BA0D86C17`
SHA384 | `7DB7F3F4AB13CE16DD76C091FB4DA97D1472CA60E4EFA868BB7F9ABA37577D1FAED19C687B3E561B92929909E50A5941`
SHA512 | `42B446D02320B9A86B9B43517AD410336D7D6DF41FB391D8A0BFAA39919C6017E19A00866239FECD276F6BC34997BECD1DEC5EC6FD7F6A7CF874DD9560D334D6`
SSDEEP | `6144:+gGAJhJYQYH8AlGr66uFz2LJGRg4kLNnei36cw:i8LYhjFCdUc`

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
* Serial: `33000001C422B2F79B793DACB20000000001C4`
* Thumbprint: `AE9C1AE54763822EEC42474983D8B635116C8452`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: sethc.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.17763.1 (WinBuild.160101.0800)
* Product Version: 10.0.17763.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\windows\system32\EaseOfAccessDialog.exe](EaseOfAccessDialog.exe-1EF5808E2ADC8AD7892E45551CE5C5CF.md) | 63
[C:\Windows\system32\EaseOfAccessDialog.exe](EaseOfAccessDialog.exe-6CF3E7D021A16A86178F840D787F2E4C.md) | 63
[C:\Windows\system32\EaseOfAccessDialog.exe](EaseOfAccessDialog.exe-9A846ED516E009A8409800B19402EF39.md) | 66
[C:\Windows\system32\sethc.exe](sethc.exe-0D68CE0D6D390F926B4ECE77E44D4E30.md) | 61
[C:\windows\system32\sethc.exe](sethc.exe-EE69991DCEA4CA4189F42DEEE5D7666A.md) | 61
[C:\Windows\system32\sethc.exe](sethc.exe-F00FAB17E7FE21D930AA4A6CABD2381F.md) | 74
[C:\Windows\SysWOW64\EaseOfAccessDialog.exe](EaseOfAccessDialog.exe-1913FD496CAFF87B409FAC35CD876274.md) | 58
[C:\windows\SysWOW64\EaseOfAccessDialog.exe](EaseOfAccessDialog.exe-69D795102CADA9D5FEC1089138DA48AF.md) | 65
[C:\Windows\SysWOW64\EaseOfAccessDialog.exe](EaseOfAccessDialog.exe-C5897612D16810BE94A68C5EB6950598.md) | 68
[C:\windows\SysWOW64\sethc.exe](sethc.exe-5EBDA250D9AD873C3879282AC6F49FB7.md) | 65
[C:\Windows\SysWOW64\sethc.exe](sethc.exe-9FE388226A8EF1B085441E21A3B0A57D.md) | 58

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


