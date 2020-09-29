---
title: NtlmShared.dll | NTLM Shared Functionality
excerpt: What is NtlmShared.dll?
---

# NtlmShared.dll 

* File Path: `C:\Windows\system32\NtlmShared.dll`
* Description: NTLM Shared Functionality

## Hashes

Type | Hash
-- | --
MD5 | `68A29D04B882CD44F52590F6E5944320`
SHA1 | `8251967983CF1E30A94C206AD60A3F6452D22ABD`
SHA256 | `62DE61059EF368F60F71C5C36101C1C8F035ECED8EA3F987DB1752AFC1FFC8C4`
SHA384 | `84C29A85A44432A864E2EAFC29F37725629C19F02B5A4923BE560EBE60A3FB9BE861FDCB2BCCFC9BB89E7B0ADD80CBC1`
SHA512 | `9D984F897ABCD0E6F832D626758621B4D61C94C8E96C26990DD10C387BFA38AFC31FDC6139B8A2ACC07FD228D1CB897848979EAC4D5FC305B9833EE7DCC1946B`
SSDEEP | `1536:i7jqbKtBqD/38km5L1AasZOKwxvIDlOvaf6KsOpRPju:i7juFm5L1AasQIfTlRru`
IMP | `6D69616C8CEDD32FEB34C17F6F0E5893`
PESHA1 | `B3F15D2A5910D0DEDFA76F690F0412D69AE96D41`
PE256 | `44B92154268301508B160E2D0AFAAB620DD82836460EE194E63458FFF4285ED6`

## DLL Exports:

Function Name | Ordinal | Type | Address | Relative Address
-- | -- | -- | -- | --
`MsvpCachePasswordsToCredential` | 1 (0x1) | Exported Function | 0x0000000180002730 | 0x00002730
`NtlmSharedFree` | 26 (0x1a) | Exported Function | 0x0000000180008650 | 0x00008650
`NtlmSharedCleanup` | 25 (0x19) | Exported Function | 0x00000001800085b0 | 0x000085b0
`NtlmSharedAllocatePrivateHeap` | 24 (0x18) | Exported Function | 0x0000000180008670 | 0x00008670
`NtlmSharedAllocate` | 23 (0x17) | Exported Function | 0x0000000180008630 | 0x00008630
`NtLmAlterRtlEqualUnicodeString` | 22 (0x16) | Exported Function | 0x0000000180008720 | 0x00008720
`MsvpValidateSupplementalCredsBuffer` | 21 (0x15) | Exported Function | 0x0000000180009470 | 0x00009470
`MsvpValidateSupplementalCreds` | 20 (0x14) | Exported Function | 0x0000000180009450 | 0x00009450
`MsvpUpdateSharedConfiguration` | 19 (0x13) | Exported Function | 0x00000001800086b0 | 0x000086b0
`MsvpPutClearOwfsInPrimaryCredential` | 18 (0x12) | Exported Function | 0x00000001800022a0 | 0x000022a0
`MsvpPasswordValidate` | 17 (0x11) | Exported Function | 0x0000000180008e00 | 0x00008e00
`MsvpNtlm3ValidateResponse` | 16 (0x10) | Exported Function | 0x0000000180008bd0 | 0x00008bd0
`MsvpNtlm3Response` | 15 (0xf) | Exported Function | 0x0000000180001c30 | 0x00001c30
`MsvpMakeSecretPasswordNT5` | 14 (0xe) | Exported Function | 0x0000000180002200 | 0x00002200
`MsvpLm3ValidateResponse` | 13 (0xd) | Exported Function | 0x0000000180008b00 | 0x00008b00
`MsvpLm3Response` | 12 (0xc) | Exported Function | 0x0000000180001a00 | 0x00001a00
`MsvpLm20GetNtlm3ChallengeResponse` | 11 (0xb) | Exported Function | 0x0000000180001e60 | 0x00001e60
`MsvpGMSACred` | 10 (0xa) | Exported Function | 0x00000001800082e0 | 0x000082e0
`MsvpDeriveSecureCredKey` | 9 (0x9) | Exported Function | 0x00000001800023e0 | 0x000023e0
`MsvpDecryptDpapiMasterKey` | 8 (0x8) | Exported Function | 0x0000000180002790 | 0x00002790
`MsvpCredentialToCachePasswords` | 7 (0x7) | Exported Function | 0x00000001800026f0 | 0x000026f0
`MsvpComputeSaltedHashedPassword` | 6 (0x6) | Exported Function | 0x0000000180002080 | 0x00002080
`MsvpCompareCredentials` | 5 (0x5) | Exported Function | 0x0000000180002640 | 0x00002640
`MsvpCalculateNtlm3Owf` | 4 (0x4) | Exported Function | 0x00000001800018c0 | 0x000018c0
`MsvpCalculateNtlm2SessionKeys` | 3 (0x3) | Exported Function | 0x00000001800017c0 | 0x000017c0
`MsvpCalculateNtlm2Challenge` | 2 (0x2) | Exported Function | 0x00000001800016b0 | 0x000016b0
`NtlmSharedFreePrivateHeap` | 27 (0x1b) | Exported Function | 0x0000000180008690 | 0x00008690
`NtlmSharedInit` | 28 (0x1c) | Exported Function | 0x00000001800082f0 | 0x000082f0


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
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/71
* VirusTotal Link: https://www.virustotal.com/gui/file/62de61059ef368f60f71c5c36101c1c8f035eced8ea3f987db1752afc1ffc8c4/detection/





MIT License. Copyright (c) 2020 Strontic.


