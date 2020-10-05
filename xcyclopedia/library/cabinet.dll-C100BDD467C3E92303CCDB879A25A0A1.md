---
title: cabinet.dll | Microsoft Cabinet File API
excerpt: What is cabinet.dll?
---

# cabinet.dll 

* File Path: `C:\Windows\system32\cabinet.dll`
* Description: Microsoft Cabinet File API

## Hashes

Type | Hash
-- | --
MD5 | `C100BDD467C3E92303CCDB879A25A0A1`
SHA1 | `11D43213FCF0FE851A8419BF27BBFD9C6B40B992`
SHA256 | `C486A6F9715D1900989740698F0BB5969E1DF537FA3DA4174BD63D6807BEC9B1`
SHA384 | `4F76F47FC174C91063AEFF709631C62E4C44C3D983135C319599799504C5DBC5869FF5F12F383732E816479B96A8536B`
SHA512 | `E44779EFA7FBCC259CA1EDEE8FC10F3769C08E7FC3E7A646C6EDBE63A46128B1B339D3C89B2446B1DF52A2936A3012DDD33845A886BFBED45BCF64707AD4F1DD`
SSDEEP | `1536:7mGoAI+ZFJNmljPxvTgfFp+5cKB/tzDau+FccNBy11S5EEolRHG5BOZKINUN+0tW:7mGkQFAqn8d/zDNmZ+1LE+DKI+NYAV4r`
IMP | `43089E1FD23B10D2778868432FE3423A`
PESHA1 | `A1F3DD1E473F3CCEE64F1A0375F4D46EFF300D59`
PE256 | `E6F24AE9EFAA3E87EE33616283B90F51DC64A9902EFC310B2399F9384E361A14`

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
* Serial: `330000026551AE1BBD005CBFBD000000000265`
* Thumbprint: `E168609353F30FF2373157B4EB8CD519D07A2BFF`
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
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/71
* VirusTotal Link: https://www.virustotal.com/gui/file/c486a6f9715d1900989740698f0bb5969e1df537fa3da4174bd63d6807bec9b1/detection/


## Possible Misuse

*The following table contains possible examples of `cabinet.dll` being misused. While `cabinet.dll` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Diantz.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Diantz.yml) | `Description: Binary that package existing files into a cabinet (.cab) file` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Makecab.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Makecab.yml) | `Description: Binary to package existing files into a cabinet (.cab) file` | 
[malware-ioc](https://github.com/eset/malware-ioc) | [nouns.txt](https://github.com/eset/malware-ioc/blob/master/kryptocibule/nouns.txt) | `cabinet` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [exploit_uac_elevators.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/exploit_uac_elevators.yar) | $l2 = "Cabinet.dll" ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)



MIT License. Copyright (c) 2020 Strontic.


