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

Function Name | Ordinal | Type | Address | Relative Address
-- | -- | -- | -- | --
`DllCanUnloadNow` | 108 (0x6c) | Exported Function | 0x000000018000e8a0 | 0x0000e8a0
`VaultGetItemType` | 122 (0x7a) | Exported Function | 0x0000000180003400 | 0x00003400
`VaultGetItem` | 121 (0x79) | Exported Function | 0x0000000180003500 | 0x00003500
`VaultGetInformation` | 120 (0x78) | Exported Function | 0x000000018001b970 | 0x0001b970
`VaultFree` | 119 (0x77) | Exported Function | 0x0000000180017410 | 0x00017410
`VaultFindItems` | 118 (0x76) | Exported Function | 0x000000018001b840 | 0x0001b840
`VaultEnumerateVaults` | 117 (0x75) | Exported Function | 0x000000018001b770 | 0x0001b770
`VaultEnumerateItemTypes` | 115 (0x73) | Exported Function | 0x000000018001b630 | 0x0001b630
`VaultEnumerateItems` | 116 (0x74) | Exported Function | 0x0000000180002820 | 0x00002820
`VaultDeleteItemType` | 114 (0x72) | Exported Function | 0x000000018001b550 | 0x0001b550
`VaultCreateItemType` | 113 (0x71) | Exported Function | 0x000000018001b440 | 0x0001b440
`VaultCloseVault` | 112 (0x70) | Exported Function | 0x0000000180003620 | 0x00003620
`VaultAddItem` | 111 (0x6f) | Exported Function | 0x000000018001b380 | 0x0001b380
`Ordinal107` | 107 (0x6b) | Exported Function | 0x00000001800036b0 | 0x000036b0
`Ordinal106` | 106 (0x6a) | Exported Function | 0x000000018001aba0 | 0x0001aba0
`Ordinal105` | 105 (0x69) | Exported Function | 0x000000018001b1f0 | 0x0001b1f0
`Ordinal104` | 104 (0x68) | Exported Function | 0x000000018001b160 | 0x0001b160
`Ordinal103` | 103 (0x67) | Exported Function | 0x000000018001af50 | 0x0001af50
`Ordinal102` | 102 (0x66) | Exported Function | 0x000000018001b080 | 0x0001b080
`Ordinal101` | 101 (0x65) | Exported Function | 0x000000018001afe0 | 0x0001afe0
`DllGetClassObject` | 110 (0x6e) | Exported Function | 0x0000000180017c30 | 0x00017c30
`DllGetActivationFactory` | 109 (0x6d) | Exported Function | 0x000000018000ea10 | 0x0000ea10
`VaultOpenVault` | 123 (0x7b) | Exported Function | 0x00000001800038f0 | 0x000038f0
`VaultRemoveItem` | 124 (0x7c) | Exported Function | 0x000000018001ba00 | 0x0001ba00


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


