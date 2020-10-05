---
title: cabinet.dll | Microsoft Cabinet File API
excerpt: What is cabinet.dll?
---

# cabinet.dll 

* File Path: `C:\Windows\SysWOW64\cabinet.dll`
* Description: Microsoft Cabinet File API

## Hashes

Type | Hash
-- | --
MD5 | `5BD52B64ACE2D6A7488FCC66BEF4A88E`
SHA1 | `F5F33582073CE95A06A3DBDFFAC2336A10335FC5`
SHA256 | `53CDCCAF41FEDD8DE8E08DE655F2DC3750BB295E6C372B27C46BFCA35CEF2C8D`
SHA384 | `F02A94D81E805CA51593DC7859EB3E871D980F1B510F6E1D2CF34149D24EC03FC2C77ECF314F2B132BCF87FC31C1136B`
SHA512 | `584160A3ABF7CE6D9845B6226EB88A44B073DD6EE32C75097CC816A567211FB7074A52A8F4CFDB93BB1E0195E684E7E3174A181D91732E7E0CB81784501DD6F7`
SSDEEP | `3072:UjdaFH7hmla16QHdVy9JxKDZseF0ro4j8vumo/jfjMmn4Gvnf:8dawlwDTZseF0roruVLMqf`
IMP | `AA8FEC983B5950909A9C036F70CA7EAD`
PESHA1 | `47DFD788F6C42FF438FF689682F36766312D4326`
PE256 | `D080DC2861F0E58E2439792A50D2DE3D2A30D3EC6DEE8C0873B1CB6F2757A62B`

## DLL Exports:

Function Name | Ordinal | Type
-- | -- | --
`FDIDestroy` | 23 | Exported Function
`FDIIsCabinet` | 21 | Exported Function
`FDITruncateCabinet` | 24 | Exported Function
`FCIFlushFolder` | 12 | Exported Function
`FDICopy` | 22 | Exported Function
`FDICreate` | 20 | Exported Function
`GetDllVersion` | 1 | Exported Function
`ResetDecompressor` | 44 | Exported Function
`SetCompressorInformation` | 31 | Exported Function
`SetDecompressorInformation` | 41 | Exported Function
`QueryCompressorInformation` | 32 | Exported Function
`QueryDecompressorInformation` | 42 | Exported Function
`ResetCompressor` | 34 | Exported Function
`CreateCompressor` | 30 | Exported Function
`CreateDecompressor` | 40 | Exported Function
`Decompress` | 43 | Exported Function
`CloseCompressor` | 35 | Exported Function
`CloseDecompressor` | 45 | Exported Function
`Compress` | 33 | Exported Function
`DeleteExtractedFiles` | 4 | Exported Function
`FCICreate` | 10 | Exported Function
`FCIDestroy` | 14 | Exported Function
`FCIFlushCabinet` | 13 | Exported Function
`DllGetVersion` | 2 | Exported Function
`Extract` | 3 | Exported Function
`FCIAddFile` | 11 | Exported Function


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: cabinet.dll
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 5.00 (WinBuild.160101.0800)
* Product Version: 5.00
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/68
* VirusTotal Link: https://www.virustotal.com/gui/file/53cdccaf41fedd8de8e08de655f2dc3750bb295e6c372b27c46bfca35cef2c8d/detection/


## Possible Misuse

*The following table contains possible examples of `cabinet.dll` being misused. While `cabinet.dll` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Diantz.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Diantz.yml) | `Description: Binary that package existing files into a cabinet (.cab) file` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Makecab.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Makecab.yml) | `Description: Binary to package existing files into a cabinet (.cab) file` | 
[malware-ioc](https://github.com/eset/malware-ioc) | [nouns.txt](https://github.com/eset/malware-ioc/blob/master/kryptocibule/nouns.txt) | `cabinet` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [exploit_uac_elevators.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/exploit_uac_elevators.yar) | $l2 = "Cabinet.dll" ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)



MIT License. Copyright (c) 2020 Strontic.


