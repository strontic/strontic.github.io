---
title: Magnify.exe | Microsoft Screen Magnifier
---

# Magnify.exe 

* File Path: `C:\WINDOWS\SysWOW64\Magnify.exe`
* Description: Microsoft Screen Magnifier
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `1838A2C6641F4ABCC882C1134709EC6C`
SHA1 | `DF2CF50AAFD65C4CA24BDE54D5EDB01957596CB9`
SHA256 | `E56E7FF8534ABA65462FBE7C5331CD327FC59A8F0CAA11C2D904008B699B215B`
SHA384 | `EDA49B04FF5095F366D30FFA8573EDC88D900310BE2A30228F60EC41AC00EACD3501D2ADCA4D2A9383FDC84DB5AF8A2D`
SHA512 | `E78BBF4051F6F5E298E8B4A3AEFCBA6A6AE8DC49F6F8791119051DE211E9B0BDE6EDA121A776BC16B774C3AFF7D718DEC50D21C783404D9708A2514503258B02`
SSDEEP | `6144:ImTH2CRKPyHXE8Bm2/zGxRDmyLHXIUypcC8l983bTPgCNi/2pcgLDrNQNG:ImTH2VPyZyHXiN8l98PPgD`

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

* Original Filename: ScreenMagnifier.exe
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.18362.449 (WinBuild.160101.0800)
* Product Version: 10.0.18362.449
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.


## Possible Misuse

*The following table contains possible examples of `Magnify.exe` being misused. While `Magnify.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_install_reg_debugger_backdoor.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_install_reg_debugger_backdoor.yml) | `            - '*\CurrentVersion\Image File Execution Options\magnify.exe*'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_stickykey_like_backdoor.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/sysmon/sysmon_stickykey_like_backdoor.yml) | `            - '*\SOFTWARE\Microsoft\Windows NT\CurrentVersion\Image File Execution Options\Magnify.exe\Debugger'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_stickykey_like_backdoor.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/sysmon/sysmon_stickykey_like_backdoor.yml) | `            - '*cmd.exe Magnify.exe *'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1546.008.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1546.008/T1546.008.md) | * Magnifier: <code>C:\Windows\System32\Magnify.exe</code> | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1546.008.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1546.008/T1546.008.md) | \| parent_list \| Comma separated list of system binaries to which you want to attach each #{attached_process}. Default: "osk.exe" \| String \| osk.exe, sethc.exe, utilman.exe, magnify.exe, narrator.exe, DisplaySwitch.exe, atbroker.exe\| | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)



MIT License. Copyright (c) 2020 Strontic.


