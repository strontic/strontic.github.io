---
title: TSTheme.exe | TSTheme Server Module
---

# TSTheme.exe 

* File Path: `C:\Windows\SysWOW64\TSTheme.exe`
* Description: TSTheme Server Module
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `CB32D9E4321504D8217683196149373A`
SHA1 | `509F20BFE552800EBDFE0A37B6189B4343D99A94`
SHA256 | `0A827CB624FB1DD5743DD5706A60FFED477988D4E939C6876BBCE398F2574065`
SHA384 | `2EDEA61F7141C2F107FAB28F0752719FA91F71FC3544FEA227F547A661BB8868D3F6B15A0B570E7C189A607152509CD9`
SHA512 | `5CFDDB139F254607D81F0E9ADDD0AB7D5FEC46FE8FACFC8F69BF789DA5DF7C0809A808144EC0A32CC841240F3C74DFC541C9BF9A24A33C57B3E4D2C9A88B2D9A`
SSDEEP | `1536:Y+7fA8LgWp8jweDL+l0YW2iwpjyrH/jak:Y+DAmgWEDL+zrim+L/2k`

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

* Original Filename: TSThemeS.exe
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


