---
title: Windows.Media.dll | Windows Media Runtime DLL
excerpt: What is Windows.Media.dll?
---

# Windows.Media.dll 

* File Path: `C:\Windows\system32\Windows.Media.dll`
* Description: Windows Media Runtime DLL

## Hashes

Type | Hash
-- | --
MD5 | `E20D87AEFC1D1A9B9E69C67C4BC490A6`
SHA1 | `63D63FD114F3B6AE319D583EC42CC3FDACE8B956`
SHA256 | `BA0A8448DF869197E9352FC3D0B7D30D9B0A82FB300BDA2BAEB950662FC724B1`
SHA384 | `0A5CCD4A7F7DADF0FA545ED2226A89F092277EB2DD6A69F775CA126C412057C41431559F2144AB41F73FD8C9B0EA7924`
SHA512 | `00ED21EDA12B9F74C66B0720E4EE1EC4C55AD9AA2B9EE2F8880C57CD6A8CCC0BF98ECCDA2D022920C5DCFEAD391144DEE28BBAC996E3D64ECF9BAE6AC01EA1B0`
SSDEEP | `49152:3UtwYYIwQ4ArBpkb2C/sQFdv70n7KoNQfmA7ppq2ysw72/wFcenH2xasBARG8a8R:3ILrSp7k+tpk2/gQKJq8We5TVae`
IMP | `3D364F250FA50341D880028927A9B3E9`
PESHA1 | `C1B5040D765B72BA75C03EE474459C9F142D65A7`
PE256 | `A6271216C77030F273E13242A8B9F6D09912F6015B7312C2AD97F872CC6D9D65`

## DLL Exports:

Function Name | Ordinal | Type | Address | Relative Address
-- | -- | -- | -- | --
`DllCanUnloadNow` | 2 (0x2) | Exported Function | 0x0000000180017440 | 0x00017440
`DllGetActivationFactory` | 1 (0x1) | Exported Function | 0x0000000180017300 | 0x00017300
`DllGetClassObject` | 3 (0x3) | Exported Function | 0x0000000180016810 | 0x00016810


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: Windows.Media.dll.MUI
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/72
* VirusTotal Link: https://www.virustotal.com/gui/file/ba0a8448df869197e9352fc3d0b7d30d9b0a82fb300bda2baeb950662fc724b1/detection/


## Possible Misuse

*The following table contains possible examples of `Windows.Media.dll` being misused. While `Windows.Media.dll` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_plugx_susp_exe_locations.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_plugx_susp_exe_locations.yml) | `Image: '*\Windows Media Player\\*'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_exec_folder.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_exec_folder.yml) | `- C:\Windows\Media\\*` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020 Strontic.


