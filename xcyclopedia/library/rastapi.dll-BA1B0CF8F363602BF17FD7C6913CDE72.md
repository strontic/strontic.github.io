---
title: rastapi.dll | Remote Access TAPI Compliance Layer
excerpt: What is rastapi.dll?
---

# rastapi.dll 

* File Path: `C:\Windows\system32\rastapi.dll`
* Description: Remote Access TAPI Compliance Layer

## Hashes

Type | Hash
-- | --
MD5 | `BA1B0CF8F363602BF17FD7C6913CDE72`
SHA1 | `754DC621F690BB17DDF2F4E307611028A3A78451`
SHA256 | `3A643EFEA08EDE36169F9ED39F3B8919A0A1BD7867576E7C4601D5CEAEC49AAD`
SHA384 | `42BE5196CD3EDB1C7AA34D7B346E309682D5E9187E336B9B8E79A79E602974DF579C22E9CDA64C3214E33A84879AAA4E`
SHA512 | `A962A9468DCFCF29139B4C9871E1ED72A9BCC00C84F2A2DDF1054190B380D8B919D93C7CF912DCC75E73C2E30819A2656C05D1E6AEF8AB484E3BE63B05002081`
SSDEEP | `3072:rgt3WC0SWarzr03m5fTpyHf8z8AlfdjALcgQ2OB0E8VJtq7YtcXu+vkFBo:Mu2rz35rtfxAwgQ2OB0Ru0tc+SkB`
IMP | `6CA60BDF616193713803642D29F451AE`
PESHA1 | `7BAE91C56D978C46FC975ED414B32B11B0A76A8E`
PE256 | `60BFA477A665CF15729A549B0C7FACDBCAC19E190A16CD100610BC28F2DE90C4`

## DLL Exports:

Function Name | Ordinal | Type | Address | Relative Address
-- | -- | -- | -- | --
`AddPorts` | 1 (0x1) | Exported Function | 0x0000000180012f00 | 0x00012f00
`PortGetIOHandle` | 24 (0x18) | Exported Function | 0x00000001800115f0 | 0x000115f0
`PortGetPortState` | 26 (0x1a) | Exported Function | 0x00000001800111b0 | 0x000111b0
`PortGetStatistics` | 27 (0x1b) | Exported Function | 0x00000001800111b0 | 0x000111b0
`PortInit` | 28 (0x1c) | Exported Function | 0x00000001800111b0 | 0x000111b0
`PortOpen` | 29 (0x1d) | Exported Function | 0x0000000180010760 | 0x00010760
`PortOpenExternal` | 30 (0x1e) | Exported Function | 0x0000000180010750 | 0x00010750
`PortReceive` | 31 (0x1f) | Exported Function | 0x0000000180011390 | 0x00011390
`PortReceiveComplete` | 32 (0x20) | Exported Function | 0x00000001800114e0 | 0x000114e0
`PortSend` | 33 (0x21) | Exported Function | 0x00000001800111c0 | 0x000111c0
`PortSetFraming` | 34 (0x22) | Exported Function | 0x00000001800111b0 | 0x000111b0
`PortSetInfo` | 35 (0x23) | Exported Function | 0x00000001800109d0 | 0x000109d0
`PortSetIoCompletionPort` | 36 (0x24) | Exported Function | 0x000000018000fe90 | 0x0000fe90
`PortTestSignalState` | 37 (0x25) | Exported Function | 0x0000000180010a40 | 0x00010a40
`RastapiGetCalledID` | 39 (0x27) | Exported Function | 0x0000000180012b90 | 0x00012b90
`RasTapiIsPulseDial` | 38 (0x26) | Exported Function | 0x0000000180012d60 | 0x00012d60
`RastapiSetCalledID` | 40 (0x28) | Exported Function | 0x0000000180012c50 | 0x00012c50
`RefreshDevices` | 41 (0x29) | Exported Function | 0x0000000180015630 | 0x00015630
`RemovePort` | 42 (0x2a) | Exported Function | 0x0000000180013030 | 0x00013030
`SetCommSettings` | 43 (0x2b) | Exported Function | 0x00000001800153f0 | 0x000153f0
`PortGetInfo` | 25 (0x19) | Exported Function | 0x0000000180010920 | 0x00010920
`UnloadRastapiDll` | 44 (0x2c) | Exported Function | 0x0000000180015210 | 0x00015210
`PortEnum` | 23 (0x17) | Exported Function | 0x000000018000feb0 | 0x0000feb0
`PortConnect` | 21 (0x15) | Exported Function | 0x0000000180010b70 | 0x00010b70
`CheckRasmanDependency` | 2 (0x2) | Exported Function | 0x0000000180015c20 | 0x00015c20
`DeviceConnect` | 3 (0x3) | Exported Function | 0x0000000180011770 | 0x00011770
`DeviceDone` | 4 (0x4) | Exported Function | 0x0000000180012250 | 0x00012250
`DeviceEnum` | 5 (0x5) | Exported Function | 0x0000000180011680 | 0x00011680
`DeviceGetDevConfig` | 6 (0x6) | Exported Function | 0x0000000180012b60 | 0x00012b60
`DeviceGetDevConfigEx` | 7 (0x7) | Exported Function | 0x0000000180012b70 | 0x00012b70
`DeviceGetInfo` | 8 (0x8) | Exported Function | 0x00000001800116a0 | 0x000116a0
`DeviceListen` | 9 (0x9) | Exported Function | 0x0000000180012000 | 0x00012000
`DeviceSetDevConfig` | 10 (0xa) | Exported Function | 0x00000001800126e0 | 0x000126e0
`DeviceSetInfo` | 11 (0xb) | Exported Function | 0x0000000180011700 | 0x00011700
`DeviceWork` | 12 (0xc) | Exported Function | 0x0000000180012260 | 0x00012260
`EnableDeviceForDialIn` | 13 (0xd) | Exported Function | 0x0000000180013190 | 0x00013190
`GetConnectInfo` | 14 (0xe) | Exported Function | 0x00000001800134b0 | 0x000134b0
`GetZeroDeviceInfo` | 15 (0xf) | Exported Function | 0x0000000180013770 | 0x00013770
`InitializeDriverIoControl` | 16 (0x10) | Exported Function | 0x000000018000f780 | 0x0000f780
`PortChangeCallback` | 17 (0x11) | Exported Function | 0x00000001800111b0 | 0x000111b0
`PortClearStatistics` | 18 (0x12) | Exported Function | 0x00000001800111b0 | 0x000111b0
`PortClose` | 19 (0x13) | Exported Function | 0x0000000180010780 | 0x00010780
`PortCompressionSetInfo` | 20 (0x14) | Exported Function | 0x00000001800111b0 | 0x000111b0
`PortDisconnect` | 22 (0x16) | Exported Function | 0x0000000180011070 | 0x00011070
`UpdateTapiService` | 45 (0x2d) | Exported Function | 0x0000000180015700 | 0x00015700


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: Rastapi.dll
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/72
* VirusTotal Link: https://www.virustotal.com/gui/file/3a643efea08ede36169f9ed39f3b8919a0a1bd7867576e7c4601d5ceaec49aad/detection/





MIT License. Copyright (c) 2020 Strontic.


