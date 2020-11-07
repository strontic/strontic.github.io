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

Function Name | Ordinal | Type
-- | -- | --
`CtfImeAssociateFocus` | 2 | Exported Function
`TF_GetGlobalCompartment` | 55 | Exported Function
`TF_GetCompatibleKeyboardLayout` | 54 | Exported Function
`TF_GetAppCompatFlags` | 53 | Exported Function
`TF_CUASAppFix` | 41 | Exported Function
`TF_CreateThreadMgr` | 52 | Exported Function
`TF_CreateLangBarMgr` | 51 | Exported Function
`TF_CreateLangBarItemMgr` | 50 | Exported Function
`TF_CreateInputProcessorProfiles` | 49 | Exported Function
`TF_CreateDisplayAttributeMgr` | 48 | Exported Function
`TF_CreateCTFWatchdogMutex` | 44 | Exported Function
`TF_CreateCicLoadWinStaMutex` | 47 | Exported Function
`TF_CreateCicLoadMutex` | 46 | Exported Function
`TF_CreateCategoryMgr` | 45 | Exported Function
`TF_CleanUpPrivateMessages` | 43 | Exported Function
`TF_CanUninitialize` | 42 | Exported Function
`TF_GetInitSystemFlags` | 56 | Exported Function
`TextInputClientWrapperCreate` | 76 | Exported Function
`TF_GetInputScope` | 57 | Exported Function
`TF_GetThreadFlags` | 59 | Exported Function
`TF_SetThreadFlags` | 73 | Exported Function
`TF_SetShowFloatingStatus` | 72 | Exported Function
`TF_SetDefaultRemoteKeyboardLayout` | 71 | Exported Function
`TF_SendLangBandMsg` | 70 | Exported Function
`TF_RunInputCPL` | 1 | Exported Function
`TF_PostAllThreadMsg` | 69 | Exported Function
`TF_Notify` | 68 | Exported Function
`TF_MapCompatibleKeyboardTip` | 67 | Exported Function
`TF_MapCompatibleHKL` | 66 | Exported Function
`TF_IsThreadWithFlags` | 65 | Exported Function
`TF_IsLanguageBarEnabled` | 64 | Exported Function
`TF_IsCtfmonRunning` | 63 | Exported Function
`TF_InvalidAssemblyListCacheIfExist` | 62 | Exported Function
`TF_InitSystem` | 61 | Exported Function
`TF_GetThreadMgr` | 60 | Exported Function
`TF_GetShowFloatingStatus` | 58 | Exported Function
`SetInputScopeXML` | 38 | Exported Function
`SetInputScopes2` | 40 | Exported Function
`SetInputScopes` | 39 | Exported Function
`CtfImeInquireExW` | 17 | Exported Function
`CtfImeInquire` | 16 | Exported Function
`CtfImeGetRegisterWordStyle` | 15 | Exported Function
`CtfImeGetGuidAtom` | 14 | Exported Function
`CtfImeEscapeEx` | 13 | Exported Function
`CtfImeEscape` | 12 | Exported Function
`CtfImeEnumRegisterWord` | 11 | Exported Function
`CtfImeDispatchDefImeMessage` | 10 | Exported Function
`CtfImeDestroyThreadMgr` | 9 | Exported Function
`CtfImeDestroyInputContext` | 8 | Exported Function
`CtfImeDestroy` | 7 | Exported Function
`CtfImeCreateThreadMgr` | 6 | Exported Function
`CtfImeCreateInputContext` | 5 | Exported Function
`CtfImeConversionList` | 4 | Exported Function
`CtfImeConfigure` | 3 | Exported Function
`CtfImeIsGuidMapEnable` | 18 | Exported Function
`CtfImeIsIME` | 19 | Exported Function
`CtfImeProcessCicHotkey` | 20 | Exported Function
`CtfImeProcessKey` | 21 | Exported Function
`SetInputScope` | 37 | Exported Function
`InputFocusMonitorCreate` | 36 | Exported Function
`HasDeferredInputForCoreDispatcher` | 35 | Exported Function
`DllUnregisterServer` | 34 | Exported Function
`DllRegisterServer` | 33 | Exported Function
`DllGetClassObject` | 32 | Exported Function
`DllCanUnloadNow` | 31 | Exported Function
`TF_UninitSystem` | 74 | Exported Function
`CtfNotifyIME` | 30 | Exported Function
`CtfImeToAsciiEx` | 28 | Exported Function
`CtfImeSetFocus` | 27 | Exported Function
`CtfImeSetCompositionString` | 26 | Exported Function
`CtfImeSetActiveContext` | 25 | Exported Function
`CtfImeSelectEx` | 24 | Exported Function
`CtfImeSelect` | 23 | Exported Function
`CtfImeRegisterWord` | 22 | Exported Function
`CtfImeUnregisterWord` | 29 | Exported Function
`TF_WaitForInitialized` | 75 | Exported Function


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


