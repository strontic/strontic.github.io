---
title: wscapi.dll | Windows Security Center API
excerpt: What is wscapi.dll?
---

# wscapi.dll 

* File Path: `C:\Windows\system32\wscapi.dll`
* Description: Windows Security Center API

## Hashes

Type | Hash
-- | --
MD5 | `9E16A7FBB34CF3CF18AA188FD46C3A8F`
SHA1 | `E3FF749AC45C5960F8A0E003A329B003A65703C6`
SHA256 | `F6263DC8AFD8D625E7679F70BCEEC631B30293DC2DAF6212F6D43B5C51B5BE04`
SHA384 | `F07517F29722B7AC7339F2B36A978502D02963E99A9DC06F86465BE05348D95BF2AA20CDCC29EFA069891A8DFC4B853B`
SHA512 | `4324DC5F1CD94E60441032FE5443E66AEC5D96015F7794A876BB0B7168EAFC1099BA3A2DAE29B3536AAB5571A89F8AACF598E1F50F7D71A4385E3F484E587915`
SSDEEP | `6144:SQZWhLzjhtf3evbby0PbRFiMuFkI1A95vZGHku4huOD7:SQkrh8jFiMuFkImPvM4Ma7`
IMP | `2FA0DACB2F334F951353FB080D58D3A3`
PESHA1 | `A30408E289355F197158E1107C69D41235D96CDA`
PE256 | `B9ACB3E5116C5956EADA71BE47EDD42156C250D10FB3FF0CF7778E9BE35910FC`

## DLL Exports:

Function Name | Ordinal | Type | Address | Relative Address
-- | -- | -- | -- | --
`CLSID_WSCDefaultProduct` | 3 (0x3) | Exported Function | 0x000000018002f100 | 0x0002f100
`wscLaunchAdminMakeDefaultUI` | 1 (0x1) | Exported Function | 0x0000000180012070 | 0x00012070
`wscLuaSettingsFix` | 29 (0x1d) | Exported Function | 0x000000018000a580 | 0x0000a580
`wscMakeDefaultProductRequest` | 30 (0x1e) | Exported Function | 0x000000018000a600 | 0x0000a600
`wscNotifyUserForNearExpiration` | 31 (0x1f) | Exported Function | 0x000000018000a690 | 0x0000a690
`wscOverrideComponentStatus` | 32 (0x20) | Exported Function | 0x000000018000a720 | 0x0000a720
`wscPing` | 33 (0x21) | Exported Function | 0x0000000180002fc0 | 0x00002fc0
`wscProductInfoFree` | 34 (0x22) | Exported Function | 0x0000000180001590 | 0x00001590
`WscQueryAntiMalwareUri` | 13 (0xd) | Exported Function | 0x000000018000dbe0 | 0x0000dbe0
`wscRegisterChangeNotification` | 35 (0x23) | Exported Function | 0x0000000180001c80 | 0x00001c80
`WscRegisterForChanges` | 14 (0xe) | Exported Function | 0x0000000180001a10 | 0x00001a10
`WscRegisterForUserNotifications` | 15 (0xf) | Exported Function | 0x0000000180001750 | 0x00001750
`wscRegisterSecurityProduct` | 36 (0x24) | Exported Function | 0x000000018000a7b0 | 0x0000a7b0
`wscSetDefaultProduct` | 37 (0x25) | Exported Function | 0x000000018000a880 | 0x0000a880
`wscShowAMSCN` | 2 (0x2) | Exported Function | 0x0000000180012200 | 0x00012200
`wscUnRegisterChangeNotification` | 38 (0x26) | Exported Function | 0x000000018000a920 | 0x0000a920
`WscUnRegisterChanges` | 16 (0x10) | Exported Function | 0x00000001800012c0 | 0x000012c0
`wscUnregisterSecurityProduct` | 39 (0x27) | Exported Function | 0x000000018000a940 | 0x0000a940
`wscIsDefenderAntivirusSupported` | 28 (0x1c) | Exported Function | 0x000000018000a4f0 | 0x0000a4f0
`wscUpdateProductStatus` | 40 (0x28) | Exported Function | 0x0000000180002d20 | 0x00002d20
`wscInitiateOfflineCleaning` | 27 (0x1b) | Exported Function | 0x000000018000a320 | 0x0000a320
`wscIcfEnable` | 25 (0x19) | Exported Function | 0x000000018000a270 | 0x0000a270
`CLSID_WSCProductList` | 4 (0x4) | Exported Function | 0x000000018002f110 | 0x0002f110
`DllCanUnloadNow` | 5 (0x5) | Exported Function | 0x0000000180001810 | 0x00001810
`DllGetClassObject` | 6 (0x6) | Exported Function | 0x00000001800047e0 | 0x000047e0
`IID_IWSCDefaultProduct` | 7 (0x7) | Exported Function | 0x000000018002e7d0 | 0x0002e7d0
`IID_IWscProduct` | 9 (0x9) | Exported Function | 0x000000018002e738 | 0x0002e738
`IID_IWSCProductList` | 8 (0x8) | Exported Function | 0x000000018002e798 | 0x0002e798
`LIBID_wscAPILib` | 10 (0xa) | Exported Function | 0x000000018002de60 | 0x0002de60
`wscAntiSpywareGetStatus` | 17 (0x11) | Exported Function | 0x0000000180009eb0 | 0x00009eb0
`wscAntiVirusExpiredBeyondThreshold` | 18 (0x12) | Exported Function | 0x0000000180009f40 | 0x00009f40
`wscAntiVirusGetStatus` | 19 (0x13) | Exported Function | 0x0000000180003ce0 | 0x00003ce0
`wscAutoUpdatesEnableScheduledMode` | 20 (0x14) | Exported Function | 0x000000018000a170 | 0x0000a170
`wscAutoUpdatesGetStatus` | 21 (0x15) | Exported Function | 0x000000018000a1f0 | 0x0000a1f0
`wscFirewallGetStatus` | 22 (0x16) | Exported Function | 0x00000001800034d0 | 0x000034d0
`wscGeneralSecurityGetStatus` | 23 (0x17) | Exported Function | 0x0000000180001870 | 0x00001870
`wscGetAlertStatus` | 24 (0x18) | Exported Function | 0x0000000180001500 | 0x00001500
`WscGetAntiMalwareUri` | 11 (0xb) | Exported Function | 0x000000018000dbe0 | 0x0000dbe0
`WscGetSecurityProviderHealth` | 12 (0xc) | Exported Function | 0x0000000180002e90 | 0x00002e90
`wscIeSettingsFix` | 26 (0x1a) | Exported Function | 0x000000018000a2f0 | 0x0000a2f0
`wscUpdateProductSubStatus` | 41 (0x29) | Exported Function | 0x0000000180002db0 | 0x00002db0


## Signature

* Status: Signature verified.
* Serial: `330000026551AE1BBD005CBFBD000000000265`
* Thumbprint: `E168609353F30FF2373157B4EB8CD519D07A2BFF`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: wscapi.dll.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/71
* VirusTotal Link: https://www.virustotal.com/gui/file/f6263dc8afd8d625e7679f70bceec631b30293dc2daf6212f6d43b5c51b5be04/detection/


## Possible Misuse

*The following table contains possible examples of `wscapi.dll` being misused. While `wscapi.dll` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[malware-ioc](https://github.com/eset/malware-ioc) | [part1.adoc](https://github.com/eset/malware-ioc/blob/master/sednit/part1.adoc) | `www.wscapi.com` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)



MIT License. Copyright (c) 2020 Strontic.


