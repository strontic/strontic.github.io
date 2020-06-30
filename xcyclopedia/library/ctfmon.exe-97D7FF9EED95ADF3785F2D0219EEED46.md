---
title: ctfmon.exe | CTF Loader
---

# ctfmon.exe 

* File Path: `C:\Windows\SysWOW64\ctfmon.exe`
* Description: CTF Loader
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `97D7FF9EED95ADF3785F2D0219EEED46`
SHA1 | `C5DED3D1979BA5CB731C7ED003AC0C8172575A8E`
SHA256 | `81CA60464F7E079A3F3411968CFEA5EADE8085A5B96EF46621E07319DC404F1E`
SHA384 | `1B342B7CECDAEF8FFD6BF066FE79E4B44D40E671835EDFB3C2E3482FA35F9F3A42F8CAC56F79C243CDB043EC3D519A24`
SHA512 | `5F2EB7F50709AE0576D471B55B14428B78DE0394A05E8B695BD20E38585FB658A72E0E85E146054FAE0368695A4FBED64A096254716E3737B28F9AA549EA48F9`
SSDEEP | `96:2E7+2I1ySDnEtAp2RLZHDGjoaS2Hy9osw2mpDJ7pRKRULEW2gWw3epu4:7Itn598ey9osw2m/yW2gWF`

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
* Serial: `33000001C422B2F79B793DACB20000000001C4`
* Thumbprint: `AE9C1AE54763822EEC42474983D8B635116C8452`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: CTFMON.EXE
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.17763.1 (WinBuild.160101.0800)
* Product Version: 10.0.17763.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Windows\SysWOW64\ctfmon.exe](ctfmon.exe-1B19D302D7FFA3D0901B3D990A4E8E12.md) | 52
[C:\Windows\SysWOW64\ctfmon.exe](ctfmon.exe-29656B9E6B04C85E7BF4018B6844BE28.md) | 36
[C:\WINDOWS\SysWOW64\ctfmon.exe](ctfmon.exe-C0D57D7289C20B3B4D8680369394F188.md) | 61

## Possible Misuse

*The following table contains possible examples of `ctfmon.exe` being misused. While `ctfmon.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[malware-ioc](https://github.com/eset/malware-ioc) | [amavaldo](https://github.com/eset/malware-ioc/blob/master/amavaldo/README.adoc) | `\| `6C04499F7406E270B590374EF813C4012530273E` \| ctfmon.exe       \| Abused legitimate application \| Clean file                             \|` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)



MIT License. Copyright (c) 2020 Strontic.


