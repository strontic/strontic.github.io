---
title: WMIADAP.exe | WMI Reverse Performance Adapter Maintenance Utility
excerpt: What is WMIADAP.exe?
---

# WMIADAP.exe 

* File Path: `C:\Windows\system32\wbem\WMIADAP.exe`
* Description: WMI Reverse Performance Adapter Maintenance Utility

## Hashes

Type | Hash
-- | --
MD5 | `44FA781649A564AD9DD8453D14758F96`
SHA1 | `F3651B5BCAC5CED5174F43DDC98DDF3BE8616CDD`
SHA256 | `9B1F44ED54A0AB6D1A18D113BA3C946D961F4D652FFBA0C3F1B2AA89A6CC7D0E`
SHA384 | `4603C8EC84358C290574773638214D59D9C8BB25073DD4582E57D46ACEE235EA1623DE8E72AC9E9615B0E346742E1486`
SHA512 | `C4E45384451823375D913C5A74D73858A7D0BAFA84825B56472731700192B16E3CA3B60CED7A79E88DA05B828035ED043266336140F25AEDF0BBF706A879C923`
SSDEEP | `1536:cg5H2POb7l/WO7bMv+MinfDTeuzP0DxPfrkiD9r+vCtrFtwgVeBLbZ1jh1aANQdo:j1JbMvefDF8DNHD9r+qzK1mwUMOofqq`
IMP | `367D299428703C9A9715504BFE071C97`
PESHA1 | `1756F43A1467F839F5D6951608CA59F0DE99C108`
PE256 | `16B0C87AEFF51A43F5FFE4B5B587446903F2410DBA147C4AB4CD9F4E35B8DB1C`

## Runtime Data

### Loaded Modules:

Path |
-- |
C:\Windows\System32\combase.dll |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\System32\msvcrt.dll |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\RPCRT4.dll |
C:\Windows\System32\sechost.dll |
C:\Windows\System32\ucrtbase.dll |
C:\Windows\system32\wbem\WMIADAP.exe |
C:\Windows\SYSTEM32\wbemcomn.dll |


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: wmicookr.dll
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.610 (WinBuild.160101.0800)
* Product Version: 10.0.19041.610
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/76
* VirusTotal Link: https://www.virustotal.com/gui/file/9b1f44ed54a0ab6d1a18d113ba3c946d961f4d652ffba0c3f1b2aa89a6cc7d0e/detection

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Windows\system32\wbem\WMIADAP.exe](WMIADAP.exe-1BFFABBD200C850E6346820E92B915DC.md) | 93

## Possible Misuse

*The following table contains possible examples of `WMIADAP.exe` being misused. While `WMIADAP.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_wmi_module_load.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/image_load/sysmon_wmi_module_load.yml) | `- '\windows\system32\wbem\WMIADAP.exe'  # https://github.com/SigmaHQ/sigma/issues/1871`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020-2021 Strontic.


