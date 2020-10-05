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

Function Name | Ordinal | Type
-- | -- | --
`TF_CreateThreadMgr` | 52 | Exported Function
`TF_CUASAppFix` | 41 | Exported Function
`TF_CreateLangBarItemMgr` | 50 | Exported Function
`TF_CreateLangBarMgr` | 51 | Exported Function
`TF_GetAppCompatFlags` | 53 | Exported Function
`TF_GetInitSystemFlags` | 56 | Exported Function
`TF_GetInputScope` | 57 | Exported Function
`TF_GetCompatibleKeyboardLayout` | 54 | Exported Function
`TF_GetGlobalCompartment` | 55 | Exported Function
`TF_CreateInputProcessorProfiles` | 49 | Exported Function
`TF_CanUninitialize` | 42 | Exported Function
`TF_CleanUpPrivateMessages` | 43 | Exported Function
`SetInputScopeXML` | 38 | Exported Function
`TextInputClientWrapperCreate` | 76 | Exported Function
`TF_CreateCategoryMgr` | 45 | Exported Function
`TF_CreateCTFWatchdogMutex` | 44 | Exported Function
`TF_CreateDisplayAttributeMgr` | 48 | Exported Function
`TF_CreateCicLoadMutex` | 46 | Exported Function
`TF_CreateCicLoadWinStaMutex` | 47 | Exported Function
`TF_RunInputCPL` | 1 | Exported Function
`TF_SendLangBandMsg` | 70 | Exported Function
`TF_Notify` | 68 | Exported Function
`TF_PostAllThreadMsg` | 69 | Exported Function
`TF_SetDefaultRemoteKeyboardLayout` | 71 | Exported Function
`TF_UninitSystem` | 74 | Exported Function
`TF_WaitForInitialized` | 75 | Exported Function
`TF_SetShowFloatingStatus` | 72 | Exported Function
`TF_SetThreadFlags` | 73 | Exported Function
`TF_MapCompatibleKeyboardTip` | 67 | Exported Function
`TF_GetThreadMgr` | 60 | Exported Function
`TF_InitSystem` | 61 | Exported Function
`TF_GetShowFloatingStatus` | 58 | Exported Function
`TF_GetThreadFlags` | 59 | Exported Function
`TF_InvalidAssemblyListCacheIfExist` | 62 | Exported Function
`TF_IsThreadWithFlags` | 65 | Exported Function
`TF_MapCompatibleHKL` | 66 | Exported Function
`TF_IsCtfmonRunning` | 63 | Exported Function
`TF_IsLanguageBarEnabled` | 64 | Exported Function
`CtfImeGetGuidAtom` | 14 | Exported Function
`CtfImeGetRegisterWordStyle` | 15 | Exported Function
`CtfImeEscape` | 12 | Exported Function
`CtfImeEscapeEx` | 13 | Exported Function
`CtfImeInquire` | 16 | Exported Function
`CtfImeIsIME` | 19 | Exported Function
`CtfImeProcessCicHotkey` | 20 | Exported Function
`CtfImeInquireExW` | 17 | Exported Function
`CtfImeIsGuidMapEnable` | 18 | Exported Function
`CtfImeEnumRegisterWord` | 11 | Exported Function
`CtfImeConversionList` | 4 | Exported Function
`CtfImeCreateInputContext` | 5 | Exported Function
`CtfImeAssociateFocus` | 2 | Exported Function
`CtfImeConfigure` | 3 | Exported Function
`CtfImeCreateThreadMgr` | 6 | Exported Function
`CtfImeDestroyThreadMgr` | 9 | Exported Function
`CtfImeDispatchDefImeMessage` | 10 | Exported Function
`CtfImeDestroy` | 7 | Exported Function
`CtfImeDestroyInputContext` | 8 | Exported Function
`DllRegisterServer` | 33 | Exported Function
`DllUnregisterServer` | 34 | Exported Function
`DllCanUnloadNow` | 31 | Exported Function
`DllGetClassObject` | 32 | Exported Function
`HasDeferredInputForCoreDispatcher` | 35 | Exported Function
`SetInputScopes` | 40 | Exported Function
`SetInputScopes2` | 39 | Exported Function
`InputFocusMonitorCreate` | 36 | Exported Function
`SetInputScope` | 37 | Exported Function
`CtfNotifyIME` | 30 | Exported Function
`CtfImeSelect` | 23 | Exported Function
`CtfImeSelectEx` | 24 | Exported Function
`CtfImeProcessKey` | 21 | Exported Function
`CtfImeRegisterWord` | 22 | Exported Function
`CtfImeSetActiveContext` | 25 | Exported Function
`CtfImeToAsciiEx` | 28 | Exported Function
`CtfImeUnregisterWord` | 29 | Exported Function
`CtfImeSetCompositionString` | 26 | Exported Function
`CtfImeSetFocus` | 27 | Exported Function


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


