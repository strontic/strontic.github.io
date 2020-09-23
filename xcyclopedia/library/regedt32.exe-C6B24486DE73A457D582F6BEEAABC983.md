---
title: regedt32.exe | Registry Editor Utility
excerpt: What is regedt32.exe?
---

# regedt32.exe 

* File Path: `C:\Windows\system32\regedt32.exe`
* Description: Registry Editor Utility

## Hashes

Type | Hash
-- | --
MD5 | `C6B24486DE73A457D582F6BEEAABC983`
SHA1 | `B876B5C799226F6D6DBC4348B161DE8F457EA968`
SHA256 | `A83D55C6F3FD0E634D4CD570CED654A8BDC1776027680BC3F003476E764CC499`
SHA384 | `4ACE1A903F35E55CC5EB69BA1062426CB47956DE6D4FE2AA5C8EE60532CC2A53460C8F6979C01D2ACD3308B8FFA8B84C`
SHA512 | `59D38AE1A915C73D565BDECB9FF10C3074B021DC2D2B144DD6636FB59BF15085C76A306F09403617065FE21A3DEC91B4F744FE63EA79004DF0DC730E14E6557C`
SSDEEP | `192:9cIya1bGZuqvFJscKonxSWR8ji6ZPl6cMWbxW:KIyQbQuOfx5nEXiENMWbxW`
IMP | `A3060EC916831020104FAE5BC9414975`
PESHA1 | `B37CE6AFB3F6D6F557B1F7825E143635379F33C6`
PE256 | `855057B96229B2831E5F9FC2506043D5DDA0B7CC0E04F6F6EDA09785F52AFCCC`

## Runtime Data

### Child Processes:
regedit.exe

### Loaded Modules:

Path |
-- |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\System32\msvcp_win.dll |
C:\Windows\System32\msvcrt.dll |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\system32\regedt32.exe |
C:\Windows\System32\SHELL32.dll |
C:\Windows\System32\ucrtbase.dll |


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: regedt32.exe
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/70
* VirusTotal Link: https://www.virustotal.com/gui/file/a83d55c6f3fd0e634d4cd570ced654a8bdc1776027680bc3f003476e764cc499/detection/


## Possible Misuse

*The following table contains possible examples of `regedt32.exe` being misused. While `regedt32.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_grizzlybear_uscert.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_grizzlybear_uscert.yar) | $a3 = "regedt32.exe" wide nocase | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)



MIT License. Copyright (c) 2020 Strontic.


