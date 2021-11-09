---
title: write.exe | Windows Write
excerpt: What is write.exe?
---

# write.exe 

* File Path: `C:\WINDOWS\SysWOW64\write.exe`
* Description: Windows Write

## Hashes

Type | Hash
-- | --
MD5 | `6F738A98257D152943A9E5DFAE1FBC44`
SHA1 | `C3D20AEB11E43042FB5CBC8C8BBCFB714DAF8F71`
SHA256 | `3875DD026772C4B2169F3001C25A169E80161CD5C405C24D4FFA07B79D5FCD57`
SHA384 | `0F1CCC71F6A7AE7F28CE469C5768A84D3924EA9346F790DC418DDF5F5761D9E9375A4364A307B51CE01BA4E54F0F8C83`
SHA512 | `5E688CE7978E5AD7F3C1EA79C7A792BD7D51B65390BE4159D0BF4214323AB748698140ABAD3356D7AD47C9BDA50D07891AE7A25371EA31643E74230A0CB46CD9`
SSDEEP | `96:eTn1wERGn9dkR2RhwFxDWzgDgx1qJ+bghguDJdMi2bKveLrxuJRdBbEWFOWw:yn1wERAmaHoJ+bghgcPuxu/UWFOW`
IMP | `B05C7142E6016FF931CDC4142BE82084`
PESHA1 | `1BD6C0E21558B70C9BDAD627E0C8FAAE69510880`
PE256 | `D79DCFC982A5BF5CB24D57C1E8073AA38A1AAA9CFE260B6DA414C18A85F9C67F`

## Runtime Data

### Child Processes:
wordpad.exe

### Loaded Modules:

Path |
-- |
C:\WINDOWS\SYSTEM32\ntdll.dll |
C:\WINDOWS\System32\wow64.dll |
C:\WINDOWS\System32\wow64base.dll |
C:\WINDOWS\System32\wow64con.dll |
C:\WINDOWS\System32\wow64cpu.dll |
C:\WINDOWS\System32\wow64win.dll |
C:\WINDOWS\SysWOW64\write.exe |


## Signature

* Status: Signature verified.
* Serial: `33000002ED2C45E4C145CF48440000000002ED`
* Thumbprint: `312860D2047EB81F8F58C29FF19ECDB4C634CF6A`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: write
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.22000.1 (WinBuild.160101.0800)
* Product Version: 10.0.22000.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/73
* VirusTotal Link: https://www.virustotal.com/gui/file/3875dd026772c4b2169f3001c25a169e80161cd5c405c24d4ffa07b79d5fcd57/detection

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\WINDOWS\system32\write.exe](write.exe-1BE2CA2A358E1BA20E1EE09EE663B7EE.md) | 43
[C:\windows\SysWOW64\write.exe](write.exe-1EFA647F97009893CC54BD677751A958.md) | 43
[C:\Windows\SysWOW64\write.exe](write.exe-3D6FDBA2878656FA9ECB81F6ECE45703.md) | 54
[C:\WINDOWS\SysWOW64\write.exe](write.exe-7FBA1268E8C8AEC66A7BF9420F54A745.md) | 58
[C:\Windows\SysWOW64\write.exe](write.exe-ED73F0253A4C10F6B7C221FF6E8BD8B4.md) | 47
[C:\WINDOWS\write.exe](write.exe-1BE2CA2A358E1BA20E1EE09EE663B7EE.md) | 43

## Possible Misuse

*The following table contains possible examples of `write.exe` being misused. While `write.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_spoolsv_child_processes.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_spoolsv_child_processes.yml) | `- \write.exe`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Tracker.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OtherMSBinaries/Tracker.yml) | `- Command: Tracker.exe /d .\calc.dll /c C:\Windows\write.exe`{:.highlight .language-yaml} | 



MIT License. Copyright (c) 2020-2021 Strontic.


