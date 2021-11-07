---
title: SecurityHealthService.exe | Windows Security Health Service
excerpt: What is SecurityHealthService.exe?
---

# SecurityHealthService.exe 

* File Path: `C:\WINDOWS\system32\SecurityHealthService.exe`
* Description: Windows Security Health Service

## Hashes

Type | Hash
-- | --
MD5 | `0D06BE475B3C82CEC609D9E9F0FBD502`
SHA1 | `F700E2A484DBE3AF1614FDC9825E19162A05B539`
SHA256 | `42B9B2200AFDCDD1ACAE40FD7C273309D2B2F0C17CD26CB03A9DCA2B65538D33`
SHA384 | `5DB4CDA4C242D6C749C040B92E3C7A1FE9D4DF0F0E3A18A4F2296167296238B3E4855FFA80B0A1C48EF50AC7D78E3336`
SHA512 | `C42E1E61C94A799438B2D54082C25FA863853A694CE1249C93194351ED52014DA3AD78874C9075E7DC82800588761F5114B12A3E744E19338ACD2ACB3A8C7AE8`
SSDEEP | `12288:uxIhIgIXlvosIWDn6F3VDccW05fvVghEyhBKKrT1Na76JUT9iZ9v:uxUIgI1vosIzcU5fvVghEvKrEuUT9cF`

## Runtime Data

### Usage (stdout):
```cmhg
Unknown switch.

```

## Signature

* Status: Signature verified.
* Serial: `330000023241FB59996DCC4DFF000000000232`
* Thumbprint: `FF82BC38E1DA5E596DF374C53E3617F7EDA36B06`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: SecurityHealthService.exe
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 4.18.1901.16384 (WinBuild.160101.0800)
* Product Version: 4.18.1901.16384
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.



## Possible Misuse

*The following table contains possible examples of `SecurityHealthService.exe` being misused. While `SecurityHealthService.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_reg_disable_sec_services.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_reg_disable_sec_services.yml) | `- '\SecurityHealthService'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020-2021 Strontic.


