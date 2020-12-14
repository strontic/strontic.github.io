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

*The following table contains possible examples of `wscapi.dll` being misused. While `wscapi.dll` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[malware-ioc](https://github.com/eset/malware-ioc) | [part1.adoc](https://github.com/eset/malware-ioc/blob/master/sednit/part1.adoc) | `www.wscapi.com` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)



MIT License. Copyright (c) 2020 Strontic.


