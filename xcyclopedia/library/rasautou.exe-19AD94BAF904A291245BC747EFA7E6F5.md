---
title: rasautou.exe | Remote Access Dialer
---

# rasautou.exe 

* File Path: `C:\WINDOWS\system32\rasautou.exe`
* Description: Remote Access Dialer

## Hashes

Type | Hash
-- | --
MD5 | `19AD94BAF904A291245BC747EFA7E6F5`
SHA1 | `65C5FD6D77E36FEFA3069889478D4619032AB4A8`
SHA256 | `2CA3D32921B11C5307DCA89834C7F1D27894FE498298EEFB5C2281448A14F783`
SHA384 | `F4624B36415A13D2127FD1B5D53618B6F1A9E2ECFCFF7504B8589208D2F79B5A0B875AD3E2A4DD915D6C749C26AEC0B9`
SHA512 | `FC1040963BD1FDE5B36A6129CCAB478B2175DA51BD3C2E19EDB57FCF98FD8C768C242796918212634EDBCBEBF1E934BD8D9A132453EBB829D65DD9FF2B58BA00`
SSDEEP | `192:ZDTs+fFF9zkrpymwkXhtruNy7Tb5wMVS5soU74V/xg+giYETwGOMpm/WM70WSBW:ZAURAsJEtvVksd7eg+uETwZ8RI0WSBW`

## Runtime Data

### Usage (stdout):
```cmhg
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
* File Version: 10.0.18362.1 (WinBuild.160101.0800)
* Product Version: 10.0.18362.1
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


