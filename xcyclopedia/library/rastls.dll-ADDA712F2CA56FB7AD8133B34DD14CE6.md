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

Function Name | Ordinal | Type | Address | Relative Address
-- | -- | -- | -- | --
`EapTls_SaveUserCredentials` | 5 (0x5) | Exported Function | 0x0000000180009e30 | 0x00009e30
`RasEapQueryUserBlobFromCredentialInputFields` | 21 (0x15) | Exported Function | 0x0000000180019520 | 0x00019520
`RasEapQueryUIBlobFromInteractiveUIInputFields` | 20 (0x14) | Exported Function | 0x0000000180019740 | 0x00019740
`RasEapQueryInteractiveUIInputFields` | 19 (0x13) | Exported Function | 0x00000001800196e0 | 0x000196e0
`RasEapQueryCredentialInputFields` | 18 (0x12) | Exported Function | 0x00000001800194b0 | 0x000194b0
`RasEapInvokeInteractiveUI` | 17 (0x11) | Exported Function | 0x000000018001cac0 | 0x0001cac0
`RasEapInvokeConfigUI` | 16 (0x10) | Exported Function | 0x000000018001c770 | 0x0001c770
`RasEapGetNextPageGuid` | 15 (0xf) | Exported Function | 0x000000018001bad0 | 0x0001bad0
`RasEapGetMethodProperties` | 14 (0xe) | Exported Function | 0x000000018001aad0 | 0x0001aad0
`RasEapGetInfo` | 13 (0xd) | Exported Function | 0x00000001800034e0 | 0x000034e0
`RasEapSetRetryFlag` | 22 (0x16) | Exported Function | 0x000000018000c660 | 0x0000c660
`RasEapGetIdentityPageGuid` | 12 (0xc) | Exported Function | 0x000000018001bb50 | 0x0001bb50
`RasEapGetCredentials` | 10 (0xa) | Exported Function | 0x000000018000c600 | 0x0000c600
`RasEapGetConfigBlobAndUserBlob` | 9 (0x9) | Exported Function | 0x000000018001c240 | 0x0001c240
`RasEapFreeMemory` | 8 (0x8) | Exported Function | 0x000000018001c620 | 0x0001c620
`RasEapCreateUserProperties2` | 4 (0x4) | Exported Function | 0x0000000180023090 | 0x00023090
`RasEapCreateUserProperties` | 7 (0x7) | Exported Function | 0x0000000180022f60 | 0x00022f60
`RasEapCreateMethodConfiguration` | 3 (0x3) | Exported Function | 0x0000000180028150 | 0x00028150
`RasEapCreateConnectionPropertiesXml` | 2 (0x2) | Exported Function | 0x0000000180027ae0 | 0x00027ae0
`RasEapCreateConnectionProperties2` | 1 (0x1) | Exported Function | 0x0000000180028350 | 0x00028350
`RasEapCreateConnectionProperties` | 6 (0x6) | Exported Function | 0x0000000180028240 | 0x00028240
`RasEapGetIdentity` | 11 (0xb) | Exported Function | 0x000000018001c4a0 | 0x0001c4a0
`RasEapUpdateServerConfig` | 23 (0x17) | Exported Function | 0x000000018001c640 | 0x0001c640


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


