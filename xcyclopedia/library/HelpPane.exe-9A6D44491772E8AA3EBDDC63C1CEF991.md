---
title: HelpPane.exe | Microsoft Help and Support
---

# HelpPane.exe 

* File Path: `C:\Windows\HelpPane.exe`
* Description: Microsoft Help and Support

## Hashes

Type | Hash
-- | --
MD5 | `9A6D44491772E8AA3EBDDC63C1CEF991`
SHA1 | `2E5284A0574F5B17ADF2C5105DC0F598919BD92D`
SHA256 | `587943F7A42FC21D636B3BAE0CAD17D66E9AA919F0689730A01A77035F7BD767`
SHA384 | `AF7ED6366A9BE1C185896D69BD25FACA7D16699CF8E09030B26A20098568E740C2028AA234BE187AC32A6D4DEFFC26BB`
SHA512 | `A1917A06606697EABBA0A73332DFAFD3CA7D44A0F3F5AE887AB0A5C219F49803A59F690FEE7F11BAB21435CAE57A28857366CC4CAFD76AF6FAF916C599F78675`
SSDEEP | `12288:VGoI5cF1qtS8e5QIjFAPWAlkS+ExyEXsXKPXPiXuHNHGb6bH/zx/GCLW/nh/X:E+qtSZJFA+ekS+El`

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
C:\Windows\System32\RPCRT4.dll |
C:\Windows\System32\sechost.dll |
C:\Windows\System32\ucrtbase.dll |
C:\Windows\System32\win32u.dll |


## Signature

* Status: Signature verified.
* Serial: `330000026551AE1BBD005CBFBD000000000265`
* Thumbprint: `E168609353F30FF2373157B4EB8CD519D07A2BFF`
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

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\WINDOWS\HelpPane.exe](HelpPane.exe-67094590E3D57130C587CD6D8AFB6597.md) | 61
[C:\windows\HelpPane.exe](HelpPane.exe-95DBA7370490F85BD8A48B913A3D8541.md) | 58
[C:\Windows\HelpPane.exe](HelpPane.exe-CB8609764B0908853541EB4718ECE471.md) | 50
[C:\Windows\HelpPane.exe](HelpPane.exe-E8B796A523D2B63A9C7BB0576DFE793E.md) | 58

## Possible Misuse

*The following table contains possible examples of `HelpPane.exe` being misused. While `HelpPane.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_user_driver_loaded.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/builtin/win_user_driver_loaded.yml) | `- '*\Windows\HelpPane.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020 Strontic.


