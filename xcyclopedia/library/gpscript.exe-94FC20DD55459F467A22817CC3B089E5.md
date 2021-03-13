---
title: gpscript.exe | Group Policy Script Application
excerpt: What is gpscript.exe?
---

# gpscript.exe 

* File Path: `C:\Windows\system32\gpscript.exe`
* Description: Group Policy Script Application

## Hashes

Type | Hash
-- | --
MD5 | `94FC20DD55459F467A22817CC3B089E5`
SHA1 | `56BE5829772F8E6F9A8C83B213145B183B5FCCD0`
SHA256 | `BB008DEED1241EAD9F245661D2CD629D02031433B614CDC2CD7B1291A753A6A7`
SHA384 | `6B2D69615863A441CE43414B101D4E96C8259F8B3C2A36652528004E6433FCCB482F8959BC63A6970AF27E51FB6FFFAA`
SHA512 | `816F681C923949E091252EBB34E95647BB27AEB6722E2B90D7DF80423AAE0B957163F12C0963710A1C62AFC57F0074B3A4AD4DF7D8B3BB24D7F574EBB1E62B4E`
SSDEEP | `768:y6eYCR0d5ylfuPJ3CFOQfs+aVdl0ex0HXdBTdTlYwGqk:7e1u5ylmB3CFOsDaVd+ex0HXdBTdTiw0`
IMP | `74C28449EAF72F02E22F89C962FB3F40`
PESHA1 | `70576F401A7E05F3D6762D8FD756963BA887954C`
PE256 | `054FFB20952D28AD5453C0C1E0A85D9FD5634CA5B93790DA612FAED86BF974F1`

## Runtime Data

### Loaded Modules:

Path |
-- |
C:\Windows\System32\GDI32.dll |
C:\Windows\System32\gdi32full.dll |
C:\Windows\system32\gpscript.exe |
C:\Windows\System32\IMM32.DLL |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\System32\msvcp_win.dll |
C:\Windows\System32\msvcrt.dll |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\RPCRT4.dll |
C:\Windows\System32\sechost.dll |
C:\Windows\System32\ucrtbase.dll |
C:\Windows\System32\USER32.dll |
C:\Windows\System32\win32u.dll |


## Signature

* Status: Signature verified.
* Serial: `330000026551AE1BBD005CBFBD000000000265`
* Thumbprint: `E168609353F30FF2373157B4EB8CD519D07A2BFF`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: GPSCRIPT.EXE
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.572 (WinBuild.160101.0800)
* Product Version: 10.0.19041.572
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/75
* VirusTotal Link: https://www.virustotal.com/gui/file/bb008deed1241ead9f245661d2cd629d02031433b614cdc2cd7b1291a753a6a7/detection

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Windows\system32\gpscript.exe](gpscript.exe-E49D088657E3653742B81D78CD8574D2.md) | 29

## Possible Misuse

*The following table contains possible examples of `gpscript.exe` being misused. While `gpscript.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Gpscript.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Gpscript.yml) | `Name: Gpscript.exe`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Gpscript.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Gpscript.yml) | `- Command: Gpscript /logon`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Gpscript.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Gpscript.yml) | `- Command: Gpscript /startup`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Gpscript.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Gpscript.yml) | `- Path: C:\Windows\System32\gpscript.exe`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Gpscript.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Gpscript.yml) | `- Path: C:\Windows\SysWOW64\gpscript.exe`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Gpscript.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Gpscript.yml) | `- IOC: Execution of Gpscript.exe after logon`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Gpscript.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Gpscript.yml) | `- Link: https://oddvar.moe/2018/04/27/gpscript-exe-another-lolbin-to-the-list/`{:.highlight .language-yaml} | 



MIT License. Copyright (c) 2020-2021 Strontic.


