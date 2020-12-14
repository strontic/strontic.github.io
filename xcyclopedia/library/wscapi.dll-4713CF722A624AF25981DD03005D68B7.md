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

Function Name | Ordinal | Type
-- | -- | --
`wscPing` | 33 | Exported Function
`wscOverrideComponentStatus` | 32 | Exported Function
`wscProductInfoFree` | 34 | Exported Function
`wscRegisterChangeNotification` | 35 | Exported Function
`WscQueryAntiMalwareUri` | 13 | Exported Function
`wscLaunchAdminMakeDefaultUI` | 1 | Exported Function
`wscIsDefenderAntivirusSupported` | 28 | Exported Function
`wscLuaSettingsFix` | 29 | Exported Function
`wscNotifyUserForNearExpiration` | 31 | Exported Function
`wscMakeDefaultProductRequest` | 30 | Exported Function
`WscUnRegisterChanges` | 16 | Exported Function
`wscUnRegisterChangeNotification` | 38 | Exported Function
`wscUnregisterSecurityProduct` | 39 | Exported Function
`wscUpdateProductSubStatus` | 41 | Exported Function
`wscUpdateProductStatus` | 40 | Exported Function
`WscRegisterForUserNotifications` | 15 | Exported Function
`WscRegisterForChanges` | 14 | Exported Function
`wscRegisterSecurityProduct` | 36 | Exported Function
`wscShowAMSCN` | 2 | Exported Function
`wscSetDefaultProduct` | 37 | Exported Function
`wscInitiateOfflineCleaning` | 27 | Exported Function
`IID_IWSCProductList` | 8 | Exported Function
`IID_IWscProduct` | 9 | Exported Function
`LIBID_wscAPILib` | 10 | Exported Function
`wscAntiVirusExpiredBeyondThreshold` | 18 | Exported Function
`wscAntiSpywareGetStatus` | 17 | Exported Function
`CLSID_WSCProductList` | 4 | Exported Function
`CLSID_WSCDefaultProduct` | 3 | Exported Function
`DllCanUnloadNow` | 5 | Exported Function
`IID_IWSCDefaultProduct` | 7 | Exported Function
`DllGetClassObject` | 6 | Exported Function
`WscGetAntiMalwareUri` | 11 | Exported Function
`wscGetAlertStatus` | 24 | Exported Function
`WscGetSecurityProviderHealth` | 12 | Exported Function
`wscIeSettingsFix` | 26 | Exported Function
`wscIcfEnable` | 25 | Exported Function
`wscAutoUpdatesEnableScheduledMode` | 20 | Exported Function
`wscAntiVirusGetStatus` | 19 | Exported Function
`wscAutoUpdatesGetStatus` | 21 | Exported Function
`wscGeneralSecurityGetStatus` | 23 | Exported Function
`wscFirewallGetStatus` | 22 | Exported Function


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

*The following table contains possible examples of `wscapi.dll` being misused. While `wscapi.dll` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[malware-ioc](https://github.com/eset/malware-ioc) | [part1.adoc](https://github.com/eset/malware-ioc/blob/master/sednit/part1.adoc) | `www.wscapi.com` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)



MIT License. Copyright (c) 2020 Strontic.


