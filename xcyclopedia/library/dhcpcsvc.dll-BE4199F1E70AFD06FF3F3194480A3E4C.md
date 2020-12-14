---
title: dhcpcsvc.dll | DHCP Client Service
excerpt: What is dhcpcsvc.dll?
---

# dhcpcsvc.dll 

* File Path: `C:\Windows\system32\dhcpcsvc.dll`
* Description: DHCP Client Service

## Hashes

Type | Hash
-- | --
MD5 | `BE4199F1E70AFD06FF3F3194480A3E4C`
SHA1 | `0271BBAA34340ADA232F016FB8DE48398AE0F746`
SHA256 | `D51D98753057AA2B98D70EC20829E0239B7FAA3313333898C908FCE62DDE98F0`
SHA384 | `0A6A123CE94C885FB6E622A2F21811536CC0B654DB73FE6EBF2032262E7018BF2B5A3EA9168DE4B8ECF846372CAA0767`
SHA512 | `D505EFBECB94B4BC8BB01E2E80D9F490A1BAF3DBDC78A5C6A4955FDC25AE81C69214D8DCE95DABC25A42DD80B253C23BB23801F06FA08AD54601F967A2D2EFB1`
SSDEEP | `1536:lgrgKJjHWD1IFtq8SbrDph9Ed12OMuzr38C8SEa7I7G84kxF:eRjHWD4wDphk2OMuH3/8SEac7G84kD`
IMP | `AF7466EACFAAF5CCFABACCD27358533F`
PESHA1 | `247BEA4D3771EF2403BF947029ED45715421DEE0`
PE256 | `A97EC2E1FAFDE2CF3B0F18CC702F3B34CD7E387D63B88E0DB0B1FA7F71860E80`

## DLL Exports:

Function Name | Ordinal | Type
-- | -- | --
`DhcpReleaseIpAddressLeaseEx` | 47 | Exported Function
`DhcpReleaseParameters` | 48 | Exported Function
`DhcpRegisterParamChange` | 45 | Exported Function
`DhcpReleaseIpAddressLease` | 46 | Exported Function
`DhcpRenewIpAddressLeaseEx` | 51 | Exported Function
`DhcpRequestCachedParams` | 52 | Exported Function
`DhcpRemoveDNSRegistrations` | 49 | Exported Function
`DhcpRenewIpAddressLease` | 50 | Exported Function
`DhcpRegisterOptions` | 44 | Exported Function
`DhcpOpenGlobalEvent` | 38 | Exported Function
`DhcpPersistentRequestParams` | 39 | Exported Function
`DhcpNotifyConfigChangeEx` | 36 | Exported Function
`DhcpNotifyMediaReconnected` | 37 | Exported Function
`DhcpQueryLeaseInfoEx` | 42 | Exported Function
`DhcpRegisterConnectionStateNotification` | 43 | Exported Function
`DhcpQueryLeaseInfo` | 40 | Exported Function
`DhcpQueryLeaseInfoArray` | 41 | Exported Function
`McastApiStartup` | 64 | Exported Function
`McastEnumerateScopes` | 65 | Exported Function
`Dhcpv4EnableDhcpEx` | 62 | Exported Function
`McastApiCleanup` | 63 | Exported Function
`McastRenewAddress` | 68 | Exported Function
`McastRequestAddress` | 69 | Exported Function
`McastGenUID` | 66 | Exported Function
`McastReleaseAddress` | 67 | Exported Function
`Dhcpv4CheckServerAvailability` | 61 | Exported Function
`DhcpSetClassId` | 55 | Exported Function
`DhcpSetClientId` | 56 | Exported Function
`DhcpRequestOptions` | 53 | Exported Function
`DhcpRequestParams` | 54 | Exported Function
`DhcpStaticRefreshParams` | 59 | Exported Function
`DhcpUndoRequestParams` | 60 | Exported Function
`DhcpSetFallbackParams` | 57 | Exported Function
`DhcpSetMSFTVendorSpecificOptions` | 58 | Exported Function
`DhcpNotifyConfigChange` | 35 | Exported Function
`DhcpEnableTracing` | 12 | Exported Function
`DhcpEnumClasses` | 13 | Exported Function
`DhcpEnableDhcp` | 10 | Exported Function
`DhcpEnableDhcpAdvanced` | 11 | Exported Function
`DhcpFreeEnumeratedInterfaces` | 16 | Exported Function
`DhcpFreeLeaseInfo` | 17 | Exported Function
`DhcpEnumInterfaces` | 14 | Exported Function
`DhcpFallbackRefreshParams` | 15 | Exported Function
`DhcpDeRegisterParamChange` | 8 | Exported Function
`DhcpCApiCleanup` | 3 | Exported Function
`DhcpCApiInitialize` | 4 | Exported Function
`DhcpAcquireParameters` | 1 | Exported Function
`DhcpAcquireParametersByBroadcast` | 2 | Exported Function
`DhcpDeRegisterConnectionStateNotification` | 6 | Exported Function
`DhcpDeRegisterOptions` | 7 | Exported Function
`DhcpClient_Generalize` | 5 | Exported Function
`DhcpDelPersistentRequestParams` | 9 | Exported Function
`DhcpGlobalTerminateEvent` | 29 | Exported Function
`DhcpHandlePnPEvent` | 30 | Exported Function
`DhcpGlobalIsShuttingDown` | 27 | Exported Function
`DhcpGlobalServiceSyncEvent` | 28 | Exported Function
`DhcpLeaseIpAddress` | 33 | Exported Function
`DhcpLeaseIpAddressEx` | 34 | Exported Function
`DhcpIsEnabled` | 31 | Exported Function
`DhcpIsMeteredDetected` | 32 | Exported Function
`DhcpGetTraceArray` | 26 | Exported Function
`DhcpGetClassId` | 20 | Exported Function
`DhcpGetClientId` | 21 | Exported Function
`DhcpFreeLeaseInfoArray` | 18 | Exported Function
`DhcpFreeMem` | 19 | Exported Function
`DhcpGetNotificationStatus` | 24 | Exported Function
`DhcpGetOriginalSubnetMask` | 25 | Exported Function
`DhcpGetDhcpServicedConnections` | 22 | Exported Function
`DhcpGetFallbackParams` | 23 | Exported Function


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: dhcpcsvc.dll.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/69
* VirusTotal Link: https://www.virustotal.com/gui/file/d51d98753057aa2b98d70ec20829e0239b7faa3313333898c908fce62dde98f0/detection/





MIT License. Copyright (c) 2020 Strontic.


