---
title: wordpad.exe | Windows Wordpad Application
excerpt: What is wordpad.exe?
---

# wordpad.exe 

* File Path: `C:\Program Files\Windows NT\Accessories\wordpad.exe`
* Description: Windows Wordpad Application

## Screenshot

![wordpad.exe](screenshots/wordpad.exe-34B557ACE63A6AF3EC4B02B4A9EC46AF-1.png)
![wordpad.exe](screenshots/wordpad.exe-61173FF6ABB1C40E3D3B580126FC5F66-1.png)
![wordpad.exe](screenshots/wordpad.exe-DF75D2712714593DA00E662055A46EF1-1.png)

## Hashes

Type | Hash
-- | --
MD5 | `334BED13A82786444560DF810A3C8530`
SHA1 | `DB538D0693E3E9B01927692A1C8A97C7F22A07D8`
SHA256 | `44A6D65442C80B5DB26742FF1F2A2A2363177F232917B714947B5CC520A4B5A7`
SHA384 | `76BE5D6BB5FA5E3A01479369D4BBF46E80DFCB2FF983DE71076E603886A7A179F5E58850876FEEC25BDF56BDBB297A4D`
SHA512 | `B52A9442B3B5A2185F8117CBFC560F558E212DD01BB6A186D19288B91FE954B3BFC84EB036F9181A5D20D3B0453C73FAB1CF1E452D63BE5771BF5CD11761E87B`
SSDEEP | `24576:eQ1J73A2r19H4xGBz2m2S7nHdb2FxvNEYr8oSUGeP9PDkjjqXB:eGAeBz207nWxvWCXSZeP9PDk3W`
IMP | `C39E5D6F53A750D16A1F75BA9C6A4004`
PESHA1 | `802798466C075DE5BA6F8DB49A553ACA371612AF`
PE256 | `0F863BDA3BA9A1D982DBC96EAF6D216A1F1FC86EA044062C246E5294F0C7B7CA`

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
(RW-)   C:\Users\user\Documents | File
(RW-)   C:\Windows\WinSxS\amd64_microsoft.windows.common-controls_6595b64144ccf1df_6.0.19041.1110_none_60b5254171f9507e | File
(RW-)   C:\Windows\WinSxS\amd64_microsoft.windows.gdiplus_6595b64144ccf1df_1.1.19041.1320_none_91a11828cc8ae445 | File
\BaseNamedObjects\__ComCatalogCache__ | Section
\BaseNamedObjects\C:\*ProgramData\*Microsoft\*Windows\*Caches\*{6AF0698E-D558-4F6E-9B3C-3716689AF493}.2.ver0x0000000000000002.db | Section
\BaseNamedObjects\C:\*ProgramData\*Microsoft\*Windows\*Caches\*{DDF571F2-BE98-426D-8288-1A9A39C3FDA2}.2.ver0x0000000000000002.db | Section
\BaseNamedObjects\C:\*ProgramData\*Microsoft\*Windows\*Caches\*cversions.2 | Section
\BaseNamedObjects\NLS_CodePage_1252_3_2_0_0 | Section
\BaseNamedObjects\NLS_CodePage_437_3_2_0_0 | Section
\Sessions\1\BaseNamedObjects\26c4HWNDInterface:e0d2c | Section
\Sessions\1\BaseNamedObjects\SessionImmersiveColorPreference | Section
\Sessions\1\BaseNamedObjects\windows_shell_global_counters | Section
\Sessions\1\Windows\Theme449731986 | Section
\Windows\Theme1396518710 | Section


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
* Serial: `33000002EC6579AD1E670890130000000002EC`
* Thumbprint: `F7C2F2C96A328C13CDA8CDB57B715BDEA2CBD1D9`
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

* VirusTotal Detections: 0/73
* VirusTotal Link: https://www.virustotal.com/gui/file/44a6d65442c80b5db26742ff1f2a2a2363177f232917b714947b5cc520a4b5a7/detection

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Program Files (x86)\Windows NT\Accessories\wordpad.exe](wordpad.exe-61173FF6ABB1C40E3D3B580126FC5F66.md) | 58
[C:\program files\Windows NT\Accessories\wordpad.exe](wordpad.exe-34B557ACE63A6AF3EC4B02B4A9EC46AF.md) | 57
[C:\Program Files\Windows NT\Accessories\wordpad.exe](wordpad.exe-DF75D2712714593DA00E662055A46EF1.md) | 57

## Possible Misuse

*The following table contains possible examples of `wordpad.exe` being misused. While `wordpad.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_winnti_burning_umbrella.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_winnti_burning_umbrella.yar) | $s1 = "Wordpad.Document.1\\shell\\open\\command\\" fullword wide | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [thor-hacktools.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/thor-hacktools.yar) | $s3 = "Accessories\\wordpad.exe" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)



MIT License. Copyright (c) 2020-2021 Strontic.


