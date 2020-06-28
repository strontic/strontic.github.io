---
title: rasautou.exe | Remote Access Dialer
---

# rasautou.exe 

* File Path: `C:\Windows\SysWOW64\rasautou.exe`
* Description: Remote Access Dialer
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `81A6467E638E5C15C0C0ABB4DA13DEAD`
SHA1 | `6F3094856E6040A92FAAB8F30B0EC2C6F957CB6D`
SHA256 | `8EC4AA31453BFC331BA80246E8AF378DBA1DB27DDF1F9483A919FA89BFFD2626`
SHA384 | `BD07306DEA53220F396C96FA982A0C9CFC633BB6668ECB10FDC902503681D6F16622DD39912F94C8A586B9DDE6A41F51`
SHA512 | `8A81ABC6891374560CAC983BD8459E9DE3DC888295D6A5E734779746A0DBEFFE375A844593E710DDD0CAE363388C14170E20BE377779A962A18FF77685EB10F3`
SSDEEP | `192:bUNL4V+TSlqEpitQ3xFey4zNq3jzoGoDY0FZsDZPW/pszJkz+ZKWHBWP0:QNLsqElBFDPzoGGZsDZuRsaaZKWHBW`

## Runtime Data

### Usage (stdout):
```Batchfile
Usage: rasautou [-f phonebook] [-a address] [-e entry] [-s]

```

### Usage (stderr):
```Batchfile

```

### Child Processes:


## Signature

* Status: Signature verified.
* Serial: `330000023241FB59996DCC4DFF000000000232`
* Thumbprint: `FF82BC38E1DA5E596DF374C53E3617F7EDA36B06`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: rasdlui.exe
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\WINDOWS\SysWOW64\rasautou.exe](rasautou.exe-BA2347843ED36587134C3B8AF434EC8C.md) | 55

## Possible Misuse

*The following table contains possible examples of `rasautou.exe` being misused. While `rasautou.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Rasautou.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Rasautou.yml) | `Name: Rasautou.exe` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Rasautou.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Rasautou.yml) | `  - Command: rasautou -d powershell.dll -p powershell -a a -e e ` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Rasautou.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Rasautou.yml) | `  - Path: C:\Windows\System32\rasautou.exe` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Rasautou.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Rasautou.yml) | ` - IOC: rasautou.exe command line containing -d and -p` | 



MIT License. Copyright (c) 2020 Strontic.


