---
title: smartscreen.exe | SmartScreen
excerpt: What is smartscreen.exe?
---

# smartscreen.exe 

* File Path: `C:\Windows\system32\smartscreen.exe`
* Description: SmartScreen

## Hashes

Type | Hash
-- | --
MD5 | `E336F6A378289D00261EBD104E1668EE`
SHA1 | `466059000E4F2AF4BCB87CABFE38E5CA6970E507`
SHA256 | `1A6BB7F3AC6574998D7628B65AB234E1D0955F8643F4713C63E236F5FB4DAB92`
SHA384 | `CF6AFBA9200B28F4CCD20E6C008BC9C5C13CD6E80F303DB7CCBFCF063BC966FCD616F6C725F394092193443A380BDAD4`
SHA512 | `C44E8A890B9740AE0BC26E0A0026E3F4C51C7EAA376F2FA638165E2EA6F03AFCCDD657E5ABAAE98A09AC01E3D3BF8F25D68A577A317F85A5834E7FD4C0B79B86`
SSDEEP | `49152:jkSUwdaXFUbZwBmHNbPBgBmQ+MSt1Fzlhv3nLl:9PxMStthv3Z`

## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: smartscreen.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.14393.0 (rs1_release.160715-1616)
* Product Version: 10.0.14393.0
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.



## Possible Misuse

*The following table contains possible examples of `smartscreen.exe` being misused. While `smartscreen.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_creation_system_file.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/file_event/sysmon_creation_system_file.yml) | `- '*\smartscreen.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_system_exe_anomaly.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_system_exe_anomaly.yml) | `- '*\smartscreen.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_suspicious_remote_thread.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/sysmon/sysmon_suspicious_remote_thread.yml) | `- '\smartscreen.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020 Strontic.


