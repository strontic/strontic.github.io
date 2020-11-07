---
title: vaultcli.dll | Credential Vault Client Library
excerpt: What is vaultcli.dll?
---

# vaultcli.dll 

* File Path: `C:\Windows\system32\vaultcli.dll`
* Description: Credential Vault Client Library

## Hashes

Type | Hash
-- | --
MD5 | `7B4B47A2DB822854AD6B5E7B30258DF0`
SHA1 | `F45EF51318D19119794013B8D9B0007763E42B31`
SHA256 | `53EBA13691F593B53B7119949D1421506A1C64C1222EFD0EB45B16B8BB9A9449`
SHA384 | `173E2D55CD4E2EA5E46EF63A20B61CE6A29C05DAB433E971900E08C42D7EEDA923E9B01EBF1D1B11292699E9B68B3804`
SHA512 | `2F0ED9857FB61AAC93BF05901C4E583DCD1E3D4B65E2C3D1ACE9485292C8D6997F521BAFA67C60BE873C773E1015BEB53234A98649100A1D7E5CE9F5E6A073EC`
SSDEEP | `3072:eCgi+/snZ3MyX6HXnIB7ZxHLiL3BU8D7M2l+swcQsAp8Z/BRwAvibWDPDG6k:eCfZPXW3I9HmOylBwqZfwpWj66`
IMP | `D74C340A21D3A0792E913BA12F081859`
PESHA1 | `82094845D9F95B91A03E94216E75FA18A822B5F3`
PE256 | `601359DE5DED29DC4893005EF2E7F0EAE107FAA83E1E522BE5EC727FDB843EA2`

## DLL Exports:

Function Name | Ordinal | Type
-- | -- | --
`DllCanUnloadNow` | 108 | Exported Function
`VaultGetItemType` | 122 | Exported Function
`VaultGetItem` | 121 | Exported Function
`VaultGetInformation` | 120 | Exported Function
`VaultFree` | 119 | Exported Function
`VaultFindItems` | 118 | Exported Function
`VaultEnumerateVaults` | 117 | Exported Function
`VaultOpenVault` | 123 | Exported Function
`VaultEnumerateItemTypes` | 115 | Exported Function
`VaultDeleteItemType` | 114 | Exported Function
`VaultCreateItemType` | 113 | Exported Function
`VaultCloseVault` | 112 | Exported Function
`VaultAddItem` | 111 | Exported Function
`DllGetClassObject` | 110 | Exported Function
`DllGetActivationFactory` | 109 | Exported Function
`VaultEnumerateItems` | 116 | Exported Function
`VaultRemoveItem` | 124 | Exported Function


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: vaultcli.dll.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/67
* VirusTotal Link: https://www.virustotal.com/gui/file/53eba13691f593b53b7119949d1421506a1c64c1222efd0eb45b16b8bb9a9449/detection/


## Possible Misuse

*The following table contains possible examples of `vaultcli.dll` being misused. While `vaultcli.dll` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_mimikatz_inmemory_detection.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/image_load/sysmon_mimikatz_inmemory_detection.yml) | `ImageLoaded: '*\vaultcli.dll'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020 Strontic.


