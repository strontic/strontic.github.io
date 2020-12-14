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
MD5 | `72AC703193E2AD95FF112D3BF08DD4B2`
SHA1 | `2244F6FE9D68A35ABF3B8A66EA85BAD3D3F787C6`
SHA256 | `25063B72FEA5A86FE12073695F8A97E6BDC72A93417EFCC0D4156EF39BC6B46B`
SHA384 | `3F5C94571B267030AA817C962C35CAC7106A532FB5C954CC091A69E8E481A10DF2ED81CC31A27811F0E9643AEE45DFD5`
SHA512 | `CE50512E42BA07601AA73ECC9B66D2F9B94026E1D08A9FB14043A74104CFB2C5A792C648F2EF026AEA94ECCBB3CD19A4997E41C2684FFED5B1A0FA458DB24EF1`
SSDEEP | `768:ZAMBmP3+XxLKZ/XMsQt1TZPIR3fDUga9MWf7td7af75Ku7plyR8u4oCGkCs1iFg:HsP3+XxLKZ/XMsQt1TZPIR3fDUqWf5mT`
IMP | `EE9E4418B777C45B6741B9CE6DFC85B9`
PESHA1 | `B892231AF7335001C9C7F70A6A4657B3D9B5BBCD`
PE256 | `BBDF39450FD9840CCC74F61E9B48B5F3DE522A2023AE0AEAA4B17BCCF97D39F4`

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
* Serial: `33000001C422B2F79B793DACB20000000001C4`
* Thumbprint: `AE9C1AE54763822EEC42474983D8B635116C8452`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: extexport.exe
* Product Name: Internet Explorer
* Company Name: Microsoft Corporation
* File Version: 11.00.17763.1 (WinBuild.160101.0800)
* Product Version: 11.00.17763.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/70
* VirusTotal Link: https://www.virustotal.com/gui/file/25063b72fea5a86fe12073695f8a97e6bdc72a93417efcc0d4156ef39bc6b46b/detection/

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Program Files (x86)\Internet Explorer\ExtExport.exe](ExtExport.exe-3253FD643C51C133C3489A146781913B.md) | 66
[C:\Program Files\internet explorer\ExtExport.exe](ExtExport.exe-1D71EDDF5BC772FF5AAE7AD292A179D4.md) | 33
[C:\Program Files\Internet Explorer\ExtExport.exe](ExtExport.exe-B11437540BDFC36FEE80CAEFFF057D41.md) | 38

## Possible Misuse

*The following table contains possible examples of `ExtExport.exe` being misused. While `ExtExport.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

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


