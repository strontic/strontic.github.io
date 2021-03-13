---
title: slui.exe | Windows Activation Client
excerpt: What is slui.exe?
---

# slui.exe 

* File Path: `C:\Windows\system32\slui.exe`
* Description: Windows Activation Client

## Hashes

Type | Hash
-- | --
MD5 | `10B472E52F5F0592076D7E093858A2C3`
SHA1 | `9CBB8EAB50D0C00616044CBF04BFE2959C25EF7C`
SHA256 | `A9E691D1E6763B8895168E8EB3FCC7F9A072C7E46C216F4DEDA3F246EDBC3438`
SHA384 | `BDEEA7254844CB2C7407E889498F0EE3B5A56E22A1FFD22EB7E96A36CF0338FCA952D5489E3F4B54FAD34C51173A83D3`
SHA512 | `DBE57A42DD234ACCE10DEE8D74F7CD235E789E3ACC8B886A58267C21A200F04F4F2EAC4DE248247F12164463EEFAD971E96AF5677301904C7C29DF9EE94120F3`
SSDEEP | `6144:RVxpC1u+z53bQeILDS7LZAwHfMqY/W5R02qO7VKCyWQp:rxIptMX26Jq3nyR`
IMP | `F2014F5555EEFEC494A169DEEBA0FEE5`
PESHA1 | `67C31874A6AE8082E7B80C5602B80C49F30A54CF`
PE256 | `8B139592FB16114EB1310E04257B2C8A0A5D4E6994A3453DC58836C64F0E6E99`

## Runtime Data

### Loaded Modules:

Path |
-- |
C:\Windows\System32\ADVAPI32.dll |
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
C:\Windows\System32\ole32.dll |
C:\Windows\System32\OLEAUT32.dll |
C:\Windows\System32\powrprof.dll |
C:\Windows\System32\profapi.dll |
C:\Windows\System32\RPCRT4.dll |
C:\Windows\System32\sechost.dll |
C:\Windows\System32\shcore.dll |
C:\Windows\System32\SHELL32.dll |
C:\Windows\System32\shlwapi.dll |
C:\Windows\system32\SLC.dll |
C:\Windows\system32\slui.exe |
C:\Windows\system32\sppc.dll |
C:\Windows\System32\ucrtbase.dll |
C:\Windows\System32\USER32.dll |
C:\Windows\System32\win32u.dll |
C:\Windows\system32\WINBRAND.dll |
C:\Windows\System32\windows.storage.dll |
C:\Windows\system32\WTSAPI32.dll |


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: slui.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.17763.1 (WinBuild.160101.0800)
* Product Version: 10.0.17763.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/71
* VirusTotal Link: https://www.virustotal.com/gui/file/a9e691d1e6763b8895168e8eb3fcc7f9a072c7e46c216f4deda3f246edbc3438/detection/

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\WINDOWS\system32\slui.exe](slui.exe-0A26DC4E016E6614991E26CE20DC9466.md) | 47
[C:\windows\system32\slui.exe](slui.exe-2D8FD9EC935EE270744B5F13F881D16E.md) | 55
[C:\Windows\system32\slui.exe](slui.exe-3A171EFE71231ACB1B45E1FC00671EDF.md) | 55
[C:\Windows\system32\slui.exe](slui.exe-68974B8AD1EE9B8F59E93A799474A339.md) | 97
[C:\Windows\system32\slui.exe](slui.exe-CAF88C49F33FA27D956BC728A041346D.md) | 99
[C:\Windows\system32\sppcommdlg.dll](sppcommdlg.dll-25059CB01909EFC95C978A189C24C20B.md) | 38

## Possible Misuse

*The following table contains possible examples of `slui.exe` being misused. While `slui.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[stockpile](https://github.com/mitre/stockpile) | [b7344901-0b02-4ead-baf6-e3f629ed545f.yml](https://github.com/mitre/stockpile/blob/master/data/abilities/privilege-escalation/b7344901-0b02-4ead-baf6-e3f629ed545f.yml) | `description: executes the slui exe file handler hijack`{:.highlight .language-yaml} | [Apache-2.0](https://github.com/mitre/stockpile/blob/master/LICENSE)



MIT License. Copyright (c) 2020-2021 Strontic.


