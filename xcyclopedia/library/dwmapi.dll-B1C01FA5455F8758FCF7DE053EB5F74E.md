---
title: dwmapi.dll | Microsoft Desktop Window Manager API
excerpt: What is dwmapi.dll?
---

# dwmapi.dll 

* File Path: `C:\Windows\SysWOW64\dwmapi.dll`
* Description: Microsoft Desktop Window Manager API

## Hashes

Type | Hash
-- | --
MD5 | `B1C01FA5455F8758FCF7DE053EB5F74E`
SHA1 | `73CF8CEDA0FADD57EBF23B4D118462C9E1FCEF94`
SHA256 | `B3DD1D5CB94D9C21ED6EC83B3D4ADC00F5CD73F94E4B353F37B0D650AAC63672`
SHA384 | `52AD3CC5A6CFCCDC96849FDB6482B87DA35D6E9BAF599CD247C7B90B4FA90475389B2AFDACBCBD755CEE7E13471CAA6A`
SHA512 | `591FD451CD197772138370E53D9FD5799D185B278B390CB9D4CE68B07414C9BC21E18EAFC0753B938FAA81A53FA58D52B60E94EF8E147FA1C6E17DFCDB82A4E8`
SSDEEP | `3072:s04DGWLQyC5jWOxy85G5sXyCp6pe5C5745dJxOzUEfdYjQPxuKQQ:W8yGjrVPXhpRKUBjQpIQ`
IMP | `68B6DCD962F05C3998994EFCF2E2E012`
PESHA1 | `0C48F7DE1624EB24157C04E1F9D2D9EA340E9948`
PE256 | `A728A15ACE7DCF0D2646F63B6C8A666CDECF7A089637A62AF53523A81D6E4FC8`

## DLL Exports:

Function Name | Ordinal | Type
-- | -- | --
`DllCanUnloadNow` | 111 | Exported Function
`DwmpEnableDDASupport` | 143 | Exported Function
`DwmpFreeSecurityDescriptor` | 137 | Exported Function
`DwmpGetColorizationParameters` | 127 | Exported Function
`DwmpRenderFlick` | 135 | Exported Function
`DwmpSetColorizationParameters` | 131 | Exported Function
`DwmpUpdateProxyWindowForCapture` | 183 | Exported Function
`DwmQueryThumbnailSourceSize` | 186 | Exported Function
`DwmRegisterThumbnail` | 187 | Exported Function
`DwmpDxUpdateWindowSharedSurface` | 101 | Exported Function
`DwmRenderGesture` | 188 | Exported Function
`DwmSetIconicLivePreviewBitmap` | 190 | Exported Function
`DwmSetIconicThumbnail` | 191 | Exported Function
`DwmSetPresentParameters` | 192 | Exported Function
`DwmSetWindowAttribute` | 193 | Exported Function
`DwmShowContact` | 194 | Exported Function
`DwmTetherContact` | 195 | Exported Function
`DwmTetherTextContact` | 156 | Exported Function
`DwmTransitionOwnedWindow` | 196 | Exported Function
`DwmSetDxFrameDuration` | 189 | Exported Function
`DwmpDxgiIsThreadDesktopComposited` | 128 | Exported Function
`DwmpDxGetWindowSharedSurface` | 100 | Exported Function
`DwmpAllocateSecurityDescriptor` | 136 | Exported Function
`DllGetClassObject` | 115 | Exported Function
`DwmAttachMilContent` | 116 | Exported Function
`DwmDefWindowProc` | 117 | Exported Function
`DwmDetachMilContent` | 118 | Exported Function
`DwmEnableBlurBehindWindow` | 119 | Exported Function
`DwmEnableComposition` | 102 | Exported Function
`DwmEnableMMCSS` | 120 | Exported Function
`DwmExtendFrameIntoClientArea` | 121 | Exported Function
`DwmFlush` | 122 | Exported Function
`DwmGetColorizationColor` | 123 | Exported Function
`DwmGetCompositionTimingInfo` | 125 | Exported Function
`DwmGetGraphicsStreamClient` | 126 | Exported Function
`DwmGetGraphicsStreamTransformHint` | 129 | Exported Function
`DwmGetTransportAttributes` | 130 | Exported Function
`DwmGetUnmetTabRequirements` | 133 | Exported Function
`DwmGetWindowAttribute` | 134 | Exported Function
`DwmInvalidateIconicBitmaps` | 149 | Exported Function
`DwmIsCompositionEnabled` | 184 | Exported Function
`DwmModifyPreviousDxFrameDuration` | 185 | Exported Function
`DwmUnregisterThumbnail` | 197 | Exported Function
`DwmUpdateThumbnailProperties` | 198 | Exported Function


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: dwmapi.dll
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.488 (WinBuild.160101.0800)
* Product Version: 10.0.19041.488
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/69
* VirusTotal Link: https://www.virustotal.com/gui/file/b3dd1d5cb94d9c21ed6ec83b3d4adc00f5cd73f94e4b353f37b0d650aac63672/detection/


## Possible Misuse

*The following table contains possible examples of `dwmapi.dll` being misused. While `dwmapi.dll` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[signature-base](https://github.com/Neo23x0/signature-base) | [exploit_uac_elevators.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/exploit_uac_elevators.yar) | $s1 = "%userprofile%\\Downloads\\dwmapi.dll" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [exploit_uac_elevators.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/exploit_uac_elevators.yar) | $s2 = "%windir%\\system32\\dwmapi.dll" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)



MIT License. Copyright (c) 2020 Strontic.


