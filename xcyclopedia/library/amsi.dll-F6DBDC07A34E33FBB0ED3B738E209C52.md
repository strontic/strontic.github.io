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

Function Name | Ordinal | Type
-- | -- | --
`DllCanUnloadNow` | 10 | Exported Function
`AmsiUninitialize` | 9 | Exported Function
`AmsiUacUninitialize` | 8 | Exported Function
`DllUnregisterServer` | 13 | Exported Function
`DllRegisterServer` | 12 | Exported Function
`DllGetClassObject` | 11 | Exported Function
`AmsiUacScan` | 7 | Exported Function
`AmsiOpenSession` | 3 | Exported Function
`AmsiInitialize` | 2 | Exported Function
`AmsiCloseSession` | 1 | Exported Function
`AmsiUacInitialize` | 6 | Exported Function
`AmsiScanString` | 5 | Exported Function
`AmsiScanBuffer` | 4 | Exported Function


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

*The following table contains possible examples of `amsi.dll` being misused. While `amsi.dll` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

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


