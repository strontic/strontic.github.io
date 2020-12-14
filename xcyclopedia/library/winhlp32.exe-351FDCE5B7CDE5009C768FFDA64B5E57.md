---
title: winhlp32.exe | Windows Winhlp32 Stub
excerpt: What is winhlp32.exe?
---

# winhlp32.exe 

* File Path: `C:\Windows\winhlp32.exe`
* Description: Windows Winhlp32 Stub

## Hashes

Type | Hash
-- | --
MD5 | `351FDCE5B7CDE5009C768FFDA64B5E57`
SHA1 | `1FAB1E89A86956A2281EE8364774BE307D81F689`
SHA256 | `0AE37C1D7FC84E5E956874458508205F4DAD68D933BE6B801CFF2E42475664B5`
SHA384 | `11F3469FF4D36905BAE955F9E0E7E713198950F9F8A9E101DFC6750DC99689D607FA27E9AFFF95FEC7538BD658CD2821`
SHA512 | `71311CD7E0AD65C0B39AE1B8EA14E536E005090815527E2FA91811D238CFE33BB14DCBA34545F68D5A6BF7E8D7FD6255AE11425F7F318C014A360E2580029BF6`
SSDEEP | `192:PvR0uTw4mh2sKYHqWZxeqQ4t5tmXdkLWMeHWthh4jBrA:PiuTorHq8ZnCqLWMeHWthh49s`
IMP | `0DFDE2C713801A5C7E6DC0108384FB68`
PESHA1 | `42A4AD10C35478AF05689EB0D648BD223D0F183D`
PE256 | `05BF298D57CB02F799ACFED77D7B44E4BEAEBD6E72203A7DC1EFC1633F0694B9`

## Runtime Data

### Loaded Modules:

Path |
-- |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\wow64.dll |
C:\Windows\System32\wow64cpu.dll |
C:\Windows\System32\wow64win.dll |
C:\Windows\winhlp32.exe |


## Signature

* Status: Signature verified.
* Serial: `33000001C422B2F79B793DACB20000000001C4`
* Thumbprint: `AE9C1AE54763822EEC42474983D8B635116C8452`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: WINHLP32.EXE.MUI
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.17763.1 (WinBuild.160101.0800)
* Product Version: 10.0.17763.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/69
* VirusTotal Link: https://www.virustotal.com/gui/file/0ae37c1d7fc84e5e956874458508205f4dad68d933be6b801cff2e42475664b5/detection/

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\WINDOWS\winhlp32.exe](winhlp32.exe-CAA192BFDFB5F2A131EBD649B7062DE3.md) | 63

## Possible Misuse

*The following table contains possible examples of `winhlp32.exe` being misused. While `winhlp32.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_korplug_fast.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_korplug_fast.yar) | $s4 = "\\winhlp32.exe" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)



MIT License. Copyright (c) 2020 Strontic.


