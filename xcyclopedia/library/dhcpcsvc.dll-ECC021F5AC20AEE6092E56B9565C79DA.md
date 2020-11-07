---
title: dhcpcsvc.dll | DHCP Client Service
excerpt: What is dhcpcsvc.dll?
---

# dhcpcsvc.dll 

* File Path: `C:\Windows\SysWOW64\dhcpcsvc.dll`
* Description: DHCP Client Service

## Hashes

Type | Hash
-- | --
MD5 | `ECC021F5AC20AEE6092E56B9565C79DA`
SHA1 | `C251CF047FFD840201C5E78BC3FE6D547B3CDBC1`
SHA256 | `3C182E137B6F10D36A0EE84B7C563927BC505D0D8641E135170FC66E6FBDC675`
SHA384 | `5B2DEBACB2D6E0F4541CC1D495BCE84800F25C0B2501E21CE4DC4B4581173108092875DE60060FB2881AFED62F4BC745`
SHA512 | `DB6600566DED2D09DAAFDE3778E525DD76348552EC52B11F5FB1570395F09B1CC061B2E09FC4F7C6473F69775707BF45DAF6973FD53EF4C16E02746A88CAB354`
SSDEEP | `1536:GJOz0PWT82dEjtkk+JShIbOYAz8S8Hme+eCZjaj+JkkeDJsk7/:GJOXT82AeXb4z8R1+fm8yDJsk7`
IMP | `63FC82444BE0DE4F05C0049583ECF84D`
PESHA1 | `736A0072C334A0DF625ACAA48EE0BE29F41FF1F2`
PE256 | `E0C249131F7B59DA9CA5EC6D996F26E746911234634884B20895026A3398F809`

## DLL Exports:

Function Name | Ordinal | Type
-- | -- | --
`DhcpAcquireParameters` | 1 | Exported Function
`DhcpNotifyMediaReconnected` | 37 | Exported Function
`DhcpOpenGlobalEvent` | 38 | Exported Function
`DhcpPersistentRequestParams` | 39 | Exported Function
`DhcpQueryLeaseInfo` | 40 | Exported Function
`DhcpQueryLeaseInfoArray` | 41 | Exported Function
`DhcpQueryLeaseInfoEx` | 42 | Exported Function
`DhcpRegisterConnectionStateNotification` | 43 | Exported Function
`DhcpRegisterOptions` | 44 | Exported Function
`DhcpRegisterParamChange` | 45 | Exported Function
`DhcpReleaseIpAddressLease` | 46 | Exported Function
`DhcpReleaseIpAddressLeaseEx` | 47 | Exported Function
`DhcpReleaseParameters` | 48 | Exported Function
`DhcpRemoveDNSRegistrations` | 49 | Exported Function
`DhcpRenewIpAddressLease` | 50 | Exported Function
`DhcpRenewIpAddressLeaseEx` | 51 | Exported Function
`DhcpRequestCachedParams` | 52 | Exported Function
`DhcpRequestOptions` | 53 | Exported Function
`McastReleaseAddress` | 67 | Exported Function
`McastGenUID` | 66 | Exported Function
`McastEnumerateScopes` | 65 | Exported Function
`McastApiStartup` | 64 | Exported Function
`McastApiCleanup` | 63 | Exported Function
`Dhcpv4EnableDhcpEx` | 62 | Exported Function
`DhcpNotifyConfigChangeEx` | 36 | Exported Function
`Dhcpv4CheckServerAvailability` | 61 | Exported Function
`DhcpStaticRefreshParams` | 59 | Exported Function
`DhcpSetMSFTVendorSpecificOptions` | 58 | Exported Function
`DhcpSetFallbackParams` | 57 | Exported Function
`DhcpSetClientId` | 56 | Exported Function
`DhcpSetClassId` | 55 | Exported Function
`DhcpRequestParams` | 54 | Exported Function
`DhcpUndoRequestParams` | 60 | Exported Function
`McastRenewAddress` | 68 | Exported Function
`DhcpNotifyConfigChange` | 35 | Exported Function
`DhcpLeaseIpAddress` | 33 | Exported Function
`DhcpAcquireParametersByBroadcast` | 2 | Exported Function
`DhcpCApiCleanup` | 3 | Exported Function
`DhcpCApiInitialize` | 4 | Exported Function
`DhcpClient_Generalize` | 5 | Exported Function
`DhcpDelPersistentRequestParams` | 9 | Exported Function
`DhcpDeRegisterConnectionStateNotification` | 6 | Exported Function
`DhcpDeRegisterOptions` | 7 | Exported Function
`DhcpDeRegisterParamChange` | 8 | Exported Function
`DhcpEnableDhcp` | 10 | Exported Function
`DhcpEnableDhcpAdvanced` | 11 | Exported Function
`DhcpEnableTracing` | 12 | Exported Function
`DhcpEnumClasses` | 13 | Exported Function
`DhcpEnumInterfaces` | 14 | Exported Function
`DhcpFallbackRefreshParams` | 15 | Exported Function
`DhcpFreeEnumeratedInterfaces` | 16 | Exported Function
`DhcpFreeLeaseInfo` | 17 | Exported Function
`DhcpFreeLeaseInfoArray` | 18 | Exported Function
`DhcpIsMeteredDetected` | 32 | Exported Function
`DhcpIsEnabled` | 31 | Exported Function
`DhcpHandlePnPEvent` | 30 | Exported Function
`DhcpGlobalTerminateEvent` | 29 | Exported Function
`DhcpGlobalServiceSyncEvent` | 28 | Exported Function
`DhcpGlobalIsShuttingDown` | 27 | Exported Function
`DhcpLeaseIpAddressEx` | 34 | Exported Function
`DhcpGetTraceArray` | 26 | Exported Function
`DhcpGetNotificationStatus` | 24 | Exported Function
`DhcpGetFallbackParams` | 23 | Exported Function
`DhcpGetDhcpServicedConnections` | 22 | Exported Function
`DhcpGetClientId` | 21 | Exported Function
`DhcpGetClassId` | 20 | Exported Function
`DhcpFreeMem` | 19 | Exported Function
`DhcpGetOriginalSubnetMask` | 25 | Exported Function
`McastRequestAddress` | 69 | Exported Function


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: dhcpcsvc.dll
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.508 (WinBuild.160101.0800)
* Product Version: 10.0.19041.508
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/69
* VirusTotal Link: https://www.virustotal.com/gui/file/3c182e137b6f10d36a0ee84b7c563927bc505d0d8641e135170fc66e6fbdc675/detection/





MIT License. Copyright (c) 2020 Strontic.


