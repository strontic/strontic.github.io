---
title: UpdateDeploymentProvider.dll | Update Deployment Provider
excerpt: What is UpdateDeploymentProvider.dll?
---

# UpdateDeploymentProvider.dll 

* File Path: `C:\Windows\system32\UpdateDeploymentProvider.dll`
* Description: Update Deployment Provider

## Hashes

Type | Hash
-- | --
MD5 | `473CC196303FB37F34AF0631EE1DFFF5`
SHA1 | `2AF873A379FEC0F83174C53B13B0311C3ADF4D4D`
SHA256 | `7F2159D4D92D9E34D80AAE590EA8A5943089848A7F31473C6AE93AC62B4BB26F`
SHA384 | `0E1EFA667721AD42B7308EF7F2A7CD9EBA3C9BA0691C922FE3F94AECDB951820EA98124DB856E8A5428ADDAAA2555AA8`
SHA512 | `21C2F1A989ECF085773D9BDC50BC3FDD39457FE3B05D5B433E40BC43EDCDC59A7049F88D3E0A41B5D6A5056FB93C7C5CC69F74C50340CDAA7B7D0F9CB0605C7F`
SSDEEP | `6144:NOisv4vZLDqShwP13GG/mCVfwUyphTnu98vUDVnDPDG4colokmmDqtnHafJeU:MiG4vZLmShwVhX8mx5P4Ha`
IMP | `4D757185193CC5C6085072A51971F093`
PESHA1 | `D361CCD1562AA48195A0B64388FEBA498FF119ED`
PE256 | `CE8120F9B7C3BC0D7DF5374614D3A16BB99A1F05ACC18C18F91D45D59DE0BCBD`

## DLL Exports:

Function Name | Ordinal | Type
-- | -- | --
`DllRegisterServer` | 6 | Exported Function
`DllUnregisterServer` | 7 | Exported Function
`DllCanUnloadNow` | 4 | Exported Function
`DllGetClassObject` | 5 | Exported Function


## Signature

* Status: Signature verified.
* Serial: `330000026551AE1BBD005CBFBD000000000265`
* Thumbprint: `E168609353F30FF2373157B4EB8CD519D07A2BFF`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: UpdateDeploymentProvider.dll
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.508 (WinBuild.160101.0800)
* Product Version: 10.0.19041.508
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/68
* VirusTotal Link: https://www.virustotal.com/gui/file/7f2159d4d92d9e34d80aae590ea8a5943089848a7f31473c6ae93ac62b4bb26f/detection/


## Possible Misuse

*The following table contains possible examples of `UpdateDeploymentProvider.dll` being misused. While `UpdateDeploymentProvider.dll` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_wuauclt.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_wuauclt.yml) | `- '/UpdateDeploymentProvider'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Wuauclt.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Wuauclt.yml) | `- Command: wuauclt.exe /UpdateDeploymentProvider <Full_Path_To_DLL> /RunHandlerComServer` | 



MIT License. Copyright (c) 2020 Strontic.


