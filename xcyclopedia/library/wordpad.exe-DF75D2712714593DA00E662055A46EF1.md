---
title: wordpad.exe | Windows Wordpad Application
excerpt: What is wordpad.exe?
---

# wordpad.exe 

* File Path: `C:\Program Files\Windows NT\Accessories\wordpad.exe`
* Description: Windows Wordpad Application

## Screenshot

![wordpad.exe](screenshots/wordpad.exe-34B557ACE63A6AF3EC4B02B4A9EC46AF-1.png)

## Hashes

Type | Hash
-- | --
MD5 | `DF75D2712714593DA00E662055A46EF1`
SHA1 | `C4B266E8A7B25411A611B1B3D3EF5FBDABED1BCD`
SHA256 | `59B86C305D6AB3867B4F7099438DBFD2EF9F9662323628E2473AF153E503F8F0`
SHA384 | `961148C3E435DB2EAFF76E95FAD38CCD415798510A2159F472C9EF50B9831CB704DA8283787E5A93EEEE84370CC160EA`
SHA512 | `C98E1DCC72FBF03B7A4BCD62249690FD20BE40421825CC61A87D89D46D59B6A0513C6BCC4ACAA219BAA29FCA7003B6E90EC7E454E5B44B50EA1497F4704CD82D`
SSDEEP | `24576:wYDp09QRTnY06ytJZuQPqJdnv+92FxvNEYr8oSUGeP9PDkjjqXv:wYDLTn8QPMdn3xvWCXSZeP9PDk3Y`
IMP | `4B18F11C110D1DD2C4E466B8EDBCEEB7`
PESHA1 | `DE7F518700F5349126EEA244002A22A1E7233D1D`
PE256 | `AA1FF5045535B65C8AC1296E6D4D14D5EE211E65C846822F08594F6212DE7EF1`

## Runtime Data

### Window Title:
Document - WordPad

### Open Handles:

Path | Type
-- | --
(R-D)   C:\Program Files\Windows NT\Accessories\en-US\wordpad.exe.mui | File
(R-D)   C:\Windows\Fonts\StaticCache.dat | File
(R-D)   C:\Windows\System32\en-US\KernelBase.dll.mui | File
(R-D)   C:\Windows\System32\en-US\MFC42u.dll.mui | File
(R-D)   C:\Windows\System32\en-US\UIRibbon.dll.mui | File
(R-D)   C:\Windows\SystemResources\imageres.dll.mun | File
(RW-)   C:\Windows\WinSxS\amd64_microsoft.windows.common-controls_6595b64144ccf1df_6.0.19041.488_none_ca04af081b815d21 | File
(RW-)   C:\Windows\WinSxS\amd64_microsoft.windows.gdiplus_6595b64144ccf1df_1.1.19041.508_none_faefa4f37613d18e | File
(RW-)   C:\xCyclopedia | File
\BaseNamedObjects\__ComCatalogCache__ | Section
\BaseNamedObjects\NLS_CodePage_1252_3_2_0_0 | Section
\BaseNamedObjects\NLS_CodePage_437_3_2_0_0 | Section
\BaseNamedObjects\windows_shell_global_counters | Section
\Sessions\1\BaseNamedObjects\1b2cHWNDInterface:390716 | Section
\Sessions\1\BaseNamedObjects\SessionImmersiveColorPreference | Section
\Sessions\1\BaseNamedObjects\windows_shell_global_counters | Section
\Sessions\1\Windows\Theme2547664911 | Section
\Windows\Theme3854699184 | Section


### Loaded Modules:

Path |
-- |
C:\Program Files\Windows NT\Accessories\wordpad.exe |
C:\Windows\SYSTEM32\apphelp.dll |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\SYSTEM32\ntdll.dll |


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: WORDPAD.EXE.MUI
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/66
* VirusTotal Link: https://www.virustotal.com/gui/file/59b86c305d6ab3867b4f7099438dbfd2ef9f9662323628e2473af153e503f8f0/detection/

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Program Files (x86)\Windows NT\Accessories\wordpad.exe](wordpad.exe-61173FF6ABB1C40E3D3B580126FC5F66.md) | 61
[C:\program files\Windows NT\Accessories\wordpad.exe](wordpad.exe-34B557ACE63A6AF3EC4B02B4A9EC46AF.md) | 77

## Possible Misuse

*The following table contains possible examples of `wordpad.exe` being misused. While `wordpad.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_winnti_burning_umbrella.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_winnti_burning_umbrella.yar) | $s1 = "Wordpad.Document.1\\shell\\open\\command\\" fullword wide | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [thor-hacktools.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/thor-hacktools.yar) | $s3 = "Accessories\\wordpad.exe" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)



MIT License. Copyright (c) 2020 Strontic.


