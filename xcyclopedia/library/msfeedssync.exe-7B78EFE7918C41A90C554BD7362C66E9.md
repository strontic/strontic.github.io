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
MD5 | `7B78EFE7918C41A90C554BD7362C66E9`
SHA1 | `94E4AC749FEB5CCAAFA3B198E99A79AEA9D77E66`
SHA256 | `CE95233922882F70354D637B12F4738042E189F9A92F4E99945FCBF84EC611F7`
SHA384 | `10C5508A3A2D11E0C5A4784209B3A122DA0F922852547BE9C4237D31ABECBE3455965D7B5F2A607A38AEEC5E2E2C96A9`
SHA512 | `4924CE094816FF9757ABA6FD2AD7E67BAD5DE3733F4E2A5C818F40FCC7C8CE7E31EFBD57658CE5943B7328F69A374CF3883E3B92C90B6755DFEAE14B28CAB3C1`
SSDEEP | `192:5hMHubsargEfoNuwHozeh5nKjB2v5v5UHGlndjadGHULBlS5WcsH:5hQMrXqueomnKNEhnnjaC8s5WcsH`

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
* File Version: 11.00.17763.1 (WinBuild.160101.0800)
* Product Version: 11.00.17763.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.


## Possible Misuse

*The following table contains possible examples of `msfeedssync.exe` being misused. While `msfeedssync.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_wmi_module_load.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/sysmon/sysmon_wmi_module_load.yml) | `            - '\msfeedssync.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020 Strontic.


