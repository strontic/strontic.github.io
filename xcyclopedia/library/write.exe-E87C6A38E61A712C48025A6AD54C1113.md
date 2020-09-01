---
title: write.exe | Windows Write
---

# write.exe 

* File Path: `C:\Windows\system32\write.exe`
* Description: Windows Write

## Hashes

Type | Hash
-- | --
MD5 | `E87C6A38E61A712C48025A6AD54C1113`
SHA1 | `C21DC47D57437909F9CAC14E786C77E9F3E78E56`
SHA256 | `7E3485F5EDD48FFCE37B0B0B735CD97F5AB514AA8DC4D6BC16CC4C40FB3FB570`
SHA384 | `E623B48D80BC55FDA97F2D6FB19F4AE35A05A810B7304D772C4D06641836D8B60CC3FBCCE563E37EB8E59C65C08FEF55`
SHA512 | `FF4B5B47E1B6E740F81C8914938FD743E0D4AFE830885234BCB3158CC6EC2DDBCBB2F68C2316BB2566B40AD3682A8E5294DD621BBA19DFCE38C06A8A97EC7117`
SSDEEP | `192:LcP+gc9TqFIiyyBiZoCirdhH1rs5hWxu/sWFOW:L1gcEFly32v3Koxu/sWFOW`

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
* Serial: `33000000BCE120FDD27CC8EE930000000000BC`
* Thumbprint: `E85459B23C232DB3CB94C7A56D47678F58E8E51E`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: write
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.14393.0 (rs1_release.160715-1616)
* Product Version: 10.0.14393.0
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Windows\system32\write.exe](write.exe-B947CCA7F485F6C1156F4D02E8C9874F.md) | 35
[C:\Windows\SysWOW64\write.exe](write.exe-ED73F0253A4C10F6B7C221FF6E8BD8B4.md) | 36
[C:\Windows\write.exe](write.exe-B947CCA7F485F6C1156F4D02E8C9874F.md) | 35

## Possible Misuse

*The following table contains possible examples of `write.exe` being misused. While `write.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Tracker.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OtherMSBinaries/Tracker.yml) | `  - Command: Tracker.exe /d .\calc.dll /c C:\Windows\write.exe` | 



MIT License. Copyright (c) 2020 Strontic.


