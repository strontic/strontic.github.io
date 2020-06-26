---
title: ComputerDefaults.exe | Set Program Access and Computer Defaults Control Panel
---

# ComputerDefaults.exe 

* File Path: `C:\Windows\system32\ComputerDefaults.exe`
* Description: Set Program Access and Computer Defaults Control Panel
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `3F032A1BDF4D7DF2F43FE7C0410AC175`
SHA1 | `1D9CFDB4C324543CC3231029913D735D6EE27C70`
SHA256 | `4978AD7650C44D4239ED6B77267DD21D50D33BBD3D875ACE4131F2DED3A11804`
SHA384 | `7C564FD80D41AEA6A7BAB82152322511CC0EB782BDC64739A9871E94FDD5393E2EBC09F56032FEC0AF3B0EDC0B6E9A95`
SHA512 | `C281C1009D2CF7CC41E45B39E3EFBBAD3AED091A21FAC30EE369281BAF4C0D9AC190B321E9BE891092BCE7FC2DDEC2195F67A5B6E70CA680BE4F9205090130A4`
SSDEEP | `1536:gS1tjONtCc7jFGPURDoq4OZZZLlCIibk:7HOocRD68wbk`

## Runtime Data

### Usage (stdout):
```Batchfile

```

### Usage (stderr):
```Batchfile

```

### Child Processes:


## Signature

* Status: Signature verified.
* Serial: `33000000BCE120FDD27CC8EE930000000000BC`
* Thumbprint: `E85459B23C232DB3CB94C7A56D47678F58E8E51E`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: ComputerDefaults.EXE.MUI
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.14393.0 (rs1_release.160715-1616)
* Product Version: 10.0.14393.0
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\WINDOWS\system32\ComputerDefaults.exe](ComputerDefaults.exe-495F18535BBBA007A18EC5EE708318FE.md) | 54
[C:\WINDOWS\system32\xwizard.exe](xwizard.exe-30D89280E86DFB29C2F232194642125E.md) | 50
[C:\Windows\system32\xwizard.exe](xwizard.exe-C0CCC55F9E988ACB8B624EFD0EC8B92B.md) | 47
[C:\WINDOWS\SysWOW64\ComputerDefaults.exe](ComputerDefaults.exe-455CCBB47F4BEF02A9E0034859CE59E2.md) | 54
[C:\Windows\SysWOW64\ComputerDefaults.exe](ComputerDefaults.exe-4A007FCF54D0379B75D1FA50F840D62B.md) | 66
[C:\Windows\SysWOW64\xwizard.exe](xwizard.exe-3C70F039EE4C07511ABD82B5664FB91B.md) | 57
[C:\WINDOWS\SysWOW64\xwizard.exe](xwizard.exe-CB72CA2B130AA4B776FAF32E18453CF6.md) | 54

## Possible Misuse

*The following table contains possible examples of `ComputerDefaults.exe` being misused. While `ComputerDefaults.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [index.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Indexes-Markdown/index.md) |   - Atomic Test #5: Bypass UAC using ComputerDefaults (PowerShell) [windows] | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [windows-index.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Indexes-Markdown/windows-index.md) |   - Atomic Test #5: Bypass UAC using ComputerDefaults (PowerShell) [windows] | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1548.002.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1548.002/T1548.002.md) | - [Atomic Test #5 - Bypass UAC using ComputerDefaults (PowerShell)](#atomic-test-5---bypass-uac-using-computerdefaults-powershell) | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1548.002.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1548.002/T1548.002.md) | ## Atomic Test #5 - Bypass UAC using ComputerDefaults (PowerShell) | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1548.002.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1548.002/T1548.002.md) | PowerShell code to bypass User Account Control using ComputerDefaults.exe on Windows 10 | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1548.002.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1548.002/T1548.002.md) | Start-Process "C:\Windows\System32\ComputerDefaults.exe" | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)



MIT License. Copyright (c) 2020 Strontic.


