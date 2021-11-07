---
title: SecurityHealthService.exe | Windows Security Health Service
excerpt: What is SecurityHealthService.exe?
---

# SecurityHealthService.exe 

* File Path: `C:\Windows\system32\SecurityHealthService.exe`
* Description: Windows Security Health Service

## Hashes

Type | Hash
-- | --
MD5 | `A11A4556A1394E6E4E06CBD194B232A0`
SHA1 | `C16E62DC77E135A7DB9AB3A2583E4C6A48CB45BB`
SHA256 | `25AFF17BDAF331ADE6418BA8CF6BF34F24FF153D1DFA2A9EBE31D1B10E362A38`
SHA384 | `3E5572CCA7162524D6C6F02879ACDACD32081E07B86EB64FC572B558A99F87A1337B6C71B3D9AA34E1EB16C5E9B549BF`
SHA512 | `7AAD8959783806C00CCA999708CED6EBF192394DFC56B3DEDE57080ADED2016A5254B4321D23F1873B11225DB7DF6267FAEDF69EE3846A66ADF432CB3C8BA403`
SSDEEP | `12288:j4MaqKIPwENuaN2Q5ka1GREDngKndwyG9cLJtbqjzuELCEezy:j4JqKawQRtK4gKndtG9cLJtbauELae`

## Runtime Data

### Usage (stdout):
```cmhg
Unknown switch.

```

## Signature

* Status: Signature verified.
* Serial: `330000026551AE1BBD005CBFBD000000000265`
* Thumbprint: `E168609353F30FF2373157B4EB8CD519D07A2BFF`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: SecurityHealthService.exe
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 4.18.1807.16384 (WinBuild.160101.0800)
* Product Version: 4.18.1807.16384
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.



## Possible Misuse

*The following table contains possible examples of `SecurityHealthService.exe` being misused. While `SecurityHealthService.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_reg_disable_sec_services.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_reg_disable_sec_services.yml) | `- '\SecurityHealthService'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020-2021 Strontic.


