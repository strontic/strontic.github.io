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
MD5 | `0629E6D130F226C009EA9AB329F37ACC`
SHA1 | `1529C6CF3265311B690992DC975443B35177BC7C`
SHA256 | `4FCE997BDD3475C42BA856D8C288FD4F9F91FD1370075AD7E0B11B1E71AE69CE`
SHA384 | `5ACC4C750A0CAC12E69E652967BAB059D050AC71533F4157176ABB3967D80D9D68A33DC57108BDC9AC5DB76FE0BB7563`
SHA512 | `A36F25CD5B79891F0CC5A8E85636CE4EF10C91EC6D6C7C0F5C5B622D0AF1F4F400C864D331CAFFAA8A51D9A2734777B5B9CE87CABB7667A9ACEAF8837E88C847`
SSDEEP | `192:ZomhYgSgGvZx5qdoth1Pdk7WneHWGhh4j8q05:L67gGnP7q7WneHWGhh44q`
IMP | `0DFDE2C713801A5C7E6DC0108384FB68`
PESHA1 | `DE7923B88BC3FDFFFB5F3EB94DAD49AC7B3AA33E`
PE256 | `84910CAE848CAD56B1F0B2AFC05F6A045EFB837FB7A3931F48BBC0A8B5055BD1`

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
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: WINHLP32.EXE.MUI
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/75
* VirusTotal Link: https://www.virustotal.com/gui/file/4fce997bdd3475c42ba856d8c288fd4f9f91fd1370075ad7e0b11b1e71ae69ce/detection


## Possible Misuse

*The following table contains possible examples of `winhlp32.exe` being misused. While `winhlp32.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_korplug_fast.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_korplug_fast.yar) | $s4 = "\\winhlp32.exe" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)



MIT License. Copyright (c) 2020 Strontic.


