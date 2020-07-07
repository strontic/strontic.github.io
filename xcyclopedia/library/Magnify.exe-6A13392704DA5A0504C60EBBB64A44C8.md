---
title: Magnify.exe | Microsoft Screen Magnifier
---

# Magnify.exe 

* File Path: `C:\windows\SysWOW64\Magnify.exe`
* Description: Microsoft Screen Magnifier
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `6A13392704DA5A0504C60EBBB64A44C8`
SHA1 | `45B309DD4F8C06F2304F652519CD331133F85BD4`
SHA256 | `E2D6EB8764DD4EC3BF840F30A5E911FBAE832D54F3C2A6939ADDD07787C08BF6`
SHA384 | `26D9F768249AC1A24A6E65B126312B69DB9E23B305F7397BF6246476A04E412F0665DA8D24F3E5C3045A4F8382A8CCCD`
SHA512 | `DDE40C05AB7D206CC582B6D225623F215FE2821CDB0D02B13A5CF2887E1B9E4081F13D223741B9DD5E866D863FA26C6A10019E14FB32F65E3118E39214B21E1B`
SSDEEP | `12288:N6xEBWFtpgcnCDr9RI2yZt8XB04dDuc/04dDuc/vq:4SWFOPS/4xI4x7v`

## Runtime Data

### Usage (stdout):
```Batchfile

```

### Usage (stderr):
```Batchfile

```

### Child Processes:


## Signature

* Status: The file C:\windows\SysWOW64\Magnify.exe is not digitally signed. You cannot run this script on the current system. For more information about running scripts and setting execution policy, see about_Execution_Policies at http://go.microsoft.com/fwlink/?LinkID=135170
* Serial: ``
* Thumbprint: ``
* Issuer: 
* Subject: 

## File Metadata

* Original Filename: ScreenMagnifier.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 6.3.9600.16384 (winblue_rtm.130821-1623)
* Product Version: 6.3.9600.16384
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\windows\system32\Magnify.exe](Magnify.exe-184D10CE4DC3456B5A39BE9CD273E7E5.md) | 63
[C:\Windows\system32\Magnify.exe](Magnify.exe-88156DA1B88F03E6591359587F3FAF2C.md) | 61
[C:\Windows\SysWOW64\Magnify.exe](Magnify.exe-E7274A1C29BF277EA232150F05812E67.md) | 52

## Possible Misuse

*The following table contains possible examples of `Magnify.exe` being misused. While `Magnify.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_install_reg_debugger_backdoor.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_install_reg_debugger_backdoor.yml) | `            - '*\CurrentVersion\Image File Execution Options\magnify.exe*'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_stickykey_like_backdoor.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/registry_event/sysmon_stickykey_like_backdoor.yml) | `            - '*\SOFTWARE\Microsoft\Windows NT\CurrentVersion\Image File Execution Options\Magnify.exe\Debugger'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_stickykey_like_backdoor.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/registry_event/sysmon_stickykey_like_backdoor.yml) | `            - '*cmd.exe Magnify.exe *'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1546.008.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1546.008/T1546.008.md) | * Magnifier: <code>C:\Windows\System32\Magnify.exe</code> | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1546.008.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1546.008/T1546.008.md) | \| parent_list \| Comma separated list of system binaries to which you want to attach each #{attached_process}. Default: "osk.exe" \| String \| osk.exe, sethc.exe, utilman.exe, magnify.exe, narrator.exe, DisplaySwitch.exe, atbroker.exe\| | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)



MIT License. Copyright (c) 2020 Strontic.


