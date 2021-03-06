﻿---
title: amsi.dll | Anti-Malware Scan Interface
excerpt: What is amsi.dll?
---

# amsi.dll 

* File Path: `C:\Windows\SysWOW64\amsi.dll`
* Description: Anti-Malware Scan Interface

## Hashes

Type | Hash
-- | --
MD5 | `539F48A75406ECA418002584B4B8B3ED`
SHA1 | `A81B9BEE708DC1217DBCFA550C3AA9F7F19B054F`
SHA256 | `A2E62B5DEF99323F66FD5F43F5044AED446B93EC0DE01A88AA50BA5E66F7B37B`
SHA384 | `CFD4E3D2C61187E7234A4CD70FCEFE9B4DE96BFA2886393801436ECC786CCCC0B04768170565159A14B216362B9CD433`
SHA512 | `45421429AE71CE2731D4D63ECBC224C13079E4FD41AF76F6D74DD0324D4FFFE4041AE635362D2386A7DC8DD0E95BCC62CF7D6B9092C3E5F5BE360882FE9940D9`
SSDEEP | `1536:D/3+b1ytbY8j+S9/c8a8enqFER0SBQbRWUeL:D/3+pyVH+SNta8enqFFSCbRW`
IMP | `15E97D6C31AF7CB0CD9E6FD978E511FF`
PESHA1 | `59855CB15DBE68653A9D1FC92C5E844C5FF3F60B`
PE256 | `417CB221BE18C022D6554F94F92673AF4AEE44C5A6D0E2F74D558796A54ECADD`

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
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/68
* VirusTotal Link: https://www.virustotal.com/gui/file/a2e62b5def99323f66fd5f43f5044aed446b93ec0de01a88aa50ba5e66f7b37b/detection/


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


