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

Function Name | Ordinal | Type | Address | Relative Address
-- | -- | -- | -- | --
`CloseCompressor` | 35 (0x23) | Exported Function | 0x00000001800040b0 | 0x000040b0
`ResetDecompressor` | 44 (0x2c) | Exported Function | 0x0000000180015480 | 0x00015480
`ResetCompressor` | 34 (0x22) | Exported Function | 0x0000000180015400 | 0x00015400
`QueryDecompressorInformation` | 42 (0x2a) | Exported Function | 0x00000001800153e0 | 0x000153e0
`QueryCompressorInformation` | 32 (0x20) | Exported Function | 0x0000000180015330 | 0x00015330
`GetDllVersion` | 1 (0x1) | Exported Function | 0x000000018000b940 | 0x0000b940
`FDITruncateCabinet` | 24 (0x18) | Exported Function | 0x000000018000cd50 | 0x0000cd50
`FDIIsCabinet` | 21 (0x15) | Exported Function | 0x0000000180008e20 | 0x00008e20
`FDIDestroy` | 23 (0x17) | Exported Function | 0x00000001800072b0 | 0x000072b0
`FDICreate` | 20 (0x14) | Exported Function | 0x0000000180008d10 | 0x00008d10
`FDICopy` | 22 (0x16) | Exported Function | 0x0000000180005f00 | 0x00005f00
`FCIFlushFolder` | 12 (0xc) | Exported Function | 0x000000018000e980 | 0x0000e980
`FCIFlushCabinet` | 13 (0xd) | Exported Function | 0x000000018000e8f0 | 0x0000e8f0
`FCIDestroy` | 14 (0xe) | Exported Function | 0x000000018000e880 | 0x0000e880
`FCICreate` | 10 (0xa) | Exported Function | 0x000000018000e5b0 | 0x0000e5b0
`FCIAddFile` | 11 (0xb) | Exported Function | 0x000000018000e450 | 0x0000e450
`Extract` | 3 (0x3) | Exported Function | 0x000000018000c630 | 0x0000c630
`DllGetVersion` | 2 (0x2) | Exported Function | 0x000000018000b8a0 | 0x0000b8a0
`DeleteExtractedFiles` | 4 (0x4) | Exported Function | 0x000000018000c560 | 0x0000c560
`Decompress` | 43 (0x2b) | Exported Function | 0x0000000180004450 | 0x00004450
`CreateDecompressor` | 40 (0x28) | Exported Function | 0x00000001800041f0 | 0x000041f0
`CreateCompressor` | 30 (0x1e) | Exported Function | 0x00000001800040c0 | 0x000040c0
`Compress` | 33 (0x21) | Exported Function | 0x0000000180004070 | 0x00004070
`CloseDecompressor` | 45 (0x2d) | Exported Function | 0x0000000180004200 | 0x00004200
`SetCompressorInformation` | 31 (0x1f) | Exported Function | 0x0000000180015490 | 0x00015490
`SetDecompressorInformation` | 41 (0x29) | Exported Function | 0x0000000180015540 | 0x00015540


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


