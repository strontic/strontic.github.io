---
title: devobj.dll | Device Information Set DLL
excerpt: What is devobj.dll?
---

# devobj.dll 

* File Path: `C:\Windows\system32\devobj.dll`
* Description: Device Information Set DLL

## Hashes

Type | Hash
-- | --
MD5 | `2AC36355F37A4EF153C1A3813CE0DFCB`
SHA1 | `233B269D4D408E31879AF3A22964C1692977130B`
SHA256 | `9482896FEDE532442750FD4BD5010FAE97636095559E88242B64F9A7D365A3F5`
SHA384 | `B694CA7F7FC2361D37004D8CAD96E5EADB4521C88A75E0F914E87CDF9A33940E4B0D34D779699A67EE31219BAE6C47AB`
SHA512 | `3A3460C77A3536E9980F240888152003EEBB0B5F732C23819E2098E1D48B8713FA27B273657669633E083436BAA1E79E95A3A11E0E4E383D46252D5D6053D41C`
SSDEEP | `3072:Z36AR8zRp93gwWc5SDzLCfcihi93EQre/zlKM:Z3kzZ39WcQDzL2LiEQg7`
IMP | `61E1DCBF3466A7EA64F08A5B873582F8`
PESHA1 | `136AD184604DCF514D4F73BE6E3690BB815A8116`
PE256 | `58C312DAD8C095077540121502329F7AD0CAC5A64F5520B0AA8205EDA0B1D1B2`

## DLL Exports:

Function Name | Ordinal | Type
-- | -- | --
`DevObjLocateDevice` | 36 | Exported Function
`DevObjGetDeviceRegistryProperty` | 35 | Exported Function
`DevObjGetDevicePropertyKeys` | 34 | Exported Function
`DevObjOpenDeviceInterface` | 40 | Exported Function
`DevObjOpenDeviceInfo` | 39 | Exported Function
`DevObjOpenClassRegKey` | 37 | Exported Function
`DevObjGetDeviceProperty` | 33 | Exported Function
`DevObjGetDeviceInterfaceAlias` | 29 | Exported Function
`DevObjGetDeviceInstanceId` | 28 | Exported Function
`DevObjGetDeviceInfoListDetail` | 27 | Exported Function
`DevObjGetDeviceInterfacePropertyKeys` | 32 | Exported Function
`DevObjGetDeviceInterfaceProperty` | 31 | Exported Function
`DevObjGetDeviceInterfaceDetail` | 30 | Exported Function
`DevObjSetDeviceInterfaceProperty` | 49 | Exported Function
`DevObjSetDeviceInterfaceDefault` | 48 | Exported Function
`DevObjSetDeviceInfoDetail` | 47 | Exported Function
`DevObjUninstallDevice` | 52 | Exported Function
`DevObjSetDeviceRegistryProperty` | 51 | Exported Function
`DevObjSetDeviceProperty` | 50 | Exported Function
`DevObjSetClassRegistryProperty` | 46 | Exported Function
`DevObjRegisterDeviceInfo` | 42 | Exported Function
`DevObjOpenDevRegKey` | 38 | Exported Function
`DevObjOpenDeviceInterfaceRegKey` | 41 | Exported Function
`DevObjSetClassProperty` | 45 | Exported Function
`DevObjRestartDevices` | 44 | Exported Function
`DevObjRemoveDeviceInterface` | 43 | Exported Function
`DevObjCreateDevRegKey` | 6 | Exported Function
`DevObjCreateDeviceInterfaceRegKey` | 10 | Exported Function
`DevObjCreateDeviceInterface` | 9 | Exported Function
`DevObjDeleteDeviceInfo` | 14 | Exported Function
`DevObjDeleteDevice` | 13 | Exported Function
`DevObjDeleteAllInterfacesForDevice` | 11 | Exported Function
`DevObjCreateDeviceInfoList` | 8 | Exported Function
`DevObjClassGuidsFromName` | 3 | Exported Function
`DevObjChangeState` | 2 | Exported Function
`DevObjBuildClassInfoList` | 1 | Exported Function
`DevObjCreateDeviceInfo` | 7 | Exported Function
`DevObjCreateClassDeviceInfoList` | 5 | Exported Function
`DevObjClassNameFromGuid` | 4 | Exported Function
`DevObjGetClassPropertyKeys` | 23 | Exported Function
`DevObjGetClassProperty` | 22 | Exported Function
`DevObjGetClassDevs` | 21 | Exported Function
`DevObjGetDeviceInfoListClass` | 26 | Exported Function
`DevObjGetDeviceInfoDetail` | 25 | Exported Function
`DevObjGetClassRegistryProperty` | 24 | Exported Function
`DevObjGetClassDescription` | 20 | Exported Function
`DevObjDeleteDevRegKey` | 12 | Exported Function
`DevObjDeleteDeviceInterfaceRegKey` | 16 | Exported Function
`DevObjDeleteDeviceInterfaceData` | 15 | Exported Function
`DevObjEnumDeviceInterfaces` | 19 | Exported Function
`DevObjEnumDeviceInfo` | 18 | Exported Function
`DevObjDestroyDeviceInfoList` | 17 | Exported Function


## Signature

* Status: Signature verified.
* Serial: `330000026551AE1BBD005CBFBD000000000265`
* Thumbprint: `E168609353F30FF2373157B4EB8CD519D07A2BFF`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: devinfoset.DLL
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/71
* VirusTotal Link: https://www.virustotal.com/gui/file/9482896fede532442750fd4bd5010fae97636095559e88242b64f9a7d365a3f5/detection/


## Possible Misuse

*The following table contains possible examples of `devobj.dll` being misused. While `devobj.dll` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[signature-base](https://github.com/Neo23x0/signature-base) | [spy_regin_fiveeyes.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/spy_regin_fiveeyes.yar) | $s1 = "SerialAddDevice - error creating new devobj [%#08lx]" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)



MIT License. Copyright (c) 2020 Strontic.


