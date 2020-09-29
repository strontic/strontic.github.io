---
title: NtlmShared.dll | NTLM Shared Functionality
excerpt: What is NtlmShared.dll?
---

# NtlmShared.dll 

* File Path: `C:\Windows\SysWOW64\NtlmShared.dll`
* Description: NTLM Shared Functionality

## Hashes

Type | Hash
-- | --
MD5 | `D1DF6A4A5B29466176A49806C10F4FE4`
SHA1 | `3689FFB90D507C26AEBC318E0D5B08C8D3C81104`
SHA256 | `005A9EBA3B99727481BBDCFD86A59B1833D3978DA239F60A462386185883FE9F`
SHA384 | `F15A946B23678C080219244CEE3F9200796132B6EF213D4C77363DEF91C8EDF3C0304DF3F9C7F50A7C71617E8F987FA8`
SHA512 | `45C2C0F48848940D4B2997F2B8983F87A5A93620FF0AFF286B4BEDB3563A59D212FAFE22D6BAFA44E9CAFE494845CDE33C1E38B29AFC216EBE58E6D2C61F9EE4`
SSDEEP | `1536:Wt5eRtymJJ343yAkIgDpFU1NUCpnY1CLwbT5BJmLKzT+nPWB:I2opnxwbVBJmuz2uB`
IMP | `AA88CE810083E9C380AE5EC38B607E7C`
PESHA1 | `35D2247A778849CE63BAF65A664E2C71645B7265`
PE256 | `ECA1417B3941536C8BB7320B3EACC2E9524BF224452099F65F4897E89F3B45BC`

## DLL Exports:

Function Name | Ordinal | Type | Address | Relative Address
-- | -- | -- | -- | --
`MsvpCachePasswordsToCredential` | 1 (0x1) | Exported Function | 0x10002d10 | 0x00002d10
`NtlmSharedFree` | 26 (0x1a) | Exported Function | 0x10007130 | 0x00007130
`NtlmSharedCleanup` | 25 (0x19) | Exported Function | 0x10007090 | 0x00007090
`NtlmSharedAllocatePrivateHeap` | 24 (0x18) | Exported Function | 0x10007160 | 0x00007160
`NtlmSharedAllocate` | 23 (0x17) | Exported Function | 0x10007100 | 0x00007100
`NtLmAlterRtlEqualUnicodeString` | 22 (0x16) | Exported Function | 0x10007240 | 0x00007240
`MsvpValidateSupplementalCredsBuffer` | 21 (0x15) | Exported Function | 0x10007d00 | 0x00007d00
`MsvpValidateSupplementalCreds` | 20 (0x14) | Exported Function | 0x10007cd0 | 0x00007cd0
`MsvpUpdateSharedConfiguration` | 19 (0x13) | Exported Function | 0x100071c0 | 0x000071c0
`MsvpPutClearOwfsInPrimaryCredential` | 18 (0x12) | Exported Function | 0x10002990 | 0x00002990
`MsvpPasswordValidate` | 17 (0x11) | Exported Function | 0x10007730 | 0x00007730
`MsvpNtlm3ValidateResponse` | 16 (0x10) | Exported Function | 0x10007560 | 0x00007560
`MsvpNtlm3Response` | 15 (0xf) | Exported Function | 0x10002570 | 0x00002570
`MsvpMakeSecretPasswordNT5` | 14 (0xe) | Exported Function | 0x10002900 | 0x00002900
`MsvpLm3ValidateResponse` | 13 (0xd) | Exported Function | 0x100074c0 | 0x000074c0
`MsvpLm3Response` | 12 (0xc) | Exported Function | 0x10002450 | 0x00002450
`MsvpLm20GetNtlm3ChallengeResponse` | 11 (0xb) | Exported Function | 0x10002690 | 0x00002690
`MsvpGMSACred` | 10 (0xa) | Exported Function | 0x10006f10 | 0x00006f10
`MsvpDeriveSecureCredKey` | 9 (0x9) | Exported Function | 0x10002a90 | 0x00002a90
`MsvpDecryptDpapiMasterKey` | 8 (0x8) | Exported Function | 0x10002d70 | 0x00002d70
`MsvpCredentialToCachePasswords` | 7 (0x7) | Exported Function | 0x10002cc0 | 0x00002cc0
`MsvpComputeSaltedHashedPassword` | 6 (0x6) | Exported Function | 0x100027e0 | 0x000027e0
`MsvpCompareCredentials` | 5 (0x5) | Exported Function | 0x10002c10 | 0x00002c10
`MsvpCalculateNtlm3Owf` | 4 (0x4) | Exported Function | 0x10002390 | 0x00002390
`MsvpCalculateNtlm2SessionKeys` | 3 (0x3) | Exported Function | 0x10002320 | 0x00002320
`MsvpCalculateNtlm2Challenge` | 2 (0x2) | Exported Function | 0x10002270 | 0x00002270
`NtlmSharedFreePrivateHeap` | 27 (0x1b) | Exported Function | 0x10007190 | 0x00007190
`NtlmSharedInit` | 28 (0x1c) | Exported Function | 0x10006f60 | 0x00006f60


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: NtlmShared.dll
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/70
* VirusTotal Link: https://www.virustotal.com/gui/file/005a9eba3b99727481bbdcfd86a59b1833d3978da239f60a462386185883fe9f/detection/





MIT License. Copyright (c) 2020 Strontic.


