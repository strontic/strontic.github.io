---
title: msports.dll | Ports Class Installer
excerpt: What is msports.dll?
---

# msports.dll 

* File Path: `C:\Windows\system32\msports.dll`
* Description: Ports Class Installer

## Hashes

Type | Hash
-- | --
MD5 | `5D89B4B9781677DA040D8D1032E9D9E9`
SHA1 | `492AA4DAA689DA95E69CDC5E9F29586EE84097F7`
SHA256 | `93247247D9C3A7268C0638ECCA1FDF31A161E028AD89E9DD5D71B97131113797`
SHA384 | `67FF7114D98BDFA8B762F8FA81729FE484306948FC7B4F1AA977ABE5A1918DF26DAFEF23F250EBAFAF6077874A250CD7`
SHA512 | `999C957C57C111C7610B7C15D7DF03AB81DAA89C7499F23BA12969096F9384BBDC26F8B3BBB4DDBA0A7AC6894DAA71064B490126CB3B94B0684A9D05901345A0`
SSDEEP | `1536:JNWE/jcyNUqal2zpjmFbFBtGdnbSx8FlJzoWd+b7OBE:JYZ1l21jmFbFBtGdnbSx8btdcOq`
IMP | `B32DF9C8FC9E287ED6070FDCF15D02E1`
PESHA1 | `4757C9141C9F381649383493F94400167F495D0A`
PE256 | `B75A1B6888BE69B09F2A96614247B3A01553BE0EA8D11B026116028083F10D2B`

## DLL Exports:

Function Name | Ordinal | Type | Address | Relative Address
-- | -- | -- | -- | --
`ComDBClaimNextFreePort` | 1 (0x1) | Exported Function | 0x0000000170104830 | 0x00004830
`ComDBClaimPort` | 2 (0x2) | Exported Function | 0x0000000170104950 | 0x00004950
`ComDBClose` | 3 (0x3) | Exported Function | 0x0000000170104520 | 0x00004520
`ComDBGetCurrentPortUsage` | 4 (0x4) | Exported Function | 0x00000001701046e0 | 0x000046e0
`ComDBOpen` | 5 (0x5) | Exported Function | 0x0000000170104080 | 0x00004080
`ComDBReleasePort` | 6 (0x6) | Exported Function | 0x0000000170104a80 | 0x00004a80
`ComDBResizeDatabase` | 7 (0x7) | Exported Function | 0x0000000170104b10 | 0x00004b10
`ParallelPortPropPageProvider` | 8 (0x8) | Exported Function | 0x00000001701083b0 | 0x000083b0
`PortsClassInstaller` | 9 (0x9) | Exported Function | 0x0000000170104e20 | 0x00004e20
`SerialDisplayAdvancedSettings` | 10 (0xa) | Exported Function | 0x00000001701011c0 | 0x000011c0
`SerialPortPropPageProvider` | 11 (0xb) | Exported Function | 0x0000000170107080 | 0x00007080


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: MsPorts.dll.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/72
* VirusTotal Link: https://www.virustotal.com/gui/file/93247247d9c3a7268c0638ecca1fdf31a161e028ad89e9dd5d71b97131113797/detection/


## Possible Misuse

*The following table contains possible examples of `msports.dll` being misused. While `msports.dll` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[signature-base](https://github.com/Neo23x0/signature-base) | [crime_upatre_oct15.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/crime_upatre_oct15.yar) | $s0 = "msports.dll" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)



MIT License. Copyright (c) 2020 Strontic.


