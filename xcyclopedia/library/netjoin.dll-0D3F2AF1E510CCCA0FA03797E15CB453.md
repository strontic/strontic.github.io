---
title: netjoin.dll | Domain Join DLL
excerpt: What is netjoin.dll?
---

# netjoin.dll 

* File Path: `C:\Windows\system32\netjoin.dll`
* Description: Domain Join DLL

## Hashes

Type | Hash
-- | --
MD5 | `0D3F2AF1E510CCCA0FA03797E15CB453`
SHA1 | `62E2BF6D7EEE7A5A679FE5021DDFC5D2B31F0879`
SHA256 | `AFB35E8D6F2E72380E3010BD4A32A7B2E6B9F7E1B30595F7193B447B4D1157A3`
SHA384 | `C423385B83B93845917EE027537D8CDE2F88B6BBA06A3661EFFC340F55C16041AD0800D8CB3661841078C7862A63A06B`
SHA512 | `55C2097A513CA8E405C4ED725C8BFFCD8F77CAEAC6636413D9D43290335CF364451AC95CC3088E944D5AE7B39CCA49111164203C693A1A9A6135C143D07D5383`
SSDEEP | `3072:YmGyCKbQXJa/a4jOH/TnHSFi4LxmmuVAJZS09hZr4TUS0E1sF72j:bXCv5SSHLHSjLxNDr4TUS0E1sF7S`
IMP | `E0A8E4CE9BFF29BF7EF5B028522C10DC`
PESHA1 | `A035B2D52A113FDF429D5C72E1F514E921D27F01`
PE256 | `0F79051E7455FA44EEE08C43DEBE9D06CAE4D7835C744C62CDE909CC262A5119`

## DLL Exports:

Function Name | Ordinal | Type | Address | Relative Address
-- | -- | -- | -- | --
`NetCreateProvisioningPackage` | 1 (0x1) | Exported Function | NETPROVFW.NetCreateProvisioningPackage | 0x000277fb
`NetRequestProvisioningPackageInstall` | 4 (0x4) | Exported Function | NETPROVFW.NetRequestProvisioningPackageInstall | 0x0002787f
`NetRequestOfflineDomainJoin` | 3 (0x3) | Exported Function | 0x000000018000c150 | 0x0000c150
`NetpValidateName` | 33 (0x21) | Exported Function | 0x0000000180010f50 | 0x00010f50
`NetpUpgradePreNT5JoinInfo` | 32 (0x20) | Exported Function | 0x0000000180010b70 | 0x00010b70
`NetpUpdateAutoenrolConfig` | 31 (0x1f) | Exported Function | 0x000000018000b6b0 | 0x0000b6b0
`NetpUnJoinDomain` | 30 (0x1e) | Exported Function | 0x0000000180010900 | 0x00010900
`NetpStopService` | 29 (0x1d) | Exported Function | 0x0000000180001e50 | 0x00001e50
`NetpSetComputerAccountPassword` | 28 (0x1c) | Exported Function | 0x000000018000a4e0 | 0x0000a4e0
`NetpSeparateUserAndDomain` | 27 (0x1b) | Exported Function | 0x000000018000a490 | 0x0000a490
`NetProvisionComputerAccount` | 2 (0x2) | Exported Function | 0x000000018000bee0 | 0x0000bee0
`NetpQueryService` | 26 (0x1a) | Exported Function | 0x0000000180001e30 | 0x00001e30
`NetpManageMachineAccountWithSid` | 25 (0x19) | Exported Function | 0x000000018000f8a0 | 0x0000f8a0
`NetpManageIPCConnect` | 24 (0x18) | Exported Function | 0x0000000180009310 | 0x00009310
`NetpMachineValidToJoin` | 23 (0x17) | Exported Function | 0x000000018000f680 | 0x0000f680
`NetSetuppCloseLog` | 5 (0x5) | Exported Function | 0x0000000180012660 | 0x00012660
`NetpLogPrintHelper` | 22 (0x16) | Exported Function | 0x0000000180012a80 | 0x00012a80
`NetpJoinProvider3Initialize` | 20 (0x14) | Exported Function | 0x0000000180004e90 | 0x00004e90
`NetpJoinProvider2Initialize` | 19 (0x13) | Exported Function | 0x0000000180004c90 | 0x00004c90
`NetpIsSetupInProgress` | 18 (0x12) | Exported Function | 0x000000018000e450 | 0x0000e450
`NetpGetMachineAccountName` | 17 (0x11) | Exported Function | 0x00000001800086b0 | 0x000086b0
`NetpGetLsaPrimaryDomain` | 16 (0x10) | Exported Function | JOINUTIL.NetpGetLsaPrimaryDomain | 0x00027a12
`NetpGetListOfJoinableOUs` | 15 (0xf) | Exported Function | 0x0000000180007dc0 | 0x00007dc0
`NetpGetJoinInformation` | 14 (0xe) | Exported Function | 0x0000000180001010 | 0x00001010
`NetpDomainJoinLicensingCheck` | 13 (0xd) | Exported Function | NETPROVFW.NetpProvDomainJoinLicensingCheck | 0x0002799f
`NetpDoDomainJoin` | 12 (0xc) | Exported Function | 0x000000018000dd50 | 0x0000dd50
`NetpCreateComputerObjectInDs` | 11 (0xb) | Exported Function | 0x00000001800055b0 | 0x000055b0
`NetpCrackNamesStatus2Win32Error` | 10 (0xa) | Exported Function | 0x0000000180005490 | 0x00005490
`NetpControlServices` | 9 (0x9) | Exported Function | 0x0000000180001d90 | 0x00001d90
`NetpChangeMachineName` | 8 (0x8) | Exported Function | 0x000000018000cff0 | 0x0000cff0
`NetpAvoidNetlogonSpnSet` | 7 (0x7) | Exported Function | JOINUTIL.NetpAvoidNetlogonSpnSet | 0x000278e9
`NetpJoinProviderInitialize` | 21 (0x15) | Exported Function | 0x00000001800049d0 | 0x000049d0
`NetSetuppOpenLog` | 6 (0x6) | Exported Function | 0x00000001800126f0 | 0x000126f0


## Signature

* Status: Signature verified.
* Serial: `330000026551AE1BBD005CBFBD000000000265`
* Thumbprint: `E168609353F30FF2373157B4EB8CD519D07A2BFF`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: NETJOIN.DLL.MUI
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/69
* VirusTotal Link: https://www.virustotal.com/gui/file/afb35e8d6f2e72380e3010bd4a32a7b2e6b9f7e1b30595f7193b447b4d1157a3/detection/





MIT License. Copyright (c) 2020 Strontic.


