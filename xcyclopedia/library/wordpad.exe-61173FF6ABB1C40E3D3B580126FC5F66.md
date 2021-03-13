---
title: wordpad.exe | Windows Wordpad Application
excerpt: What is wordpad.exe?
---

# wordpad.exe 

* File Path: `C:\Program Files (x86)\Windows NT\Accessories\wordpad.exe`
* Description: Windows Wordpad Application

## Screenshot

![wordpad.exe](screenshots/wordpad.exe-34B557ACE63A6AF3EC4B02B4A9EC46AF-1.png)
![wordpad.exe](screenshots/wordpad.exe-61173FF6ABB1C40E3D3B580126FC5F66-1.png)
![wordpad.exe](screenshots/wordpad.exe-DF75D2712714593DA00E662055A46EF1-1.png)

## Hashes

Type | Hash
-- | --
MD5 | `61173FF6ABB1C40E3D3B580126FC5F66`
SHA1 | `C017E91A526DFBB37293CD79D86A1D7261ED0141`
SHA256 | `09F10E7344CA61B53A080E4D54C7CB6ECD4E3308254B350906437E29E7A7D9B2`
SHA384 | `0A8951333DEA88F9EF4CAD098E8B502420F7F074EBECC14A10878F43092F0A6C5AE77CBC3C17815EFC76B6CE5CB0A1AE`
SHA512 | `C5C8D5AD867987D18F88EF7D88E86E9A8DE13185F17F2E722409816D83147152ADB87EAB4A88E6327CBB1BD60D0223BBFE8689D54F747438BC66DD93C76CD9DA`
SSDEEP | `24576:pxHn7MgYE6WM73vT62FxvNEYr8oSUGeP9PDkjjqX+l:pxH7MgYE67BxvWCXSZeP9PDk37l`
IMP | `792625AE31F87E1BD7777B3CDA7BBC92`
PESHA1 | `9F3A45591A07D68469519C80F02C572432298540`
PE256 | `644FCBB03223AF7112AB34897B385F4909CF096889201D7D6B930170010ED9D6`

## Runtime Data

### Child Processes:
splwow64.exe

### Window Title:
Document - WordPad

### Open Handles:

Path | Type
-- | --
(R-D)   C:\Program Files (x86)\Windows NT\Accessories\en-US\wordpad.exe.mui | File
(R-D)   C:\Windows\Fonts\StaticCache.dat | File
(R-D)   C:\Windows\System32\en-US\KernelBase.dll.mui | File
(R-D)   C:\Windows\System32\en-US\MFC42u.dll.mui | File
(R-D)   C:\Windows\SystemResources\imageres.dll.mun | File
(R-D)   C:\Windows\SysWOW64\en-US\UIRibbon.dll.mui | File
(RW-)   C:\Users\user\Documents | File
(RW-)   C:\Windows | File
(RW-)   C:\Windows\WinSxS\x86_microsoft.windows.common-controls_6595b64144ccf1df_6.0.19041.488_none_11b1e5df2ffd8627 | File
(RW-)   C:\Windows\WinSxS\x86_microsoft.windows.gdiplus_6595b64144ccf1df_1.1.19041.508_none_429cdbca8a8ffa94 | File
\BaseNamedObjects\__ComCatalogCache__ | Section
\BaseNamedObjects\NLS_CodePage_1252_3_2_0_0 | Section
\BaseNamedObjects\NLS_CodePage_437_3_2_0_0 | Section
\BaseNamedObjects\windows_shell_global_counters | Section
\Sessions\1\BaseNamedObjects\1820HWNDInterface:69049c | Section
\Sessions\1\BaseNamedObjects\SessionImmersiveColorPreference | Section
\Sessions\1\BaseNamedObjects\windows_shell_global_counters | Section
\Sessions\1\Windows\Theme64749523 | Section
\Windows\Theme1120315852 | Section


### Loaded Modules:

Path |
-- |
C:\Program Files (x86)\Windows NT\Accessories\wordpad.exe |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\wow64.dll |
C:\Windows\System32\wow64cpu.dll |
C:\Windows\System32\wow64win.dll |


## Signature

* Status: Signature verified.
* Serial: `330000023241FB59996DCC4DFF000000000232`
* Thumbprint: `FF82BC38E1DA5E596DF374C53E3617F7EDA36B06`
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
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/68
* VirusTotal Link: https://www.virustotal.com/gui/file/09f10e7344ca61b53a080e4d54c7cb6ecd4e3308254b350906437e29e7a7d9b2/detection/

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\program files\Windows NT\Accessories\wordpad.exe](wordpad.exe-34B557ACE63A6AF3EC4B02B4A9EC46AF.md) | 60
[C:\Program Files\Windows NT\Accessories\wordpad.exe](wordpad.exe-DF75D2712714593DA00E662055A46EF1.md) | 61

## Possible Misuse

*The following table contains possible examples of `wordpad.exe` being misused. While `wordpad.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_winnti_burning_umbrella.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_winnti_burning_umbrella.yar) | $s1 = "Wordpad.Document.1\\shell\\open\\command\\" fullword wide | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [thor-hacktools.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/thor-hacktools.yar) | $s3 = "Accessories\\wordpad.exe" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)



MIT License. Copyright (c) 2020-2021 Strontic.


