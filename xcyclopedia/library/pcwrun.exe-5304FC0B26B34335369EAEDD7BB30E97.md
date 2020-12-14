---
title: pcwrun.exe | Program Compatibility Troubleshooter Invoker
excerpt: What is pcwrun.exe?
---

# pcwrun.exe 

* File Path: `C:\Windows\system32\pcwrun.exe`
* Description: Program Compatibility Troubleshooter Invoker

## Hashes

Type | Hash
-- | --
MD5 | `5304FC0B26B34335369EAEDD7BB30E97`
SHA1 | `A194040DD88C66A6C61033A8BA8727E07C8200BC`
SHA256 | `E3D136C667662A2198DA3D45A4637DF1EFE1F61B2B948F421FC0F8EEE6D83C3A`
SHA384 | `A6417550886393FC9A9052BC5DF6F3447F1F28B9AED55116F3B21D83EBF5F00EDEE0BE1FAC2075E22E070FEDF8832100`
SHA512 | `DE582402580A4D87E51AD992625024AC9E6E0E5CD9E4C88C2BFB5608F9DE99FB8BE037E055670BAEB71E2698E3E06CB017882FEF9D9963ED873E386FB39E8C8B`
SSDEEP | `384:9uqm53yj33csvrp6rThI/NfiiJoJ4fA+cWMgW:9+ij33cGrMrwNfiiJcOA+C`
IMP | `B78658A8BFA515AFA2CD46E53317253F`
PESHA1 | `CAC074C20335A643C190F2E08B8B2E30C12DDC76`
PE256 | `792309C4B1874121DD841D2EA0400289FD40FE47DD84B23E4C464C51B4659B95`

## Runtime Data

### Child Processes:
msdt.exe

### Loaded Modules:

Path |
-- |
C:\Windows\System32\combase.dll |
C:\Windows\System32\GDI32.dll |
C:\Windows\System32\gdi32full.dll |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\System32\msvcp_win.dll |
C:\Windows\System32\msvcrt.dll |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\OLEAUT32.dll |
C:\Windows\system32\pcwrun.exe |
C:\Windows\System32\RPCRT4.dll |
C:\Windows\System32\SHELL32.dll |
C:\Windows\System32\SHLWAPI.dll |
C:\Windows\System32\ucrtbase.dll |
C:\Windows\System32\USER32.dll |
C:\Windows\System32\win32u.dll |


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: pcwrun.exe
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/74
* VirusTotal Link: https://www.virustotal.com/gui/file/e3d136c667662a2198da3d45a4637df1efe1f61b2b948f421fc0f8eee6d83c3a/detection


## Possible Misuse

*The following table contains possible examples of `pcwrun.exe` being misused. While `pcwrun.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Pcwrun.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Pcwrun.yml) | `Name: Pcwrun.exe` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Pcwrun.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Pcwrun.yml) | `- Command: Pcwrun.exe c:\temp\beacon.exe` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Pcwrun.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Pcwrun.yml) | `- Path: C:\Windows\System32\pcwrun.exe` | 



MIT License. Copyright (c) 2020 Strontic.


