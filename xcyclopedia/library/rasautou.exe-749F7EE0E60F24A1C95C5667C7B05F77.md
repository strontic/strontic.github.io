---
title: rasautou.exe | Remote Access Dialer
---

# rasautou.exe 

* File Path: `C:\Windows\system32\rasautou.exe`
* Description: Remote Access Dialer

## Hashes

Type | Hash
-- | --
MD5 | `749F7EE0E60F24A1C95C5667C7B05F77`
SHA1 | `47C97952A612B2542A9EFEF8E243D0D26AE36616`
SHA256 | `3784BC31BF8A72D3D8AF7726F6944B7C8C17AC6D797654830F462A4A3A33A013`
SHA384 | `FE7D95C5E1882DAC1CB2B8DCB227F62254C06658C13FB3B9C9AA3A30619F3313292D73A8CD5B93285FE117D32CA5CB20`
SHA512 | `46BDD2FDECD54962DCC8E51A20B92334C7984B6DB7B2CA0532CB973CF1FE559ACC23DB8747BC4C5F84995D0DE48DC6E856FF221CDE9E49F1A79A5A6E003565D1`
SSDEEP | `384:EsTMuRLrDeL9wSDT7VUyoZyTw5PYcWHBW:EQ/D5SRU/fZY9`

## Runtime Data

### Usage (stdout):
```Batchfile
Usage: rasautou [-f phonebook] [-a address] [-e entry] [-s]

```

## Signature

* Status: Signature verified.
* Serial: `330000023241FB59996DCC4DFF000000000232`
* Thumbprint: `FF82BC38E1DA5E596DF374C53E3617F7EDA36B06`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: rasdlui.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.


## Possible Misuse

*The following table contains possible examples of `rasautou.exe` being misused. While `rasautou.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Rasautou.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Rasautou.yml) | `Name: Rasautou.exe` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Rasautou.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Rasautou.yml) | `  - Command: rasautou -d powershell.dll -p powershell -a a -e e ` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Rasautou.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Rasautou.yml) | `  - Path: C:\Windows\System32\rasautou.exe` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Rasautou.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Rasautou.yml) | ` - IOC: rasautou.exe command line containing -d and -p` | 



MIT License. Copyright (c) 2020 Strontic.


