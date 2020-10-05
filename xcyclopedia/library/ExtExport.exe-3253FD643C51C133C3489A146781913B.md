---
title: ExtExport.exe | Internet Explorer ImpExp FF exporter
excerpt: What is ExtExport.exe?
---

# ExtExport.exe 

* File Path: `C:\Program Files (x86)\Internet Explorer\ExtExport.exe`
* Description: Internet Explorer ImpExp FF exporter

## Hashes

Type | Hash
-- | --
MD5 | `3253FD643C51C133C3489A146781913B`
SHA1 | `73360B5D4769AD80BF90DFF956BEA7C9C04DB1B5`
SHA256 | `D8820E333BE39B27712C42766D1F141CB45FFBE183C43286E55ECC1B9A82FA4B`
SHA384 | `DACD35D0BCEA814EAE5925B3F718EA7FC201AA4BB86F23C9D87C11AD62C3286C82A099D597EDE5641CB8D3CD5CD9CDBC`
SHA512 | `238C1AA3AE4551BA0784C93F332CE7702377AF13C11C4233CFF7D426B9ABEE388EEA387A4C797B438544FF51B0960D1BBAB323A7337E12DA5E5970C467AABC70`
SSDEEP | `768:ksAMBmP3+XxLKZ/XMsQt1TZPI5yGz786Hyew0fPcLqCgGc00kZ4e537trS:9sP3+XxLKZ/XMsQt1TZPI5yGz7bS/XLk`
IMP | `3868F993A68746205F088529EA9E5225`
PESHA1 | `3DC083D8D21E9EA02FAD61A94F945A2C26B34D28`
PE256 | `D4D4817D4BBF56BDC0C538C7EDD95F7BB3E72E69F1CFB8B8B2C15BAD642CB1F0`

## Runtime Data

### Loaded Modules:

Path |
-- |
C:\Program Files (x86)\Internet Explorer\ExtExport.exe |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\wow64.dll |
C:\Windows\System32\wow64cpu.dll |
C:\Windows\System32\wow64win.dll |


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: extexport.exe
* Product Name: Internet Explorer
* Company Name: Microsoft Corporation
* File Version: 11.00.19041.1 (WinBuild.160101.0800)
* Product Version: 11.00.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/70
* VirusTotal Link: https://www.virustotal.com/gui/file/d8820e333be39b27712c42766d1f141cb45ffbe183c43286e55ecc1b9a82fa4b/detection/

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Program Files\Internet Explorer\ExtExport.exe](ExtExport.exe-B11437540BDFC36FEE80CAEFFF057D41.md) | 38

## Possible Misuse

*The following table contains possible examples of `ExtExport.exe` being misused. While `ExtExport.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Extexport.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Extexport.yml) | `Name: Extexport.exe` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Extexport.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Extexport.yml) | `- Command: Extexport.exe c:\test foo bar` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Extexport.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Extexport.yml) | `- Path: C:\Program Files\Internet Explorer\Extexport.exe` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Extexport.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Extexport.yml) | `- Path: C:\Program Files (x86)\Internet Explorer\Extexport.exe` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Extexport.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Extexport.yml) | `- IOC: Extexport.exe loads dll and is execute from other folder the original path` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Extexport.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Extexport.yml) | `- Link: http://www.hexacorn.com/blog/2018/04/24/extexport-yet-another-lolbin/` | 
[malware-ioc](https://github.com/eset/malware-ioc) | [guildma](https://github.com/eset/malware-ioc/blob/master/guildma/README.adoc) | `** `C:\Program Files (x86)\Internet Explorer\ExtExport.exe`` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [guildma](https://github.com/eset/malware-ioc/blob/master/guildma/README.adoc) | `** `C:\Program Files\Internet Explorer\ExtExport.exe`` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)



MIT License. Copyright (c) 2020 Strontic.


