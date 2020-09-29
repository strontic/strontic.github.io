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

Function Name | Ordinal | Type | Address | Relative Address
-- | -- | -- | -- | --
`EapTls_SaveUserCredentials` | 5 (0x5) | Exported Function | 0x731b0ac0 | 0x00010ac0
`RasEapQueryUserBlobFromCredentialInputFields` | 21 (0x15) | Exported Function | 0x731bdc00 | 0x0001dc00
`RasEapQueryUIBlobFromInteractiveUIInputFields` | 20 (0x14) | Exported Function | 0x731bdd70 | 0x0001dd70
`RasEapQueryInteractiveUIInputFields` | 19 (0x13) | Exported Function | 0x731bdd20 | 0x0001dd20
`RasEapQueryCredentialInputFields` | 18 (0x12) | Exported Function | 0x731bdbb0 | 0x0001dbb0
`RasEapInvokeInteractiveUI` | 17 (0x11) | Exported Function | 0x731c0620 | 0x00020620
`RasEapInvokeConfigUI` | 16 (0x10) | Exported Function | 0x731c03f0 | 0x000203f0
`RasEapGetNextPageGuid` | 15 (0xf) | Exported Function | 0x731bfb00 | 0x0001fb00
`RasEapGetMethodProperties` | 14 (0xe) | Exported Function | 0x731bec30 | 0x0001ec30
`RasEapGetInfo` | 13 (0xd) | Exported Function | 0x731ab950 | 0x0000b950
`RasEapSetRetryFlag` | 22 (0x16) | Exported Function | 0x731b2b70 | 0x00012b70
`RasEapGetIdentityPageGuid` | 12 (0xc) | Exported Function | 0x731bfb80 | 0x0001fb80
`RasEapGetCredentials` | 10 (0xa) | Exported Function | 0x731b2b00 | 0x00012b00
`RasEapGetConfigBlobAndUserBlob` | 9 (0x9) | Exported Function | 0x731c00c0 | 0x000200c0
`RasEapFreeMemory` | 8 (0x8) | Exported Function | 0x731c02f0 | 0x000202f0
`RasEapCreateUserProperties2` | 4 (0x4) | Exported Function | 0x731c57d0 | 0x000257d0
`RasEapCreateUserProperties` | 7 (0x7) | Exported Function | 0x731c5710 | 0x00025710
`RasEapCreateMethodConfiguration` | 3 (0x3) | Exported Function | 0x731c9340 | 0x00029340
`RasEapCreateConnectionPropertiesXml` | 2 (0x2) | Exported Function | 0x731c8de0 | 0x00028de0
`RasEapCreateConnectionProperties2` | 1 (0x1) | Exported Function | 0x731c94c0 | 0x000294c0
`RasEapCreateConnectionProperties` | 6 (0x6) | Exported Function | 0x731c9400 | 0x00029400
`RasEapGetIdentity` | 11 (0xb) | Exported Function | 0x731c0250 | 0x00020250
`RasEapUpdateServerConfig` | 23 (0x17) | Exported Function | 0x731c0310 | 0x00020310


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


