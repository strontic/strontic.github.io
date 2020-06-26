---
title: PresentationHost.exe | Windows Presentation Foundation Host
---

# PresentationHost.exe 

* File Path: `C:\Windows\SysWOW64\PresentationHost.exe`
* Description: Windows Presentation Foundation Host
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `7DB413989BDDFD23AF251B26FC9F6055`
SHA1 | `BEC2EBF815BD690BE58408C32D962BCD96144587`
SHA256 | `EF0751761E476E3233666BACB2839EBDC54ABC962841CD92DD87358351402A40`
SHA384 | `C38CB8C56C204D7AF1C3DA01078E54532BCAF28F74FBAAB561A4A268089380CBAE2F118F33C17238BAE7E9D7F783B55B`
SHA512 | `E45E2592FC700C8B3BAC335C72D93598B34C5113EC4B0B936B4A8E35CB24DD802C1348396F513290903486F9FF5B0A71328CA3AC0844C0C012A4A9609916B6F0`
SSDEEP | `6144:GH6JkGUE9rFiZA5KNXwy3Odjp19k5KNXf:rJkibyMKVwy3OdLaKV`

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
* Serial: `33000000BCE120FDD27CC8EE930000000000BC`
* Thumbprint: `E85459B23C232DB3CB94C7A56D47678F58E8E51E`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: PresentationHost.exe
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.14393.0 (rs1_release.160715-1616)
* Product Version: 10.0.14393.0
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Windows\system32\PresentationHost.exe](PresentationHost.exe-3DD3F827425D39663544135A427CEC92.md) | 63
[C:\WINDOWS\system32\PresentationHost.exe](PresentationHost.exe-49FA711824925D5FA0286A7FDE8C1821.md) | 60
[C:\WINDOWS\SysWOW64\PresentationHost.exe](PresentationHost.exe-A1204EFC65BFBF5198A23CB21E1C0562.md) | 61

## Possible Misuse

*The following table contains possible examples of `PresentationHost.exe` being misused. While `PresentationHost.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Presentationhost.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Presentationhost.yml) | `Name: Presentationhost.exe` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Presentationhost.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Presentationhost.yml) | `  - Command: Presentationhost.exe C:\temp\Evil.xbap` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Presentationhost.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Presentationhost.yml) | `  - Path: C:\Windows\System32\Presentationhost.exe` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Presentationhost.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Presentationhost.yml) | `  - Path: C:\Windows\SysWOW64\Presentationhost.exe` | 



MIT License. Copyright (c) 2020 Strontic.


