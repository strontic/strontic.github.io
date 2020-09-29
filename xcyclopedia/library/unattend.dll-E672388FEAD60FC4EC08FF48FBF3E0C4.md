---
title: unattend.dll | Unattend Library
excerpt: What is unattend.dll?
---

# unattend.dll 

* File Path: `C:\Windows\system32\unattend.dll`
* Description: Unattend Library

## Hashes

Type | Hash
-- | --
MD5 | `E672388FEAD60FC4EC08FF48FBF3E0C4`
SHA1 | `0CFE9522417806B01AE0E79036E6E6099AEBEDC5`
SHA256 | `31C11EF13621B0EE530F7AC0D99A379A097191ACBCD7505B4F09696BED6209FE`
SHA384 | `0B04E57E47FE027443D299F377A5F6514484F366C428B6D51A07A570AF732225BC6518281793AC03BDC3BD5F25DBA178`
SHA512 | `A10B0F89036DFD8BE58730B79A0AF13D678F3233F323719AF831A04F518656A7EB513600BEE219F48506F4FA4A1E98740EFD8491D44F5F674A0BAEFDD14FFA50`
SSDEEP | `3072:6PueAxuxQRLVyWMFVsrkP4HRM5DNOKt+EdM9NhTmIpQ0ovMqjmVu9BWBBJV:Ve84oVzMErkP6m5pz+Db230`
IMP | `402645DFB881F44C623B537DC9D8FE6F`
PESHA1 | `0DE813BA700A13BF2D60277CA4725482673B80CF`
PE256 | `DB46D057A773FFD5BE769C5EE20B8ECA70473DEBEF9E697EB288B547B18A542A`

## DLL Exports:

Function Name | Ordinal | Type | Address | Relative Address
-- | -- | -- | -- | --
`DllCanUnloadNow` | 1 (0x1) | Exported Function | 0x0000000180001070 | 0x00001070
`UnattendCtxSetString` | 52 (0x34) | Exported Function | 0x00000001800017d0 | 0x000017d0
`UnattendCtxSetNodeName` | 51 (0x33) | Exported Function | 0x0000000180003af0 | 0x00003af0
`UnattendCtxSerializeToStreamFromNode` | 50 (0x32) | Exported Function | 0x0000000180004740 | 0x00004740
`UnattendCtxSerializeToStream` | 49 (0x31) | Exported Function | 0x00000001800046b0 | 0x000046b0
`UnattendCtxSerializeToBufferFromNode` | 48 (0x30) | Exported Function | 0x0000000180002540 | 0x00002540
`UnattendCtxSerializeToBuffer` | 47 (0x2f) | Exported Function | 0x00000001800016c0 | 0x000016c0
`UnattendCtxSetStringByNode` | 53 (0x35) | Exported Function | 0x0000000180003b40 | 0x00003b40
`UnattendCtxSerializeSettingsStream` | 46 (0x2e) | Exported Function | 0x00000001800047c0 | 0x000047c0
`UnattendCtxReplaceNode` | 44 (0x2c) | Exported Function | 0x0000000180003bb0 | 0x00003bb0
`UnattendCtxReplaceMatchedNodesWithText` | 43 (0x2b) | Exported Function | 0x0000000180003680 | 0x00003680
`UnattendCtxRemoveNode` | 42 (0x2a) | Exported Function | 0x00000001800038a0 | 0x000038a0
`UnattendCtxRemoveAttr` | 41 (0x29) | Exported Function | 0x00000001800038f0 | 0x000038f0
`UnattendCtxPrettyPrint` | 40 (0x28) | Exported Function | 0x00000001800025a0 | 0x000025a0
`UnattendCtxOpenNodeByNode` | 39 (0x27) | Exported Function | 0x0000000180002210 | 0x00002210
`UnattendCtxSerialize` | 45 (0x2d) | Exported Function | 0x0000000180001620 | 0x00001620
`UnattendCtxSpliceTrees` | 54 (0x36) | Exported Function | 0x0000000180003e70 | 0x00003e70
`UnattendDeserializeWithResults` | 55 (0x37) | Exported Function | 0x0000000180001080 | 0x00001080
`UnattendEnumFree` | 56 (0x38) | Exported Function | 0x0000000180002c50 | 0x00002c50
`UnattendIsPassUnusedInCtx` | 71 (0x47) | Exported Function | 0x00000001800065b0 | 0x000065b0
`UnattendIsNodeValid` | 70 (0x46) | Exported Function | 0x00000001800022e0 | 0x000022e0
`UnattendGetString` | 69 (0x45) | Exported Function | 0x00000001800011b0 | 0x000011b0
`UnattendGetImplicitContext` | 68 (0x44) | Exported Function | 0x0000000180001120 | 0x00001120
`UnattendGetFlag` | 67 (0x43) | Exported Function | 0x0000000180001220 | 0x00001220
`UnattendGetFirstFailingSetting` | 66 (0x42) | Exported Function | 0x0000000180004060 | 0x00004060
`UnattendGetCount` | 65 (0x41) | Exported Function | 0x0000000180001140 | 0x00001140
`UnattendFreeSetting` | 64 (0x40) | Exported Function | 0x00000001800041f0 | 0x000041f0
`UnattendFreeResults` | 63 (0x3f) | Exported Function | 0x0000000180004390 | 0x00004390
`UnattendFreeNode` | 62 (0x3e) | Exported Function | 0x0000000180002300 | 0x00002300
`UnattendFormatPath` | 61 (0x3d) | Exported Function | 0x00000001800043c0 | 0x000043c0
`UnattendFindFileFromCmdLine` | 60 (0x3c) | Exported Function | 0x00000001800063e0 | 0x000063e0
`UnattendFindAnswerFileWithResults` | 59 (0x3b) | Exported Function | 0x0000000180004f60 | 0x00004f60
`UnattendFindAnswerFileSkipPantherFolder` | 58 (0x3a) | Exported Function | 0x0000000180005050 | 0x00005050
`UnattendFindAnswerFile` | 57 (0x39) | Exported Function | 0x0000000180004a90 | 0x00004a90
`UnattendCtxOpenNode` | 38 (0x26) | Exported Function | 0x0000000180002110 | 0x00002110
`UnattendMarkPassUsedInCtx` | 72 (0x48) | Exported Function | 0x0000000180006510 | 0x00006510
`UnattendCtxGetUlongByNode` | 37 (0x25) | Exported Function | 0x0000000180002f90 | 0x00002f90
`UnattendCtxGetStringByNode` | 35 (0x23) | Exported Function | 0x0000000180002e00 | 0x00002e00
`UnattendCtxDeserializeWithResults` | 15 (0xf) | Exported Function | 0x0000000180001270 | 0x00001270
`UnattendCtxDeserializeString` | 14 (0xe) | Exported Function | 0x0000000180001500 | 0x00001500
`UnattendCtxDeserializeFile` | 13 (0xd) | Exported Function | 0x00000001800013d0 | 0x000013d0
`UnattendCtxDeserializeBuffer` | 12 (0xc) | Exported Function | 0x0000000180001540 | 0x00001540
`UnattendCtxDeserialize` | 11 (0xb) | Exported Function | 0x0000000180001260 | 0x00001260
`UnattendCtxCompareNodes` | 10 (0xa) | Exported Function | 0x0000000180001be0 | 0x00001be0
`UnattendCtxEnumGet` | 16 (0x10) | Exported Function | 0x0000000180002cd0 | 0x00002cd0
`UnattendCtxCommitModify` | 9 (0x9) | Exported Function | 0x00000001800035c0 | 0x000035c0
`UnattendCtxCancelModify` | 7 (0x7) | Exported Function | 0x00000001800035e0 | 0x000035e0
`UnattendCtxBeginModify` | 6 (0x6) | Exported Function | 0x0000000180003540 | 0x00003540
`UnattendCtxAddOrModifyNodeText` | 5 (0x5) | Exported Function | 0x0000000180003630 | 0x00003630
`UnattendCleanup` | 4 (0x4) | Exported Function | 0x00000001800010a0 | 0x000010a0
`UnattendAddResults` | 3 (0x3) | Exported Function | 0x00000001800042e0 | 0x000042e0
`DllMain` | 2 (0x2) | Exported Function | 0x0000000180001040 | 0x00001040
`UnattendCtxCleanup` | 8 (0x8) | Exported Function | 0x0000000180001740 | 0x00001740
`UnattendCtxEnumOrderedSubNodes` | 17 (0x11) | Exported Function | 0x0000000180002a60 | 0x00002a60
`UnattendCtxGetCount` | 18 (0x12) | Exported Function | 0x0000000180001820 | 0x00001820
`UnattendCtxGetCountByNode` | 19 (0x13) | Exported Function | 0x0000000180002d80 | 0x00002d80
`UnattendCtxGetString` | 34 (0x22) | Exported Function | 0x0000000180001890 | 0x00001890
`UnattendCtxGetShowUIFromNode` | 33 (0x21) | Exported Function | 0x00000001800030b0 | 0x000030b0
`UnattendCtxGetShowUI` | 32 (0x20) | Exported Function | 0x0000000180001a80 | 0x00001a80
`UnattendCtxGetRootNode` | 31 (0x1f) | Exported Function | 0x0000000180003260 | 0x00003260
`UnattendCtxGetNodeValue` | 30 (0x1e) | Exported Function | 0x00000001800024f0 | 0x000024f0
`UnattendCtxGetNodeChild` | 29 (0x1d) | Exported Function | 0x0000000180002430 | 0x00002430
`UnattendCtxGetNodeAttr` | 28 (0x1c) | Exported Function | 0x0000000180002380 | 0x00002380
`UnattendCtxGetLongByNode` | 27 (0x1b) | Exported Function | 0x0000000180002ef0 | 0x00002ef0
`UnattendCtxGetLong` | 26 (0x1a) | Exported Function | 0x0000000180001930 | 0x00001930
`UnattendCtxGetFlagByNode` | 25 (0x19) | Exported Function | 0x0000000180003030 | 0x00003030
`UnattendCtxGetFlag` | 24 (0x18) | Exported Function | 0x00000001800019f0 | 0x000019f0
`UnattendCtxGetExpandedStringByNode` | 23 (0x17) | Exported Function | 0x0000000180002e30 | 0x00002e30
`UnattendCtxGetExpandedString` | 22 (0x16) | Exported Function | 0x00000001800018c0 | 0x000018c0
`UnattendCtxGetEnumValueByNode` | 21 (0x15) | Exported Function | 0x0000000180003060 | 0x00003060
`UnattendCtxGetEnumValue` | 20 (0x14) | Exported Function | 0x0000000180001a30 | 0x00001a30
`UnattendCtxGetUlong` | 36 (0x24) | Exported Function | 0x0000000180001990 | 0x00001990
`UnattendUsedPassesExistInCtx` | 73 (0x49) | Exported Function | 0x0000000180006690 | 0x00006690


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: UNATTEND.DLL
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/67
* VirusTotal Link: https://www.virustotal.com/gui/file/31c11ef13621b0ee530f7ac0d99a379a097191acbcd7505b4f09696bed6209fe/detection/


## Possible Misuse

*The following table contains possible examples of `unattend.dll` being misused. While `unattend.dll` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [index.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Indexes-Markdown/index.md) | - Atomic Test #4: Access unattend.xml [windows] | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [windows-index.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Indexes-Markdown/windows-index.md) | - Atomic Test #4: Access unattend.xml [windows] | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1552.001.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1552.001/T1552.001.md) | - [Atomic Test #4 - Access unattend.xml](#atomic-test-4---access-unattendxml) | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1552.001.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1552.001/T1552.001.md) | ## Atomic Test #4 - Access unattend.xml | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1552.001.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1552.001/T1552.001.md) | Attempts to access unattend.xml, where credentials are commonly stored, within the Panther directory where installation logs are stored. | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1552.001.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1552.001/T1552.001.md) | type C:\Windows\Panther\unattend.xml | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1552.001.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1552.001/T1552.001.md) | type C:\Windows\Panther\Unattend\unattend.xml | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)



MIT License. Copyright (c) 2020 Strontic.


