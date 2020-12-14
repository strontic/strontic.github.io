---
title: ctfmon.exe | CTF Loader
excerpt: What is ctfmon.exe?
---

# ctfmon.exe 

* File Path: `C:\Windows\system32\ctfmon.exe`
* Description: CTF Loader

## Hashes

Type | Hash
-- | --
MD5 | `B625C18E177D5BEB5A6F6432CCF46FB3`
SHA1 | `ABB864E1911C59F785B0E1822701B9A5AB31BA1E`
SHA256 | `484FED5F039F429ED933931BA607B7EFDA7D1A343D79CFAB60910E1843147012`
SHA384 | `837300F82D6F1419643D369B7350C16D08BA4768D3875DA3D6BA3970C6A43DB01F9F18F70E20B7191454DF352D9D15C9`
SHA512 | `D908BBDC26504B7BF6527C6F436D1BA0EDFD9D2D09981ECE411551BB3C5E1CFD046675A09A98438C5C59A2A4D9BA689FB0F1DD017190DF6705EA088F11CC0C7F`
SSDEEP | `96:09AOfIKFb3nPWsv+5g3U2QD6S1EswBm5R00hTTpTq6mmyJfLODJVpRKLsLEWhgWq:AX3DPWsD7DS1EswEnp5q6mmy1CMWhgW`
IMP | `6FD43544FB51C12382CAD7C88F550240`
PESHA1 | `ADFB83DD927ED15B5AE5696F0A88D0422F86D373`
PE256 | `BF1AFF435CA010D8BF927C22E891E16682BF2148CF17D037FDA0DD75DE325671`

## Runtime Data

### Loaded Modules:

Path |
-- |
C:\Windows\System32\combase.dll |
C:\Windows\system32\ctfmon.exe |
C:\Windows\System32\GDI32.dll |
C:\Windows\System32\gdi32full.dll |
C:\Windows\System32\IMM32.dll |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\System32\MSCTF.dll |
C:\Windows\system32\MsCtfMonitor.DLL |
C:\Windows\system32\MSUTB.dll |
C:\Windows\System32\msvcp_win.dll |
C:\Windows\System32\msvcrt.dll |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\OLEAUT32.dll |
C:\Windows\System32\RPCRT4.dll |
C:\Windows\System32\sechost.dll |
C:\Windows\System32\ucrtbase.dll |
C:\Windows\System32\USER32.dll |
C:\Windows\System32\win32u.dll |
C:\Windows\system32\WINSTA.dll |


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: CTFMON.EXE.MUI
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/76
* VirusTotal Link: https://www.virustotal.com/gui/file/484fed5f039f429ed933931ba607b7efda7d1a343d79cfab60910e1843147012/detection

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\windows\system32\ctfmon.exe](ctfmon.exe-9929D83891B1C86F4E12C0C90BD8632E.md) | 38

## Possible Misuse

*The following table contains possible examples of `ctfmon.exe` being misused. While `ctfmon.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[malware-ioc](https://github.com/eset/malware-ioc) | [amavaldo](https://github.com/eset/malware-ioc/blob/master/amavaldo/README.adoc) | `\| `6C04499F7406E270B590374EF813C4012530273E` \| ctfmon.exe       \| Abused legitimate application \| Clean file                             \|` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_four_element_sword.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_four_element_sword.yar) | $s1 = "\\System32\\ctfmon.exe" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_poisonivy.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_poisonivy.yar) | $s0 = "%USERPROFILE%\\AppData\\Local\\Temp\\Low\\ctfmon.log" fullword ascii /* PEStudio Blacklist: strings */ /* score: '43.015' */ | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_poisonivy.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_poisonivy.yar) | $s1 = "%USERPROFILE%\\AppData\\Local\\Temp\\ctfmon.tmp" fullword ascii /* PEStudio Blacklist: strings */ /* score: '37.015' */ | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_poisonivy.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_poisonivy.yar) | $s2 = "\\temp\\ctfmon.tmp" fullword ascii /* PEStudio Blacklist: strings */ /* score: '28.01' */ | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)



MIT License. Copyright (c) 2020 Strontic.


