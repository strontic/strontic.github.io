---
title: SrTasks.exe | Microsoft Windows System Protection background tasks.
excerpt: What is SrTasks.exe?
---

# SrTasks.exe 

* File Path: `C:\WINDOWS\system32\SrTasks.exe`
* Description: Microsoft Windows System Protection background tasks.

## Hashes

Type | Hash
-- | --
MD5 | `DB5D54D9E84D7922C5E054D5F67A9935`
SHA1 | `4106DA0E17487C5B10222C6B987D96FA368622AE`
SHA256 | `58A7644B6B850A4A8A73D9846D625F51F86EA223C70D061C35E4E3B5BDA63EEE`
SHA384 | `AC598DAE58E4CEEC866DEC179F36F76D6BCFFD7E90442632845C94EA339CBB674BB3C304782760B6D57C126B76B19BA6`
SHA512 | `18B3AFAEF59A4FF07D8055016F1EA7B676F98107154CD86819F8C059C11A6B9127A2E4EC307F7F078CDC25967E6C3945091249EAF4892731D4CE9CEB87CDBC42`
SSDEEP | `1536:C3gX8TSn0hfjI2q3Mtacqkem62A3kKeztHq+Ker:C3ifMt0kk3WRq+KM`
IMP | `DA5162FC74286D3065F624C6773BD09D`
PESHA1 | `26004E66020B94BB302879BA210C5FBC692DB030`
PE256 | `C1144BC92D876D6836A3115C0929508F27A29C8EEF55E24293E30CA0FE8139EA`

## Runtime Data

### Loaded Modules:

Path |
-- |
C:\WINDOWS\System32\KERNEL32.DLL |
C:\WINDOWS\System32\KERNELBASE.dll |
C:\WINDOWS\SYSTEM32\ntdll.dll |
C:\WINDOWS\system32\SrTasks.exe |


## Signature

* Status: Signature verified.
* Serial: `33000002ED2C45E4C145CF48440000000002ED`
* Thumbprint: `312860D2047EB81F8F58C29FF19ECDB4C634CF6A`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: srtasks.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.22000.1 (WinBuild.160101.0800)
* Product Version: 10.0.22000.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/73
* VirusTotal Link: https://www.virustotal.com/gui/file/58a7644b6b850a4a8a73d9846d625f51f86ea223c70d061c35e4e3b5bda63eee/detection


## Possible Misuse

*The following table contains possible examples of `SrTasks.exe` being misused. While `SrTasks.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_suspicious_vss_ps_load.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/image_load/win_suspicious_vss_ps_load.yml) | `- '\srtasks.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020-2021 Strontic.


