---
title: AppVClient.exe | Microsoft Application Virtualization Client Service
excerpt: What is AppVClient.exe?
---

# AppVClient.exe 

* File Path: `C:\Windows\system32\AppVClient.exe`
* Description: Microsoft Application Virtualization Client Service

## Hashes

Type | Hash
-- | --
MD5 | `64650F0876BE00054EA65B7C3A081450`
SHA1 | `488520C688D96219E057D54942DBCC23D7F5C881`
SHA256 | `B9D349C732032C405415B2F85A9365526D3EAE3007E404042957B73D647F534A`
SHA384 | `BE6EA327942ECD8DF49CCB3EC79D48FF36B45B5FD06FA0671931092F970FB244D5377C3E0539CDDFAE9CB61877E42AD1`
SHA512 | `B0A5E5DAB0DB46E142F3444E8D003F9D7BA11472CB2733CDEEF97297EAC8BB954A21F4B95C7190146508C0458B5DEF7A95A5EFA0A7CDB93350CB4D6B2ABB431C`
SSDEEP | `12288:EA3NOjSfAJuWjHArR57r/zmCGNUbTNR0MXsJl:EA3uXJdHArR57rmMX0l`

## Runtime Data

### Loaded Modules:

Path |
-- |
C:\Windows\system32\AppVClient.exe |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\SYSTEM32\ntdll.dll |


## Signature

* Status: Signature verified.
* Serial: `330000026551AE1BBD005CBFBD000000000265`
* Thumbprint: `E168609353F30FF2373157B4EB8CD519D07A2BFF`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: AppVClient.exe
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.17763.1007 (WinBuild.160101.0800)
* Product Version: 10.0.17763.1007
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.



## Possible Misuse

*The following table contains possible examples of `AppVClient.exe` being misused. While `AppVClient.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_wmi_spwns_powershell.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_wmi_spwns_powershell.yml) | `- AppvClient` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020 Strontic.


