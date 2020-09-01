---
title: Dism.exe | Dism Image Servicing Utility
---

# Dism.exe 

* File Path: `C:\WINDOWS\system32\Dism.exe`
* Description: Dism Image Servicing Utility

## Hashes

Type | Hash
-- | --
MD5 | `666F42B887E9F05A78E048BCC7AC9261`
SHA1 | `26CDB57E1EF5F97A39B2DB4762AC21306CB535DC`
SHA256 | `C32CD1528CD9D3A2D6763357061A85D1E02DA2209377A4EAD1F4F7D7E3C1367C`
SHA384 | `A32F6C3EBC5A1E8C749F4CD795E2625AC99A445836B3884EF338E1D7F2DE87E957D90740FA0EBA26F729B23D274870DF`
SHA512 | `88CEDC8184869DAF21AECB65B4B2EAD952B9AFC53F6DD404BA427924FB289E06DBE50682E7272FA90A64FEE6BD50F54BEAD5BDC4B64702264B6CA1636783541D`
SSDEEP | `6144:sgLBFT2TLLjUQi7fv+KaNMlWExBuTMs2jCrs:GAJCEE2n`

## Runtime Data

### Usage (stdout):
```Batchfile

Error: 740

Elevated permissions are required to run DISM. 
Use an elevated command prompt to complete these tasks.

```

### Loaded Modules:

Path |
-- |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\wow64.dll |
C:\Windows\System32\wow64cpu.dll |
C:\Windows\System32\wow64win.dll |
C:\Windows\SysWOW64\Dism.exe |


## Signature

* Status: Signature verified.
* Serial: `330000023241FB59996DCC4DFF000000000232`
* Thumbprint: `FF82BC38E1DA5E596DF374C53E3617F7EDA36B06`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: DISM.EXE.MUI
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.18362.1 (WinBuild.160101.0800)
* Product Version: 10.0.18362.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.


## Possible Misuse

*The following table contains possible examples of `Dism.exe` being misused. While `Dism.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_user_driver_loaded.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/builtin/win_user_driver_loaded.yml) | `            - '*\Windows\System32\Dism.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020 Strontic.


