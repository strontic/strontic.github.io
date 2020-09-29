---
title: rastapi.dll | Remote Access TAPI Compliance Layer
excerpt: What is rastapi.dll?
---

# rastapi.dll 

* File Path: `C:\Windows\SysWOW64\rastapi.dll`
* Description: Remote Access TAPI Compliance Layer

## Hashes

Type | Hash
-- | --
MD5 | `17DCC80DC506962AD325280DDCA941C7`
SHA1 | `B4D84879A25513FB6FA5126708440ED521F01946`
SHA256 | `3564FE96FC3DDD898B44ACCAE0967CD45890F4ADAA8F6C03AF21FC79DA71DD1C`
SHA384 | `A5FFF2959AD11A66D4580991F754EAC05B1EF7F252CF92895EEA7457F1CCD0276877033FFF4536D8AC63C85865B68D0F`
SHA512 | `6ED0A51E86985CE91B054EB2E5B789BBC2948DD573CF141DE436558F92062F5C978A4A83BE5D0CF2AE6C0DE3BEC4F4BB1A516C29CA8791AED5614ED8B650ACB6`
SSDEEP | `3072:pbYtMH+VvkJIR0BbZbw5e0BbZN0BbZydmrK0BbPQG2sJjnc6lt0FIyeF01C9HhrC:pUtMeV0IyplYA0FIoCLZKc+95UB`
IMP | `EF53E37CA8F73A82E53327177D0E627B`
PESHA1 | `78A9E9BDCD66A94F78A4E81FC577FEB4483560D2`
PE256 | `CCFDE227115E970486A60A8066D7D4D71BCBF379BDDB5B1E9C74A26101EB90A0`

## DLL Exports:

Function Name | Ordinal | Type | Address | Relative Address
-- | -- | -- | -- | --
`AddPorts` | 1 (0x1) | Exported Function | 0x1001fc70 | 0x0001fc70
`PortGetIOHandle` | 24 (0x18) | Exported Function | 0x1001e770 | 0x0001e770
`PortGetPortState` | 26 (0x1a) | Exported Function | 0x1001e750 | 0x0001e750
`PortGetStatistics` | 27 (0x1b) | Exported Function | 0x1001e750 | 0x0001e750
`PortInit` | 28 (0x1c) | Exported Function | 0x1001e3e0 | 0x0001e3e0
`PortOpen` | 29 (0x1d) | Exported Function | 0x1001db50 | 0x0001db50
`PortOpenExternal` | 30 (0x1e) | Exported Function | 0x1001db20 | 0x0001db20
`PortReceive` | 31 (0x1f) | Exported Function | 0x1001e550 | 0x0001e550
`PortReceiveComplete` | 32 (0x20) | Exported Function | 0x1001e660 | 0x0001e660
`PortSend` | 33 (0x21) | Exported Function | 0x1001e3f0 | 0x0001e3f0
`PortSetFraming` | 34 (0x22) | Exported Function | 0x1001e760 | 0x0001e760
`PortSetInfo` | 35 (0x23) | Exported Function | 0x1001dd50 | 0x0001dd50
`PortSetIoCompletionPort` | 36 (0x24) | Exported Function | 0x1001d410 | 0x0001d410
`PortTestSignalState` | 37 (0x25) | Exported Function | 0x1001ddb0 | 0x0001ddb0
`RastapiGetCalledID` | 39 (0x27) | Exported Function | 0x1001f9e0 | 0x0001f9e0
`RasTapiIsPulseDial` | 38 (0x26) | Exported Function | 0x1001fb40 | 0x0001fb40
`RastapiSetCalledID` | 40 (0x28) | Exported Function | 0x1001fa70 | 0x0001fa70
`RefreshDevices` | 41 (0x29) | Exported Function | 0x100218f0 | 0x000218f0
`RemovePort` | 42 (0x2a) | Exported Function | 0x1001fd70 | 0x0001fd70
`SetCommSettings` | 43 (0x2b) | Exported Function | 0x10021750 | 0x00021750
`PortGetInfo` | 25 (0x19) | Exported Function | 0x1001dce0 | 0x0001dce0
`UnloadRastapiDll` | 44 (0x2c) | Exported Function | 0x10021630 | 0x00021630
`PortEnum` | 23 (0x17) | Exported Function | 0x1001d430 | 0x0001d430
`PortConnect` | 21 (0x15) | Exported Function | 0x1001ded0 | 0x0001ded0
`CheckRasmanDependency` | 2 (0x2) | Exported Function | 0x10021d00 | 0x00021d00
`DeviceConnect` | 3 (0x3) | Exported Function | 0x1001e8b0 | 0x0001e8b0
`DeviceDone` | 4 (0x4) | Exported Function | 0x1001f200 | 0x0001f200
`DeviceEnum` | 5 (0x5) | Exported Function | 0x1001e7e0 | 0x0001e7e0
`DeviceGetDevConfig` | 6 (0x6) | Exported Function | 0x1001f9a0 | 0x0001f9a0
`DeviceGetDevConfigEx` | 7 (0x7) | Exported Function | 0x1001f9c0 | 0x0001f9c0
`DeviceGetInfo` | 8 (0x8) | Exported Function | 0x1001e800 | 0x0001e800
`DeviceListen` | 9 (0x9) | Exported Function | 0x1001f010 | 0x0001f010
`DeviceSetDevConfig` | 10 (0xa) | Exported Function | 0x1001f650 | 0x0001f650
`DeviceSetInfo` | 11 (0xb) | Exported Function | 0x1001e850 | 0x0001e850
`DeviceWork` | 12 (0xc) | Exported Function | 0x1001f210 | 0x0001f210
`EnableDeviceForDialIn` | 13 (0xd) | Exported Function | 0x1001fe80 | 0x0001fe80
`GetConnectInfo` | 14 (0xe) | Exported Function | 0x100200f0 | 0x000200f0
`GetZeroDeviceInfo` | 15 (0xf) | Exported Function | 0x100203b0 | 0x000203b0
`InitializeDriverIoControl` | 16 (0x10) | Exported Function | 0x1001cf20 | 0x0001cf20
`PortChangeCallback` | 17 (0x11) | Exported Function | 0x1001e3e0 | 0x0001e3e0
`PortClearStatistics` | 18 (0x12) | Exported Function | 0x1001e3e0 | 0x0001e3e0
`PortClose` | 19 (0x13) | Exported Function | 0x1001db80 | 0x0001db80
`PortCompressionSetInfo` | 20 (0x14) | Exported Function | 0x1001e3e0 | 0x0001e3e0
`PortDisconnect` | 22 (0x16) | Exported Function | 0x1001e2e0 | 0x0001e2e0
`UpdateTapiService` | 45 (0x2d) | Exported Function | 0x10021990 | 0x00021990


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
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/71
* VirusTotal Link: https://www.virustotal.com/gui/file/3564fe96fc3ddd898b44accae0967cd45890f4adaa8f6c03af21fc79da71dd1c/detection/





MIT License. Copyright (c) 2020 Strontic.


