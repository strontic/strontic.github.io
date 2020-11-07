---
title: syncutil.dll | Sync utilities for mail, contacts, calendar
excerpt: What is syncutil.dll?
---

# syncutil.dll 

* File Path: `C:\Windows\system32\syncutil.dll`
* Description: Sync utilities for mail, contacts, calendar

## Hashes

Type | Hash
-- | --
MD5 | `6586A395B568F1B7F49D8A3AB92FEC2B`
SHA1 | `DB6F30C35017985EADFDEEA83607EB8013D3E2F7`
SHA256 | `3BD5BE568E2FCC9A03E569B0D47596E45E5160B30D7A08A68E4F2DDE68721E7C`
SHA384 | `B68EAAD2F9826478EC680BDBF1F1C0279F162320B8F1577AD120851EA3FA49ACF2BF6653A0D5683B19E252E3C96C8CC3`
SHA512 | `003C95264433564FE698F757FEC470E9CEC40765F3CC1D75E7F25C95F7A82734949998FB2FA4F76AEC77E439D69BE567294091DA60A57E54272B2F335378F7BC`
SSDEEP | `6144:FzlX58ixftiUT2hwffQmUa+W4lNK3jkXGsgR/lsmq4:FZp8cftiUShwffQVxK37Sm`
IMP | `ECDDA2E70321E28BCB4F1C7B03D0DA35`
PESHA1 | `39A01438BB847F3075788960913D8C3EA3069772`
PE256 | `5086F05D36D5ABAE3D3EE2D650D27CE2CC9209F50DBE87769D90F14067E3D660`

## DLL Exports:

Function Name | Ordinal | Type
-- | -- | --
`AcquireDataStoreLock` | 77 | Exported Function
`LogSyncBiweeklySQM` | 167 | Exported Function
`LoadHeartbeatValues` | 166 | Exported Function
`IsValidAADAuthUri` | 165 | Exported Function
`IsScreenOn` | 46 | Exported Function
`IsPwdSaved` | 164 | Exported Function
`IsMatchingClientCertificateEx` | 163 | Exported Function
`IsFirstSyncEver` | 162 | Exported Function
`IsACOn` | 45 | Exported Function
`InvalidateOAuthAccessTokenForPartnership` | 161 | Exported Function
`InitializeSyncStatus` | 160 | Exported Function
`InitializeServerReadyEvents` | 43 | Exported Function
`InitializeMsaStore` | 159 | Exported Function
`InitializeMeContact` | 158 | Exported Function
`InitializeCredVault` | 157 | Exported Function
`HasNeverSyncedSuccessfully` | 156 | Exported Function
`GetWebAccountProviderFromProviderId` | 16 | Exported Function
`GetWebAccountProvider` | 12 | Exported Function
`GetWebAccountId` | 11 | Exported Function
`GetSyncWorkOnBehalfTicket` | 155 | Exported Function
`MarkServerReady` | 57 | Exported Function
`GetSyncTargetName` | 154 | Exported Function
`MarkServerShutdown` | 58 | Exported Function
`OAuthHelper_CreateInstance` | 169 | Exported Function
`WaitForSignalOrShutdown` | 76 | Exported Function
`WaitForServerReady` | 75 | Exported Function
`VerifyDataStoreLockOwner` | 183 | Exported Function
`UpdateYahooAccountType` | 70 | Exported Function
`UninitializeServerReadyEvents` | 63 | Exported Function
`TryGetDefaultSignInAccountInfo` | 182 | Exported Function
`SyncSqmUpdateStats` | 181 | Exported Function
`SetSyncWorkOnBehalfTicket` | 180 | Exported Function
`SetOutgoingMessageSizeLimit` | 179 | Exported Function
`SetMonitorDisplayState` | 178 | Exported Function
`SetDefaultStoreDirty` | 177 | Exported Function
`SetBatterySaverWnfName` | 176 | Exported Function
`SetAuthCertHash` | 175 | Exported Function
`ReleaseDataStoreLock` | 174 | Exported Function
`RegisterSsoAccountsCallback` | 173 | Exported Function
`ReadPasswordForPartnership` | 172 | Exported Function
`ReadOAuthRefreshTokenForPartnership` | 171 | Exported Function
`OpenProviderKey` | 62 | Exported Function
`OpenMimeBufferedStream` | 170 | Exported Function
`MarkUserDataAccountAsHidden` | 168 | Exported Function
`GetSHA1HashOfString` | 1 | Exported Function
`GetSessionSyncStats` | 153 | Exported Function
`GetProviderUri` | 8 | Exported Function
`DllGetClassObject` | 116 | Exported Function
`DllCanUnloadNow` | 115 | Exported Function
`DeviceNeedsProvisioning` | 5 | Exported Function
`DeletePwd` | 114 | Exported Function
`DeleteOAuthRefreshTokenForPartnership` | 110 | Exported Function
`DeleteHttpTransport` | 102 | Exported Function
`DeleteDataSource` | 101 | Exported Function
`DeleteAuthCertHash` | 99 | Exported Function
`CredVaultWrite` | 98 | Exported Function
`CredVaultRead` | 97 | Exported Function
`CredVaultDelete` | 96 | Exported Function
`CreateSyncBufferedStream` | 92 | Exported Function
`CreateDataStoreLock` | 91 | Exported Function
`CreateAuthHandler` | 90 | Exported Function
`CoCreateInstanceElevated` | 82 | Exported Function
`CloseDataStoreLock` | 81 | Exported Function
`AggregateSessionSyncStats` | 80 | Exported Function
`AggregateAccountSyncStats` | 79 | Exported Function
`AcquireDataStoreLockEx` | 78 | Exported Function
`DoesServerSupportAutoMoveSentItem` | 117 | Exported Function
`FindErrorCode` | 410 | Exported Function
`GetAADToken` | 126 | Exported Function
`GetAccountSyncStats` | 127 | Exported Function
`GetOutgoingMessageSizeLimit` | 152 | Exported Function
`GetOAuthHelperForProvider` | 151 | Exported Function
`GetOAuthHelperForAccount` | 150 | Exported Function
`GetOAuthAccessTokenForPartnership` | 149 | Exported Function
`GetMsaCustomerId` | 148 | Exported Function
`GetMonitorDisplayState` | 147 | Exported Function
`GetGoldenPartnershipId` | 146 | Exported Function
`GetGalSearchResultsFolderAndPartnerGuidEx` | 7 | Exported Function
`GetDomainFromEmail` | 145 | Exported Function
`WriteOAuthRefreshTokenForPartnership` | 184 | Exported Function
`GetDefaultStoreDirty` | 144 | Exported Function
`GetDefaultDeviceType` | 142 | Exported Function
`GetCurrentSyncStatsForStore` | 141 | Exported Function
`GetCurrentSyncStatsForMessage` | 140 | Exported Function
`GetCurrentSyncStats` | 139 | Exported Function
`GetBatterySaverWnfName` | 138 | Exported Function
`GetAuthority` | 6 | Exported Function
`GetAuthCertTargetAndUser` | 137 | Exported Function
`GetAuthCertHash` | 136 | Exported Function
`GetAccountUsernameFromToken` | 129 | Exported Function
`GetDefaultMsaWebAccountId` | 143 | Exported Function
`WritePasswordForPartnership` | 185 | Exported Function


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: SyncUtil.dll.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/67
* VirusTotal Link: https://www.virustotal.com/gui/file/3bd5be568e2fcc9a03e569b0d47596e45e5160b30d7a08a68e4f2dde68721e7c/detection/





MIT License. Copyright (c) 2020 Strontic.


