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
MD5 | `21A5E8E802DE750575AE1FE9EB4CCBFA`
SHA1 | `14B5F144402DD793958799EF9E0EB25F3C20597C`
SHA256 | `8E0AFE17637281A257CA5BCAE90CE4AA9EF4E9C2EC57B16DFDA08B27DCC6C72F`
SHA384 | `3D5BE37DA429158D35207C1C9BC814D911F7BACD144B44564D20D67DE29665D979400030DB554A3DD4869C0656E919F0`
SHA512 | `EC8316EC73DDF85C33E09A827F2B50FBA1DF371B7200F2EC44F6C89047E2939F36FB34D15D0E11A6B613177F14D555F28AD2732A4443C6C85589601B6C73405C`
SSDEEP | `192:E2ry5uafCNQdQ54r1yQ7CuMKzgNi6xtU/1EWQxW:E2ujS2RF7CucNi8tQEWQxW`
IMP | `A3060EC916831020104FAE5BC9414975`
PESHA1 | `C02C998DE32B4D4B53710F5E5BA504FB6743FA6B`
PE256 | `5342162CB00EB324773ADB05BF2D2981859EB1068CBCA95F7E27EE843BC99735`

## Runtime Data

### Child Processes:
regedit.exe

### Loaded Modules:

Path |
-- |
C:\Windows\System32\advapi32.dll |
C:\Windows\System32\bcryptPrimitives.dll |
C:\Windows\System32\cfgmgr32.dll |
C:\Windows\System32\combase.dll |
C:\Windows\System32\cryptsp.dll |
C:\Windows\System32\GDI32.dll |
C:\Windows\System32\gdi32full.dll |
C:\Windows\System32\kernel.appcore.dll |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\System32\msvcp_win.dll |
C:\Windows\System32\msvcrt.dll |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\powrprof.dll |
C:\Windows\System32\profapi.dll |
C:\Windows\system32\regedt32.exe |
C:\Windows\System32\RPCRT4.dll |
C:\Windows\System32\sechost.dll |
C:\Windows\System32\shcore.dll |
C:\Windows\System32\SHELL32.dll |
C:\Windows\System32\shlwapi.dll |
C:\Windows\System32\ucrtbase.dll |
C:\Windows\System32\USER32.dll |
C:\Windows\System32\win32u.dll |
C:\Windows\System32\windows.storage.dll |


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
* File Version: 10.0.17763.1 (WinBuild.160101.0800)
* Product Version: 10.0.17763.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/67
* VirusTotal Link: https://www.virustotal.com/gui/file/8e0afe17637281a257ca5bcae90ce4aa9ef4e9c2ec57b16dfda08b27dcc6c72f/detection/

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\WINDOWS\system32\regedt32.exe](regedt32.exe-A7F7948EAA6287A29805FFD997E4016F.md) | 60

## Possible Misuse

*The following table contains possible examples of `regedt32.exe` being misused. While `regedt32.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_grizzlybear_uscert.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_grizzlybear_uscert.yar) | $a3 = "regedt32.exe" wide nocase | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)



MIT License. Copyright (c) 2020-2021 Strontic.


