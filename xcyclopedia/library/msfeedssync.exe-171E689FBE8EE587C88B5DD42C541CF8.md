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
MD5 | `171E689FBE8EE587C88B5DD42C541CF8`
SHA1 | `7D208A8EDE1B07FFDED269521A9A3DC17633336F`
SHA256 | `3FC5FE27C7374A491BAB62BF59D807183EBDE91572B0CBB85BA21F67898F48DD`
SHA384 | `8FEF80E2725A201C439B06B65B0EF110BA7CED8BAC084FF62BFF3F0EDAAC919966261ABF6912E0E95F4789F1C2E2780B`
SHA512 | `5BBCEBA34C184962A0A8D440709C7E23974240BDA6A4C2E3D90259F9A2A1AB550D3D40548D9AAFE7B447637E1FB2C3D87FAE220155F85ED215E3C8434675FB5E`
SSDEEP | `384:tGOXdlDM4a3QPG0ysD69iMdlZaD3jJWcsL:vNZaID3jQL`

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
* File Version: 11.00.14393.2007 (rs1_release.171231-1800)
* Product Version: 11.00.14393.2007
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.


## Possible Misuse

*The following table contains possible examples of `msfeedssync.exe` being misused. While `msfeedssync.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_wmi_module_load.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/sysmon/sysmon_wmi_module_load.yml) | `            - '\msfeedssync.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020 Strontic.


