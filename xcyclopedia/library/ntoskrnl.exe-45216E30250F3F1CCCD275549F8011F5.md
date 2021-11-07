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
MD5 | `45216E30250F3F1CCCD275549F8011F5`
SHA1 | `A1496A868D693AEC10F389DA8875D449A551BE92`
SHA256 | `7DD334EDD7DB7FC6F8C170F3338C92E2CF30A621CDF5B50727D210D8434974EE`
SHA384 | `3C64270D6134F4B8871AA579E957C8330819CA60CE29A1A026D0A3EC9CCEB39205B3BF9917E35227AB47D6C1FE5130A4`
SHA512 | `46E8E8050117942E803FEB31ED10FF5DFC841B14AC49D6CA9E0FF5D82693F8FE797DCE1668A650763F2301BC6622116E6A3E33DCB5AECFC7C952B3CFFE392938`
SSDEEP | `196608:Xt+2fP5dtCuUcqXuxIr5b3mghXuRMRIw+zE/e8rnm:cC3tNTqXuxItb3mgZuSt+zSej`
IMP | `E0E869BBD92F59B58E146BA81EEE3F6D`
PESHA1 | `ECE9A40ADE05DE01C767E92EA691414FCDFE9980`
PE256 | `91FAFD88DE150EA5D02E93986AB673E6317E2B5B7B940CF4AA5E4A7F812602F8`

## Signature

* Status: Signature verified.
* Serial: `33000002EC6579AD1E670890130000000002EC`
* Thumbprint: `F7C2F2C96A328C13CDA8CDB57B715BDEA2CBD1D9`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: ntkrnlmp.exe
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1320 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1320
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/73
* VirusTotal Link: https://www.virustotal.com/gui/file/7dd334edd7db7fc6f8c170f3338c92e2cf30a621cdf5b50727d210d8434974ee/detection


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



MIT License. Copyright (c) 2020-2021 Strontic.


