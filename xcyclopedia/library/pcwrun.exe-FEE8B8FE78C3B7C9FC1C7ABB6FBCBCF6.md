---
title: pcwrun.exe | Program Compatibility Troubleshooter Invoker
---

# pcwrun.exe 

* File Path: `C:\Windows\system32\pcwrun.exe`
* Description: Program Compatibility Troubleshooter Invoker
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `FEE8B8FE78C3B7C9FC1C7ABB6FBCBCF6`
SHA1 | `B49557BDAB527B36BE2DD1E3D9049772DCDBCFB3`
SHA256 | `3DE0D85F8170457E741B8C7B2EC0CBFC5BDF6EB37012E4A5E7EEE93B149AE7CF`
SHA384 | `06DB31B19C4868B733C3734482475E38EA0140E04A1E75D5523A00578927C4DD06B61CCB15823BCD71477396BDCBA7B3`
SHA512 | `C8FE23122B7EB5425E93BDB72FCA0E8E449DF57D72D0892E95C79C578013A1EFD02A17A3187094C0E886FAB95433B0D5007ABE29F889A5745DB930EDF0DC1A8F`
SSDEEP | `192:0HWN2ogLOLwB1EcMOchQXfRpO5gSlNssAQG7SU2dR75lvmsWHgW:0HEgLOLZhOc6R0Ogmnl2TesWHgW`

## Runtime Data

### Usage (stdout):
```Batchfile

```

### Usage (stderr):
```Batchfile

```

### Child Processes:
msdt.exe

## Signature

* Status: Signature verified.
* Serial: `33000001C422B2F79B793DACB20000000001C4`
* Thumbprint: `AE9C1AE54763822EEC42474983D8B635116C8452`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: pcwrun.exe
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.17763.1 (WinBuild.160101.0800)
* Product Version: 10.0.17763.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\WINDOWS\system32\pcwrun.exe](pcwrun.exe-8EF6CF4E50D1D30D34F9F451EBB4A781.md) | 69

## Possible Misuse

*The following table contains possible examples of `pcwrun.exe` being misused. While `pcwrun.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Pcwrun.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Pcwrun.yml) | `Name: Pcwrun.exe` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Pcwrun.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Pcwrun.yml) | `  - Command: Pcwrun.exe c:\temp\beacon.exe` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Pcwrun.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Pcwrun.yml) | `  - Path: C:\Windows\System32\pcwrun.exe` | 



MIT License. Copyright (c) 2020 Strontic.


