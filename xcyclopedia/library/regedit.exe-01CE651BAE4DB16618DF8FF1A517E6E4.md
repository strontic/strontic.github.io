
# regedit.exe 

* File Path: `C:\WINDOWS\SysWOW64\regedit.exe`
* Description: Registry Editor
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `01CE651BAE4DB16618DF8FF1A517E6E4`
SHA1 | `1712BCAB8201D1436E47B4C109AE0B4979443E9D`
SHA256 | `D5DE45DECFD0FA08AC12F5725DFC7E5AF1E3ED0325559101990FDCF02C439441`
SHA384 | `C7E21727634F0620336227C0006BA2D2859BFD0AC3FA466F8AC94F4BE40B828D8AC2F68F0E8E1AC4BCE01271B37B0B5A`
SHA512 | `8C17839B19E6A52775598435EAAE81DA7DF06F4FCC6BEEEC2EB6785B94B4FE438A8BEF5B6769562F1176044EE0905FDFB6C0D3E317343F134C37137F7ED3267E`
SSDEEP | `6144:Y1thznQC4hEgB/w2KBi+sQRZ66z+n4VZbd8g79pgrXNgRnVLjyzhbkidNN2:Y1DzneEm9KOQRZ66z24VZbdrpgrXN2LS`

## Runtime Data

### Usage (stdout):
```Batchfile

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

* Original Filename: REGEDIT.EXE.MUI
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.18362.1 (WinBuild.160101.0800)
* Product Version: 10.0.18362.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\WINDOWS\regedit.exe](regedit.exe-29409008DF22243BB320333F9FD5C060.md) | 100
[C:\Windows\regedit.exe](regedit.exe-BF5D30514FEA913E25CCC9E546257088.md) | 72
[C:\Windows\SysWOW64\regedit.exe](regedit.exe-2E327F27B5B836D8304DF46E8E20341A.md) | 72

## Possible Misuse

*The following table contains possible examples of `regedit.exe` being misused. While this file is **not** malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Regedit.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Regedit.yml) | `Name: Regedit.exe` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Regedit.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Regedit.yml) | `  - Command: regedit /E c:\ads\file.txt:regfile.reg HKEY_CURRENT_USER\MyCustomRegKey` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Regedit.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Regedit.yml) | `  - Command: regedit C:\ads\file.txt:regfile.reg` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Regedit.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Regedit.yml) | `  - Path: C:\Windows\System32\regedit.exe` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Regedit.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Regedit.yml) | `  - Path: C:\Windows\SysWOW64\regedit.exe` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Regedit.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Regedit.yml) | ` - IOC: regedit.exe reading and writing to alternate data stream` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Regedit.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Regedit.yml) | ` - IOC: regedit.exe should normally not be executed by end-users` | 
[malware-ioc](https://github.com/eset/malware-ioc) | [rtm](https://github.com/eset/malware-ioc/blob/master/rtm/README.adoc) | `regedit.exe` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1564.004.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1564.004/T1564.004.md) | regedit /E #{path}\file.txt:regfile.reg HKEY_CURRENT_USER\MyCustomRegKey | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)



MIT License. Copyright (c) 2020 Strontic.


