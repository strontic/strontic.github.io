---
title: wtsapi32.dll | Windows Remote Desktop Session Host Server SDK APIs
excerpt: What is wtsapi32.dll?
---

# wtsapi32.dll 

* File Path: `C:\Windows\SysWOW64\wtsapi32.dll`
* Description: Windows Remote Desktop Session Host Server SDK APIs

## Hashes

Type | Hash
-- | --
MD5 | `D0404C8E3AE16A5B6036FFA971D4D9EA`
SHA1 | `FE0D1077B9A8E1E60C3649924DC1E18DA341B380`
SHA256 | `D4E754AD5AA18AA1CF06CC42A7042ED01DBACDD8771C9BFC931C2709953C2FA0`
SHA384 | `789C2C985E94CE520F7E80288EC868C322EB047D087FADDF4D64861D6E4BF7F5622FD92D9E86F1569719C111E01DE656`
SHA512 | `24B17884E15B78055F8771C78D1DBDED8672D4AE2DA6F9C3B2BE36D5B49E5744BBBD79CDA13A557B609D8E45F1758762D41B459D6145B9236E1CA1257FA859B9`
SSDEEP | `1536:4BPK/mFR/+hdaWMDxYVxnlXVzq9gGMoPLJSG:8PK+FsdUDAxnFtq9g4jJSG`
IMP | `05DE2F62058708C9549030BB966BAF5C`
PESHA1 | `9CE2536EFF66F4335C81484B04B969413506E460`
PE256 | `713551B3ADFEE2CC1360D34CE2A475984B36F5570184F51964B29F144D22737A`

## DLL Exports:

Function Name | Ordinal | Type | Address | Relative Address
-- | -- | -- | -- | --
`IsInteractiveUserSession` | 1 (0x1) | Exported Function | 0x30002570 | 0x00002570
`WTSQueryListenerConfigW` | 37 (0x25) | Exported Function | 0x30008270 | 0x00008270
`WTSQuerySessionInformationA` | 38 (0x26) | Exported Function | 0x300053a0 | 0x000053a0
`WTSQuerySessionInformationW` | 39 (0x27) | Exported Function | 0x30001a60 | 0x00001a60
`WTSQueryUserConfigA` | 40 (0x28) | Exported Function | 0x30006ad0 | 0x00006ad0
`WTSQueryUserConfigW` | 41 (0x29) | Exported Function | 0x30006c60 | 0x00006c60
`WTSQueryUserToken` | 42 (0x2a) | Exported Function | 0x30001930 | 0x00001930
`WTSRegisterSessionNotification` | 43 (0x2b) | Exported Function | 0x300024f0 | 0x000024f0
`WTSRegisterSessionNotificationEx` | 44 (0x2c) | Exported Function | 0x30005510 | 0x00005510
`WTSSendMessageA` | 45 (0x2d) | Exported Function | 0x30005530 | 0x00005530
`WTSSendMessageW` | 46 (0x2e) | Exported Function | 0x30005590 | 0x00005590
`WTSSetListenerSecurityA` | 47 (0x2f) | Exported Function | 0x300084e0 | 0x000084e0
`WTSSetListenerSecurityW` | 48 (0x30) | Exported Function | 0x30008560 | 0x00008560
`WTSSetRenderHint` | 49 (0x31) | Exported Function | 0x30003f50 | 0x00003f50
`WTSSetSessionInformationA` | 50 (0x32) | Exported Function | 0x300055f0 | 0x000055f0
`WTSSetSessionInformationW` | 51 (0x33) | Exported Function | 0x300055f0 | 0x000055f0
`WTSSetUserConfigA` | 52 (0x34) | Exported Function | 0x30006fa0 | 0x00006fa0
`WTSSetUserConfigW` | 53 (0x35) | Exported Function | 0x30007100 | 0x00007100
`WTSVirtualChannelRead` | 67 (0x43) | Exported Function | 0x30006450 | 0x00006450
`WTSVirtualChannelQuery` | 66 (0x42) | Exported Function | 0x30006350 | 0x00006350
`WTSVirtualChannelPurgeOutput` | 65 (0x41) | Exported Function | 0x30006330 | 0x00006330
`WTSVirtualChannelPurgeInput` | 64 (0x40) | Exported Function | 0x30006310 | 0x00006310
`WTSVirtualChannelOpenEx` | 63 (0x3f) | Exported Function | 0x300062f0 | 0x000062f0
`WTSVirtualChannelOpen` | 62 (0x3e) | Exported Function | 0x300062d0 | 0x000062d0
`WTSQueryListenerConfigA` | 36 (0x24) | Exported Function | 0x300081b0 | 0x000081b0
`WTSVirtualChannelClose` | 61 (0x3d) | Exported Function | 0x30006270 | 0x00006270
`WTSUnRegisterSessionNotification` | 59 (0x3b) | Exported Function | 0x30002a10 | 0x00002a10
`WTSTerminateProcess` | 58 (0x3a) | Exported Function | 0x300061d0 | 0x000061d0
`WTSStopRemoteControlSession` | 57 (0x39) | Exported Function | 0x300040c0 | 0x000040c0
`WTSStartRemoteControlSessionW` | 56 (0x38) | Exported Function | 0x30004090 | 0x00004090
`WTSStartRemoteControlSessionA` | 55 (0x37) | Exported Function | 0x30003fe0 | 0x00003fe0
`WTSShutdownSystem` | 54 (0x36) | Exported Function | 0x30003f70 | 0x00003f70
`WTSUnRegisterSessionNotificationEx` | 60 (0x3c) | Exported Function | 0x30005600 | 0x00005600
`WTSVirtualChannelWrite` | 68 (0x44) | Exported Function | 0x30006500 | 0x00006500
`WTSOpenServerW` | 35 (0x23) | Exported Function | 0x30004680 | 0x00004680
`WTSOpenServerExA` | 33 (0x21) | Exported Function | 0x30004640 | 0x00004640
`QueryActiveSession` | 2 (0x2) | Exported Function | 0x30002550 | 0x00002550
`QueryUserToken` | 3 (0x3) | Exported Function | 0x30001930 | 0x00001930
`RegisterUsertokenForNoWinlogon` | 4 (0x4) | Exported Function | 0x30004e60 | 0x00004e60
`WTSCloseServer` | 5 (0x5) | Exported Function | 0x30004370 | 0x00004370
`WTSConnectSessionA` | 6 (0x6) | Exported Function | 0x30003d90 | 0x00003d90
`WTSConnectSessionW` | 7 (0x7) | Exported Function | 0x30003e50 | 0x00003e50
`WTSCreateListenerA` | 8 (0x8) | Exported Function | 0x30007710 | 0x00007710
`WTSCreateListenerW` | 9 (0x9) | Exported Function | 0x300077d0 | 0x000077d0
`WTSDisconnectSession` | 10 (0xa) | Exported Function | 0x30004fb0 | 0x00004fb0
`WTSEnableChildSessions` | 11 (0xb) | Exported Function | 0x30003e80 | 0x00003e80
`WTSEnumerateListenersA` | 12 (0xc) | Exported Function | 0x30007d80 | 0x00007d80
`WTSEnumerateListenersW` | 13 (0xd) | Exported Function | 0x30007e70 | 0x00007e70
`WTSEnumerateProcessesA` | 14 (0xe) | Exported Function | 0x300058e0 | 0x000058e0
`WTSEnumerateProcessesExA` | 15 (0xf) | Exported Function | 0x30005b40 | 0x00005b40
`WTSEnumerateProcessesExW` | 16 (0x10) | Exported Function | 0x30005bd0 | 0x00005bd0
`WTSEnumerateProcessesW` | 17 (0x11) | Exported Function | 0x30005ed0 | 0x00005ed0
`WTSEnumerateServersA` | 18 (0x12) | Exported Function | 0x30004380 | 0x00004380
`WTSOpenServerA` | 32 (0x20) | Exported Function | 0x30004620 | 0x00004620
`WTSLogoffSession` | 31 (0x1f) | Exported Function | 0x30005380 | 0x00005380
`WTSIsChildSessionsEnabled` | 30 (0x1e) | Exported Function | 0x30003f10 | 0x00003f10
`WTSGetListenerSecurityW` | 29 (0x1d) | Exported Function | 0x30008020 | 0x00008020
`WTSGetListenerSecurityA` | 28 (0x1c) | Exported Function | 0x30007fa0 | 0x00007fa0
`WTSGetChildSessionId` | 27 (0x1b) | Exported Function | 0x30003ee0 | 0x00003ee0
`WTSOpenServerExW` | 34 (0x22) | Exported Function | 0x30004660 | 0x00004660
`WTSFreeMemoryExW` | 26 (0x1a) | Exported Function | 0x300023e0 | 0x000023e0
`WTSFreeMemory` | 24 (0x18) | Exported Function | 0x300024a0 | 0x000024a0
`WTSEnumerateSessionsW` | 23 (0x17) | Exported Function | 0x30002250 | 0x00002250
`WTSEnumerateSessionsExW` | 22 (0x16) | Exported Function | 0x30001ec0 | 0x00001ec0
`WTSEnumerateSessionsExA` | 21 (0x15) | Exported Function | 0x30005200 | 0x00005200
`WTSEnumerateSessionsA` | 20 (0x14) | Exported Function | 0x30004fd0 | 0x00004fd0
`WTSEnumerateServersW` | 19 (0x13) | Exported Function | 0x300044c0 | 0x000044c0
`WTSFreeMemoryExA` | 25 (0x19) | Exported Function | 0x30003ea0 | 0x00003ea0
`WTSWaitSystemEvent` | 69 (0x45) | Exported Function | 0x300040e0 | 0x000040e0


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
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/71
* VirusTotal Link: https://www.virustotal.com/gui/file/d4e754ad5aa18aa1cf06cc42a7042ed01dbacdd8771c9bfc931c2709953c2fa0/detection/


## Possible Misuse

*The following table contains possible examples of `wtsapi32.dll` being misused. While `wtsapi32.dll` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_uboat_rat.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_uboat_rat.yar) | $s6 = "WTSAPI32.dll" ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)



MIT License. Copyright (c) 2020 Strontic.


