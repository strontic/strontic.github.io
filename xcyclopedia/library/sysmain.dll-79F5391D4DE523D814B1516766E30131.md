---
title: sysmain.dll | SysMain Service Host
excerpt: What is sysmain.dll?
---

# sysmain.dll 

* File Path: `C:\Windows\system32\sysmain.dll`
* Description: SysMain Service Host

## Hashes

Type | Hash
-- | --
MD5 | `79F5391D4DE523D814B1516766E30131`
SHA1 | `C47A12DCB2C9DA99D01712CC5BFE4E9663B40D80`
SHA256 | `362E6845CAE723A886A4AF8762356AEA2F19783573B2BAB2056D8A1D3E2E1403`
SHA384 | `F3E9C71160894CE2EF29C7CCB37EAF3E7BE8235292AA6EA4F634DDA9E558CAC8A09521AD69F418F0E2BE428ABD236AF8`
SHA512 | `1A3E3AA34BA1326E009077153EBC5E3313ECBA79324852626197B2F64505410FAACAD8DC193BE3722287D1705C259783E56A1151570F582E36DF676A9AFD9451`
SSDEEP | `24576:2pf7Ckq7daWsaeqBCNbInCQIdXclYZytkzIgLju2:VlkWs3tNECQIdMlYZl`
IMP | `089727AE43B1B6B75782A8D9978D03F3`
PESHA1 | `B391885A53F246D889DB511AEEE0F1AEAE929CAC`
PE256 | `7E5B7D6B266A99F7F4DA7D631D28F40EA4DB63712087F1DD8E969F5BA2148041`

## DLL Exports:

Function Name | Ordinal | Type
-- | -- | --
`MI_Main` | 12 | Exported Function
`OpenReadyBoostPerfData` | 13 | Exported Function
`DllUnregisterServer` | 10 | Exported Function
`GetProviderClassID` | 11 | Exported Function
`PfSvWsSwapAssessmentTask` | 1 | Exported Function
`SysMtServiceMain` | 16 | Exported Function
`PfSvSysprepCleanup` | 14 | Exported Function
`PfSvUnattendCallback` | 15 | Exported Function
`AgTwLoad` | 4 | Exported Function
`CloseReadyBoostPerfData` | 5 | Exported Function
`AgGlLoad` | 2 | Exported Function
`AgPdLoad` | 3 | Exported Function
`DllGetClassObject` | 8 | Exported Function
`DllRegisterServer` | 9 | Exported Function
`CollectReadyBoostPerfData` | 6 | Exported Function
`DllCanUnloadNow` | 7 | Exported Function


## Signature

* Status: Signature verified.
* Serial: `330000026551AE1BBD005CBFBD000000000265`
* Thumbprint: `E168609353F30FF2373157B4EB8CD519D07A2BFF`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: sysmain.dll.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/67
* VirusTotal Link: https://www.virustotal.com/gui/file/362e6845cae723a886a4af8762356aea2f19783573b2bab2056d8a1d3e2e1403/detection/


## Possible Misuse

*The following table contains possible examples of `sysmain.dll` being misused. While `sysmain.dll` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1546.011.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1546.011/T1546.011.md) | * <code>%WINDIR%\AppPatch\sysmain.sdb</code> and | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)



MIT License. Copyright (c) 2020 Strontic.


