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

Function Name | Ordinal | Type | Address | Relative Address
-- | -- | -- | -- | --
`AgGlLoad` | 2 (0x2) | Exported Function | 0x0000000180069810 | 0x00069810
`AgPdLoad` | 3 (0x3) | Exported Function | 0x000000018006a540 | 0x0006a540
`AgTwLoad` | 4 (0x4) | Exported Function | 0x0000000180071630 | 0x00071630
`CloseReadyBoostPerfData` | 5 (0x5) | Exported Function | 0x000000018004d4e0 | 0x0004d4e0
`CollectReadyBoostPerfData` | 6 (0x6) | Exported Function | 0x0000000180067920 | 0x00067920
`DllCanUnloadNow` | 7 (0x7) | Exported Function | 0x00000001800687f0 | 0x000687f0
`DllGetClassObject` | 8 (0x8) | Exported Function | 0x0000000180068830 | 0x00068830
`DllRegisterServer` | 9 (0x9) | Exported Function | 0x00000001800689c0 | 0x000689c0
`DllUnregisterServer` | 10 (0xa) | Exported Function | 0x0000000180068a00 | 0x00068a00
`GetProviderClassID` | 11 (0xb) | Exported Function | 0x0000000180068a40 | 0x00068a40
`MI_Main` | 12 (0xc) | Exported Function | 0x0000000180068200 | 0x00068200
`OpenReadyBoostPerfData` | 13 (0xd) | Exported Function | 0x0000000180067a50 | 0x00067a50
`PfSvSysprepCleanup` | 14 (0xe) | Exported Function | 0x000000018007a5f0 | 0x0007a5f0
`PfSvUnattendCallback` | 15 (0xf) | Exported Function | 0x000000018007abc0 | 0x0007abc0
`PfSvWsSwapAssessmentTask` | 1 (0x1) | Exported Function | 0x0000000180068420 | 0x00068420
`SysMtServiceMain` | 16 (0x10) | Exported Function | 0x0000000180067ef0 | 0x00067ef0


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


