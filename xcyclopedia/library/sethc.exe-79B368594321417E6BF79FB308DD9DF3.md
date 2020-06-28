---
title: sethc.exe | Accessibility shortcut keys
---

# sethc.exe 

* File Path: `C:\Windows\SysWOW64\sethc.exe`
* Description: Accessibility shortcut keys
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `79B368594321417E6BF79FB308DD9DF3`
SHA1 | `5AA90CC89A95C8532117B9FA857C9BAAC88ABB5C`
SHA256 | `D4BB52D9E13A5B26CBCD96F5CE78005FF28B4ECA91E6EC3B86ED31D51AD1472F`
SHA384 | `C8449CD7A231175A1F7688426490816BB13277A7AFBADD687B86221A6B1DA1D1DDF30FB0E72A60E050EE158EE77C237D`
SHA512 | `F661752CB2D877B04AC0452FBC11674A32DEFDF87CCE051132CF9BECA65549993B78CDD17D5D1D073101D7AA0DE23E7B51EC3322FF5EEBCBA8039B1529690ABD`
SSDEEP | `1536:4wCLVHHq2YZSd6IbKIgKd+aKx5Ba9g1qzWO0vmTZB1+hKW/Gz4BgXo:4nq+6ImIrIJHisA4Bg`

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
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Windows\SysWOW64\EaseOfAccessDialog.exe](EaseOfAccessDialog.exe-E3F4970C45200284908BF474D26FCF3E.md) | 46
[C:\WINDOWS\SysWOW64\EaseOfAccessDialog.exe](EaseOfAccessDialog.exe-E76BBB4FA720040460D84005E90D2585.md) | 44
[C:\WINDOWS\SysWOW64\sethc.exe](sethc.exe-0E6CDF17D71D663ECA4659AAA94735DB.md) | 50

## Possible Misuse

*The following table contains possible examples of `sethc.exe` being misused. While `sethc.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_install_reg_debugger_backdoor.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_install_reg_debugger_backdoor.yml) | `            - '*\CurrentVersion\Image File Execution Options\sethc.exe*'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_stickykey_like_backdoor.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/sysmon/sysmon_stickykey_like_backdoor.yml) | `            - '*\SOFTWARE\Microsoft\Windows NT\CurrentVersion\Image File Execution Options\sethc.exe\Debugger'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_stickykey_like_backdoor.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/sysmon/sysmon_stickykey_like_backdoor.yml) | `            - '*cmd.exe sethc.exe *'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1546.008.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1546.008/T1546.008.md) | Two common accessibility programs are <code>C:\Windows\System32\sethc.exe</code>, launched when the shift key is pressed five times and <code>C:\Windows\System32\utilman.exe</code>, launched when the Windows + U key combination is pressed. The sethc.exe program is often referred to as "sticky keys", and has been used by adversaries for unauthenticated access through a remote desktop login screen. (Citation: FireEye Hikit Rootkit) | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1546.008.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1546.008/T1546.008.md) | \| parent_list \| Comma separated list of system binaries to which you want to attach each #{attached_process}. Default: "osk.exe" \| String \| osk.exe, sethc.exe, utilman.exe, magnify.exe, narrator.exe, DisplaySwitch.exe, atbroker.exe\| | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)



MIT License. Copyright (c) 2020 Strontic.


