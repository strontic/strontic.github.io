---
title: dwmapi.dll | Microsoft Desktop Window Manager API
excerpt: What is dwmapi.dll?
---

# dwmapi.dll 

* File Path: `C:\Windows\system32\dwmapi.dll`
* Description: Microsoft Desktop Window Manager API

## Hashes

Type | Hash
-- | --
MD5 | `B6C56EF697891DFC671CFA87D546D44B`
SHA1 | `7381173F9731CA8083864714BF4502FAD133FF1A`
SHA256 | `A3F660E5E7F20170D663A4F34BC2EC9CCD3D76675B4B9FABDF76E7B19F9BC012`
SHA384 | `A7A32EC9F4F1DA8E7F639F8DFB58259AD36A291C2D23B25BA0B2C3C66E5A07218AFC82C2FCF3468E2016E4AA864A10FF`
SHA512 | `7076EA0B757E69138A79ECEAE25BAB3081F4D6C934436FBF6A4AE86641F2E79552F6F51D0FA05B4E23DA54EC86C0CB9F2269A8F9B33AA701C667851242CB6866`
SSDEEP | `3072:LWMVhhxK+6NKxcqt2oiN+P39d2jFJA/uXN:FVbk+6Nkcq/iNNjFJAk`
IMP | `AD400860F9D4836AA3A33D24EF565116`
PESHA1 | `84DC937D1F3386FC70AB68CD09D11F7ACD1BE506`
PE256 | `07F543AC99D95F1C1C778E6B56C8C98BDB7979B167BD3453E2A78C5CEBAF6859`

## DLL Exports:

Function Name | Ordinal | Type
-- | -- | --
`DwmpUpdateProxyWindowForCapture` | 183 | Exported Function
`DwmpSetColorizationParameters` | 131 | Exported Function
`DwmQueryThumbnailSourceSize` | 186 | Exported Function
`DwmRenderGesture` | 188 | Exported Function
`DwmRegisterThumbnail` | 187 | Exported Function
`DwmpRenderFlick` | 135 | Exported Function
`DwmpDxUpdateWindowSharedSurface` | 101 | Exported Function
`DwmpDxgiIsThreadDesktopComposited` | 128 | Exported Function
`DwmpEnableDDASupport` | 143 | Exported Function
`DwmpGetColorizationParameters` | 127 | Exported Function
`DwmpFreeSecurityDescriptor` | 137 | Exported Function
`DwmTetherTextContact` | 156 | Exported Function
`DwmTetherContact` | 195 | Exported Function
`DwmTransitionOwnedWindow` | 196 | Exported Function
`DwmUpdateThumbnailProperties` | 198 | Exported Function
`DwmUnregisterThumbnail` | 197 | Exported Function
`DwmShowContact` | 194 | Exported Function
`DwmSetIconicLivePreviewBitmap` | 190 | Exported Function
`DwmSetDxFrameDuration` | 189 | Exported Function
`DwmSetIconicThumbnail` | 191 | Exported Function
`DwmSetWindowAttribute` | 193 | Exported Function
`DwmSetPresentParameters` | 192 | Exported Function
`DwmEnableMMCSS` | 120 | Exported Function
`DwmEnableComposition` | 102 | Exported Function
`DwmExtendFrameIntoClientArea` | 121 | Exported Function
`DwmGetColorizationColor` | 123 | Exported Function
`DwmFlush` | 122 | Exported Function
`DwmEnableBlurBehindWindow` | 119 | Exported Function
`DllGetClassObject` | 115 | Exported Function
`DllCanUnloadNow` | 111 | Exported Function
`DwmAttachMilContent` | 116 | Exported Function
`DwmDetachMilContent` | 118 | Exported Function
`DwmDefWindowProc` | 117 | Exported Function
`DwmIsCompositionEnabled` | 184 | Exported Function
`DwmInvalidateIconicBitmaps` | 149 | Exported Function
`DwmModifyPreviousDxFrameDuration` | 185 | Exported Function
`DwmpDxGetWindowSharedSurface` | 100 | Exported Function
`DwmpAllocateSecurityDescriptor` | 136 | Exported Function
`DwmGetWindowAttribute` | 134 | Exported Function
`DwmGetGraphicsStreamClient` | 126 | Exported Function
`DwmGetCompositionTimingInfo` | 125 | Exported Function
`DwmGetGraphicsStreamTransformHint` | 129 | Exported Function
`DwmGetUnmetTabRequirements` | 133 | Exported Function
`DwmGetTransportAttributes` | 130 | Exported Function


## Signature

* Status: Signature verified.
* Serial: `330000026551AE1BBD005CBFBD000000000265`
* Thumbprint: `E168609353F30FF2373157B4EB8CD519D07A2BFF`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: dwmapi.dll.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/69
* VirusTotal Link: https://www.virustotal.com/gui/file/a3f660e5e7f20170d663a4f34bc2ec9ccd3d76675b4b9fabdf76e7b19f9bc012/detection/


## Possible Misuse

*The following table contains possible examples of `dwmapi.dll` being misused. While `dwmapi.dll` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[malware-ioc](https://github.com/eset/malware-ioc) | [misp-turla-crutch-event.json](https://github.com/eset/malware-ioc/blob/master/turla/misp-turla-crutch-event.json) | `"value": "%PROGRAMFILES%\\(x86)\\Google\\Chrome\\Application\\dwmapi.dll",` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [misp-turla-crutch-event.json](https://github.com/eset/malware-ioc/blob/master/turla/misp-turla-crutch-event.json) | `"value": "%LOCALAPPDATA%\\Microsoft\\OneDrive\\dwmapi.dll",` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [turla](https://github.com/eset/malware-ioc/blob/master/turla/README.adoc) | `* `++C:\Program Files (x86)\Google\Chrome\Application\dwmapi.dll++`` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [turla](https://github.com/eset/malware-ioc/blob/master/turla/README.adoc) | `* `++%LOCALAPPDATA%\Microsoft\OneDrive\dwmapi.dll++`` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [exploit_uac_elevators.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/exploit_uac_elevators.yar) | $s1 = "%userprofile%\\Downloads\\dwmapi.dll" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [exploit_uac_elevators.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/exploit_uac_elevators.yar) | $s2 = "%windir%\\system32\\dwmapi.dll" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)



MIT License. Copyright (c) 2020 Strontic.


