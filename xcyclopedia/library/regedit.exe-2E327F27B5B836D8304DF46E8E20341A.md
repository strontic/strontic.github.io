
# regedit.exe 

* File Path: `C:\Windows\SysWOW64\regedit.exe`
* Description: Registry Editor
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `2E327F27B5B836D8304DF46E8E20341A`
SHA1 | `9A7D4330F2E164C5338CCBA80CF73FFCCEF09ADC`
SHA256 | `1EDA28D11BB4EC6DE741B7A9323B1358D93F796791799F787AC5626116B4ACBC`
SHA384 | `3F2C9237A17FD1A00F600121FF309801BA2F51F3F75C36092E14FEE9FD555278DF04429D043256A738476D4F1C0FCFF7`
SHA512 | `FD50D83560A79A26BF593CEB3373CF87D1270F314F78C93BF5064FFF310AFDBE7FF7CF7C902A42F1B00A54699B4A847B0CF3BC9D9E94E95F531803F2DEBB54EA`
SSDEEP | `6144:75oI77kJde8bLgu0Z48rSQRZ66z+n4VZbd8g79pgrXNgRnVLjyzhbkidNNhC:1oI7e/OrSQRZ66z24VZbdrpgrXN2LWzy`

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
* Serial: `33000001733031072665B8B9B3000000000173`
* Thumbprint: `14590DC5C3AAF238FCFD7785B4B93F4071402C34`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: REGEDIT.EXE.MUI
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.14393.0 (rs1_release.160715-1616)
* Product Version: 10.0.14393.0
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\WINDOWS\regedit.exe](regedit.exe-29409008DF22243BB320333F9FD5C060.md) | 72
[C:\Windows\regedit.exe](regedit.exe-BF5D30514FEA913E25CCC9E546257088.md) | 100
[C:\WINDOWS\SysWOW64\regedit.exe](regedit.exe-01CE651BAE4DB16618DF8FF1A517E6E4.md) | 72

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


