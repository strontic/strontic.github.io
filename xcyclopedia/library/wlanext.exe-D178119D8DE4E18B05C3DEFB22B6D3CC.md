---
title: wlanext.exe | Windows Wireless LAN 802.11 Extensibility Framework
---

# wlanext.exe 

* File Path: `C:\Windows\system32\wlanext.exe`
* Description: Windows Wireless LAN 802.11 Extensibility Framework

## Hashes

Type | Hash
-- | --
MD5 | `D178119D8DE4E18B05C3DEFB22B6D3CC`
SHA1 | `0CBF3F61C88E7A944294D8E577011F44DD99A9B4`
SHA256 | `8456099DEB994F309FDE890E4F0E571A0A67F9B7DD079516905175CD1500FA52`
SHA384 | `89748309A3C9179084972E211638F875820D609D9FA5272370E6FFA937376211EE6685001F73F03161EC6480D374EBC1`
SHA512 | `EA97A93C3B6E9ADA6ACEB6DBA358C9E4A6EE4EDF1228942378C8879ECA8A60A6B85112D11E0DB387999729203707A0D4292CC80697CBB8CF42B4BE2202762E44`
SSDEEP | `1536:Q9XHUkfBwkQ1meRIZN1Y8t93q91YI/JIq7cNn5LfDb5s:QR1fOkby8tyL/JZsnJu`

## Runtime Data

### Loaded Modules:

Path |
-- |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\system32\wlanext.exe |


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: wlanext.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.


## Possible Misuse

*The following table contains possible examples of `wlanext.exe` being misused. While `wlanext.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_creation_system_file.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/file_event/sysmon_creation_system_file.yml) | `            - '*\wlanext.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_system_exe_anomaly.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_system_exe_anomaly.yml) | `            - '*\wlanext.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020 Strontic.


