---
title: wercplsupport.dll | Problem Reports
excerpt: What is wercplsupport.dll?
---

# wercplsupport.dll 

* File Path: `C:\Windows\system32\wercplsupport.dll`
* Description: Problem Reports

## Hashes

Type | Hash
-- | --
MD5 | `581F0C56ABE314018378E2DE22D50FBA`
SHA1 | `DA83335360FB58B93B8FBA14B5ADC3EDF7FEBFD5`
SHA256 | `A92428643D1C99BBC13E7CD5C5E2D91464D3D77C585C86794BDB91C980815241`
SHA384 | `6F576DC4A49D1E716C66E4D16CB61FB77177457C6A65BC9B1EB28E4F9A96C5FEA49B2AC8281B6CA7C1BD3F00AAE15F1E`
SHA512 | `C88721E5307CB0932E40F59E6D46E7EEA7E1EE947C60C94D13AF6809E3E99EDF3F015F8819EC27086DD8B51FB5A5F44AEE52CA286FB4927E300FAF77EE617171`
SSDEEP | `1536:dYpZJIy+opBRL2EN8ebfUAX7m+5lYojRVEaDLbA4Ua4dvtMI5wTAf5QmH80zvp:y5+EWVYll5jHfHbxOvmi285Qmhz`
IMP | `66D449D8D67FDB2379AC254AE18B16F9`
PESHA1 | `7D48100A4184035C9286A78A0566584106B5F999`
PE256 | `30384BA9A36E9A16F98D092513782A82BCBC8A8CD60FA1126A3BBA6AF637314B`

## DLL Exports:

Function Name | Ordinal | Type
-- | -- | --
`SvchostPushServiceGlobals` | 2 | Exported Function
`WerComGetAdminStores` | 3 | Exported Function
`ServiceMain` | 1 | Exported Function
`DllCanUnloadNow` | 4 | Exported Function
`DllGetClassObject` | 5 | Exported Function


## Signature

* Status: Signature verified.
* Serial: `330000026551AE1BBD005CBFBD000000000265`
* Thumbprint: `E168609353F30FF2373157B4EB8CD519D07A2BFF`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: ERC
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/68
* VirusTotal Link: https://www.virustotal.com/gui/file/a92428643d1c99bbc13e7cd5c5e2d91464d3d77c585c86794bdb91c980815241/detection/


## Possible Misuse

*The following table contains possible examples of `wercplsupport.dll` being misused. While `wercplsupport.dll` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_mal_blue_mockingbird.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/malware/win_mal_blue_mockingbird.yml) | `- '\CurrentControlSet\Services\wercplsupport\Parameters\ServiceDll'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020 Strontic.


