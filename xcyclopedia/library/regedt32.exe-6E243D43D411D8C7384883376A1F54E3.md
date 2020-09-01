---
title: regedt32.exe | Registry Editor Utility
---

# regedt32.exe 

* File Path: `C:\WINDOWS\SysWOW64\regedt32.exe`
* Description: Registry Editor Utility

## Hashes

Type | Hash
-- | --
MD5 | `6E243D43D411D8C7384883376A1F54E3`
SHA1 | `CEE18194F8230E09D0D4EC1B80E480BAF4577B07`
SHA256 | `757A4758B2FAA5D6944BD337ED7DA9563E32D2C5E31D5A0363CBBCC0CC4756D1`
SHA384 | `A218EBD13056DD928FC07EEB83D7036D2F16A2313AE7406D75A612D1A3AA39AE5B6F3E2A812E913FE818213478181A4B`
SHA512 | `3BE61D18F80EDD140220200827E7306ABD696AEB41916AB4689B6F92F6E6D5C93773B4844AEF102E7A3E653D1981A1D99073270B16C082C7B7FE909465831A72`
SSDEEP | `96:bzam5S/tfZOWkcDLEp2TyIRoJoPcDGjs0nt+UFoiNVRrDJFMVW9EWUZhHWwP2f:6m56rDaGRomx+UFoiNVRb0WWxW9`

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
* Serial: `330000023241FB59996DCC4DFF000000000232`
* Thumbprint: `FF82BC38E1DA5E596DF374C53E3617F7EDA36B06`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: regedt32.exe
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.18362.1 (WinBuild.160101.0800)
* Product Version: 10.0.18362.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Windows\SysWOW64\regedt32.exe](regedt32.exe-1F64004A05B6B683C49E877084CFF97E.md) | 68
[C:\Windows\SysWOW64\regedt32.exe](regedt32.exe-49E9EA6F79338B350A8B23CEA47D1A86.md) | 66

## Possible Misuse

*The following table contains possible examples of `regedt32.exe` being misused. While `regedt32.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_grizzlybear_uscert.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_grizzlybear_uscert.yar) |       $a3 = "regedt32.exe" wide nocase | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)



MIT License. Copyright (c) 2020 Strontic.


