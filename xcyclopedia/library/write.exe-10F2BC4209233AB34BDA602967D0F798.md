---
title: write.exe | Windows Write
excerpt: What is write.exe?
---

# write.exe 

* File Path: `C:\Windows\system32\write.exe`
* Description: Windows Write

## Hashes

Type | Hash
-- | --
MD5 | `10F2BC4209233AB34BDA602967D0F798`
SHA1 | `923BE1A95641EC2BE6F8F7E2CFF51E40C2655D65`
SHA256 | `664256FDE0E3A7C39801D91DD20204250638048E0E3F12C5891A84FFE283680A`
SHA384 | `149D613DFD9FB7A153DD2603D1A93F71B271A9DD4C2FC3C0C4DE09F727F65279FE6DAC7E88162B6FCC13658377BB430C`
SHA512 | `3B57E4832D29071782D9A18B1F1D7D70789368E6DFA10707BE27903DCECBC53A233015F397CAEC1EE896E24CE8273FF791D5946CAD03912E56D107FC3F79BFA6`
SSDEEP | `192:kfN8IBpmrj0DyjZ3NRvWkHbTTHrdguUxhWxu/0WhOW:kCIB20uddBWMb9Ioxu/0WhOW`
IMP | `90A23F469BA0443719430CBA4569B220`
PESHA1 | `9A77A959845F1EA9C1550BD205B9EE0E2F588A69`
PE256 | `C56A2287601FB53393F35585F4D12C76A740742B8BCA1503F6CA9860BDF60029`

## Runtime Data

### Child Processes:
wordpad.exe

### Loaded Modules:

Path |
-- |
C:\Windows\System32\advapi32.dll |
C:\Windows\System32\bcryptPrimitives.dll |
C:\Windows\System32\cfgmgr32.dll |
C:\Windows\System32\clbcatq.dll |
C:\Windows\System32\combase.dll |
C:\Windows\System32\cryptsp.dll |
C:\Windows\system32\edputil.dll |
C:\Windows\System32\GDI32.dll |
C:\Windows\System32\gdi32full.dll |
C:\Windows\System32\IMM32.DLL |
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
C:\Windows\system32\PROPSYS.dll |
C:\Windows\System32\RPCRT4.dll |
C:\Windows\System32\sechost.dll |
C:\Windows\System32\shcore.dll |
C:\Windows\System32\SHELL32.dll |
C:\Windows\System32\shlwapi.dll |
C:\Windows\System32\ucrtbase.dll |
C:\Windows\System32\USER32.dll |
C:\Windows\system32\uxtheme.dll |
C:\Windows\System32\win32u.dll |
C:\Windows\System32\windows.storage.dll |
C:\Windows\system32\write.exe |


## Signature

* Status: Signature verified.
* Serial: `33000001C422B2F79B793DACB20000000001C4`
* Thumbprint: `AE9C1AE54763822EEC42474983D8B635116C8452`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: write
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.17763.1 (WinBuild.160101.0800)
* Product Version: 10.0.17763.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/71
* VirusTotal Link: https://www.virustotal.com/gui/file/664256fde0e3a7c39801d91dd20204250638048e0e3f12c5891a84ffe283680a/detection/

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Windows\SysWOW64\write.exe](write.exe-55A288C36EBDFBA8F977307A8A2619D1.md) | 41
[C:\Windows\write.exe](write.exe-10F2BC4209233AB34BDA602967D0F798.md) | 100

## Possible Misuse

*The following table contains possible examples of `write.exe` being misused. While `write.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Tracker.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OtherMSBinaries/Tracker.yml) | `- Command: Tracker.exe /d .\calc.dll /c C:\Windows\write.exe` | 



MIT License. Copyright (c) 2020 Strontic.


