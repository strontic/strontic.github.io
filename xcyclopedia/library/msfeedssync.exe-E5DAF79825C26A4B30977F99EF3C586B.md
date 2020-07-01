---
title: msfeedssync.exe | Microsoft Feeds Synchronization
---

# msfeedssync.exe 

* File Path: `C:\windows\SysWOW64\msfeedssync.exe`
* Description: Microsoft Feeds Synchronization
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `E5DAF79825C26A4B30977F99EF3C586B`
SHA1 | `7CCE795933C950BA9780D5F412148ACDF54504D7`
SHA256 | `FF2144014012A9BDEB2F2E1775BA18EA0810CFA2771CFDC9BC075A2E3716C219`
SHA384 | `3A6AAEE7DF51E0D61B746152F13B048B6F1D1D0B6B471A250C7DE3898CA55B83480803A5661086179B6249E1BE0EF3B4`
SHA512 | `F258341EF0E88324AAD807968572CA9C29F970BB73CF13213135026317580F4FF416E0461828FCC27B58A0EE0726E43BE9243590AEF34CC3DAF22C7D2D7305A4`
SSDEEP | `192:Iu6hgnIpf3E4CAjSUb+lDAB808qmqObZDRM/2mdopWcsHMhQY8:IbSnIhFCgFb+2imqbZDC+PpWcsHQQV`

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

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\WINDOWS\SysWOW64\msfeedssync.exe](msfeedssync.exe-1AD138EDAFB9EAD8442F72E108512405.md) | 35

## Possible Misuse

*The following table contains possible examples of `msfeedssync.exe` being misused. While `msfeedssync.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_wmi_module_load.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/sysmon/sysmon_wmi_module_load.yml) | `            - '\msfeedssync.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020 Strontic.


