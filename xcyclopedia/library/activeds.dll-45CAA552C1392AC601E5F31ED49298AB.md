---
title: activeds.dll | ADs Router Layer DLL
excerpt: What is activeds.dll?
---

# activeds.dll 

* File Path: `C:\Windows\system32\activeds.dll`
* Description: ADs Router Layer DLL

## Hashes

Type | Hash
-- | --
MD5 | `45CAA552C1392AC601E5F31ED49298AB`
SHA1 | `72759E7D7228E367A8FF41B77D22153B9DEF9A6F`
SHA256 | `67E98C5D16548A5CC7131724329C213E607D62530A41E8556DE4FB2C7940981F`
SHA384 | `D32AD83595E5D27BF2587E2E821AB3D776EFF76F8C74F3BA774B58AE999FF19016385F0584DB39C616DBBDE21AA47944`
SHA512 | `47DF1443A6B2C5D98853ECFDE0B8679B0A5DE64BC7BB749754DA083EBF89C046F3A1D3479210EA4B9FB1A01A381AA81D202A3F43E8D0CE08ADAFAE220B3D035F`
SSDEEP | `6144:0ZHevISEPHPonCfSIgbRWKQ9GnWEbxOZ61BjZ8:0JP7HPonCfSIoRWh92WEFOZ63Z8`
IMP | `0EE180C40BE7065C4D3C53E2BEC29F75`
PESHA1 | `E6D072F1F81B50D01B3D0BE420CC1C44BC1DFEE1`
PE256 | `F0FCD8DE8DE675A015AB1AA3DD90EA22648D72EF76BAC86636588153CCD775D4`

## DLL Exports:

Function Name | Ordinal | Type
-- | -- | --
`ConvertTrusteeToSid` | 31 | Exported Function
`DllCanUnloadNow` | 10 | Exported Function
`DllGetClassObject` | 11 | Exported Function
`ConvertSecurityDescriptorToSecDes` | 28 | Exported Function
`AllocADsStr` | 17 | Exported Function
`BinarySDToSecurityDescriptor` | 29 | Exported Function
`ConvertSecDescriptorToVariant` | 27 | Exported Function
`ReallocADsMem` | 16 | Exported Function
`ReallocADsStr` | 19 | Exported Function
`SecurityDescriptorToBinarySD` | 30 | Exported Function
`PropVariantToAdsType2` | 26 | Exported Function
`FreeADsMem` | 15 | Exported Function
`FreeADsStr` | 18 | Exported Function
`PropVariantToAdsType` | 21 | Exported Function
`AllocADsMem` | 14 | Exported Function
`ADsEncodeBinaryData` | 20 | Exported Function
`ADsEnumerateNext` | 6 | Exported Function
`AdsFreeAdsValues` | 23 | Exported Function
`ADsDecodeBinaryData` | 24 | Exported Function
`ADsBuildEnumerator` | 4 | Exported Function
`ADsBuildVarArrayInt` | 8 | Exported Function
`ADsBuildVarArrayStr` | 7 | Exported Function
`ADsSetLastError` | 12 | Exported Function
`AdsTypeToPropVariant` | 22 | Exported Function
`AdsTypeToPropVariant2` | 25 | Exported Function
`ADsOpenObject` | 9 | Exported Function
`ADsFreeEnumerator` | 5 | Exported Function
`ADsGetLastError` | 13 | Exported Function
`ADsGetObject` | 3 | Exported Function


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: ADs
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/67
* VirusTotal Link: https://www.virustotal.com/gui/file/67e98c5d16548a5cc7131724329c213e607d62530a41e8556de4fb2c7940981f/detection/


## Possible Misuse

*The following table contains possible examples of `activeds.dll` being misused. While `activeds.dll` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[malware-ioc](https://github.com/eset/malware-ioc) | [evilnum](https://github.com/eset/malware-ioc/blob/master/evilnum/README.adoc) | `1F287AA922911F72F68B4B0C8645B4C909EB07B9 – ACTIVEDS.dll` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_agent_btz.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_agent_btz.yar) | description = "Detects Agent-BTZ Proxy DLL - activeds.dll" | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_agent_btz.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_agent_btz.yar) | $s2 = "activeds.dll" ascii fullword | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)



MIT License. Copyright (c) 2020 Strontic.


