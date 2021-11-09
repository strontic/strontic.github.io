---
title: HelpPane.exe | Microsoft Help and Support
excerpt: What is HelpPane.exe?
---

# HelpPane.exe 

* File Path: `C:\Windows\HelpPane.exe`
* Description: Microsoft Help and Support

## Hashes

Type | Hash
-- | --
MD5 | `7E8FAEC2E175C8B45B6D380A6A4C9503`
SHA1 | `54257C75CCC39038706F9C08E896989E1B482BA7`
SHA256 | `42C2C94EDF6F5E2E75556F455039CACD8A23BC825E8BEEF864B8572C3007DB5A`
SHA384 | `732D576F79CE082D4F26519BE43EABC6974933196B7FBDA77BC3F6D1C9A838FBE1E4A56EECB7E0720963A0C803AF2437`
SHA512 | `38780489F15A52B620ECAB577F6D4190E6D639EF1C433A063F08A147284722DB6A207A3A190FBCE3D9F8F6C70F5B5180DCFDEE3FE100DBA32BB12A5B476B3597`
SSDEEP | `12288:DGrARa7TAPZfMiuU9YAioFOVdgnFoA7aXKPXPiXuHNHGb6bH/zx/GCLW/nh/X:DBwmZ33qAioFmymA7`
IMP | `A71B59777FDF47EB06D8F9729F3BF423`
PESHA1 | `BBE0321CF1D4585B05C6B9CA0CCAC0BC42904989`
PE256 | `3A54D94877B8F5D34E881B4BC626BF7FD02C19DECB23B64260823F5A3CEBFD75`

## Runtime Data

### Loaded Modules:

Path |
-- |
C:\Windows\HelpPane.exe |
C:\Windows\System32\ADVAPI32.dll |
C:\Windows\System32\GDI32.dll |
C:\Windows\System32\gdi32full.dll |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\System32\msvcp_win.dll |
C:\Windows\System32\msvcrt.dll |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\ole32.dll |
C:\Windows\System32\RPCRT4.dll |
C:\Windows\System32\sechost.dll |
C:\Windows\System32\ucrtbase.dll |
C:\Windows\System32\USER32.dll |
C:\Windows\System32\win32u.dll |


## Signature

* Status: Signature verified.
* Serial: `33000002EC6579AD1E670890130000000002EC`
* Thumbprint: `F7C2F2C96A328C13CDA8CDB57B715BDEA2CBD1D9`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: HelpPane.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/74
* VirusTotal Link: https://www.virustotal.com/gui/file/42c2c94edf6f5e2e75556f455039cacd8a23bc825e8beef864b8572c3007db5a/detection

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\WINDOWS\HelpPane.exe](HelpPane.exe-4C082991729EC909E361DE7864E25D21.md) | 41
[C:\WINDOWS\HelpPane.exe](HelpPane.exe-67094590E3D57130C587CD6D8AFB6597.md) | 63
[C:\windows\HelpPane.exe](HelpPane.exe-95DBA7370490F85BD8A48B913A3D8541.md) | 63
[C:\Windows\HelpPane.exe](HelpPane.exe-9A6D44491772E8AA3EBDDC63C1CEF991.md) | 57
[C:\Windows\HelpPane.exe](HelpPane.exe-CB8609764B0908853541EB4718ECE471.md) | 52
[C:\Windows\HelpPane.exe](HelpPane.exe-E8B796A523D2B63A9C7BB0576DFE793E.md) | 60

## Possible Misuse

*The following table contains possible examples of `HelpPane.exe` being misused. While `HelpPane.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_user_driver_loaded.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/builtin/win_user_driver_loaded.yml) | `- '\Windows\HelpPane.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020-2021 Strontic.


