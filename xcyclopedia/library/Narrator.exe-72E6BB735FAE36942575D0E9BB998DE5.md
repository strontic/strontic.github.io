---
title: Narrator.exe | Screen Reader
---

# Narrator.exe 

* File Path: `C:\windows\system32\Narrator.exe`
* Description: Screen Reader
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `72E6BB735FAE36942575D0E9BB998DE5`
SHA1 | `2119746F730403BF15D9F44F0FFB8E642B95C9B3`
SHA256 | `7CB42636E62C41160BDC26882AC3347F30E277D54835EA30E1E847519E5CD229`
SHA384 | `24361A32BE55215817DB92A438703FA31D0C04FE031DE15C652EC5522E5BD9B41F9C3914A1CE1F2C5848E334AAFFABF1`
SHA512 | `9E20D6D076F846711B7AA878539FDCEFBA73CC5494863346695D4B716F841796DF209325036AE0D19894F2E0EB334F0809E8E1577A9E6E869DA351B8E743251E`
SSDEEP | `6144:QpaUuFEcH1sbDUZujO34yoVAjk9AQFgZKUV:suFESmDUCOr3kiAuV`

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
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: SR.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.17763.1 (WinBuild.160101.0800)
* Product Version: 10.0.17763.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Windows\system32\Narrator.exe](Narrator.exe-E70F18EA635D530B901D5EC31451DDB8.md) | 32

## Possible Misuse

*The following table contains possible examples of `Narrator.exe` being misused. While `Narrator.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_install_reg_debugger_backdoor.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_install_reg_debugger_backdoor.yml) | `            - '*\CurrentVersion\Image File Execution Options\narrator.exe*'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_narrator_feedback_persistance.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/registry_event/sysmon_narrator_feedback_persistance.yml) | `title: Narrator's Feedback-Hub Persistence` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_narrator_feedback_persistance.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/registry_event/sysmon_narrator_feedback_persistance.yml) | `description: Detects abusing Windows 10 Narrator's Feedback-Hub` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_stickykey_like_backdoor.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/registry_event/sysmon_stickykey_like_backdoor.yml) | `            - '*\SOFTWARE\Microsoft\Windows NT\CurrentVersion\Image File Execution Options\Narrator.exe\Debugger'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_stickykey_like_backdoor.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/registry_event/sysmon_stickykey_like_backdoor.yml) | `            - '*cmd.exe Narrator.exe *'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_narrator_feedback_persistance.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/sysmon/sysmon_narrator_feedback_persistance.yml) | `title: Narrator's Feedback-Hub Persistence` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_narrator_feedback_persistance.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/sysmon/sysmon_narrator_feedback_persistance.yml) | `description: Detects abusing Windows 10 Narrator's Feedback-Hub` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_stickykey_like_backdoor.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/sysmon/sysmon_stickykey_like_backdoor.yml) | `            - '*\SOFTWARE\Microsoft\Windows NT\CurrentVersion\Image File Execution Options\Narrator.exe\Debugger'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_stickykey_like_backdoor.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/sysmon/sysmon_stickykey_like_backdoor.yml) | `            - '*cmd.exe Narrator.exe *'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1546.008.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1546.008/T1546.008.md) | * Narrator: <code>C:\Windows\System32\Narrator.exe</code> | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1546.008.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1546.008/T1546.008.md) | \| parent_list \| Comma separated list of system binaries to which you want to attach each #{attached_process}. Default: "osk.exe" \| String \| osk.exe, sethc.exe, utilman.exe, magnify.exe, narrator.exe, DisplaySwitch.exe, atbroker.exe\| | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)



MIT License. Copyright (c) 2020 Strontic.


