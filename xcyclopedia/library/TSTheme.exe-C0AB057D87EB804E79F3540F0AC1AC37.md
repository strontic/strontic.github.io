---
title: TSTheme.exe | TSTheme Server Module
---

# TSTheme.exe 

* File Path: `C:\Windows\system32\TSTheme.exe`
* Description: TSTheme Server Module
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `C0AB057D87EB804E79F3540F0AC1AC37`
SHA1 | `1E1EC63ED702B6BB96DE0A99C793103B4CA96129`
SHA256 | `31114F153F14D9AABD425D75A0F3F87D68A3A4C30E6185D9C040B86AE6470CEE`
SHA384 | `7174073AF10D2DCEE152459BE41C7274D065F4154273F92E45A305786B8488F11E3443D4E954CD18B5396F3E8C354B91`
SHA512 | `76C7EAAD1A3F5DDA5F2F037C7AEFCB560BE063A77CD925B61F124D5B4401283FD345F0037A396642CF7D6CAF8BBF2D4D2693A2D9D36EF31D9308268181997F09`
SSDEEP | `1536:V6TIIfttRqCLNvA3glLTsRe774HrPU8wIBS0s+rPjundilyq//v2:4sWD36YTUe774HrM8JBA+DjudicI/+`

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

* Original Filename: TSThemeS.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.


## Possible Misuse

*The following table contains possible examples of `TSTheme.exe` being misused. While `TSTheme.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_suspicious_remote_thread.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/sysmon/sysmon_suspicious_remote_thread.yml) | `            - '\tstheme.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020 Strontic.


