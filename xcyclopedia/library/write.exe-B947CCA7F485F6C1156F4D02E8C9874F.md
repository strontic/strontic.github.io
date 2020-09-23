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
MD5 | `B947CCA7F485F6C1156F4D02E8C9874F`
SHA1 | `9F184E48F17F104C6A476687E8E760A65A0326B5`
SHA256 | `A70D52EDA892EDC073932B462CC367CDBFBACE3F4196857D8D4FA869A13DE792`
SHA384 | `54333EC10CFCAB874257FA46DCF5E9F30D3F982B194D32C4022D7533AB04356D7093EF6B2552D164126EF9B5D2AB830D`
SHA512 | `28C6FF32BC94AAD8B201E469F854DDE32CAD9EB2E7A80ED858AC2FF99648312CECCA06918BCE96E8D905D52D5EBEE076BD08D957F7933602C0C79D93EAD20EE3`
SSDEEP | `192:ZV89t7hglDCS8O3GbXdYFWihWxu/sWGOW:ZVM7hceSP3IXioxu/sWGOW`
IMP | `90A23F469BA0443719430CBA4569B220`
PESHA1 | `A4F66FA28EB11A219C177052029687C0C3E983CE`
PE256 | `C0B77A27E77A38B21724E115C8BF3C8EF59F820DAF3AE4F83084218C730DA403`

## Runtime Data

### Child Processes:
wordpad.exe

### Loaded Modules:

Path |
-- |
C:\Windows\System32\GDI32.dll |
C:\Windows\System32\gdi32full.dll |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\System32\msvcp_win.dll |
C:\Windows\System32\msvcrt.dll |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\SHELL32.dll |
C:\Windows\System32\ucrtbase.dll |
C:\Windows\System32\USER32.dll |
C:\Windows\System32\win32u.dll |
C:\Windows\system32\write.exe |


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: write
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/68
* VirusTotal Link: https://www.virustotal.com/gui/file/a70d52eda892edc073932b462cc367cdbfbace3f4196857d8d4fa869a13de792/detection/

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Windows\system32\write.exe](write.exe-E87C6A38E61A712C48025A6AD54C1113.md) | 35
[C:\Windows\SysWOW64\write.exe](write.exe-3D6FDBA2878656FA9ECB81F6ECE45703.md) | 43
[C:\Windows\write.exe](write.exe-B947CCA7F485F6C1156F4D02E8C9874F.md) | 100

## Possible Misuse

*The following table contains possible examples of `write.exe` being misused. While `write.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Tracker.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OtherMSBinaries/Tracker.yml) | `- Command: Tracker.exe /d .\calc.dll /c C:\Windows\write.exe` | 



MIT License. Copyright (c) 2020 Strontic.


