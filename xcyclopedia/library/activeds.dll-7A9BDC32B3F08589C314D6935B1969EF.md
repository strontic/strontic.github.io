---
title: activeds.dll | ADs Router Layer DLL
excerpt: What is activeds.dll?
---

# activeds.dll 

* File Path: `C:\Windows\SysWOW64\activeds.dll`
* Description: ADs Router Layer DLL

## Hashes

Type | Hash
-- | --
MD5 | `7A9BDC32B3F08589C314D6935B1969EF`
SHA1 | `B5CA5973D8D03E9D90857AB60192B44361A6F92A`
SHA256 | `78FB0AC33F7EAD29F16EC1B9A0B44843962722346BB9A938434950C69DC15468`
SHA384 | `78EDDF61FE2C1BFEFA5AA08573178E4F858B7D6493DA121BBE016172432FF3B8B69D473DE3B31B62623A3AFDAF6DC0A3`
SHA512 | `B766F7E4D22DF80E831AE9330EB99C9449F50C158622E15425C01A6C536CA43E1ADF193DBF9993C5B351D0C65557A67E2D590AB486A35A9567E1B0EDA9F0BBAD`
SSDEEP | `6144:qqxLnlGakgCKl71z29t5oM0tqB63Lje5:qqxLnBkgN6XKMwK6P`
IMP | `A84D85413A75CD6302EE7E19425039C3`
PESHA1 | `0FD576E2D83A88AE70EE3211662A34EB6E35F757`
PE256 | `63D79EB45ACD06DFA59F0E7ABFAD00BC456B1EF4CFE93C1B1FFDD862A8B0534C`

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
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/70
* VirusTotal Link: https://www.virustotal.com/gui/file/78fb0ac33f7ead29f16ec1b9a0b44843962722346bb9a938434950c69dc15468/detection/


## Possible Misuse

*The following table contains possible examples of `activeds.dll` being misused. While `activeds.dll` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[malware-ioc](https://github.com/eset/malware-ioc) | [evilnum](https://github.com/eset/malware-ioc/blob/master/evilnum/README.adoc) | `1F287AA922911F72F68B4B0C8645B4C909EB07B9 – ACTIVEDS.dll` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_agent_btz.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_agent_btz.yar) | description = "Detects Agent-BTZ Proxy DLL - activeds.dll" | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_agent_btz.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_agent_btz.yar) | $s2 = "activeds.dll" ascii fullword | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)



MIT License. Copyright (c) 2020 Strontic.


