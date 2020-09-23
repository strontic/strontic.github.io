---
title: wlanext.exe | Windows Wireless LAN 802.11 Extensibility Framework
excerpt: What is wlanext.exe?
---

# wlanext.exe 

* File Path: `C:\Windows\SysWOW64\wlanext.exe`
* Description: Windows Wireless LAN 802.11 Extensibility Framework

## Hashes

Type | Hash
-- | --
MD5 | `0D5F0A7CA2A8A47E3A26FB1CB67E118C`
SHA1 | `CD2F50FD5A7BD6291DE1948F100415044C767E63`
SHA256 | `3C928B9AFF2E651AA35EA798C29FDE398E9F7817E3451AE0F4C97C86630DC92B`
SHA384 | `A00F79D689B1B09624415409AA92BE148E74F6957CCF2914FF8B49A038EA13910D573312C3FF6AEE11F3A154D98BD2E3`
SHA512 | `84398D4E5680C2EA1679D0076468207A9503B053A233932FD3EFAEFDBF4559CFEAB5A0E95F526644C6382A88C17B6A62D3993323012211AB685DA4C4B025C045`
SSDEEP | `1536:UbDMdx4Tm9lSD2HAcOqa57xlYuNxo8b1E:+MduTm9lSD7rNKk6`
IMP | `DF1E2B2A61EF32982A6D4F4D8DD9F55A`
PESHA1 | `DA974224A232E72806CA6C2B4D5BFAAF0547698D`
PE256 | `DAC922BF57E44406D6611671A0B2A85AE4CF5466BFF85CD9626F88CC5964D831`

## Runtime Data

### Loaded Modules:

Path |
-- |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\wow64.dll |
C:\Windows\System32\wow64cpu.dll |
C:\Windows\System32\wow64win.dll |
C:\Windows\SysWOW64\wlanext.exe |


## Signature

* Status: Signature verified.
* Serial: `330000026551AE1BBD005CBFBD000000000265`
* Thumbprint: `E168609353F30FF2373157B4EB8CD519D07A2BFF`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: wlanext.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/73
* VirusTotal Link: https://www.virustotal.com/gui/file/3c928b9aff2e651aa35ea798c29fde398e9f7817e3451ae0f4c97c86630dc92b/detection/


## Possible Misuse

*The following table contains possible examples of `wlanext.exe` being misused. While `wlanext.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_creation_system_file.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/file_event/sysmon_creation_system_file.yml) | `- '*\wlanext.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_system_exe_anomaly.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_system_exe_anomaly.yml) | `- '*\wlanext.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020 Strontic.


