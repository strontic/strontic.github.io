---
title: syskey.exe | SAM Lock Tool
---

# syskey.exe 

* File Path: `C:\Windows\SysWOW64\syskey.exe`
* Description: SAM Lock Tool
* Comments: 

## Screenshot

![syskey.exe](screenshots/syskey.exe-8D00177CA1D11D9A61CBF6F0D2F0420B-3.png)
![syskey.exe](screenshots/syskey.exe-EFDF337667EB0516CC325BA74A7F9411-1.png)

## Hashes

Type | Hash
-- | --
MD5 | `EFDF337667EB0516CC325BA74A7F9411`
SHA1 | `AB2B69E0154B397546BB644E47484FB87E2F3ABA`
SHA256 | `29D60AA6C35719216CABE7E2290B08DBF6D7BE0E1ECC66B88E8760EA0AD54459`
SHA384 | `70CF220B857BF6D4117A41E8D7764AC64E84456DE6931EA7C97C1195F2A75085D449F291C8F1A99ED7E5804B470A2138`
SHA512 | `79DB4349ED2349C9D05FC5E6BC848768C8302E6095EF2167CA7B38C18F41378FC2BB8473B72C94B6948E014A85EDB7A37159324264D8EEAE72EA25E691B8CC61`
SSDEEP | `384:2Tf/M5xZu0TnS07ZQnnCvhK5I37X8xuVTy+SC7uHUrSjaU1KC1Q1fWaxWVf:eX+xQ0TnSZChK5I3d5/iHUrSjaN0`

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
* Serial: `33000000BCE120FDD27CC8EE930000000000BC`
* Thumbprint: `E85459B23C232DB3CB94C7A56D47678F58E8E51E`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: samlock.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.14393.0 (rs1_release.160715-1616)
* Product Version: 10.0.14393.0
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Windows\system32\syskey.exe](syskey.exe-8D00177CA1D11D9A61CBF6F0D2F0420B.md) | 33
[C:\windows\SysWOW64\syskey.exe](syskey.exe-C72F56AC33E9F1204528020CD0840A5A.md) | 29

## Possible Misuse

*The following table contains possible examples of `syskey.exe` being misused. While `syskey.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [godmode_sigma_rule.yml](https://github.com/Neo23x0/sigma/blob/master/other/godmode_sigma_rule.yml) | `            - 'reg SAVE HKLM\SAM'  # save registry SAM - syskey extraction` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_syskey_registry_access.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/builtin/win_syskey_registry_access.yml) | `title: SysKey Registry Keys Access` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_syskey_registry_access.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/builtin/win_syskey_registry_access.yml) | `description: Detects handle requests and access operations to specific registry keys to calculate the SysKey` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020 Strontic.


