---
title: wlansec.dll | Windows Wireless LAN 802.11 MSM Security Module DLL
excerpt: What is wlansec.dll?
---

# wlansec.dll 

* File Path: `C:\Windows\system32\wlansec.dll`
* Description: Windows Wireless LAN 802.11 MSM Security Module DLL

## Hashes

Type | Hash
-- | --
MD5 | `D262FDA22853A97B260BC19C6E8E1A47`
SHA1 | `9A5DC282E938BD03E7397077288B3B91838BECD0`
SHA256 | `9AF56A91453F755256D77B012ACD82FD341E289FAAB86F8B98EE4770825FA311`
SHA384 | `6BEF053854B9D25035EB1EBF904DB447354900E9D567BBD4CD6256D8F4594CB33EA5031FE085210E7866B16B9AA87081`
SHA512 | `350C7C1023B42A0B6D1B5E07C3043005EF6EB63553BD0B1A5F8DF7074CDE43BF91D9DBADCE17E0288A2991F1930E50ADC3EE2F7459E4BD75F94FD3AB544F0357`
SSDEEP | `6144:ur+uwPh2e0X/iI6vMfYQeMDD+Mhg1FyqpBAsSlWTFVxOCtRgscl/kf8YBiJkVYTt:rbAe0X/i16YQeU16sJsHVxOCtR0lyY1`
IMP | `D9392CAF2F672671AC08EEE949445F2A`
PESHA1 | `911FD3BE474CDA9DFDB4460D819A2FA0A555BA6E`
PE256 | `B98BC69D7154914171ACCE1EE6BAB1DFFC7D44A264E78DB39B57B12050DB3767`

## DLL Exports:

Function Name | Ordinal | Type | Address | Relative Address
-- | -- | -- | -- | --
`MSMSecConnectionHealthCheck` | 1 (0x1) | Exported Function | 0x0000000180008890 | 0x00008890
`MSMSecStopPostAssociateSecurity` | 32 (0x20) | Exported Function | 0x0000000180004f80 | 0x00004f80
`MSMSecSetWcnOneXEnable` | 31 (0x1f) | Exported Function | 0x0000000180009250 | 0x00009250
`MSMSecSetRuntimeState` | 30 (0x1e) | Exported Function | 0x0000000180008d10 | 0x00008d10
`MSMSecSetAPSecondaryPSK` | 29 (0x1d) | Exported Function | 0x0000000180009680 | 0x00009680
`MSMSecSetAPPeerKey` | 28 (0x1c) | Exported Function | 0x0000000180009a90 | 0x00009a90
`MSMSecSendPktCompletion` | 27 (0x1b) | Exported Function | 0x0000000180007370 | 0x00007370
`MSMSecRemoveAPPeerKey` | 26 (0x1a) | Exported Function | 0x0000000180009ef0 | 0x00009ef0
`MSMSecRedoSecurity` | 25 (0x19) | Exported Function | 0x0000000180007f20 | 0x00007f20
`MSMSecRecvPacket` | 24 (0x18) | Exported Function | 0x0000000180005570 | 0x00005570
`MSMSecRecvIndication` | 23 (0x17) | Exported Function | 0x0000000180005cf0 | 0x00005cf0
`MSMSecQueryPeerState` | 22 (0x16) | Exported Function | 0x00000001800074f0 | 0x000074f0
`MSMSecQueryIntfState` | 21 (0x15) | Exported Function | 0x0000000180007b90 | 0x00007b90
`MSMSecQueryAPPeerPSKIndex` | 20 (0x14) | Exported Function | 0x000000018000a280 | 0x0000a280
`MSMSecProcessSessionChange` | 19 (0x13) | Exported Function | 0x0000000180007220 | 0x00007220
`MSMSecPerformPreAssociateSecurityEx` | 18 (0x12) | Exported Function | 0x00000001800036b0 | 0x000036b0
`MSMSecPerformPreAssociateSecurity` | 17 (0x11) | Exported Function | 0x0000000180004250 | 0x00004250
`MSMSecPerformPostAssociateSecurity` | 16 (0x10) | Exported Function | 0x0000000180004640 | 0x00004640
`MSMSecCreateDiscoveryProfiles` | 2 (0x2) | Exported Function | 0x0000000180006b60 | 0x00006b60
`MSMSecDeinitialize` | 3 (0x3) | Exported Function | 0x0000000180002cb0 | 0x00002cb0
`MSMSecDeinitializeAdapter` | 4 (0x4) | Exported Function | 0x0000000180003170 | 0x00003170
`MSMSecDisableIpAddressAllocation` | 5 (0x5) | Exported Function | 0x000000018000a940 | 0x0000a940
`MSMSecEnableIpAddressAllocation` | 6 (0x6) | Exported Function | 0x000000018000a5e0 | 0x0000a5e0
`MSMSecFreeIntfState` | 7 (0x7) | Exported Function | 0x0000000180007e00 | 0x00007e00
`MSMSecStopSecurity` | 33 (0x21) | Exported Function | 0x00000001800042c0 | 0x000042c0
`MSMSecFreeMemory` | 8 (0x8) | Exported Function | 0x0000000180002dd0 | 0x00002dd0
`MSMSecFreeProfile` | 10 (0xa) | Exported Function | 0x00000001800070d0 | 0x000070d0
`MSMSecGetPeerIpAddress` | 11 (0xb) | Exported Function | 0x000000018000ac90 | 0x0000ac90
`MSMSecInitialize` | 12 (0xc) | Exported Function | 0x0000000180002a50 | 0x00002a50
`MSMSecInitializeAdapter` | 13 (0xd) | Exported Function | 0x0000000180002f40 | 0x00002f40
`MSMSecIsUIRequestPending` | 14 (0xe) | Exported Function | 0x0000000180006860 | 0x00006860
`MSMSecPerformCapabilityMatch` | 15 (0xf) | Exported Function | 0x00000001800032d0 | 0x000032d0
`MSMSecFreePeerState` | 9 (0x9) | Exported Function | 0x0000000180007a70 | 0x00007a70
`MSMSecUIResponse` | 34 (0x22) | Exported Function | 0x00000001800062e0 | 0x000062e0


## Signature

* Status: Signature verified.
* Serial: `330000026551AE1BBD005CBFBD000000000265`
* Thumbprint: `E168609353F30FF2373157B4EB8CD519D07A2BFF`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: wlansec.dll
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.488 (WinBuild.160101.0800)
* Product Version: 10.0.19041.488
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/67
* VirusTotal Link: https://www.virustotal.com/gui/file/9af56a91453f755256d77b012acd82fd341e289faab86f8b98ee4770825fa311/detection/





MIT License. Copyright (c) 2020 Strontic.


