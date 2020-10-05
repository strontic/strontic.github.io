---
title: rastls.dll | Remote Access PPP EAP-TLS
excerpt: What is rastls.dll?
---

# rastls.dll 

* File Path: `C:\Windows\SysWOW64\rastls.dll`
* Description: Remote Access PPP EAP-TLS

## Hashes

Type | Hash
-- | --
MD5 | `8249088FAB372970FBB19B3D581F0AD9`
SHA1 | `DB046F207FD13BFF801A232D8DFEE2B479B90960`
SHA256 | `495D4109CE742F828A0CE6B7AE0FFECEE6B1E59E7468828256B76BB3AC2A595E`
SHA384 | `618E29FF76CB958B6A2C4421541098760B0DD11B0C89161B0BA623A98B24566F27A326B44EEE7A04A16DE3DFDBC273DC`
SHA512 | `B4E5C7D5756394CBED9DE443C7FCEDF0F29B4B750EAD0B41312C87E62EA6BA4D82E62AADB4452400E6F55979830AB57FDDB15E02B7B32E307EF9A17D7498FF05`
SSDEEP | `6144:HWTo5QHAu6L/Vq+Yo3j2I7A89rSkuV3IKxdJWyJ/FeHKbGQwEcp:YpAj/Vq+Y8P7A89ryhdxpIHcGg`
IMP | `C5EAEF510A4BDBF71DE11ED632C7B9D2`
PESHA1 | `37F92871E5869D15E3EE226BF875B3A6E9988EBC`
PE256 | `2ABF2231ACCBD253BCC617F4A8CB7EAA75DABCE5E573A7EFA7C8BD994262D4D9`

## DLL Exports:

Function Name | Ordinal | Type
-- | -- | --
`RasEapInvokeConfigUI` | 16 | Exported Function
`RasEapInvokeInteractiveUI` | 17 | Exported Function
`RasEapGetNextPageGuid` | 15 | Exported Function
`RasEapGetInfo` | 13 | Exported Function
`RasEapGetMethodProperties` | 14 | Exported Function
`RasEapQueryCredentialInputFields` | 18 | Exported Function
`RasEapSetRetryFlag` | 22 | Exported Function
`RasEapUpdateServerConfig` | 23 | Exported Function
`RasEapQueryUserBlobFromCredentialInputFields` | 21 | Exported Function
`RasEapQueryInteractiveUIInputFields` | 19 | Exported Function
`RasEapQueryUIBlobFromInteractiveUIInputFields` | 20 | Exported Function
`RasEapGetIdentityPageGuid` | 12 | Exported Function
`RasEapCreateConnectionPropertiesXml` | 2 | Exported Function
`RasEapCreateMethodConfiguration` | 3 | Exported Function
`RasEapCreateConnectionProperties2` | 1 | Exported Function
`EapTls_SaveUserCredentials` | 5 | Exported Function
`RasEapCreateConnectionProperties` | 6 | Exported Function
`RasEapCreateUserProperties` | 7 | Exported Function
`RasEapGetCredentials` | 10 | Exported Function
`RasEapGetIdentity` | 11 | Exported Function
`RasEapGetConfigBlobAndUserBlob` | 9 | Exported Function
`RasEapCreateUserProperties2` | 4 | Exported Function
`RasEapFreeMemory` | 8 | Exported Function


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
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/72
* VirusTotal Link: https://www.virustotal.com/gui/file/495d4109ce742f828a0ce6b7ae0ffecee6b1e59e7468828256b76bb3ac2a595e/detection/


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


