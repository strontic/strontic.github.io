---
title: devobj.dll | Device Information Set DLL
excerpt: What is devobj.dll?
---

# devobj.dll 

* File Path: `C:\Windows\SysWOW64\devobj.dll`
* Description: Device Information Set DLL

## Hashes

Type | Hash
-- | --
MD5 | `E19993D41A066F6AF38BEE29C13690FD`
SHA1 | `08B64DA0BA5CDA3DFE316CA59B4E28AA8601466E`
SHA256 | `37AD97FCCA05E05A257BE90919794EFA607E840C05F00A4F9DC91562289FFF95`
SHA384 | `FEDF7A6F0C2F1879A78208D083F2C2F3C1100A654EED74988CCF49A7819A49A62BCB5D9E6A52882B92B5D627CEB4DA74`
SHA512 | `A601AADD2AC41C8CF8B95721FF22971C5DB12DBB4611F8F2420C69B0A951369536EC20AB31A5D18B32139A91A9BCD3E51004099F932AD9B429DC733D4C6C982D`
SSDEEP | `3072:VsvXevI/emME6pbP2JuYWw8ALvre/1SS38mc:OXmKemMEqIWwnvql`
IMP | `2CC3E3091A8B17702DF5EBD18E578CF8`
PESHA1 | `C4141CE9265B866CA44CDE0724929AB1AAD0D7C8`
PE256 | `411E5B553EA96CE19AFC41B517249D99DF78A666ADD564D14A02363F3FE238FB`

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
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
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
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/68
* VirusTotal Link: https://www.virustotal.com/gui/file/37ad97fcca05e05a257be90919794efa607e840c05f00a4f9dc91562289fff95/detection/


## Possible Misuse

*The following table contains possible examples of `devobj.dll` being misused. While `devobj.dll` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[signature-base](https://github.com/Neo23x0/signature-base) | [spy_regin_fiveeyes.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/spy_regin_fiveeyes.yar) | $s1 = "SerialAddDevice - error creating new devobj [%#08lx]" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)



MIT License. Copyright (c) 2020 Strontic.


