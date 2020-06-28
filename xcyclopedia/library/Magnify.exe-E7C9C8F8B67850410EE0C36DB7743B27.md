---
title: Magnify.exe | Microsoft Screen Magnifier
---

# Magnify.exe 

* File Path: `C:\Windows\SysWOW64\Magnify.exe`
* Description: Microsoft Screen Magnifier
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `E7C9C8F8B67850410EE0C36DB7743B27`
SHA1 | `D0B00DC14233A7EC509A3D2393DD64263FB38B3E`
SHA256 | `72187106E9C57D2655ADB2AB6176A00267878B5C3C698FE321CEF5BAA14346E8`
SHA384 | `ABF484EE1C9A2F9DED60E64EDAB4F89B05003C567B273B6D0D346CEDF6FA38F07B85601AC77B3D33B6BCB8A7D46F11B3`
SHA512 | `8EC507502BC44DB80A8CA3745B7FBA625A9B9E61D8519B724A4138DD4877AFCEEFB44F7E2EED0D33FEFABBF721FE2091DC55E7E8F247432C28AD010A81B971A6`
SSDEEP | `6144:oEVfyJw2fggMDFXb3uWeA3g6ZKhWYs07/Nts9LbWrzkdY5j4VppD+QFKQ0N4PkeN:oiyJKnDF5e2KhvsQW+5YppDT0NHFC`

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
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
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


