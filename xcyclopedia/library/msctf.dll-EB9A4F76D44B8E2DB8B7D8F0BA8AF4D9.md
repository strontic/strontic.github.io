---
title: msctf.dll | MSCTF Server DLL
excerpt: What is msctf.dll?
---

# msctf.dll 

* File Path: `C:\Windows\system32\msctf.dll`
* Description: MSCTF Server DLL

## Hashes

Type | Hash
-- | --
MD5 | `EB9A4F76D44B8E2DB8B7D8F0BA8AF4D9`
SHA1 | `7710BC3BBD9EBDDE5BC966FBD80FDC5AA4F1483C`
SHA256 | `CF1D60BB24CFF2BF0D1CB3CE85E756DD19FB4DE828AAEAD16AAD4A9B581AF525`
SHA384 | `29E80AF18BA25BEDDEED355188369224515EB30B93F4F7C7307D1EAB5EF669513D33AF83DBD29AA4F91E740E964A4CC6`
SHA512 | `9F3FBDA0AD06F721872E64DE336C7E89C840060046D018C83E21850BA076BA6EC13ADF072AE9B00C5A9199CA6923683C869E4A433ABB32DCA30EF4B723F1D086`
SSDEEP | `24576:hUIotpiaj/UD3CAI7ZPiL4jOcT6UvMgXlpU0Y25QrE5N8W:QiajcDyAIpacOKWSpU0Y25QrE5Nb`
IMP | `CE74A0C32AEC667D9E7894CC9AB62FD2`
PESHA1 | `DDCE5D40F94A9B527BA2EA69230E3C622CD3EA63`
PE256 | `763080EE169F875DA01EA83E3282E931CCD84605CD99046CBA8D1D8F08F44802`

## DLL Exports:

Function Name | Ordinal | Type | Address | Relative Address
-- | -- | -- | -- | --
`CtfImeAssociateFocus` | 2 (0x2) | Exported Function | 0x0000000180017f30 | 0x00017f30
`TF_GetGlobalCompartment` | 55 (0x37) | Exported Function | 0x000000018005e8b0 | 0x0005e8b0
`TF_GetCompatibleKeyboardLayout` | 54 (0x36) | Exported Function | 0x000000018005e770 | 0x0005e770
`TF_GetAppCompatFlags` | 53 (0x35) | Exported Function | 0x0000000180011230 | 0x00011230
`TF_CUASAppFix` | 41 (0x29) | Exported Function | 0x000000018005e6a0 | 0x0005e6a0
`TF_CreateThreadMgr` | 52 (0x34) | Exported Function | 0x000000018005e750 | 0x0005e750
`TF_CreateLangBarMgr` | 51 (0x33) | Exported Function | 0x000000018003aa50 | 0x0003aa50
`TF_CreateLangBarItemMgr` | 50 (0x32) | Exported Function | 0x000000018005e730 | 0x0005e730
`TF_CreateInputProcessorProfiles` | 49 (0x31) | Exported Function | 0x000000018003bbe0 | 0x0003bbe0
`TF_CreateDisplayAttributeMgr` | 48 (0x30) | Exported Function | 0x000000018005e710 | 0x0005e710
`TF_CreateCTFWatchdogMutex` | 44 (0x2c) | Exported Function | 0x000000018002e760 | 0x0002e760
`TF_CreateCicLoadWinStaMutex` | 47 (0x2f) | Exported Function | 0x000000018002e840 | 0x0002e840
`TF_CreateCicLoadMutex` | 46 (0x2e) | Exported Function | 0x000000018002c3c0 | 0x0002c3c0
`TF_CreateCategoryMgr` | 45 (0x2d) | Exported Function | 0x000000018005e6e0 | 0x0005e6e0
`TF_CleanUpPrivateMessages` | 43 (0x2b) | Exported Function | 0x00000001800065d0 | 0x000065d0
`TF_CanUninitialize` | 42 (0x2a) | Exported Function | 0x00000001800064f0 | 0x000064f0
`TF_GetInitSystemFlags` | 56 (0x38) | Exported Function | 0x000000018001fa60 | 0x0001fa60
`TextInputClientWrapperCreate` | 76 (0x4c) | Exported Function | 0x000000018001cd60 | 0x0001cd60
`TF_GetInputScope` | 57 (0x39) | Exported Function | 0x000000018001db90 | 0x0001db90
`TF_GetThreadFlags` | 59 (0x3b) | Exported Function | 0x0000000180031eb0 | 0x00031eb0
`TF_SetThreadFlags` | 73 (0x49) | Exported Function | 0x000000018003cc70 | 0x0003cc70
`TF_SetShowFloatingStatus` | 72 (0x48) | Exported Function | 0x000000018007e8a0 | 0x0007e8a0
`TF_SetDefaultRemoteKeyboardLayout` | 71 (0x47) | Exported Function | 0x0000000180040780 | 0x00040780
`TF_SendLangBandMsg` | 70 (0x46) | Exported Function | 0x000000018005eb20 | 0x0005eb20
`TF_RunInputCPL` | 1 (0x1) | Exported Function | 0x000000018005e070 | 0x0005e070
`TF_PostAllThreadMsg` | 69 (0x45) | Exported Function | 0x000000018003c3b0 | 0x0003c3b0
`TF_Notify` | 68 (0x44) | Exported Function | 0x0000000180026830 | 0x00026830
`TF_MapCompatibleKeyboardTip` | 67 (0x43) | Exported Function | 0x000000018005eb10 | 0x0005eb10
`TF_MapCompatibleHKL` | 66 (0x42) | Exported Function | 0x000000018005ea80 | 0x0005ea80
`TF_IsThreadWithFlags` | 65 (0x41) | Exported Function | 0x000000018003cc70 | 0x0003cc70
`TF_IsLanguageBarEnabled` | 64 (0x40) | Exported Function | 0x000000018005e980 | 0x0005e980
`TF_IsCtfmonRunning` | 63 (0x3f) | Exported Function | 0x000000018000c830 | 0x0000c830
`TF_InvalidAssemblyListCacheIfExist` | 62 (0x3e) | Exported Function | 0x000000018003cc70 | 0x0003cc70
`TF_InitSystem` | 61 (0x3d) | Exported Function | 0x000000018002c520 | 0x0002c520
`TF_GetThreadMgr` | 60 (0x3c) | Exported Function | 0x000000018005e8c0 | 0x0005e8c0
`TF_GetShowFloatingStatus` | 58 (0x3a) | Exported Function | 0x000000018007e890 | 0x0007e890
`SetInputScopeXML` | 38 (0x26) | Exported Function | 0x000000018007a6d0 | 0x0007a6d0
`SetInputScopes2` | 40 (0x28) | Exported Function | 0x0000000180036dc0 | 0x00036dc0
`SetInputScopes` | 39 (0x27) | Exported Function | 0x000000018007a720 | 0x0007a720
`CtfImeInquireExW` | 17 (0x11) | Exported Function | 0x0000000180015cd0 | 0x00015cd0
`CtfImeInquire` | 16 (0x10) | Exported Function | 0x000000018005e440 | 0x0005e440
`CtfImeGetRegisterWordStyle` | 15 (0xf) | Exported Function | 0x000000018005e410 | 0x0005e410
`CtfImeGetGuidAtom` | 14 (0xe) | Exported Function | 0x000000018005e3a0 | 0x0005e3a0
`CtfImeEscapeEx` | 13 (0xd) | Exported Function | 0x000000018005e310 | 0x0005e310
`CtfImeEscape` | 12 (0xc) | Exported Function | 0x000000018005e2e0 | 0x0005e2e0
`CtfImeEnumRegisterWord` | 11 (0xb) | Exported Function | 0x000000018005e2b0 | 0x0005e2b0
`CtfImeDispatchDefImeMessage` | 10 (0xa) | Exported Function | 0x000000018000b0d0 | 0x0000b0d0
`CtfImeDestroyThreadMgr` | 9 (0x9) | Exported Function | 0x00000001800076d0 | 0x000076d0
`CtfImeDestroyInputContext` | 8 (0x8) | Exported Function | 0x000000018000b6b0 | 0x0000b6b0
`CtfImeDestroy` | 7 (0x7) | Exported Function | 0x000000018005e280 | 0x0005e280
`CtfImeCreateThreadMgr` | 6 (0x6) | Exported Function | 0x00000001800084b0 | 0x000084b0
`CtfImeCreateInputContext` | 5 (0x5) | Exported Function | 0x00000001800330f0 | 0x000330f0
`CtfImeConversionList` | 4 (0x4) | Exported Function | 0x000000018005e250 | 0x0005e250
`CtfImeConfigure` | 3 (0x3) | Exported Function | 0x000000018005e240 | 0x0005e240
`CtfImeIsGuidMapEnable` | 18 (0x12) | Exported Function | 0x000000018005e470 | 0x0005e470
`CtfImeIsIME` | 19 (0x13) | Exported Function | 0x000000018005e4e0 | 0x0005e4e0
`CtfImeProcessCicHotkey` | 20 (0x14) | Exported Function | 0x000000018001afc0 | 0x0001afc0
`CtfImeProcessKey` | 21 (0x15) | Exported Function | 0x0000000180017a90 | 0x00017a90
`SetInputScope` | 37 (0x25) | Exported Function | 0x0000000180040460 | 0x00040460
`InputFocusMonitorCreate` | 36 (0x24) | Exported Function | 0x0000000180030900 | 0x00030900
`HasDeferredInputForCoreDispatcher` | 35 (0x23) | Exported Function | 0x000000018001aa00 | 0x0001aa00
`DllUnregisterServer` | 34 (0x22) | Exported Function | 0x000000018005c880 | 0x0005c880
`DllRegisterServer` | 33 (0x21) | Exported Function | 0x000000018005c500 | 0x0005c500
`DllGetClassObject` | 32 (0x20) | Exported Function | 0x000000018003cb20 | 0x0003cb20
`DllCanUnloadNow` | 31 (0x1f) | Exported Function | 0x000000018003bfa0 | 0x0003bfa0
`TF_UninitSystem` | 74 (0x4a) | Exported Function | 0x000000018002daa0 | 0x0002daa0
`CtfNotifyIME` | 30 (0x1e) | Exported Function | 0x0000000180014900 | 0x00014900
`CtfImeToAsciiEx` | 28 (0x1c) | Exported Function | 0x000000018005e660 | 0x0005e660
`CtfImeSetFocus` | 27 (0x1b) | Exported Function | 0x000000018005e5d0 | 0x0005e5d0
`CtfImeSetCompositionString` | 26 (0x1a) | Exported Function | 0x000000018005e5c0 | 0x0005e5c0
`CtfImeSetActiveContext` | 25 (0x19) | Exported Function | 0x000000018002fbd0 | 0x0002fbd0
`CtfImeSelectEx` | 24 (0x18) | Exported Function | 0x0000000180033860 | 0x00033860
`CtfImeSelect` | 23 (0x17) | Exported Function | 0x000000018005e590 | 0x0005e590
`CtfImeRegisterWord` | 22 (0x16) | Exported Function | 0x000000018005e560 | 0x0005e560
`CtfImeUnregisterWord` | 29 (0x1d) | Exported Function | 0x000000018005e670 | 0x0005e670
`TF_WaitForInitialized` | 75 (0x4b) | Exported Function | 0x00000001800065d0 | 0x000065d0


## Signature

* Status: Signature verified.
* Serial: `330000026551AE1BBD005CBFBD000000000265`
* Thumbprint: `E168609353F30FF2373157B4EB8CD519D07A2BFF`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: MSCTF.DLL.MUI
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/64
* VirusTotal Link: https://www.virustotal.com/gui/file/cf1d60bb24cff2bf0d1cb3ce85e756dd19fb4de828aaead16aad4a9b581af525/detection/


## Possible Misuse

*The following table contains possible examples of `msctf.dll` being misused. While `msctf.dll` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_turla.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_turla.yar) | $x4 = "Global\\MSCTF.Shared.MUTEX.ZRX" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)



MIT License. Copyright (c) 2020 Strontic.


