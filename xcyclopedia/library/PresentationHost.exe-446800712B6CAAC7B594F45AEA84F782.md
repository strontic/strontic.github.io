---
title: PresentationHost.exe | Windows Presentation Foundation Host
excerpt: What is PresentationHost.exe?
---

# PresentationHost.exe 

* File Path: `C:\WINDOWS\system32\PresentationHost.exe`
* Description: Windows Presentation Foundation Host

## Hashes

Type | Hash
-- | --
MD5 | `446800712B6CAAC7B594F45AEA84F782`
SHA1 | `55B9DF2F1090688C79F02751A9A96C346CE105E0`
SHA256 | `BB432C938C36F4127EC91B074CD88D4AAD73EF3947E542DB8295B04052C75D0C`
SHA384 | `BCF5862C16FB0EC7BD778F2CBC7C8468D78C3C779D853838EBA4DE9E1DD6CE12582A0C98A2DA18D80A0BC7EE091FBED5`
SHA512 | `FD9952B899C24553B7C887019D28981C4CE71CEC1D60C9250D07DDDD88EB107910640B2431FD4986AF557EB2CA648E1D7FF6A4C34631D91668A272D3B471A40B`
SSDEEP | `6144:vXhWMcgT1nmZ5k+J1qKNZNgIbUnbO5KNXwy3Odjp19k5KNXf:vXhW9gT1mZpq+ZNVgbGKVwy3OdLaKV`
IMP | `B1C8422BE3A752BDAD4E20658B636E91`
PESHA1 | `69B357ECA418A7A2A251F1DE45E370DF2BED9528`
PE256 | `DCD1579DA5E81F0023C395A3E3D1E158434F494596525F05DAE089962E73A3C5`

## Runtime Data

### Child Processes:
iexplore.exe

### Loaded Modules:

Path |
-- |
C:\WINDOWS\System32\KERNEL32.DLL |
C:\WINDOWS\System32\KERNELBASE.dll |
C:\WINDOWS\SYSTEM32\ntdll.dll |
C:\WINDOWS\system32\PresentationHost.exe |


## Signature

* Status: Signature verified.
* Serial: `33000002ED2C45E4C145CF48440000000002ED`
* Thumbprint: `312860D2047EB81F8F58C29FF19ECDB4C634CF6A`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: PresentationHost.exe
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.22000.1 (WinBuild.160101.0800)
* Product Version: 10.0.22000.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/71
* VirusTotal Link: https://www.virustotal.com/gui/file/bb432c938c36f4127ec91b074cd88d4aad73ef3947e542db8295b04052c75d0c/detection

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Windows\system32\PresentationHost.exe](PresentationHost.exe-193F1CA0ADF261816AC02CFD6553C96D.md) | 52
[C:\windows\system32\PresentationHost.exe](PresentationHost.exe-35200D32C398793D85F900B0273E6F43.md) | 55
[C:\Windows\system32\PresentationHost.exe](PresentationHost.exe-3DD3F827425D39663544135A427CEC92.md) | 55
[C:\WINDOWS\system32\PresentationHost.exe](PresentationHost.exe-49FA711824925D5FA0286A7FDE8C1821.md) | 61
[C:\Windows\system32\PresentationHost.exe](PresentationHost.exe-EF27D65B92D89E8175E6751A57ED9D93.md) | 54
[C:\windows\SysWOW64\PresentationHost.exe](PresentationHost.exe-19F810B1F9ABC04F6E6CB66A2AFB5327.md) | 60
[C:\WINDOWS\SysWOW64\PresentationHost.exe](PresentationHost.exe-5C08493395E7427487B608CE0926F678.md) | 54
[C:\Windows\SysWOW64\PresentationHost.exe](PresentationHost.exe-7DB413989BDDFD23AF251B26FC9F6055.md) | 54
[C:\WINDOWS\SysWOW64\PresentationHost.exe](PresentationHost.exe-A1204EFC65BFBF5198A23CB21E1C0562.md) | 54
[C:\Windows\SysWOW64\PresentationHost.exe](PresentationHost.exe-B73ECB016B35D5B7ACB91125924525E5.md) | 52
[C:\Windows\SysWOW64\PresentationHost.exe](PresentationHost.exe-C6671F8B9F073785FD617661AD1F1C45.md) | 54

## Possible Misuse

*The following table contains possible examples of `PresentationHost.exe` being misused. While `PresentationHost.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Presentationhost.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Presentationhost.yml) | `Name: Presentationhost.exe`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Presentationhost.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Presentationhost.yml) | `- Command: Presentationhost.exe C:\temp\Evil.xbap`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Presentationhost.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Presentationhost.yml) | `- Path: C:\Windows\System32\Presentationhost.exe`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Presentationhost.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Presentationhost.yml) | `- Path: C:\Windows\SysWOW64\Presentationhost.exe`{:.highlight .language-yaml} | 



MIT License. Copyright (c) 2020-2021 Strontic.


