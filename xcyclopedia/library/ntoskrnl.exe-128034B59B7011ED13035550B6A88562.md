---
title: ntoskrnl.exe | NT Kernel & System
excerpt: What is ntoskrnl.exe?
---

# ntoskrnl.exe 

* File Path: `C:\Windows\system32\ntoskrnl.exe`
* Description: NT Kernel & System

## Hashes

Type | Hash
-- | --
MD5 | `128034B59B7011ED13035550B6A88562`
SHA1 | `FB9961E163E09B431C9FC347DEE28D26A5E50FC3`
SHA256 | `ACEC36B1C1A3665CA16349A928B36F2F90335E4D1D385F7239AF2474D7AC25B9`
SHA384 | `42E852EB15C8B44D97521D838D4BF44A032F3A8CC800AE65EB9F0B865EC48958245996D154E2AF0CC9EC893AF011BB40`
SHA512 | `66EB8FAB35CF40C0EE65CA268F4E04716499421710218DE0D26CCD12C93567A8F1C1AD06718075E180198DCA687564DBBEDD1295D2E80CEA81588383FE7A7E56`
SSDEEP | `196608:6uFi6ixIuYIfjHjtPeZ6aiYmd++lWanDRkMMjN:6uU7xsmjHjtPew/Ymd+NO/Q`
IMP | `E0E869BBD92F59B58E146BA81EEE3F6D`
PESHA1 | `8D4187A23AAE6D3B3364DDD532820305A6222EA2`
PE256 | `907C9422577F7A948F9B14C6A5F4261CA41AFFAF2CF784C1CEF371700F226D25`

## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: ntkrnlmp.exe
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.685 (WinBuild.160101.0800)
* Product Version: 10.0.19041.685
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/76
* VirusTotal Link: https://www.virustotal.com/gui/file/acec36b1c1a3665ca16349a928b36f2f90335e4d1d385f7239af2474d7ac25b9/detection


## Possible Misuse

*The following table contains possible examples of `ntoskrnl.exe` being misused. While `ntoskrnl.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_hackingteam_rules.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_hackingteam_rules.yar) | $x4 = "C:\\\\Windows\\\\Sysnative\\\\ntoskrnl.exe" fullword ascii /* PEStudio Blacklist: strings */ | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_winnti.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_winnti.yar) | $s17 = "NTOSKRNL.EXE" fullword wide /* Goodware String - occured 4 times */ | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_winnti.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_winnti.yar) | $a5 = "ntoskrnl.exe" ascii fullword | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_winnti.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_winnti.yar) | $a3 = "%SystemRoot%\\System32\\ntoskrnl.exe" ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_winnti_hdroot.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_winnti_hdroot.yar) | $s1 = "\\system32\\ntoskrnl.exe" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [spy_querty_fiveeyes.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/spy_querty_fiveeyes.yar) | $s3 = "ntoskrnl.exe" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [spy_regin_fiveeyes.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/spy_regin_fiveeyes.yar) | $s4 = "ntoskrnl.exe" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)



MIT License. Copyright (c) 2020 Strontic.


