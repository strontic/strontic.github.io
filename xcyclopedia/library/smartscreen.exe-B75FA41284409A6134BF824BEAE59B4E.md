---
title: smartscreen.exe | Windows Defender SmartScreen
---

# smartscreen.exe 

* File Path: `C:\Windows\system32\smartscreen.exe`
* Description: Windows Defender SmartScreen
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `B75FA41284409A6134BF824BEAE59B4E`
SHA1 | `75BDDAB181B87DF4C60751A787AA5FD35783ADEB`
SHA256 | `B790B17EA61FC4EDC3D385FF83D0BC565A41594BB86920DEEF990A83B8862097`
SHA384 | `7300F3624A08A2A5BB6E2C6CEAB281FDFC6D5232AE482F728DA56EF9743A288FCF93C03B425A4FA38F67C19A837DAFDE`
SHA512 | `9F67BF42243EC3E27C160269C23ED9DCE4194E9693CC0194D872E56CD7E005ECEBAA2210D988F2F0A13C1368A5B10C8858288E7607D45385F11A7B42D7E49FD6`
SSDEEP | `49152:+CYVj023iHrPnXdzsXOVCQ1TRfOqI/TYh/Y6PInI/A8r37UnxNDi:lrgSr37eN`

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

* Original Filename: smartscreen.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\WINDOWS\system32\smartscreen.exe](smartscreen.exe-6033F55F30364319ED5B7E1C6E6C9ED4.md) | 30

## Possible Misuse

*The following table contains possible examples of `smartscreen.exe` being misused. While `smartscreen.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_system_exe_anomaly.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_system_exe_anomaly.yml) | `            - '*\smartscreen.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_creation_system_file.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/sysmon/sysmon_creation_system_file.yml) | `            - '*\smartscreen.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_suspicious_remote_thread.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/sysmon/sysmon_suspicious_remote_thread.yml) | `            - '\smartscreen.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020 Strontic.


