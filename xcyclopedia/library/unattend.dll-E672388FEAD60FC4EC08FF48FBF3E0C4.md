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

Function Name | Ordinal | Type
-- | -- | --
`UnattendCtxSerializeToStream` | 49 | Exported Function
`UnattendCtxSerializeToStreamFromNode` | 50 | Exported Function
`UnattendCtxSerializeToBuffer` | 47 | Exported Function
`UnattendCtxSerializeToBufferFromNode` | 48 | Exported Function
`UnattendCtxSetNodeName` | 51 | Exported Function
`UnattendCtxSpliceTrees` | 54 | Exported Function
`UnattendDeserializeWithResults` | 55 | Exported Function
`UnattendCtxSetString` | 52 | Exported Function
`UnattendCtxSetStringByNode` | 53 | Exported Function
`UnattendCtxPrettyPrint` | 40 | Exported Function
`UnattendCtxRemoveAttr` | 41 | Exported Function
`UnattendCtxOpenNode` | 38 | Exported Function
`UnattendCtxOpenNodeByNode` | 39 | Exported Function
`UnattendCtxRemoveNode` | 42 | Exported Function
`UnattendCtxSerialize` | 45 | Exported Function
`UnattendCtxSerializeSettingsStream` | 46 | Exported Function
`UnattendCtxReplaceMatchedNodesWithText` | 43 | Exported Function
`UnattendCtxReplaceNode` | 44 | Exported Function
`UnattendGetFlag` | 67 | Exported Function
`UnattendGetImplicitContext` | 68 | Exported Function
`UnattendGetCount` | 65 | Exported Function
`UnattendGetFirstFailingSetting` | 66 | Exported Function
`UnattendGetString` | 69 | Exported Function
`UnattendMarkPassUsedInCtx` | 72 | Exported Function
`UnattendUsedPassesExistInCtx` | 73 | Exported Function
`UnattendIsNodeValid` | 70 | Exported Function
`UnattendIsPassUnusedInCtx` | 71 | Exported Function
`UnattendFindAnswerFileSkipPantherFolder` | 58 | Exported Function
`UnattendFindAnswerFileWithResults` | 59 | Exported Function
`UnattendEnumFree` | 56 | Exported Function
`UnattendFindAnswerFile` | 57 | Exported Function
`UnattendFindFileFromCmdLine` | 60 | Exported Function
`UnattendFreeResults` | 63 | Exported Function
`UnattendFreeSetting` | 64 | Exported Function
`UnattendFormatPath` | 61 | Exported Function
`UnattendFreeNode` | 62 | Exported Function
`UnattendCtxGetUlongByNode` | 37 | Exported Function
`UnattendCtxDeserializeBuffer` | 12 | Exported Function
`UnattendCtxDeserializeFile` | 13 | Exported Function
`UnattendCtxCompareNodes` | 10 | Exported Function
`UnattendCtxDeserialize` | 11 | Exported Function
`UnattendCtxDeserializeString` | 14 | Exported Function
`UnattendCtxEnumOrderedSubNodes` | 17 | Exported Function
`UnattendCtxGetCount` | 18 | Exported Function
`UnattendCtxDeserializeWithResults` | 15 | Exported Function
`UnattendCtxEnumGet` | 16 | Exported Function
`UnattendAddResults` | 3 | Exported Function
`UnattendCleanup` | 4 | Exported Function
`DllCanUnloadNow` | 1 | Exported Function
`DllMain` | 2 | Exported Function
`UnattendCtxAddOrModifyNodeText` | 5 | Exported Function
`UnattendCtxCleanup` | 8 | Exported Function
`UnattendCtxCommitModify` | 9 | Exported Function
`UnattendCtxBeginModify` | 6 | Exported Function
`UnattendCtxCancelModify` | 7 | Exported Function
`UnattendCtxGetNodeValue` | 30 | Exported Function
`UnattendCtxGetRootNode` | 31 | Exported Function
`UnattendCtxGetNodeAttr` | 28 | Exported Function
`UnattendCtxGetNodeChild` | 29 | Exported Function
`UnattendCtxGetShowUI` | 32 | Exported Function
`UnattendCtxGetStringByNode` | 35 | Exported Function
`UnattendCtxGetUlong` | 36 | Exported Function
`UnattendCtxGetShowUIFromNode` | 33 | Exported Function
`UnattendCtxGetString` | 34 | Exported Function
`UnattendCtxGetEnumValueByNode` | 21 | Exported Function
`UnattendCtxGetExpandedString` | 22 | Exported Function
`UnattendCtxGetCountByNode` | 19 | Exported Function
`UnattendCtxGetEnumValue` | 20 | Exported Function
`UnattendCtxGetExpandedStringByNode` | 23 | Exported Function
`UnattendCtxGetLong` | 26 | Exported Function
`UnattendCtxGetLongByNode` | 27 | Exported Function
`UnattendCtxGetFlag` | 24 | Exported Function
`UnattendCtxGetFlagByNode` | 25 | Exported Function


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


