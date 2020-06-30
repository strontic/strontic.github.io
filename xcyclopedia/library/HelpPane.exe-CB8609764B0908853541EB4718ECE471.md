---
title: HelpPane.exe | Microsoft Help and Support
---

# HelpPane.exe 

* File Path: `C:\Windows\HelpPane.exe`
* Description: Microsoft Help and Support
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `CB8609764B0908853541EB4718ECE471`
SHA1 | `D8457897875FBB48A5510392EA2B913940E1F45D`
SHA256 | `61A42C1904275294E6D1446F53275C64A752D0BFE362B03ED5F4ECC7DCBFA7B3`
SHA384 | `25DCA0017E3884B81E8E33B48525F1BFED30CA4D69462954F41581A4C51E28837331A0A0E725D3CC05E24AE06C67972C`
SHA512 | `E70D457D017D91CF1D171FEED4509EBDF2E59BF877DDB9F5D58325A3DAD757FDAC2954845BA3CF1BC04B639F0D47C081FCAA55C82D89CA40AE1CA8A182D995CC`
SSDEEP | `12288:CYQskmB4b43OYv/x+Pzr2PKlfs9W1W3MT3HOXKPXPiXuHNHGb6bH/zx/GCLW/nhf:lQlrYEzrWKlfs9WAe3H`

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

* Original Filename: HelpPane.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.17763.1 (WinBuild.160101.0800)
* Product Version: 10.0.17763.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\WINDOWS\HelpPane.exe](HelpPane.exe-67094590E3D57130C587CD6D8AFB6597.md) | 52
[C:\Windows\HelpPane.exe](HelpPane.exe-9A6D44491772E8AA3EBDDC63C1CEF991.md) | 50
[C:\Windows\HelpPane.exe](HelpPane.exe-E8B796A523D2B63A9C7BB0576DFE793E.md) | 52

## Possible Misuse

*The following table contains possible examples of `HelpPane.exe` being misused. While `HelpPane.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_user_driver_loaded.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/builtin/win_user_driver_loaded.yml) | `            - '*\Windows\HelpPane.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020 Strontic.


