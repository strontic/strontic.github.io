---
title: PresentationHost.exe | Windows Presentation Foundation Host
---

# PresentationHost.exe 

* File Path: `C:\Windows\SysWOW64\PresentationHost.exe`
* Description: Windows Presentation Foundation Host
* Comments: Flavor=Retail

## Hashes

Type | Hash
-- | --
MD5 | `C6671F8B9F073785FD617661AD1F1C45`
SHA1 | `DA141EC60E3CE6CC8A9CF60D13C4DEB6CB105B4A`
SHA256 | `D9C533B6109160ABBF139D83C438806563E212D5C877192B64E4304806626C0A`
SHA384 | `88AE0D8BA707375F80B836041B9E8C6F77AC01E5AAD33ED6DADD60D6259631ABFC7D460AB539DC74150F3EDE879E9469`
SHA512 | `DC2D3A9E766F46DC5FC3296B2AC17642234BE1CC87EAA83EC7994C68915AF31CD5FE7CA7B561253EDAAE775E669E9D8AF926A0C20F3634037AF7A40257B09DBE`
SSDEEP | `6144:A0z2luCY78kez5KNXwy3Odjp19k5KNXf:AC2lu97ZQKVwy3OdLaKV`

## Runtime Data

### Usage (stdout):
```Batchfile

```

### Usage (stderr):
```Batchfile

```

### Child Processes:
iexplore.exe

## Signature

* Status: Signature verified.
* Serial: `330000023241FB59996DCC4DFF000000000232`
* Thumbprint: `FF82BC38E1DA5E596DF374C53E3617F7EDA36B06`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: PresentationHost.exe.mui
* Product Name: Microsoft .NET Framework
* Company Name: Microsoft Corporation
* File Version: 4.0.41210.0 built by: Main
* Product Version: 4.0.41210.0
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation.  All rights reserved.

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Windows\system32\PresentationHost.exe](PresentationHost.exe-3DD3F827425D39663544135A427CEC92.md) | 65
[C:\WINDOWS\system32\PresentationHost.exe](PresentationHost.exe-49FA711824925D5FA0286A7FDE8C1821.md) | 61
[C:\Windows\system32\PresentationHost.exe](PresentationHost.exe-EF27D65B92D89E8175E6751A57ED9D93.md) | 66
[C:\Windows\SysWOW64\PresentationHost.exe](PresentationHost.exe-7DB413989BDDFD23AF251B26FC9F6055.md) | 63
[C:\WINDOWS\SysWOW64\PresentationHost.exe](PresentationHost.exe-A1204EFC65BFBF5198A23CB21E1C0562.md) | 69

## Possible Misuse

*The following table contains possible examples of `PresentationHost.exe` being misused. While `PresentationHost.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Presentationhost.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Presentationhost.yml) | `Name: Presentationhost.exe` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Presentationhost.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Presentationhost.yml) | `  - Command: Presentationhost.exe C:\temp\Evil.xbap` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Presentationhost.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Presentationhost.yml) | `  - Path: C:\Windows\System32\Presentationhost.exe` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Presentationhost.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Presentationhost.yml) | `  - Path: C:\Windows\SysWOW64\Presentationhost.exe` | 



MIT License. Copyright (c) 2020 Strontic.


