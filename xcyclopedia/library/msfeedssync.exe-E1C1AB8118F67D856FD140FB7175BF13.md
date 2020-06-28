---
title: msfeedssync.exe | Microsoft Feeds Synchronization
---

# msfeedssync.exe 

* File Path: `C:\Windows\SysWOW64\msfeedssync.exe`
* Description: Microsoft Feeds Synchronization
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `E1C1AB8118F67D856FD140FB7175BF13`
SHA1 | `FC8716EB4A2C5EB980022F8683DFBD4CD9A5B727`
SHA256 | `73CD7E458475E0A83CDE7FAA3982FCD341A6B6C4AFAB33E4950BCCD15635EADF`
SHA384 | `CEAFD3226395D7642D1E2E9EF6DCA67EACBA36F6F7FB4E6E76D5FAC04652E3B3CC911C9F924B32718E14A1CE7F2DBB20`
SHA512 | `1B7278347C8ABD2536A61B017574718FA3B5ADD4A9F0ACD22576C4380F1CF0A2FF9057AE4E405A047B2C4D2539695D1E142E4CD0DC55FC5D3E5AB8B2A6FDFAE5`
SSDEEP | `192:DgOt5Km8/ddLDVIg3wHmm4DvXFhRM3s8oRWcs0oj:DBt5A/dFJI02mmyFhCARWcs0I`

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


