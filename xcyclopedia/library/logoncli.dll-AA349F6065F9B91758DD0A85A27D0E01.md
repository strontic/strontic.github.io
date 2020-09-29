---
title: logoncli.dll | Net Logon Client DLL
excerpt: What is logoncli.dll?
---

# logoncli.dll 

* File Path: `C:\Windows\system32\logoncli.dll`
* Description: Net Logon Client DLL

## Hashes

Type | Hash
-- | --
MD5 | `AA349F6065F9B91758DD0A85A27D0E01`
SHA1 | `898EBEBEB1006DB656A1A9464037E646AC9E869A`
SHA256 | `6D95876CA1A91BCE22D09D008976047156496CC5C85909D5C6554042FAF34D7E`
SHA384 | `E554A4397D8AF7DF1DE5A109ACD6CA193E733B635C276D2388F6995E60775F82C0E28D36A904542CF69D6D33A8AEA7DD`
SHA512 | `B38B661623300D5DF964C7AF69B53F28D42F23A2CCC6F11238CE0D68788DF0D575CB342827EB4845D1F261CB0093DC701D314C24204BB0D99480E133957CF33F`
SSDEEP | `3072:7TTCDuE/4ED0okvhw7obeG/qYDM8/zAJwrgirMzF:7TTCD0okhUqMwECGF`
IMP | `BD4E054811FEAB07339938AF1BFB41AD`
PESHA1 | `71DD704391CCB3E096B092ED5141B66023AAE881`
PE256 | `5B06749080651E91828D5071BA2F862E8384B3604EB9925408EF7875AB2B97D2`

## DLL Exports:

Function Name | Ordinal | Type | Address | Relative Address
-- | -- | -- | -- | --
`AuthzrExtAccessCheck` | 1 (0x1) | Exported Function | 0x000000018001cfd0 | 0x0001cfd0
`I_NetQuerySecureChannelDCInfo` | 57 (0x39) | Exported Function | 0x0000000180017750 | 0x00017750
`I_NetLogonUasLogon` | 56 (0x38) | Exported Function | 0x00000001800163d0 | 0x000163d0
`I_NetLogonUasLogoff` | 55 (0x37) | Exported Function | 0x0000000180016360 | 0x00016360
`I_NetLogonSendToSam` | 54 (0x36) | Exported Function | 0x00000001800162c0 | 0x000162c0
`I_NetLogonSamLogonWithFlags` | 53 (0x35) | Exported Function | 0x0000000180016180 | 0x00016180
`I_NetLogonSamLogonEx` | 52 (0x34) | Exported Function | 0x0000000180016030 | 0x00016030
`I_NetLogonSamLogon` | 51 (0x33) | Exported Function | 0x0000000180015f00 | 0x00015f00
`I_NetLogonSamLogoff` | 50 (0x32) | Exported Function | 0x0000000180015e60 | 0x00015e60
`I_NetlogonGetTrustRid` | 71 (0x47) | Exported Function | 0x0000000180018000 | 0x00018000
`I_NetLogonGetDomainInfo` | 49 (0x31) | Exported Function | 0x0000000180017680 | 0x00017680
`I_NetLogonGetCapabilities` | 48 (0x30) | Exported Function | 0x00000001800175e0 | 0x000175e0
`I_NetLogonControl2` | 47 (0x2f) | Exported Function | 0x0000000180017480 | 0x00017480
`I_NetLogonControl` | 46 (0x2e) | Exported Function | 0x00000001800173f0 | 0x000173f0
`I_NetlogonComputeServerSignature` | 70 (0x46) | Exported Function | 0x0000000180017f50 | 0x00017f50
`I_NetlogonComputeServerDigest` | 69 (0x45) | Exported Function | 0x0000000180017ec0 | 0x00017ec0
`I_NetlogonComputeClientSignature` | 68 (0x44) | Exported Function | 0x0000000180017e10 | 0x00017e10
`I_NetlogonComputeClientDigest` | 67 (0x43) | Exported Function | 0x0000000180017d80 | 0x00017d80
`I_NetServerAuthenticate` | 58 (0x3a) | Exported Function | 0x00000001800177c0 | 0x000177c0
`I_NetServerAuthenticate2` | 59 (0x3b) | Exported Function | 0x0000000180017860 | 0x00017860
`I_NetServerAuthenticate3` | 60 (0x3c) | Exported Function | 0x0000000180017900 | 0x00017900
`I_NetServerGetTrustInfo` | 61 (0x3d) | Exported Function | 0x00000001800179b0 | 0x000179b0
`NlBindingRemoveServerFromCache` | 84 (0x54) | Exported Function | 0x0000000180016800 | 0x00016800
`NlBindingAddServerToCache` | 83 (0x53) | Exported Function | 0x0000000180016570 | 0x00016570
`NetRemoveServiceAccount` | 82 (0x52) | Exported Function | 0x0000000180018740 | 0x00018740
`NetQueryServiceAccount` | 81 (0x51) | Exported Function | 0x0000000180018690 | 0x00018690
`NetLogonSetServiceBits` | 80 (0x50) | Exported Function | 0x0000000180018180 | 0x00018180
`NetLogonGetTimeServiceParentDomain` | 79 (0x4f) | Exported Function | 0x0000000180018110 | 0x00018110
`NetIsServiceAccount` | 78 (0x4e) | Exported Function | 0x0000000180018620 | 0x00018620
`NetGetDCName` | 77 (0x4d) | Exported Function | 0x0000000180014d70 | 0x00014d70
`I_NetGetForestTrustInformation` | 45 (0x2d) | Exported Function | 0x0000000180017350 | 0x00017350
`NetGetAnyDCName` | 76 (0x4c) | Exported Function | 0x0000000180014d00 | 0x00014d00
`NetEnumerateServiceAccounts` | 74 (0x4a) | Exported Function | 0x0000000180018540 | 0x00018540
`NetAddServiceAccount` | 73 (0x49) | Exported Function | 0x00000001800184c0 | 0x000184c0
`I_RpcExtInitializeExtensionPoint` | 72 (0x48) | Exported Function | 0x0000000180007d20 | 0x00007d20
`I_NetServerTrustPasswordsGet` | 66 (0x42) | Exported Function | 0x0000000180017cd0 | 0x00017cd0
`I_NetServerReqChallenge` | 65 (0x41) | Exported Function | 0x0000000180017c50 | 0x00017c50
`I_NetServerPasswordSet2` | 64 (0x40) | Exported Function | 0x0000000180017bb0 | 0x00017bb0
`I_NetServerPasswordSet` | 63 (0x3f) | Exported Function | 0x0000000180017b10 | 0x00017b10
`I_NetServerPasswordGet` | 62 (0x3e) | Exported Function | 0x0000000180017a70 | 0x00017a70
`NetEnumerateTrustedDomains` | 75 (0x4b) | Exported Function | 0x0000000180018070 | 0x00018070
`I_NetGetDCList` | 44 (0x2c) | Exported Function | 0x0000000180012a90 | 0x00012a90
`I_NetExtendMachinePasswordExpirationTimeout` | 43 (0x2b) | Exported Function | 0x00000001800172f0 | 0x000172f0
`I_NetDatabaseSync2` | 42 (0x2a) | Exported Function | 0x0000000180017160 | 0x00017160
`DsGetDcNameW` | 19 (0x13) | Exported Function | 0x0000000180006f80 | 0x00006f80
`DsGetDcNameA` | 18 (0x12) | Exported Function | 0x0000000180013950 | 0x00013950
`DsGetDcCloseW` | 17 (0x11) | Exported Function | 0x0000000180013940 | 0x00013940
`DsEnumerateDomainTrustsW` | 16 (0x10) | Exported Function | 0x0000000180016f40 | 0x00016f40
`DsEnumerateDomainTrustsA` | 15 (0xf) | Exported Function | 0x0000000180016ad0 | 0x00016ad0
`DsDeregisterDnsHostRecordsW` | 14 (0xe) | Exported Function | 0x0000000180016a40 | 0x00016a40
`DsDeregisterDnsHostRecordsA` | 13 (0xd) | Exported Function | 0x0000000180016940 | 0x00016940
`DsAddressToSiteNamesW` | 12 (0xc) | Exported Function | 0x0000000180013770 | 0x00013770
`DsGetDcNameWithAccountA` | 20 (0x14) | Exported Function | 0x0000000180013990 | 0x00013990
`DsAddressToSiteNamesExW` | 11 (0xb) | Exported Function | 0x00000001800134b0 | 0x000134b0
`DsAddressToSiteNamesA` | 9 (0x9) | Exported Function | 0x0000000180012e10 | 0x00012e10
`AuthzrExtModifyClaims` | 8 (0x8) | Exported Function | 0x000000018001d410 | 0x0001d410
`AuthzrExtInitializeRemoteResourceManager` | 7 (0x7) | Exported Function | 0x000000018001d2b0 | 0x0001d2b0
`AuthzrExtInitializeContextFromSid` | 6 (0x6) | Exported Function | 0x000000018001d210 | 0x0001d210
`AuthzrExtInitializeCompoundContext` | 5 (0x5) | Exported Function | 0x000000018001d180 | 0x0001d180
`AuthzrExtGetInformationFromContext` | 4 (0x4) | Exported Function | 0x000000018001d110 | 0x0001d110
`AuthzrExtFreeResourceManager` | 3 (0x3) | Exported Function | 0x000000018001d0e0 | 0x0001d0e0
`AuthzrExtFreeContext` | 2 (0x2) | Exported Function | 0x000000018001d060 | 0x0001d060
`DsAddressToSiteNamesExA` | 10 (0xa) | Exported Function | 0x00000001800130d0 | 0x000130d0
`NlBindingSetAuthInfo` | 85 (0x55) | Exported Function | 0x0000000180016860 | 0x00016860
`DsGetDcNameWithAccountW` | 21 (0x15) | Exported Function | 0x0000000180006fc0 | 0x00006fc0
`DsGetDcNextW` | 23 (0x17) | Exported Function | 0x0000000180014000 | 0x00014000
`I_NetDatabaseSync` | 41 (0x29) | Exported Function | 0x0000000180017160 | 0x00017160
`I_NetDatabaseRedo` | 40 (0x28) | Exported Function | 0x0000000180017160 | 0x00017160
`I_NetDatabaseDeltas` | 39 (0x27) | Exported Function | 0x0000000180017160 | 0x00017160
`I_NetChainSetClientAttributes2` | 38 (0x26) | Exported Function | 0x0000000180017230 | 0x00017230
`I_NetChainSetClientAttributes` | 37 (0x25) | Exported Function | 0x0000000180017170 | 0x00017170
`I_NetAccountSync` | 36 (0x24) | Exported Function | 0x0000000180017160 | 0x00017160
`I_NetAccountDeltas` | 35 (0x23) | Exported Function | 0x0000000180017160 | 0x00017160
`I_DsUpdateReadOnlyServerDnsRecords` | 34 (0x22) | Exported Function | 0x0000000180014c60 | 0x00014c60
`DsGetDcNextA` | 22 (0x16) | Exported Function | 0x0000000180013ee0 | 0x00013ee0
`DsValidateSubnetNameW` | 33 (0x21) | Exported Function | 0x0000000180014ac0 | 0x00014ac0
`DsMergeForestTrustInformationW` | 31 (0x1f) | Exported Function | 0x0000000180017100 | 0x00017100
`DsGetSiteNameW` | 30 (0x1e) | Exported Function | 0x0000000180014870 | 0x00014870
`DsGetSiteNameA` | 29 (0x1d) | Exported Function | 0x00000001800147c0 | 0x000147c0
`DsGetForestTrustInformationW` | 28 (0x1c) | Exported Function | 0x0000000180017060 | 0x00017060
`DsGetDcSiteCoverageW` | 27 (0x1b) | Exported Function | 0x00000001800145f0 | 0x000145f0
`DsGetDcSiteCoverageA` | 26 (0x1a) | Exported Function | 0x0000000180014380 | 0x00014380
`DsGetDcOpenW` | 25 (0x19) | Exported Function | 0x0000000180014250 | 0x00014250
`DsGetDcOpenA` | 24 (0x18) | Exported Function | 0x0000000180014120 | 0x00014120
`DsValidateSubnetNameA` | 32 (0x20) | Exported Function | 0x0000000180014a60 | 0x00014a60
`NlSetDsIsCloningPDC` | 86 (0x56) | Exported Function | 0x0000000180014fd0 | 0x00014fd0


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: LOGONCLI.DLL
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.388 (WinBuild.160101.0800)
* Product Version: 10.0.19041.388
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/70
* VirusTotal Link: https://www.virustotal.com/gui/file/6d95876ca1a91bce22d09d008976047156496cc5c85909d5c6554042faf34d7e/detection/


## Possible Misuse

*The following table contains possible examples of `logoncli.dll` being misused. While `logoncli.dll` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_mimikatz_inmemory_detection.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/image_load/sysmon_mimikatz_inmemory_detection.yml) | `- 'logoncli.dll'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020 Strontic.


