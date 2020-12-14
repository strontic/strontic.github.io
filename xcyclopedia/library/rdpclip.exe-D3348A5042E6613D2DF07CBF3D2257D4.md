---
title: rdpclip.exe | RDP Clipboard Monitor
excerpt: What is rdpclip.exe?
---

# rdpclip.exe 

* File Path: `C:\Windows\system32\rdpclip.exe`
* Description: RDP Clipboard Monitor

## Hashes

Type | Hash
-- | --
MD5 | `D3348A5042E6613D2DF07CBF3D2257D4`
SHA1 | `9BF306B58F5DDA6B0EEFF5DF0EE8CE45907E84DB`
SHA256 | `8AB6E280B961D73082C5F6C67E843CB2F8B666DFFA4104995DAFC454432847D6`
SHA384 | `7B5CE312D9DA04C81AB0B85D12C84B6C6569919D9ADC2B5E83EA817AFE4CD14E74E9353637938AD5F843FD2063A1818E`
SHA512 | `543DBFF7BA26F6D4B9F26AC9AC64CC7455BA08981DB4356544ABDD5AEB4AA9BBB922A7D34349D681C929639B818B86806310171BF60EE06AA3E30C0A08FC6F0D`
SSDEEP | `12288:A34oYkqYnFYTuW8Pq4C4bhObjoSpPwevZu2oxuXet9qviLboBcquUwQtBpDlJ5y8:3oYkqYFYTuW8Pq49bhOb6nRDbyFb1`
IMP | `810E64B8DF587DC8C95D4C20115A7F58`
PESHA1 | `287C693231871C2C3AE4269F07128E795C74DF51`
PE256 | `B6DCFA67E90042BBB38E16D379A5E4DD9E80C693F981256716FAA36F6C814F12`

## Runtime Data

### Loaded Modules:

Path |
-- |
C:\Windows\System32\ADVAPI32.dll |
C:\Windows\System32\GDI32.dll |
C:\Windows\System32\gdi32full.dll |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\System32\msvcp_win.dll |
C:\Windows\System32\msvcrt.dll |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\system32\rdpclip.exe |
C:\Windows\System32\RPCRT4.dll |
C:\Windows\System32\sechost.dll |
C:\Windows\System32\ucrtbase.dll |
C:\Windows\System32\USER32.dll |
C:\Windows\System32\win32u.dll |


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: rdpclip.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/76
* VirusTotal Link: https://www.virustotal.com/gui/file/8ab6e280b961d73082c5f6c67e843cb2f8b666dffa4104995dafc454432847d6/detection


## Possible Misuse

*The following table contains possible examples of `rdpclip.exe` being misused. While `rdpclip.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_termserv_proc_spawn.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_termserv_proc_spawn.yml) | `Image: '*\rdpclip.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020 Strontic.


