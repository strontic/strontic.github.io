---
title: WerFault.exe | Windows Problem Reporting
---

# WerFault.exe 

* File Path: `C:\windows\system32\WerFault.exe`
* Description: Windows Problem Reporting
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `92359F1A602727435067F18083B912C6`
SHA1 | `602763AC02AE092378C58E3CDD5B11822B34114B`
SHA256 | `FE943A3AD65D3DB0AF499D5367989A0148B981BFD9B80149D8A7B65D692039B8`
SHA384 | `ABBC9FF0ED3A55195108F417CEB78D58798558EFC45B387CD397E85057856920E7E4B19F591C0D889D7AC3D7381EBA1A`
SHA512 | `C9085322785C98F9B77042DD3CC4C1CC4B7C7CE612EF08F7A87E2E99828EA32110248FB320BA772C8AECFD50EFB3B0D3F7DE7DD54340166D894D1FDF3F28985A`
SSDEEP | `12288:/B0YzmpEwOYQOEq+D4lURVX5foUFK1wc2HywV:pYAtxGUloUFK1wcyhV`

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

* Original Filename: WerFault.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.17763.1 (WinBuild.160101.0800)
* Product Version: 10.0.17763.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.


## Possible Misuse

*The following table contains possible examples of `WerFault.exe` being misused. While `WerFault.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_lsass_dump.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_lsass_dump.yml) | `        Image\|endswith: '\werfault.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020 Strontic.


