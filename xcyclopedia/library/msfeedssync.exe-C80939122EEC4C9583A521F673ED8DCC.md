---
title: msfeedssync.exe | Microsoft Feeds Synchronization
---

# msfeedssync.exe 

* File Path: `C:\Windows\system32\msfeedssync.exe`
* Description: Microsoft Feeds Synchronization
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `C80939122EEC4C9583A521F673ED8DCC`
SHA1 | `B9006DAF6092C3788C0BEF9568A66DD93AE54AD5`
SHA256 | `D842C0AA333567D6B14A5F7429282652917A10B449BBAB8A79D7F4C4821A5D9F`
SHA384 | `8CF439B72E2D5AE237C3221CEAEFB9505978EA7E7E37E0C3AA8D2B858EA23CAE895B55AE0DE9B7BAC91F366BAE9CB5AE`
SHA512 | `76D6D8ADAAAAC72244A4116698A652027FF910FAF570A0BBBD79CE560EE01B615E6691B941605062A29B5FCD6B1017FEDFBF1750E3CCF9FE200736673D73A051`
SSDEEP | `192:aTRvrbsW2+9r8ZoT2U9NhZGFxAGGGZIW8XmMjQ+adCeeQtShWcs0:Otr2U8ZoLhQ2GNd82iaCQ0hWcs0`

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

* Original Filename: msfeedssync.exe
* Product Name: Internet Explorer
* Company Name: Microsoft Corporation
* File Version: 11.00.19041.1 (WinBuild.160101.0800)
* Product Version: 11.00.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.


## Possible Misuse

*The following table contains possible examples of `msfeedssync.exe` being misused. While `msfeedssync.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_wmi_module_load.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/sysmon/sysmon_wmi_module_load.yml) | `            - '\msfeedssync.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020 Strontic.


