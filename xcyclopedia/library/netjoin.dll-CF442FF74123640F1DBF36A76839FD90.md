---
title: netjoin.dll | Domain Join DLL
excerpt: What is netjoin.dll?
---

# netjoin.dll 

* File Path: `C:\Windows\SysWOW64\netjoin.dll`
* Description: Domain Join DLL

## Hashes

Type | Hash
-- | --
MD5 | `CF442FF74123640F1DBF36A76839FD90`
SHA1 | `1CE9E0879E2C56158A8498551A9BCD4F796310BA`
SHA256 | `25F4A71B3993A2E1ED26A950F2EC32FB4A07C9A528F2163C3778475EAE62ABEA`
SHA384 | `19ABECB24DCA643F5853886418AE38BAB7D95E940372A099F860EBA8CE7461D5426ABBE650C3BF8B515409F9BE3C2F0E`
SHA512 | `5C9F44B6B5FF24C7A94347E41CD472858E363B276E0A39462EBAFC4B1046FD25A024C58D8B3BDD88782245E317795F6252BCBDC7A00E4F702FA086F1237E08EC`
SSDEEP | `3072:ziPLxGG+VwJZS09RWCPdossvZXQcWX4woIsdMeZ62r4JUS0r1sJ837:KLx98CGsQeXHoVOejr4JUS0r1si`
IMP | `E57ACD01950B237FF003DE118CF36D33`
PESHA1 | `BBE6341B3912316360579981522FFD9E44F52528`
PE256 | `B3703895922FFE027B02648F0AB2CD29918C2FE39150F8659A83B43955E19E68`

## DLL Exports:

Function Name | Ordinal | Type | Address | Relative Address
-- | -- | -- | -- | --
`NetCreateProvisioningPackage` | 1 (0x1) | Exported Function | NETPROVFW.NetCreateProvisioningPackage | 0x0001f33b
`NetRequestProvisioningPackageInstall` | 4 (0x4) | Exported Function | NETPROVFW.NetRequestProvisioningPackageInstall | 0x0001f3bf
`NetRequestOfflineDomainJoin` | 3 (0x3) | Exported Function | 0x10017880 | 0x00017880
`NetpValidateName` | 33 (0x21) | Exported Function | 0x1001b700 | 0x0001b700
`NetpUpgradePreNT5JoinInfo` | 32 (0x20) | Exported Function | 0x1001b400 | 0x0001b400
`NetpUpdateAutoenrolConfig` | 31 (0x1f) | Exported Function | 0x10016fc0 | 0x00016fc0
`NetpUnJoinDomain` | 30 (0x1e) | Exported Function | 0x1001b1f0 | 0x0001b1f0
`NetpStopService` | 29 (0x1d) | Exported Function | 0x100107d0 | 0x000107d0
`NetpSetComputerAccountPassword` | 28 (0x1c) | Exported Function | 0x10016250 | 0x00016250
`NetpSeparateUserAndDomain` | 27 (0x1b) | Exported Function | 0x10016210 | 0x00016210
`NetProvisionComputerAccount` | 2 (0x2) | Exported Function | 0x100176a0 | 0x000176a0
`NetpQueryService` | 26 (0x1a) | Exported Function | 0x100107b0 | 0x000107b0
`NetpManageMachineAccountWithSid` | 25 (0x19) | Exported Function | 0x1001a3c0 | 0x0001a3c0
`NetpManageIPCConnect` | 24 (0x18) | Exported Function | 0x10015490 | 0x00015490
`NetpMachineValidToJoin` | 23 (0x17) | Exported Function | 0x1001a250 | 0x0001a250
`NetSetuppCloseLog` | 5 (0x5) | Exported Function | 0x1001c7f0 | 0x0001c7f0
`NetpLogPrintHelper` | 22 (0x16) | Exported Function | 0x1001cb40 | 0x0001cb40
`NetpJoinProvider3Initialize` | 20 (0x14) | Exported Function | 0x10012110 | 0x00012110
`NetpJoinProvider2Initialize` | 19 (0x13) | Exported Function | 0x10011f60 | 0x00011f60
`NetpIsSetupInProgress` | 18 (0x12) | Exported Function | 0x10019450 | 0x00019450
`NetpGetMachineAccountName` | 17 (0x11) | Exported Function | 0x10014ba0 | 0x00014ba0
`NetpGetLsaPrimaryDomain` | 16 (0x10) | Exported Function | JOINUTIL.NetpGetLsaPrimaryDomain | 0x0001f552
`NetpGetListOfJoinableOUs` | 15 (0xf) | Exported Function | 0x100144e0 | 0x000144e0
`NetpGetJoinInformation` | 14 (0xe) | Exported Function | 0x1000fa90 | 0x0000fa90
`NetpDomainJoinLicensingCheck` | 13 (0xd) | Exported Function | NETPROVFW.NetpProvDomainJoinLicensingCheck | 0x0001f4df
`NetpDoDomainJoin` | 12 (0xc) | Exported Function | 0x10018ef0 | 0x00018ef0
`NetpCreateComputerObjectInDs` | 11 (0xb) | Exported Function | 0x10012700 | 0x00012700
`NetpCrackNamesStatus2Win32Error` | 10 (0xa) | Exported Function | 0x100125f0 | 0x000125f0
`NetpControlServices` | 9 (0x9) | Exported Function | 0x10010780 | 0x00010780
`NetpChangeMachineName` | 8 (0x8) | Exported Function | 0x100184d0 | 0x000184d0
`NetpAvoidNetlogonSpnSet` | 7 (0x7) | Exported Function | JOINUTIL.NetpAvoidNetlogonSpnSet | 0x0001f429
`NetpJoinProviderInitialize` | 21 (0x15) | Exported Function | 0x10011d10 | 0x00011d10
`NetSetuppOpenLog` | 6 (0x6) | Exported Function | 0x1001c850 | 0x0001c850


## Signature

* Status: Signature verified.
* Serial: `330000026551AE1BBD005CBFBD000000000265`
* Thumbprint: `E168609353F30FF2373157B4EB8CD519D07A2BFF`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: NETJOIN.DLL
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/71
* VirusTotal Link: https://www.virustotal.com/gui/file/25f4a71b3993a2e1ed26a950f2ec32fb4a07c9a528f2163c3778475eae62abea/detection/





MIT License. Copyright (c) 2020 Strontic.


