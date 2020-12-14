---
title: wimserv.exe | Wimfltr v2 extractor
excerpt: What is wimserv.exe?
---

# wimserv.exe 

* File Path: `C:\Windows\system32\wimserv.exe`
* Description: Wimfltr v2 extractor

## Hashes

Type | Hash
-- | --
MD5 | `2466B0BDEB916DB79519E8228D5BB209`
SHA1 | `49816EF2976C9F6B85A7869C88BE7B60A1018CB4`
SHA256 | `BA2B58BC77D665E43C9CEC3B8D8B88AEBFFD67114F38B29A0D1635AE4D7643EA`
SHA384 | `D646841F9B1C9E7D9C9F8244CFC8F775AD20D5A5761C32D7416DC433D681ABBCA074FC71ED9761631BA0DBD0D9216D23`
SHA512 | `51530F785666F50ED69FF0541B03CBDF2F1BAE75349A7F40147B505A2DF0FED699BD40F8A90A3583693C995B45407763B4861B7B2FFB495D26B067EF59BD8E1F`
SSDEEP | `12288:yz3cdi8KxgGNaCJTJrQMTIFXCu+GWx4aLY:yzv8KxgGAl3XCsi4a0`
IMP | `21FF17E6BA14FECC2B52892F3530717B`
PESHA1 | `7C2FDAC070CA65AFDE7161D6252361BCCC0C9DFF`
PE256 | `ACADB94306DC2EDB940D2A87994157DA42DC7138179D986804556A3EA3FF7C6B`

## Runtime Data

### Loaded Modules:

Path |
-- |
C:\Windows\System32\bcrypt.dll |
C:\Windows\system32\Cabinet.dll |
C:\Windows\system32\FLTLIB.DLL |
C:\Windows\System32\GDI32.dll |
C:\Windows\System32\gdi32full.dll |
C:\Windows\System32\IMM32.DLL |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\System32\msvcp_win.dll |
C:\Windows\System32\msvcrt.dll |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\RPCRT4.dll |
C:\Windows\System32\ucrtbase.dll |
C:\Windows\System32\user32.dll |
C:\Windows\system32\wimserv.exe |
C:\Windows\System32\win32u.dll |


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: extractr.exe
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.17763.1518 (WinBuild.160101.0800)
* Product Version: 10.0.17763.1518
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: Unknown
* VirusTotal Link: n/a


## Possible Misuse

*The following table contains possible examples of `wimserv.exe` being misused. While `wimserv.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_user_driver_loaded.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/builtin/win_user_driver_loaded.yml) | `- '*\Windows\System32\wimserv.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020 Strontic.


