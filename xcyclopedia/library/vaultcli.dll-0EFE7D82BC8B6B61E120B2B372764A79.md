---
title: vaultcli.dll | Credential Vault Client Library
excerpt: What is vaultcli.dll?
---

# vaultcli.dll 

* File Path: `C:\Windows\SysWOW64\vaultcli.dll`
* Description: Credential Vault Client Library

## Hashes

Type | Hash
-- | --
MD5 | `0EFE7D82BC8B6B61E120B2B372764A79`
SHA1 | `4E7994F68D23782858A7413ABA781E944C4F7B9E`
SHA256 | `1ABE5B981D6D2E15ECE19492C370EF65E5D108FA9C3F5BD30AF95E8309C4336E`
SHA384 | `5E1C13DB6D61BF54E27074B3E565A8256D98BEA0C0BE9B19D362366E5AD03634B21E4D81E90CFD96B783E4A7E590A7FE`
SHA512 | `586955E14C57CC8CD63E7BC904581BEB0AD6727329AA360BA2950693FC9B76F39EBD0BA8219F8BBE4432C1F7B1323EE759785816D2E6A0BC0923A896212E1E5C`
SSDEEP | `3072:up+FZ3QsApi6nZSPU8uMx3X40wGGGyZl3ggqAGrCfWKzsVqkl4y0R6K7Rh7Fsv9i:muZMEUhMFXzYFNsVq5f7R09U`
IMP | `8B824B587B693BF72EF4CD3CF1854355`
PESHA1 | `8BAB4B901A8C0A415DD62FE337ACEE52E8E08A29`
PE256 | `7FFA59479AA6A42BDAE81378B650AB840A48462511C81F4640C214C7586B0920`

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
* Serial: `330000026551AE1BBD005CBFBD000000000265`
* Thumbprint: `E168609353F30FF2373157B4EB8CD519D07A2BFF`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: vaultcli.dll
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.264 (WinBuild.160101.0800)
* Product Version: 10.0.19041.264
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/71
* VirusTotal Link: https://www.virustotal.com/gui/file/1abe5b981d6d2e15ece19492c370ef65e5d108fa9c3f5bd30af95e8309c4336e/detection/


## Possible Misuse

*The following table contains possible examples of `vaultcli.dll` being misused. While `vaultcli.dll` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_mimikatz_inmemory_detection.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/image_load/sysmon_mimikatz_inmemory_detection.yml) | `ImageLoaded: '*\vaultcli.dll'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020 Strontic.


