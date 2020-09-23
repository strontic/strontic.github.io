---
title: regedt32.exe | Registry Editor Utility
excerpt: What is regedt32.exe?
---

# regedt32.exe 

* File Path: `C:\Windows\SysWOW64\regedt32.exe`
* Description: Registry Editor Utility

## Hashes

Type | Hash
-- | --
MD5 | `49E9EA6F79338B350A8B23CEA47D1A86`
SHA1 | `B51311EEE2A58FDF80CD55616B5A15291A5EE951`
SHA256 | `B9A0659A5F8173629C2CC702F9D786F699BE2C1C1BD10EE354494DF75C618954`
SHA384 | `0B7D872C1AE2C053CECCB83BEA2A393105F573E60C5FD8BF6397627A2511151A91A474B7BE855FB09D66B6DA0244002B`
SHA512 | `A6F473794315E9A38C3D08F1777BA14D0DE3F98F560E8DB120F96ED6FB6EF2A14568F444783AE2520F958E872223A8D4CFAEB98718089E3BC5A3DA35539C85E0`
SSDEEP | `96:cT/8zwOtfZOWkcTLEp2TyIRoJIP3DGjsl3tTZFovnzeDJFMVWVEWlZhHWwB:cT8zwqrTaGRoTeTZFovnz0MWbxWG`
IMP | `FA8607DE86B3096660A35E6483D8EACA`
PESHA1 | `0306A05C48621FA8AD80B1364AF9DCB540733308`
PE256 | `7F31C7F1219A508D4BF5EFEC627F58BC47EC0FF8DDB13003666F0A52C46E48A5`

## Runtime Data

### Child Processes:
regedit.exe

### Loaded Modules:

Path |
-- |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\wow64.dll |
C:\Windows\System32\wow64cpu.dll |
C:\Windows\System32\wow64win.dll |
C:\Windows\SysWOW64\regedt32.exe |


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
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/66
* VirusTotal Link: https://www.virustotal.com/gui/file/b9a0659a5f8173629c2cc702f9d786f699be2c1c1bd10ee354494df75c618954/detection/

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\WINDOWS\SysWOW64\regedt32.exe](regedt32.exe-6E243D43D411D8C7384883376A1F54E3.md) | 66

## Possible Misuse

*The following table contains possible examples of `regedt32.exe` being misused. While `regedt32.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_grizzlybear_uscert.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_grizzlybear_uscert.yar) | $a3 = "regedt32.exe" wide nocase | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)



MIT License. Copyright (c) 2020 Strontic.


