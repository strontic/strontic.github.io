---
title: Narrator.exe | Screen Reader
---

# Narrator.exe 

* File Path: `C:\WINDOWS\system32\Narrator.exe`
* Description: Screen Reader
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `503BF6A9F3166CA04949AFB82D0CABF9`
SHA1 | `4B5B4180980335EED4878AD3FF8861755F4CEB79`
SHA256 | `F99C747B0A22172BEF6158EB5855EA5A5B4F758F9DE6274A5CF85593ECDCFF8F`
SHA384 | `028B814CDD4E8E44D1B9971D71F524A1DE0BBB9928868DE934888260B0D44DAE93586131E717D5A4EC896CDD48EDF300`
SHA512 | `74168F4FE678B926B247DA539CB5CEE3A10F5C9D563B24B4491757E29E1BE4FDDC9FCBC33B6095A426684C3D646617300EC667AD3F3F15A58A4620D5D55957E3`
SSDEEP | `6144:AfEpTAwIWqIq83D2NKPgtHBKnV942qjn6+5v6fUTfzyX:fpTtIWq6SNKPgtHBQy6+cozy`

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

* Original Filename: SR.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.18362.1 (WinBuild.160101.0800)
* Product Version: 10.0.18362.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.


## Possible Misuse

*The following table contains possible examples of `Narrator.exe` being misused. While `Narrator.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_install_reg_debugger_backdoor.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_install_reg_debugger_backdoor.yml) | `            - '*\CurrentVersion\Image File Execution Options\narrator.exe*'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_narrator_feedback_persistance.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/registry_event/sysmon_narrator_feedback_persistance.yml) | `title: Narrator's Feedback-Hub Persistence` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_narrator_feedback_persistance.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/registry_event/sysmon_narrator_feedback_persistance.yml) | `description: Detects abusing Windows 10 Narrator's Feedback-Hub` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_stickykey_like_backdoor.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/registry_event/sysmon_stickykey_like_backdoor.yml) | `            - '*\SOFTWARE\Microsoft\Windows NT\CurrentVersion\Image File Execution Options\Narrator.exe\Debugger'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_stickykey_like_backdoor.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/registry_event/sysmon_stickykey_like_backdoor.yml) | `            - '*cmd.exe Narrator.exe *'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1546.008.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1546.008/T1546.008.md) | * Narrator: <code>C:\Windows\System32\Narrator.exe</code> | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1546.008.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1546.008/T1546.008.md) | \| parent_list \| Comma separated list of system binaries to which you want to attach each #{attached_process}. Default: "osk.exe" \| String \| osk.exe, sethc.exe, utilman.exe, magnify.exe, narrator.exe, DisplaySwitch.exe, atbroker.exe\| | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)



MIT License. Copyright (c) 2020 Strontic.


