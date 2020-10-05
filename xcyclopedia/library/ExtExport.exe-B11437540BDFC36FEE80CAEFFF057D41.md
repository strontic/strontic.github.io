---
title: ExtExport.exe | Internet Explorer ImpExp FF exporter
excerpt: What is ExtExport.exe?
---

# ExtExport.exe 

* File Path: `C:\Program Files\Internet Explorer\ExtExport.exe`
* Description: Internet Explorer ImpExp FF exporter

## Hashes

Type | Hash
-- | --
MD5 | `B11437540BDFC36FEE80CAEFFF057D41`
SHA1 | `6A42E42B74AF85DE5BCB5DEEC54CBEF83CA66E27`
SHA256 | `EDC454BCA93A7D41D193A59953BDE82766FC6874345A71BEA2A8C52E71D06E29`
SHA384 | `38934CA37FEB702F3BA7D943E7EB49F36C1AC8A29462106D17E4AB447FD3A1440B949B308AF097366C0C70D166DD611C`
SHA512 | `8BDCB574DBD83E805E101E325B081E1ABE19078ACF1679BF6167041476A1AFB4FE813B1B1F5D6DD6C97B4B1C2D659425232AE699DD26ABB7945B8F7AB0096433`
SSDEEP | `1536:uMzsdDPVEPBLllUau56M+gQFafuVHVcCU+Mv3+3xbKZ/nMsQt1TZ/I8PScMI:uM4dDVEjlUau56M+gQ3HO7+Mv3+3xbKo`
IMP | `9F19CF94DB3339462A59D9352CFE30B0`
PESHA1 | `1A678C7DB2FBC9A30F96547EF1AF905F60D21394`
PE256 | `9EA77BDDCE763434180573FAEAF3D1F9687ECBF37B50941E5B6145E8F3C4CD72`

## Runtime Data

### Loaded Modules:

Path |
-- |
C:\Program Files\Internet Explorer\ExtExport.exe |
C:\Windows\System32\ADVAPI32.dll |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\System32\msvcrt.dll |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\ole32.dll |
C:\Windows\System32\RPCRT4.dll |
C:\Windows\System32\sechost.dll |
C:\Windows\System32\ucrtbase.dll |


## Signature

* Status: Signature verified.
* Serial: `330000026551AE1BBD005CBFBD000000000265`
* Thumbprint: `E168609353F30FF2373157B4EB8CD519D07A2BFF`
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
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/70
* VirusTotal Link: https://www.virustotal.com/gui/file/edc454bca93a7d41d193a59953bde82766fc6874345a71bea2a8c52e71d06e29/detection/

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Program Files (x86)\Internet Explorer\ExtExport.exe](ExtExport.exe-3253FD643C51C133C3489A146781913B.md) | 38

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


