---
title: wimserv.exe | Wimfltr v2 extractor
---

# wimserv.exe 

* File Path: `C:\Windows\system32\wimserv.exe`
* Description: Wimfltr v2 extractor
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `88FEB4547F8965A9685CF44B1593CEA3`
SHA1 | `613F7BC0EE3E9394D6A43F47CEEA731BC6C1E2E2`
SHA256 | `B2898F0B6078A4E919C45C67AC4D2793E0E1CAE68FA86DD43C3F0667E0FBDD8A`
SHA384 | `30CC567AD8E4D13F55D1177F2B5B65DDDA044DFDC658241FEB25F75B2074D575ED10693D1F6E0DE6E253D6DE65CE020A`
SHA512 | `92312B1A9C391D5D8667199EE1FD9D741677CF07A2E42F314B8D085DF577A08FA78EA4E006AF9072F5B6130C3CE9927C721DBB4576B768F52EC061166F2F9FD7`
SSDEEP | `6144:Eu0ZvbFD+iX57q5SCdMaJ29mi+DfS70+FBMlsDPkPw26EhN8K4oP9oQn8vND:8boiZqnHJ29mi+DfW+wdEhN8SqQn8vND`

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

* Original Filename: extractr.exe
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.84 (WinBuild.160101.0800)
* Product Version: 10.0.19041.84
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.


## Possible Misuse

*The following table contains possible examples of `wimserv.exe` being misused. While `wimserv.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_user_driver_loaded.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/builtin/win_user_driver_loaded.yml) | `            - '*\Windows\System32\wimserv.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020 Strontic.


