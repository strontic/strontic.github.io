---
title: bootmgr.exe | Boot Manager
excerpt: What is bootmgr.exe?
---

# bootmgr.exe 

* File Path: `C:\Windows\system32\RemInst\boot\x64\bootmgr.exe`
* Description: Boot Manager

## Hashes

Type | Hash
-- | --
MD5 | `D392AFA4F19AF11FF69A407D7CA73873`
SHA1 | `3BD5C60D9374644DC40A22BFD572BA3B285DBECA`
SHA256 | `306E509ACDB8DA4074A98AE86494D3585E84FD545BCA421547675FE25397411B`
SHA384 | `FFBE95C03C81D8163BFB0B45E56E40E387519038AA2710B19E2F2CC54A34B3B5270FA275DADC490DAC11A3C363CA2AC2`
SHA512 | `91C2509754723E2E1D712F0C4719EA06A99E333279CDE4E02FFF6B79312F6024AE696444E79D2DC9531ADB1EBAE97BFB51F1D1691535413A7599FB26A4FBC6A2`
SSDEEP | `12288:9oIqC5qSvYJZtuu1IYEVTIjM77DqJbij6csQaPpVmjpl4m9dmz/AJkodQvQaJ5Ui:9oI3qqQ+u1EIjM77DqJbJc0pAcAGVJ`

## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: bootmgr.exe
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.17763.1 (WinBuild.160101.0800)
* Product Version: 10.0.17763.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.


## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Windows\system32\RemInst\boot\x86\bootmgr.exe](bootmgr.exe-D392AFA4F19AF11FF69A407D7CA73873.md) | 100

## Possible Misuse

*The following table contains possible examples of `bootmgr.exe` being misused. While `bootmgr.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[malware-ioc](https://github.com/eset/malware-ioc) | [rtm](https://github.com/eset/malware-ioc/blob/master/rtm/README.adoc) | `bootmgr` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [crime_ransom_ragna_locker.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/crime_ransom_ragna_locker.yar) | $f2 = "bootmgr.efi" fullword wide | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)



MIT License. Copyright (c) 2020 Strontic.


