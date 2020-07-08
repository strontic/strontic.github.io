---
title: TSTheme.exe | TSTheme Server Module
---

# TSTheme.exe 

* File Path: `C:\windows\system32\TSTheme.exe`
* Description: TSTheme Server Module

## Hashes

Type | Hash
-- | --
MD5 | `7F664C2449A91878B131716D2DD79553`
SHA1 | `9BF3F1EF045E15BF6B2B941A67BB4918222DB362`
SHA256 | `0DA195AECD8794062AB5CB3BDEF2BE0230C1E76050C7B11CF609E4F3F23A9DDC`
SHA384 | `9D7526C80131BA671970B3BB7962D61955F2B2708750DE17B20298C3C504D70D1DED7EA58E073DE7BE0D566BCA2E7F9A`
SHA512 | `4986387C88D7165CB8B871C48478235C76B9845F8B3053A093936269C5D2A662A940E385744E001703428945E477D3600899E380854A60D4BC54D582AA6163A9`
SSDEEP | `1536:YhT+AO0YYhOi/oX6CJYX0YOWbKuhuEiiGWv2:Y9+qpoX1U0YOshuEi9W+`

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
* File Version: 10.0.17763.1 (WinBuild.160101.0800)
* Product Version: 10.0.17763.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.


## Possible Misuse

*The following table contains possible examples of `TSTheme.exe` being misused. While `TSTheme.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_suspicious_remote_thread.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/sysmon/sysmon_suspicious_remote_thread.yml) | `            - '\tstheme.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020 Strontic.


