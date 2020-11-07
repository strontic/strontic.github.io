---
title: rastls.dll | Remote Access PPP EAP-TLS
excerpt: What is rastls.dll?
---

# rastls.dll 

* File Path: `C:\Windows\system32\rastls.dll`
* Description: Remote Access PPP EAP-TLS

## Hashes

Type | Hash
-- | --
MD5 | `ADDA712F2CA56FB7AD8133B34DD14CE6`
SHA1 | `D22042CC24FCD8812E923D782A0C0C1E5C18D64A`
SHA256 | `C12DC1D630A12EA466E3C89D9DDFDF6D7DB8C8CFF4CC0F4FE936BDB8318BCE5F`
SHA384 | `0B0649C694719DD723F475CA90E447F2000EFB88BA2C29F75984C93D5FFB649F70AF2DDF0CBEA1E83E4BE2A43287BB8A`
SHA512 | `4CC9BA68F64A203F5F9079267DF8A5CF63E634E2B19829F7419CFC977C7177F432451CC43949FEE644A7D718A2D9DFF999296BF1823E4675ED43E0321F63D008`
SSDEEP | `6144:W05qUUQZYsYYWo3P65YB0wsHwTekXsIOwRdJY2Nky9lT7TGmNrwEVIVJnpttHzI:WfLQZcgP6+vcUu0RXY09EmNkLVFF0`
IMP | `1715F15D7BC859ECA7FDB10FE035CB51`
PESHA1 | `A119FA1044B8AB141071C3B0D04558427D2AB8B9`
PE256 | `9B1C6319A8F9B93A2FCE4B08381092F43FFEAE9CDC75EB9BFDBFA83EA900BA95`

## DLL Exports:

Function Name | Ordinal | Type
-- | -- | --
`EapTls_SaveUserCredentials` | 5 | Exported Function
`RasEapQueryUserBlobFromCredentialInputFields` | 21 | Exported Function
`RasEapQueryUIBlobFromInteractiveUIInputFields` | 20 | Exported Function
`RasEapQueryInteractiveUIInputFields` | 19 | Exported Function
`RasEapQueryCredentialInputFields` | 18 | Exported Function
`RasEapInvokeInteractiveUI` | 17 | Exported Function
`RasEapInvokeConfigUI` | 16 | Exported Function
`RasEapGetNextPageGuid` | 15 | Exported Function
`RasEapGetMethodProperties` | 14 | Exported Function
`RasEapGetInfo` | 13 | Exported Function
`RasEapSetRetryFlag` | 22 | Exported Function
`RasEapGetIdentityPageGuid` | 12 | Exported Function
`RasEapGetCredentials` | 10 | Exported Function
`RasEapGetConfigBlobAndUserBlob` | 9 | Exported Function
`RasEapFreeMemory` | 8 | Exported Function
`RasEapCreateUserProperties2` | 4 | Exported Function
`RasEapCreateUserProperties` | 7 | Exported Function
`RasEapCreateMethodConfiguration` | 3 | Exported Function
`RasEapCreateConnectionPropertiesXml` | 2 | Exported Function
`RasEapCreateConnectionProperties2` | 1 | Exported Function
`RasEapCreateConnectionProperties` | 6 | Exported Function
`RasEapGetIdentity` | 11 | Exported Function
`RasEapUpdateServerConfig` | 23 | Exported Function


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: rastls.dll.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/72
* VirusTotal Link: https://www.virustotal.com/gui/file/c12dc1d630a12ea466e3c89d9ddfdf6d7db8c8cff4cc0f4fe936bdb8318bce5f/detection/


## Possible Misuse

*The following table contains possible examples of `rastls.dll` being misused. While `rastls.dll` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[malware-ioc](https://github.com/eset/malware-ioc) | [oceanlotus-rtf_ocx_campaigns.misp.event.json](https://github.com/eset/malware-ioc/blob/master/oceanlotus/oceanlotus-rtf_ocx_campaigns.misp.event.json) | `"info": "OceanLotus: rastls",` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [oceanlotus.misp.event.json](https://github.com/eset/malware-ioc/blob/master/oceanlotus/oceanlotus.misp.event.json) | `"info": "OceanLotus: rastls",` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [oceanlotus.misp.event.json](https://github.com/eset/malware-ioc/blob/master/oceanlotus/oceanlotus.misp.event.json) | `"value": "rastls.dll\|82e579bd49d69845133c9aa8585f8bd26736437b",` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [oceanlotus.misp.event.json](https://github.com/eset/malware-ioc/blob/master/oceanlotus/oceanlotus.misp.event.json) | `"value": "rastls.dll\|981640ae7c12e94aafca3cb4356e37a362f66f53",` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [oceanlotus.misp.event.json](https://github.com/eset/malware-ioc/blob/master/oceanlotus/oceanlotus.misp.event.json) | `"value": "rastls.dll\|1bd6f7e4c74a339d04d2fbf0e672363531145f49",` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [oceanlotus](https://github.com/eset/malware-ioc/blob/master/oceanlotus/README.adoc) | `For a description of OceanLotus' latest campaign (using side-loaded binaries such as rastls.exe)` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [oceanlotus](https://github.com/eset/malware-ioc/blob/master/oceanlotus/README.adoc) | `\|`82e579bd49d69845133c9aa8585f8bd26736437b`\|rastls.dll\|Win32/Salgorea.BD` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_cn_pp_zerot.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_cn_pp_zerot.yar) | $s2 = "RasTls.dll" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_cn_pp_zerot.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_cn_pp_zerot.yar) | $s1 = "RasTls.dll" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_cn_pp_zerot.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_cn_pp_zerot.yar) | $s2 = "RasTls.exe" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)



MIT License. Copyright (c) 2020 Strontic.


