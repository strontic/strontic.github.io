---
title: wtsapi32.dll | Windows Remote Desktop Session Host Server SDK APIs
excerpt: What is wtsapi32.dll?
---

# wtsapi32.dll 

* File Path: `C:\Windows\system32\wtsapi32.dll`
* Description: Windows Remote Desktop Session Host Server SDK APIs

## Hashes

Type | Hash
-- | --
MD5 | `8A74CE8D744EE03A61806B349CD55387`
SHA1 | `C63F61F0BB509CA44D964967F6A709092BFF961A`
SHA256 | `EA14059AB9FF886189088D9812880837DAC54851457A5F446E506CD613D18B97`
SHA384 | `44D3A6C77E96192DF7CE72E99C85FEE6BB81C7459E017AABE4CDEDD8ECE807EBCB908925E3EAA23D6A2F99B78CAF8C8B`
SHA512 | `C96F375FAD450C2E72FD9B3531818DB1FE51E604C483964F887B19DF86873A3B404CDFA4D87B79ECA009D8D87F16E539E434F30B75355DA33B4205AE7E28617E`
SSDEEP | `1536:U7UOp5LXS15qdCJCLXWwapUgQPAX5q9uP:yp9CLqdCJCGwapbQPo5q9u`
IMP | `1D3A55F1B05A4AA4D327269FDE13BA58`
PESHA1 | `E4F419651A23B21C165624A145DCACEF60E61211`
PE256 | `47E0F8C14A5BBBDD1B480A4E72F87E564701A097D39BD045D71A3E2B74E01A0D`

## DLL Exports:

Function Name | Ordinal | Type | Address | Relative Address
-- | -- | -- | -- | --
`IsInteractiveUserSession` | 1 (0x1) | Exported Function | 0x0000000130002630 | 0x00002630
`WTSQueryListenerConfigW` | 37 (0x25) | Exported Function | 0x0000000130009cb0 | 0x00009cb0
`WTSQuerySessionInformationA` | 38 (0x26) | Exported Function | 0x0000000130006060 | 0x00006060
`WTSQuerySessionInformationW` | 39 (0x27) | Exported Function | 0x00000001300011f0 | 0x000011f0
`WTSQueryUserConfigA` | 40 (0x28) | Exported Function | 0x0000000130007cb0 | 0x00007cb0
`WTSQueryUserConfigW` | 41 (0x29) | Exported Function | 0x0000000130007ed0 | 0x00007ed0
`WTSQueryUserToken` | 42 (0x2a) | Exported Function | 0x0000000130001010 | 0x00001010
`WTSRegisterSessionNotification` | 43 (0x2b) | Exported Function | 0x0000000130002210 | 0x00002210
`WTSRegisterSessionNotificationEx` | 44 (0x2c) | Exported Function | 0x0000000130006250 | 0x00006250
`WTSSendMessageA` | 45 (0x2d) | Exported Function | 0x0000000130006270 | 0x00006270
`WTSSendMessageW` | 46 (0x2e) | Exported Function | 0x0000000130006300 | 0x00006300
`WTSSetListenerSecurityA` | 47 (0x2f) | Exported Function | 0x0000000130009f70 | 0x00009f70
`WTSSetListenerSecurityW` | 48 (0x30) | Exported Function | 0x000000013000a040 | 0x0000a040
`WTSSetRenderHint` | 49 (0x31) | Exported Function | 0x0000000130004710 | 0x00004710
`WTSSetSessionInformationA` | 50 (0x32) | Exported Function | 0x0000000130006390 | 0x00006390
`WTSSetSessionInformationW` | 51 (0x33) | Exported Function | 0x0000000130006390 | 0x00006390
`WTSSetUserConfigA` | 52 (0x34) | Exported Function | 0x00000001300082f0 | 0x000082f0
`WTSSetUserConfigW` | 53 (0x35) | Exported Function | 0x00000001300084d0 | 0x000084d0
`WTSVirtualChannelRead` | 67 (0x43) | Exported Function | 0x0000000130007470 | 0x00007470
`WTSVirtualChannelQuery` | 66 (0x42) | Exported Function | 0x0000000130002520 | 0x00002520
`WTSVirtualChannelPurgeOutput` | 65 (0x41) | Exported Function | 0x0000000130007450 | 0x00007450
`WTSVirtualChannelPurgeInput` | 64 (0x40) | Exported Function | 0x0000000130007430 | 0x00007430
`WTSVirtualChannelOpenEx` | 63 (0x3f) | Exported Function | 0x0000000130002470 | 0x00002470
`WTSVirtualChannelOpen` | 62 (0x3e) | Exported Function | 0x0000000130002460 | 0x00002460
`WTSQueryListenerConfigA` | 36 (0x24) | Exported Function | 0x0000000130009b70 | 0x00009b70
`WTSVirtualChannelClose` | 61 (0x3d) | Exported Function | 0x00000001300025c0 | 0x000025c0
`WTSUnRegisterSessionNotification` | 59 (0x3b) | Exported Function | 0x0000000130002290 | 0x00002290
`WTSTerminateProcess` | 58 (0x3a) | Exported Function | 0x0000000130007340 | 0x00007340
`WTSStopRemoteControlSession` | 57 (0x39) | Exported Function | 0x0000000130004900 | 0x00004900
`WTSStartRemoteControlSessionW` | 56 (0x38) | Exported Function | 0x00000001300048d0 | 0x000048d0
`WTSStartRemoteControlSessionA` | 55 (0x37) | Exported Function | 0x00000001300047c0 | 0x000047c0
`WTSShutdownSystem` | 54 (0x36) | Exported Function | 0x0000000130004730 | 0x00004730
`WTSUnRegisterSessionNotificationEx` | 60 (0x3c) | Exported Function | 0x00000001300063a0 | 0x000063a0
`WTSVirtualChannelWrite` | 68 (0x44) | Exported Function | 0x0000000130007580 | 0x00007580
`WTSOpenServerW` | 35 (0x23) | Exported Function | 0x0000000130005020 | 0x00005020
`WTSOpenServerExA` | 33 (0x21) | Exported Function | 0x0000000130004fe0 | 0x00004fe0
`QueryActiveSession` | 2 (0x2) | Exported Function | 0x0000000130005a20 | 0x00005a20
`QueryUserToken` | 3 (0x3) | Exported Function | 0x0000000130001010 | 0x00001010
`RegisterUsertokenForNoWinlogon` | 4 (0x4) | Exported Function | 0x0000000130005a20 | 0x00005a20
`WTSCloseServer` | 5 (0x5) | Exported Function | 0x0000000130004c50 | 0x00004c50
`WTSConnectSessionA` | 6 (0x6) | Exported Function | 0x00000001300044e0 | 0x000044e0
`WTSConnectSessionW` | 7 (0x7) | Exported Function | 0x0000000130004600 | 0x00004600
`WTSCreateListenerA` | 8 (0x8) | Exported Function | 0x0000000130008c80 | 0x00008c80
`WTSCreateListenerW` | 9 (0x9) | Exported Function | 0x0000000130008da0 | 0x00008da0
`WTSDisconnectSession` | 10 (0xa) | Exported Function | 0x0000000130005b90 | 0x00005b90
`WTSEnableChildSessions` | 11 (0xb) | Exported Function | 0x0000000130004630 | 0x00004630
`WTSEnumerateListenersA` | 12 (0xc) | Exported Function | 0x0000000130009530 | 0x00009530
`WTSEnumerateListenersW` | 13 (0xd) | Exported Function | 0x0000000130009680 | 0x00009680
`WTSEnumerateProcessesA` | 14 (0xe) | Exported Function | 0x0000000130006860 | 0x00006860
`WTSEnumerateProcessesExA` | 15 (0xf) | Exported Function | 0x0000000130006b30 | 0x00006b30
`WTSEnumerateProcessesExW` | 16 (0x10) | Exported Function | 0x0000000130006be0 | 0x00006be0
`WTSEnumerateProcessesW` | 17 (0x11) | Exported Function | 0x0000000130006fa0 | 0x00006fa0
`WTSEnumerateServersA` | 18 (0x12) | Exported Function | 0x0000000130004c70 | 0x00004c70
`WTSOpenServerA` | 32 (0x20) | Exported Function | 0x0000000130004fc0 | 0x00004fc0
`WTSLogoffSession` | 31 (0x1f) | Exported Function | 0x0000000130006040 | 0x00006040
`WTSIsChildSessionsEnabled` | 30 (0x1e) | Exported Function | 0x00000001300046d0 | 0x000046d0
`WTSGetListenerSecurityW` | 29 (0x1d) | Exported Function | 0x0000000130009910 | 0x00009910
`WTSGetListenerSecurityA` | 28 (0x1c) | Exported Function | 0x0000000130009820 | 0x00009820
`WTSGetChildSessionId` | 27 (0x1b) | Exported Function | 0x0000000130004690 | 0x00004690
`WTSOpenServerExW` | 34 (0x22) | Exported Function | 0x0000000130005000 | 0x00005000
`WTSFreeMemoryExW` | 26 (0x1a) | Exported Function | 0x00000001300020f0 | 0x000020f0
`WTSFreeMemory` | 24 (0x18) | Exported Function | 0x00000001300020d0 | 0x000020d0
`WTSEnumerateSessionsW` | 23 (0x17) | Exported Function | 0x0000000130001f10 | 0x00001f10
`WTSEnumerateSessionsExW` | 22 (0x16) | Exported Function | 0x0000000130001a80 | 0x00001a80
`WTSEnumerateSessionsExA` | 21 (0x15) | Exported Function | 0x0000000130005e50 | 0x00005e50
`WTSEnumerateSessionsA` | 20 (0x14) | Exported Function | 0x0000000130005bb0 | 0x00005bb0
`WTSEnumerateServersW` | 19 (0x13) | Exported Function | 0x0000000130004e30 | 0x00004e30
`WTSFreeMemoryExA` | 25 (0x19) | Exported Function | 0x0000000130004650 | 0x00004650
`WTSWaitSystemEvent` | 69 (0x45) | Exported Function | 0x0000000130004930 | 0x00004930


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: wtsapi32.dll
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/70
* VirusTotal Link: https://www.virustotal.com/gui/file/ea14059ab9ff886189088d9812880837dac54851457a5f446e506cd613d18b97/detection/


## Possible Misuse

*The following table contains possible examples of `wtsapi32.dll` being misused. While `wtsapi32.dll` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_uboat_rat.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_uboat_rat.yar) | $s6 = "WTSAPI32.dll" ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)



MIT License. Copyright (c) 2020 Strontic.


