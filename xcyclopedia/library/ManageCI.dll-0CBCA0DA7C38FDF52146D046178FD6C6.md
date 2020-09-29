---
title: ManageCI.dll | Code Integrity Management Interface
excerpt: What is ManageCI.dll?
---

# ManageCI.dll 

* File Path: `C:\Windows\system32\ManageCI.dll`
* Description: Code Integrity Management Interface

## Hashes

Type | Hash
-- | --
MD5 | `0CBCA0DA7C38FDF52146D046178FD6C6`
SHA1 | `0077085515339ADBF303971B4449827BDC7CAF2E`
SHA256 | `9169C4502FA22A85CA117E87EA93FFFE411A7D82537DADB4F4E931B9BF2C7299`
SHA384 | `6BB37733ACE00CF853A28C35352A4CB3BE2206F44A4EA5466CD288170DF90288597EAA0C38666690616CDDCABF343C0C`
SHA512 | `D0063551F14146A57B89E04E22FA2932F6A53E91C06DA73AAC77E1C3C574B3969899D109EA35AF8186D34C14DF6A39C934CE326EC076EE33F2C77057E2E8FD83`
SSDEEP | `6144:gr5oIMeF1UJt7qM7odtpnCq2OGtycNBQo:Q5TMQw757odtpngOGtycI`
IMP | `2F7DF33D707DC08B35E78DA4C7BAAA6B`
PESHA1 | `D5C5800BB5B39BFA547452EF06A86F806B48084E`
PE256 | `499A9B5F293722C61FA316349DC25F8C4729A5D6BFD5D542033A378EFDB4B1E6`

## DLL Exports:

Function Name | Ordinal | Type | Address | Relative Address
-- | -- | -- | -- | --
`BeginRemoveCIPolicy` | 1 (0x1) | Exported Function | 0x0000000180009b00 | 0x00009b00
`ManageCI_Commit` | 29 (0x1d) | Exported Function | 0x0000000180006790 | 0x00006790
`ManageCI_End` | 30 (0x1e) | Exported Function | 0x0000000180005d50 | 0x00005d50
`ManageCI_GetAllCIPolicies` | 31 (0x1f) | Exported Function | 0x0000000180005e70 | 0x00005e70
`ManageCI_GetAllSBCPTokens` | 32 (0x20) | Exported Function | 0x0000000180006160 | 0x00006160
`ManageCI_GetCIPolicyByID` | 33 (0x21) | Exported Function | 0x0000000180005da0 | 0x00005da0
`ManageCI_GetPoliciesAuthorizedBySBCPToken` | 34 (0x22) | Exported Function | 0x0000000180005f80 | 0x00005f80
`ManageCI_GetPolicyInformation` | 35 (0x23) | Exported Function | 0x0000000180006620 | 0x00006620
`ManageCI_GetSBCPTokenByID` | 36 (0x24) | Exported Function | 0x0000000180006090 | 0x00006090
`ManageCI_GetSBCPTokensForPolicyID` | 37 (0x25) | Exported Function | 0x00000001800062e0 | 0x000062e0
`ManageCI_GetSModeUnlockID` | 38 (0x26) | Exported Function | 0x0000000180006560 | 0x00006560
`ManageCI_GetTenantID` | 39 (0x27) | Exported Function | 0x0000000180006500 | 0x00006500
`ManageCI_GetTokenInformation` | 40 (0x28) | Exported Function | 0x0000000180006740 | 0x00006740
`ManageCI_IsInProgress` | 41 (0x29) | Exported Function | 0x0000000180005d90 | 0x00005d90
`ManageCI_ParsePolicy` | 42 (0x2a) | Exported Function | 0x0000000180005c80 | 0x00005c80
`ManageCI_Rollback` | 43 (0x2b) | Exported Function | 0x00000001800067b0 | 0x000067b0
`ManageCI_Start` | 44 (0x2c) | Exported Function | 0x0000000180005d10 | 0x00005d10
`ManageCI_ValidateState` | 45 (0x2d) | Exported Function | 0x0000000180005d70 | 0x00005d70
`ParsePolicy` | 19 (0x13) | Exported Function | 0x000000018000b750 | 0x0000b750
`Rollback` | 20 (0x14) | Exported Function | 0x000000018000b2a0 | 0x0000b2a0
`ManageCI_BeginUpsertCIPolicy` | 28 (0x1c) | Exported Function | 0x0000000180006480 | 0x00006480
`Start` | 21 (0x15) | Exported Function | 0x0000000180008cc0 | 0x00008cc0
`ManageCI_BeginTransaction` | 27 (0x1b) | Exported Function | 0x0000000180005d30 | 0x00005d30
`ManageCI_BeginRemoveSBCPToken` | 25 (0x19) | Exported Function | 0x0000000180006460 | 0x00006460
`BeginRemoveSBCPToken` | 2 (0x2) | Exported Function | 0x0000000180009510 | 0x00009510
`BeginSetSBCPToken` | 3 (0x3) | Exported Function | 0x0000000180009cc0 | 0x00009cc0
`BeginTransaction` | 4 (0x4) | Exported Function | 0x0000000180008e60 | 0x00008e60
`BeginUpsertCIPolicy` | 5 (0x5) | Exported Function | 0x0000000180009890 | 0x00009890
`Commit` | 6 (0x6) | Exported Function | 0x000000018000af40 | 0x0000af40
`End` | 7 (0x7) | Exported Function | 0x00000001800056b0 | 0x000056b0
`GetAllCIPolicies` | 8 (0x8) | Exported Function | 0x0000000180009440 | 0x00009440
`GetAllSBCPTokens` | 9 (0x9) | Exported Function | 0x00000001800092d0 | 0x000092d0
`GetCIPolicyByID` | 10 (0xa) | Exported Function | 0x00000001800090b0 | 0x000090b0
`GetPoliciesAuthorizedBySBCPToken` | 11 (0xb) | Exported Function | 0x0000000180009130 | 0x00009130
`GetPolicyInformation` | 12 (0xc) | Exported Function | 0x000000018000acc0 | 0x0000acc0
`GetSBCPTokenByID` | 13 (0xd) | Exported Function | 0x0000000180009150 | 0x00009150
`GetSBCPTokensForPolicyID` | 14 (0xe) | Exported Function | 0x0000000180009420 | 0x00009420
`GetSModeUnlockID` | 15 (0xf) | Exported Function | 0x000000018000abf0 | 0x0000abf0
`GetTenantID` | 16 (0x10) | Exported Function | 0x000000018000a190 | 0x0000a190
`GetTokenInformation` | 17 (0x11) | Exported Function | 0x000000018000ad40 | 0x0000ad40
`IsInProgress` | 18 (0x12) | Exported Function | 0x0000000180009080 | 0x00009080
`ManageCI` | 23 (0x17) | Exported Function | 0x00000001800067d0 | 0x000067d0
`ManageCI_BeginRemoveCIPolicy` | 24 (0x18) | Exported Function | 0x00000001800064b0 | 0x000064b0
`ManageCI_BeginSetSBCPToken` | 26 (0x1a) | Exported Function | 0x00000001800064d0 | 0x000064d0
`ValidateState` | 22 (0x16) | Exported Function | 0x0000000180009070 | 0x00009070


## Signature

* Status: Signature verified.
* Serial: `330000023241FB59996DCC4DFF000000000232`
* Thumbprint: `FF82BC38E1DA5E596DF374C53E3617F7EDA36B06`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: ManageCI.dll.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/72
* VirusTotal Link: https://www.virustotal.com/gui/file/9169c4502fa22a85ca117e87ea93fffe411a7d82537dadb4f4e931b9bf2c7299/detection/





MIT License. Copyright (c) 2020 Strontic.


