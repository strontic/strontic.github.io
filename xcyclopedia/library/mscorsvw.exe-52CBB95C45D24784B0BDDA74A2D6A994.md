---
title: mscorsvw.exe | .NET Runtime Optimization Service
excerpt: What is mscorsvw.exe?
---

# mscorsvw.exe 

* File Path: `C:\Windows\Microsoft.NET\Framework64\v4.0.30319\mscorsvw.exe`
* Description: .NET Runtime Optimization Service
* Comments: Flavor=Retail


## Hashes

Type | Hash
-- | --
MD5 | `52CBB95C45D24784B0BDDA74A2D6A994`
SHA1 | `9E4EA76C491D88F6BC941EE20F8E40E2D7E1BADE`
SHA256 | `1974BA6039355E657E78C97B5AC21E83087E43AAC9FB40DF5F0BC567D822A4A1`
SHA384 | `C2BB0CE45C267E6A51D9F209B0D201DC2A2B3A5B06A701AA7F010238A156624196978B7D91398CDDB3EA9593B97A044F`
SHA512 | `6B71DAA38FDB03A4D593FB63EFD7205000D2143581ECDEE37C307326BDEC3EA2100719E8178BCE55F4CF407E691DC0256B8DC30BD40C5BFAB26CBD0BE6AAB02D`
SSDEEP | `1536:zU9CKhO4uG8KStHYEyQaEuK9zNVnlK1WDh/hUeZOr2u+b+0czptbtC2dpc:zaD86ExaE1Jnk1QhZUeZOBtrzptLpc`
IMP | `B6FFAAE8AD145B27B7F899BF03C8EEE0`
PESHA1 | `40253C4563CD4ABECFED1D8C7676B831EA0200F1`
PE256 | `0BDAFBB8AFC14213E52255F5F9168834FF62C419D683B7F01A7F1EFD7ADA7493`

## Runtime Data

### Loaded Modules:

Path |
-- |
C:\Windows\Microsoft.NET\Framework64\v4.0.30319\mscorsvw.exe |
C:\Windows\System32\ADVAPI32.dll |
C:\Windows\System32\combase.dll |
C:\Windows\System32\GDI32.dll |
C:\Windows\System32\gdi32full.dll |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\SYSTEM32\mscoree.dll |
C:\Windows\System32\msvcp_win.dll |
C:\Windows\System32\msvcrt.dll |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\ole32.dll |
C:\Windows\System32\OLEAUT32.dll |
C:\Windows\System32\RPCRT4.dll |
C:\Windows\System32\sechost.dll |
C:\Windows\System32\ucrtbase.dll |
C:\Windows\SYSTEM32\ucrtbase_clr0400.dll |
C:\Windows\System32\USER32.dll |
C:\Windows\SYSTEM32\VCRUNTIME140_CLR0400.dll |
C:\Windows\System32\win32u.dll |


## Signature

* Status: Signature verified.
* Serial: `330000023241FB59996DCC4DFF000000000232`
* Thumbprint: `FF82BC38E1DA5E596DF374C53E3617F7EDA36B06`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: mscorsvw.exe
* Product Name: Microsoft .NET Framework
* Company Name: Microsoft Corporation
* File Version: 4.8.4084.0 built by: NET48REL1
* Product Version: 4.8.4084.0
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation.  All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/76
* VirusTotal Link: https://www.virustotal.com/gui/file/1974ba6039355e657e78c97b5ac21e83087e43aac9fb40df5f0bc567d822a4a1/detection


## Possible Misuse

*The following table contains possible examples of `mscorsvw.exe` being misused. While `mscorsvw.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_in_memory_powershell.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/image_load/sysmon_in_memory_powershell.yml) | `- '\mscorsvw.exe'  # c:\Windows\Microsoft.NET\Framework64\v4.0.30319\mscorsw.exe for instance` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020 Strontic.


