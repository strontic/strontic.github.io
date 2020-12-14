---
title: WmiApRpl.dll | WMI Performance Reverse Adapter
excerpt: What is WmiApRpl.dll?
---

# WmiApRpl.dll 

* File Path: `C:\Windows\SysWOW64\wbem\WmiApRpl.dll`
* Description: WMI Performance Reverse Adapter

## Hashes

Type | Hash
-- | --
MD5 | `6AD0CEECBE1C4DDDE0D88A848E54F4A8`
SHA1 | `A88B247840CFC36755C49ECC3B7BE17C987D8AF2`
SHA256 | `7D681ADC24813188E0C6A005AAD5BB046B93214B1451083A86634DC40C3FD3E6`
SHA384 | `D1052264C27FC2E02FD0AE5CC35B4D6660152E203E9AB590571C15B94E4F65C30F85C1046B1ABF5D78F213BA63D53264`
SHA512 | `F4FF1E4ED7F8567B017243C5854E9842B14E65B5CB073D57988581CD68D084F036BD30445B7ADD546725F8CFD35EE9A3DDD9B9354666771AF15165AB264C49D4`
SSDEEP | `1536:X3+35SxIn/bznfWDnCINAd5IT0bNMrY8mXabuDuRIzzqDhBeegTu:n+3E+/FIKdoEpXabOuuGhBPgT`
IMP | `10FC9218EC5CEA64D2CBD1823D014A18`
PESHA1 | `5E0AE2E7877FBEC9000AFA2B0CD4C03A5DCCCF6B`
PE256 | `09A26E760DA5970BD54BAF2204A0C4EF302F818366FCB0FF2CB3570DAC0FE320`

## DLL Exports:

Function Name | Ordinal | Type
-- | -- | --
`WmiCollectPerfData` | 2 | Exported Function
`WmiOpenPerfData` | 3 | Exported Function
`WmiClosePerfData` | 1 | Exported Function
`DllRegisterServer` | 4 | Exported Function
`DllUnregisterServer` | 5 | Exported Function


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: WMIApRpl.dll.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/67
* VirusTotal Link: https://www.virustotal.com/gui/file/7d681adc24813188e0c6a005aad5bb046b93214b1451083a86634dc40c3fd3e6/detection/


## Possible Misuse

*The following table contains possible examples of `WmiApRpl.dll` being misused. While `WmiApRpl.dll` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_wmi_module_load.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/image_load/sysmon_wmi_module_load.yml) | `- '\WmiApRpl.dll'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020 Strontic.


