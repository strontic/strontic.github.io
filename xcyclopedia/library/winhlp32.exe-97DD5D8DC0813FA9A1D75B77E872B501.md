---
title: winhlp32.exe | Windows Winhlp32 Stub
excerpt: What is winhlp32.exe?
---

# winhlp32.exe 

* File Path: `C:\WINDOWS\winhlp32.exe`
* Description: Windows Winhlp32 Stub

## Hashes

Type | Hash
-- | --
MD5 | `97DD5D8DC0813FA9A1D75B77E872B501`
SHA1 | `9B56C6862A0BE0582F530B1760B1DCFC2DA5A8A4`
SHA256 | `38C485EB266C08D3F6B469094B26A7EDF655F09191E561A180A3078C3595BAD8`
SHA384 | `753A9CECAEDED13A7FA449CEA935B7D18A2A02E04C249EC9F07DF467D86CB688FC61CCF2D1C64AFAF15E309EB6B02D62`
SHA512 | `649BA9EF7B3C77F66B01CCCBF71E283EDC22E7564D3BB5B901DC9DCB998FF429E17D1D1BD711AD3185652A6DC5A6BEB444F5D189BDC0DF9B4B79D018E972F3F7`
SSDEEP | `192:QIB0GnbSAvuOqaoYgMgUdkbWoeHWxhh4jFH8b:3XWAvu32qbWoeHWxhh4pH8b`
IMP | `0DFDE2C713801A5C7E6DC0108384FB68`
PESHA1 | `8848A6534F7FD5956828F70624404B418969A37B`
PE256 | `C9E6448728A93424C364E0A2268E353F1FC3B90C8838F2E54093BF74839AB075`

## Runtime Data

### Loaded Modules:

Path |
-- |
C:\WINDOWS\SYSTEM32\ntdll.dll |
C:\WINDOWS\System32\wow64.dll |
C:\WINDOWS\System32\wow64base.dll |
C:\WINDOWS\System32\wow64con.dll |
C:\WINDOWS\System32\wow64cpu.dll |
C:\WINDOWS\System32\wow64win.dll |
C:\WINDOWS\winhlp32.exe |


## Signature

* Status: Signature verified.
* Serial: `33000002ED2C45E4C145CF48440000000002ED`
* Thumbprint: `312860D2047EB81F8F58C29FF19ECDB4C634CF6A`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: WINHLP32.EXE.MUI
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.22000.1 (WinBuild.160101.0800)
* Product Version: 10.0.22000.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/73
* VirusTotal Link: https://www.virustotal.com/gui/file/38c485eb266c08d3f6b469094b26a7edf655f09191e561a180a3078c3595bad8/detection


## Possible Misuse

*The following table contains possible examples of `winhlp32.exe` being misused. While `winhlp32.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_korplug_fast.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_korplug_fast.yar) | $s4 = "\\winhlp32.exe" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)



MIT License. Copyright (c) 2020-2021 Strontic.


