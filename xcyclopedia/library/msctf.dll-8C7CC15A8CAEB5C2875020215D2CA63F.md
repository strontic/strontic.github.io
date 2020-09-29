---
title: msctf.dll | MSCTF Server DLL
excerpt: What is msctf.dll?
---

# msctf.dll 

* File Path: `C:\Windows\SysWOW64\msctf.dll`
* Description: MSCTF Server DLL

## Hashes

Type | Hash
-- | --
MD5 | `8C7CC15A8CAEB5C2875020215D2CA63F`
SHA1 | `33EAA238525C7EA20140199444CF479B8E3F5E87`
SHA256 | `132345349278D4F12BB5138C100C607316ABF1F9382B74F03A89B233EA5D1093`
SHA384 | `5A6DC0F4E11D6E30CE16810F5DBEEA92FC2338C3CFCB10FC847A9B0AC013AB174BC1C57D3BDA3C18E5EF83AB630F7A65`
SHA512 | `5D7DDB0F9FC3F40B496E3E541A924A63C15DBDB82B19CD6693C79944E5885BC4995864E55325596C548FC6E5B667C145302C994F7D58E2F597DA253AF24A7451`
SSDEEP | `24576:77pB9QFmq3Jm7ECvlsPJwZnGnYnEM7zokOuxcmRQYD7sRw9zQ0CN:779QZmACvlQCZnGnu/zokO9mNsRazQZN`
IMP | `C816CE002AB05FD9FEBBC7CBBD5E1E97`
PESHA1 | `97EC9B0BE504BF0594F9361898C10AD347B86406`
PE256 | `453A92A7FAFE85DACAA7201B7BD0EBBCCE798C143CD91DFC83BD03EAA5377495`

## DLL Exports:

Function Name | Ordinal | Type | Address | Relative Address
-- | -- | -- | -- | --
`CtfImeAssociateFocus` | 2 (0x2) | Exported Function | 0x100348c0 | 0x000348c0
`TF_GetGlobalCompartment` | 55 (0x37) | Exported Function | 0x10066f20 | 0x00066f20
`TF_GetCompatibleKeyboardLayout` | 54 (0x36) | Exported Function | 0x10066e60 | 0x00066e60
`TF_GetAppCompatFlags` | 53 (0x35) | Exported Function | 0x100384e0 | 0x000384e0
`TF_CUASAppFix` | 41 (0x29) | Exported Function | 0x1004b340 | 0x0004b340
`TF_CreateThreadMgr` | 52 (0x34) | Exported Function | 0x10048260 | 0x00048260
`TF_CreateLangBarMgr` | 51 (0x33) | Exported Function | 0x1001e650 | 0x0001e650
`TF_CreateLangBarItemMgr` | 50 (0x32) | Exported Function | 0x10066e40 | 0x00066e40
`TF_CreateInputProcessorProfiles` | 49 (0x31) | Exported Function | 0x10020910 | 0x00020910
`TF_CreateDisplayAttributeMgr` | 48 (0x30) | Exported Function | 0x10049df0 | 0x00049df0
`TF_CreateCTFWatchdogMutex` | 44 (0x2c) | Exported Function | 0x1004d7a0 | 0x0004d7a0
`TF_CreateCicLoadWinStaMutex` | 47 (0x2f) | Exported Function | 0x1004d640 | 0x0004d640
`TF_CreateCicLoadMutex` | 46 (0x2e) | Exported Function | 0x10045d40 | 0x00045d40
`TF_CreateCategoryMgr` | 45 (0x2d) | Exported Function | 0x10049dd0 | 0x00049dd0
`TF_CleanUpPrivateMessages` | 43 (0x2b) | Exported Function | 0x10020a60 | 0x00020a60
`TF_CanUninitialize` | 42 (0x2a) | Exported Function | 0x100205b0 | 0x000205b0
`TF_GetInitSystemFlags` | 56 (0x38) | Exported Function | 0x1002ac70 | 0x0002ac70
`TextInputClientWrapperCreate` | 76 (0x4c) | Exported Function | 0x10029e20 | 0x00029e20
`TF_GetInputScope` | 57 (0x39) | Exported Function | 0x10038470 | 0x00038470
`TF_GetThreadFlags` | 59 (0x3b) | Exported Function | 0x10044e50 | 0x00044e50
`TF_SetThreadFlags` | 73 (0x49) | Exported Function | 0x10047280 | 0x00047280
`TF_SetShowFloatingStatus` | 72 (0x48) | Exported Function | 0x1007b800 | 0x0007b800
`TF_SetDefaultRemoteKeyboardLayout` | 71 (0x47) | Exported Function | 0x1004be10 | 0x0004be10
`TF_SendLangBandMsg` | 70 (0x46) | Exported Function | 0x10067090 | 0x00067090
`TF_RunInputCPL` | 1 (0x1) | Exported Function | 0x10066b70 | 0x00066b70
`TF_PostAllThreadMsg` | 69 (0x45) | Exported Function | 0x10020720 | 0x00020720
`TF_Notify` | 68 (0x44) | Exported Function | 0x10030880 | 0x00030880
`TF_MapCompatibleKeyboardTip` | 67 (0x43) | Exported Function | 0x10067070 | 0x00067070
`TF_MapCompatibleHKL` | 66 (0x42) | Exported Function | 0x10067050 | 0x00067050
`TF_IsThreadWithFlags` | 65 (0x41) | Exported Function | 0x10047760 | 0x00047760
`TF_IsLanguageBarEnabled` | 64 (0x40) | Exported Function | 0x10066f80 | 0x00066f80
`TF_IsCtfmonRunning` | 63 (0x3f) | Exported Function | 0x1004d8b0 | 0x0004d8b0
`TF_InvalidAssemblyListCacheIfExist` | 62 (0x3e) | Exported Function | 0x10047210 | 0x00047210
`TF_InitSystem` | 61 (0x3d) | Exported Function | 0x10043c60 | 0x00043c60
`TF_GetThreadMgr` | 60 (0x3c) | Exported Function | 0x10066f30 | 0x00066f30
`TF_GetShowFloatingStatus` | 58 (0x3a) | Exported Function | 0x1007b7e0 | 0x0007b7e0
`SetInputScopeXML` | 38 (0x26) | Exported Function | 0x10078a50 | 0x00078a50
`SetInputScopes2` | 39 (0x27) | Exported Function | 0x100463f0 | 0x000463f0
`SetInputScopes` | 40 (0x28) | Exported Function | 0x1004b810 | 0x0004b810
`CtfImeInquireExW` | 17 (0x11) | Exported Function | 0x100421a0 | 0x000421a0
`CtfImeInquire` | 16 (0x10) | Exported Function | 0x10066d10 | 0x00066d10
`CtfImeGetRegisterWordStyle` | 15 (0xf) | Exported Function | 0x10066cf0 | 0x00066cf0
`CtfImeGetGuidAtom` | 14 (0xe) | Exported Function | 0x10066cd0 | 0x00066cd0
`CtfImeEscapeEx` | 13 (0xd) | Exported Function | 0x10066cb0 | 0x00066cb0
`CtfImeEscape` | 12 (0xc) | Exported Function | 0x10066c90 | 0x00066c90
`CtfImeEnumRegisterWord` | 11 (0xb) | Exported Function | 0x10066c70 | 0x00066c70
`CtfImeDispatchDefImeMessage` | 10 (0xa) | Exported Function | 0x10040310 | 0x00040310
`CtfImeDestroyThreadMgr` | 9 (0x9) | Exported Function | 0x10024380 | 0x00024380
`CtfImeDestroyInputContext` | 8 (0x8) | Exported Function | 0x10041c60 | 0x00041c60
`CtfImeDestroy` | 7 (0x7) | Exported Function | 0x10066c50 | 0x00066c50
`CtfImeCreateThreadMgr` | 6 (0x6) | Exported Function | 0x10029750 | 0x00029750
`CtfImeCreateInputContext` | 5 (0x5) | Exported Function | 0x1003e900 | 0x0003e900
`CtfImeConversionList` | 4 (0x4) | Exported Function | 0x10066c30 | 0x00066c30
`CtfImeConfigure` | 3 (0x3) | Exported Function | 0x10066c10 | 0x00066c10
`CtfImeIsGuidMapEnable` | 18 (0x12) | Exported Function | 0x10066d30 | 0x00066d30
`CtfImeIsIME` | 19 (0x13) | Exported Function | 0x1001fa40 | 0x0001fa40
`CtfImeProcessCicHotkey` | 20 (0x14) | Exported Function | 0x100346e0 | 0x000346e0
`CtfImeProcessKey` | 21 (0x15) | Exported Function | 0x10038e50 | 0x00038e50
`SetInputScope` | 37 (0x25) | Exported Function | 0x10046420 | 0x00046420
`InputFocusMonitorCreate` | 36 (0x24) | Exported Function | 0x1004c790 | 0x0004c790
`HasDeferredInputForCoreDispatcher` | 35 (0x23) | Exported Function | 0x10037960 | 0x00037960
`DllUnregisterServer` | 34 (0x22) | Exported Function | 0x10065da0 | 0x00065da0
`DllRegisterServer` | 33 (0x21) | Exported Function | 0x10065ac0 | 0x00065ac0
`DllGetClassObject` | 32 (0x20) | Exported Function | 0x10046d20 | 0x00046d20
`DllCanUnloadNow` | 31 (0x1f) | Exported Function | 0x100204f0 | 0x000204f0
`TF_UninitSystem` | 74 (0x4a) | Exported Function | 0x1004c200 | 0x0004c200
`CtfNotifyIME` | 30 (0x1e) | Exported Function | 0x1001ad00 | 0x0001ad00
`CtfImeToAsciiEx` | 28 (0x1c) | Exported Function | 0x10066df0 | 0x00066df0
`CtfImeSetFocus` | 27 (0x1b) | Exported Function | 0x10066dc0 | 0x00066dc0
`CtfImeSetCompositionString` | 26 (0x1a) | Exported Function | 0x10066d90 | 0x00066d90
`CtfImeSetActiveContext` | 25 (0x19) | Exported Function | 0x100353f0 | 0x000353f0
`CtfImeSelectEx` | 24 (0x18) | Exported Function | 0x1003eca0 | 0x0003eca0
`CtfImeSelect` | 23 (0x17) | Exported Function | 0x10066d70 | 0x00066d70
`CtfImeRegisterWord` | 22 (0x16) | Exported Function | 0x10066d50 | 0x00066d50
`CtfImeUnregisterWord` | 29 (0x1d) | Exported Function | 0x10066e20 | 0x00066e20
`TF_WaitForInitialized` | 75 (0x4b) | Exported Function | 0x10020a60 | 0x00020a60


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: MSCTF.DLL
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.488 (WinBuild.160101.0800)
* Product Version: 10.0.19041.488
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/65
* VirusTotal Link: https://www.virustotal.com/gui/file/132345349278d4f12bb5138c100c607316abf1f9382b74f03a89b233ea5d1093/detection/


## Possible Misuse

*The following table contains possible examples of `msctf.dll` being misused. While `msctf.dll` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_turla.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_turla.yar) | $x4 = "Global\\MSCTF.Shared.MUTEX.ZRX" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)



MIT License. Copyright (c) 2020 Strontic.


