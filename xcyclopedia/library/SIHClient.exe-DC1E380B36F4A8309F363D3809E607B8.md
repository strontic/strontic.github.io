---
title: SIHClient.exe | SIH Client
---

# SIHClient.exe 

* File Path: `C:\windows\system32\SIHClient.exe`
* Description: SIH Client
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `DC1E380B36F4A8309F363D3809E607B8`
SHA1 | `145EF8D82CF1E451381584CD9565A2D35A442504`
SHA256 | `0E0BB70AE1888060B3FFB9A320963551B56DD0D4CE0B5DC1C8FADDA4B7BF3F6A`
SHA384 | `11C72C0FBE6EF5BEC80D7A7139873893D3C2DA51DEB666E87D3E4B4070A410F9F45272CD3B7C7BFA7200E22DB81E6D23`
SHA512 | `75048486C6BC5726053356FFFB323C1DCC7528E8DEB24FC718E4B0E7EF8DAF1C3AF40C079CD2988AE2A7B3070B3CFBAB7F5C9222484F1DDE4BE8CABE0B915001`
SSDEEP | `6144:67Ux/VyGIvD4gwOpcZ93McOZWswvZdCiMMZuTwE:67UDRgTpwFMc20jCnsOwE`

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

* Original Filename: sihclient.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.17763.1 (WinBuild.160101.0800)
* Product Version: 10.0.17763.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.


## Possible Misuse

*The following table contains possible examples of `SIHClient.exe` being misused. While `SIHClient.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_wmi_module_load.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/image_load/sysmon_wmi_module_load.yml) | `            - '\SIHClient.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020 Strontic.


