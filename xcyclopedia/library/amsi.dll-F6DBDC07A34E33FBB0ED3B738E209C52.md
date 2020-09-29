---
title: amsi.dll | Anti-Malware Scan Interface
excerpt: What is amsi.dll?
---

# amsi.dll 

* File Path: `C:\Windows\system32\amsi.dll`
* Description: Anti-Malware Scan Interface

## Hashes

Type | Hash
-- | --
MD5 | `F6DBDC07A34E33FBB0ED3B738E209C52`
SHA1 | `5AA02F6FCD770D4BFEC9F34557A05CE1801E381E`
SHA256 | `DD5F528E2CCC027A0B42038511C7FAE11032D1277F5D529C539346DDDC529E88`
SHA384 | `097E7B0B5203FA0496980A139903C32FFA204B1645BDCB248C8B889EE9FBB559B4B8E6119220EEEDF7144D5387B2343B`
SHA512 | `517AE4736ADCE2CA6B03283740E0DA6AAB558F04AEB507DEDFFB1EC00A090E8251783FDCBADC2E250877A75D29E03F4F437DF5C1A0AF1E21A1947F2F03146790`
SSDEEP | `1536:ZTL8OqtA5WAj0ILiOaiuC899zw+8ba50N17eTQ4MWU:Zk2cFC8M+8baON16s4MW`
IMP | `FD5133722D119EA56EC3FA027F24FF94`
PESHA1 | `E5EADECC72051B192313442AC435D4D342659B45`
PE256 | `2309F926BB6C32A971CC6369315228B7C00AD44A74DF643FDA88169DE610EE51`

## DLL Exports:

Function Name | Ordinal | Type | Address | Relative Address
-- | -- | -- | -- | --
`AmsiCloseSession` | 1 (0x1) | Exported Function | 0x00000001800026f0 | 0x000026f0
`AmsiInitialize` | 2 (0x2) | Exported Function | 0x0000000180002370 | 0x00002370
`AmsiOpenSession` | 3 (0x3) | Exported Function | 0x0000000180002690 | 0x00002690
`AmsiScanBuffer` | 4 (0x4) | Exported Function | 0x0000000180002710 | 0x00002710
`AmsiScanString` | 5 (0x5) | Exported Function | 0x0000000180002810 | 0x00002810
`AmsiUacInitialize` | 6 (0x6) | Exported Function | 0x0000000180002870 | 0x00002870
`AmsiUacScan` | 7 (0x7) | Exported Function | 0x0000000180002af0 | 0x00002af0
`AmsiUacUninitialize` | 8 (0x8) | Exported Function | 0x0000000180002a90 | 0x00002a90
`AmsiUninitialize` | 9 (0x9) | Exported Function | 0x0000000180002630 | 0x00002630
`DllCanUnloadNow` | 10 (0xa) | Exported Function | 0x0000000180001970 | 0x00001970
`DllGetClassObject` | 11 (0xb) | Exported Function | 0x00000001800019b0 | 0x000019b0
`DllRegisterServer` | 12 (0xc) | Exported Function | 0x0000000180001af0 | 0x00001af0
`DllUnregisterServer` | 13 (0xd) | Exported Function | 0x0000000180001af0 | 0x00001af0


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: amsi.dll
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/70
* VirusTotal Link: https://www.virustotal.com/gui/file/dd5f528e2ccc027a0b42038511c7fae11032d1277f5d529c539346dddc529e88/detection/


## Possible Misuse

*The following table contains possible examples of `amsi.dll` being misused. While `amsi.dll` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [index.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Indexes-Markdown/index.md) | - Atomic Test #1: DLL Search Order Hijacking - amsi.dll [windows] | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [windows-index.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Indexes-Markdown/windows-index.md) | - Atomic Test #1: DLL Search Order Hijacking - amsi.dll [windows] | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1574.001.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1574.001/T1574.001.md) | - [Atomic Test #1 - DLL Search Order Hijacking - amsi.dll](#atomic-test-1---dll-search-order-hijacking---amsidll) | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1574.001.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1574.001/T1574.001.md) | ## Atomic Test #1 - DLL Search Order Hijacking - amsi.dll | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1574.001.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1574.001/T1574.001.md) | Adversaries can take advantage of insecure library loading by PowerShell to load a vulnerable version of amsi.dll in order to bypass AMSI (Anti-Malware Scanning Interface) | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1574.001.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1574.001/T1574.001.md) | Upon successful execution, powershell.exe will be copied and renamed to updater.exe and load amsi.dll from a non-standard path. | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1574.001.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1574.001/T1574.001.md) | copy %windir%\System32\amsi.dll %APPDATA%\amsi.dll | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1574.001.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1574.001/T1574.001.md) | del %APPDATA%\amsi.dll >nul 2>&1 | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)



MIT License. Copyright (c) 2020 Strontic.


