---
title: wscapi.dll | Windows Security Center API
excerpt: What is wscapi.dll?
---

# wscapi.dll 

* File Path: `C:\Windows\SysWOW64\wscapi.dll`
* Description: Windows Security Center API

## Hashes

Type | Hash
-- | --
MD5 | `4713CF722A624AF25981DD03005D68B7`
SHA1 | `AACA542D9F65485F6CA86D909E9F179632B48694`
SHA256 | `1A91C5322C1677AEAC0AE5CCAF1E860B27A5717BB1B69540EE6E1AA6F532A277`
SHA384 | `72AF4D0EEB5F737C80EE0DF72F4642A1FA9D85E008B674246FB541E5BC5838E99382E895CEC356E35D7E841EE048FEEB`
SHA512 | `D5F8407DEB4251F608DC016FAFCB8CBF46CBEDC7A8E825CBC765501E988982C826F9E1CD9511DD7F41642DD84D98C5CCAB45BE05CD3CC1FE5C267E41B72C685C`
SSDEEP | `3072:SZ+cKvk8PHnOwqmcHDVxlLfgJyT2hJbubCW5XjbMohb2TzEkFHDLcuKqCsEXwc9V:SZdmsDVxljgJY2hJojbMFHwvaJa57UE`
IMP | `441890DA21AEC1F6E2BC9FECF0F2DB75`
PESHA1 | `780F3FB3C7472689E27694254753C23CD9388B1B`
PE256 | `802DD3A2BCEA85F8266240468018972C35AF6F341D6E055039F912B86BB2283F`

## DLL Exports:

Function Name | Ordinal | Type | Address | Relative Address
-- | -- | -- | -- | --
`CLSID_WSCDefaultProduct` | 3 (0x3) | Exported Function | 0x10005cbc | 0x00005cbc
`wscLaunchAdminMakeDefaultUI` | 1 (0x1) | Exported Function | 0x100197d0 | 0x000197d0
`wscLuaSettingsFix` | 29 (0x1d) | Exported Function | 0x100137f0 | 0x000137f0
`wscMakeDefaultProductRequest` | 30 (0x1e) | Exported Function | 0x10013870 | 0x00013870
`wscNotifyUserForNearExpiration` | 31 (0x1f) | Exported Function | 0x10013900 | 0x00013900
`wscOverrideComponentStatus` | 32 (0x20) | Exported Function | 0x10013990 | 0x00013990
`wscPing` | 33 (0x21) | Exported Function | 0x1000d6a0 | 0x0000d6a0
`wscProductInfoFree` | 34 (0x22) | Exported Function | 0x1000ee70 | 0x0000ee70
`WscQueryAntiMalwareUri` | 13 (0xd) | Exported Function | 0x10016030 | 0x00016030
`wscRegisterChangeNotification` | 35 (0x23) | Exported Function | 0x10013a10 | 0x00013a10
`WscRegisterForChanges` | 14 (0xe) | Exported Function | 0x1000bee0 | 0x0000bee0
`WscRegisterForUserNotifications` | 15 (0xf) | Exported Function | 0x1000bcd0 | 0x0000bcd0
`wscRegisterSecurityProduct` | 36 (0x24) | Exported Function | 0x10013a30 | 0x00013a30
`wscSetDefaultProduct` | 37 (0x25) | Exported Function | 0x10013ac0 | 0x00013ac0
`wscShowAMSCN` | 2 (0x2) | Exported Function | 0x10019920 | 0x00019920
`wscUnRegisterChangeNotification` | 38 (0x26) | Exported Function | 0x10013b50 | 0x00013b50
`WscUnRegisterChanges` | 16 (0x10) | Exported Function | 0x1000b980 | 0x0000b980
`wscUnregisterSecurityProduct` | 39 (0x27) | Exported Function | 0x10013b70 | 0x00013b70
`wscIsDefenderAntivirusSupported` | 28 (0x1c) | Exported Function | 0x10013760 | 0x00013760
`wscUpdateProductStatus` | 40 (0x28) | Exported Function | 0x1000bde0 | 0x0000bde0
`wscInitiateOfflineCleaning` | 27 (0x1b) | Exported Function | 0x10013640 | 0x00013640
`wscIcfEnable` | 25 (0x19) | Exported Function | 0x100135b0 | 0x000135b0
`CLSID_WSCProductList` | 4 (0x4) | Exported Function | 0x10005ccc | 0x00005ccc
`DllCanUnloadNow` | 5 (0x5) | Exported Function | 0x1000f220 | 0x0000f220
`DllGetClassObject` | 6 (0x6) | Exported Function | 0x1000e800 | 0x0000e800
`IID_IWSCDefaultProduct` | 7 (0x7) | Exported Function | 0x10005328 | 0x00005328
`IID_IWscProduct` | 9 (0x9) | Exported Function | 0x100052ac | 0x000052ac
`IID_IWSCProductList` | 8 (0x8) | Exported Function | 0x10005308 | 0x00005308
`LIBID_wscAPILib` | 10 (0xa) | Exported Function | 0x10004f68 | 0x00004f68
`wscAntiSpywareGetStatus` | 17 (0x11) | Exported Function | 0x10013270 | 0x00013270
`wscAntiVirusExpiredBeyondThreshold` | 18 (0x12) | Exported Function | 0x100132f0 | 0x000132f0
`wscAntiVirusGetStatus` | 19 (0x13) | Exported Function | 0x1000e090 | 0x0000e090
`wscAutoUpdatesEnableScheduledMode` | 20 (0x14) | Exported Function | 0x100134c0 | 0x000134c0
`wscAutoUpdatesGetStatus` | 21 (0x15) | Exported Function | 0x10013530 | 0x00013530
`wscFirewallGetStatus` | 22 (0x16) | Exported Function | 0x1000d970 | 0x0000d970
`wscGeneralSecurityGetStatus` | 23 (0x17) | Exported Function | 0x1000bd60 | 0x0000bd60
`wscGetAlertStatus` | 24 (0x18) | Exported Function | 0x1000edb0 | 0x0000edb0
`WscGetAntiMalwareUri` | 11 (0xb) | Exported Function | 0x10016020 | 0x00016020
`WscGetSecurityProviderHealth` | 12 (0xc) | Exported Function | 0x1000d5c0 | 0x0000d5c0
`wscIeSettingsFix` | 26 (0x1a) | Exported Function | 0x10013620 | 0x00013620
`wscUpdateProductSubStatus` | 41 (0x29) | Exported Function | 0x10013c00 | 0x00013c00


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: wscapi.dll
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/70
* VirusTotal Link: https://www.virustotal.com/gui/file/1a91c5322c1677aeac0ae5ccaf1e860b27a5717bb1b69540ee6e1aa6f532a277/detection/


## Possible Misuse

*The following table contains possible examples of `wscapi.dll` being misused. While `wscapi.dll` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[malware-ioc](https://github.com/eset/malware-ioc) | [part1.adoc](https://github.com/eset/malware-ioc/blob/master/sednit/part1.adoc) | `www.wscapi.com` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)



MIT License. Copyright (c) 2020 Strontic.


