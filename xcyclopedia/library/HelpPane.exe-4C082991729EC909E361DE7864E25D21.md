---
title: HelpPane.exe | Microsoft Help and Support
excerpt: What is HelpPane.exe?
---

# HelpPane.exe 

* File Path: `C:\WINDOWS\HelpPane.exe`
* Description: Microsoft Help and Support

## Hashes

Type | Hash
-- | --
MD5 | `4C082991729EC909E361DE7864E25D21`
SHA1 | `70E89DF8E4ACB8B64DEE585FA95335874C7F4762`
SHA256 | `C78ED77036D2EACC60052A51DFDD1140E3C7607385669787F9B0BAB1609614A0`
SHA384 | `869A0F89B8D2502E6887FA2E76CAB9B118B94A7A5533E8FFA0AA8ED07584CF9DCB4D7364E5C6347292B88536758FA079`
SHA512 | `0348F4C34AD8F473F98AA4A619B3068EBC1C7153590E23D0C911E52BDDA28D672F440C690854B5B3F1A6ADD483A7D3B0D1E0546C39A08946480AA071A42AAF55`
SSDEEP | `12288:CcpfTBts/f729oCs+DeyvX8o4o3PQesSFyQZUsN5gAPs+XKPXPiXuHNHGb6bH/zu:CcpfTA/EI+Sy/8o4UPQesSFyqxgAPs`
IMP | `2C182B2462698DA85D486D71D6B1A6D3`
PESHA1 | `E269B066733EA2E793DB56BBEC6D89B2A0543E67`
PE256 | `1F2BD526231E77B4737C999B4E8778C08D772830296F5F4D32F6D1EBE2A10C85`

## Runtime Data

### Loaded Modules:

Path |
-- |
C:\WINDOWS\HelpPane.exe |
C:\WINDOWS\SYSTEM32\ntdll.dll |


## Signature

* Status: Signature verified.
* Serial: `33000002ED2C45E4C145CF48440000000002ED`
* Thumbprint: `312860D2047EB81F8F58C29FF19ECDB4C634CF6A`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: HelpPane.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.22000.1 (WinBuild.160101.0800)
* Product Version: 10.0.22000.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/73
* VirusTotal Link: https://www.virustotal.com/gui/file/c78ed77036d2eacc60052a51dfdd1140e3c7607385669787f9b0bab1609614a0/detection

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\WINDOWS\HelpPane.exe](HelpPane.exe-67094590E3D57130C587CD6D8AFB6597.md) | 44
[C:\Windows\HelpPane.exe](HelpPane.exe-7E8FAEC2E175C8B45B6D380A6A4C9503.md) | 41
[C:\windows\HelpPane.exe](HelpPane.exe-95DBA7370490F85BD8A48B913A3D8541.md) | 40
[C:\Windows\HelpPane.exe](HelpPane.exe-9A6D44491772E8AA3EBDDC63C1CEF991.md) | 43
[C:\Windows\HelpPane.exe](HelpPane.exe-CB8609764B0908853541EB4718ECE471.md) | 40
[C:\Windows\HelpPane.exe](HelpPane.exe-E8B796A523D2B63A9C7BB0576DFE793E.md) | 38

## Possible Misuse

*The following table contains possible examples of `HelpPane.exe` being misused. While `HelpPane.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_user_driver_loaded.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/builtin/win_user_driver_loaded.yml) | `- '\Windows\HelpPane.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020-2021 Strontic.


