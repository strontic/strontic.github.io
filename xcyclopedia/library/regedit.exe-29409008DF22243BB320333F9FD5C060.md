
# regedit.exe 

* File Path: `C:\WINDOWS\regedit.exe`
* Description: Registry Editor
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `29409008DF22243BB320333F9FD5C060`
SHA1 | `DA0EDFBDBFFAAACA65326EE337BED0DDC8443AA7`
SHA256 | `7ACC4A0B686D829D4D4C8AFBF9E38E562BE5A6F708A1C2273358AA7E41E1CB97`
SHA384 | `E22B95E3E13A0E5F26DE1941B14493B8FD4A92BC61FAC085831ED80060AD272E1436EA52D577A4BE87147E169CAC34A1`
SHA512 | `AE416407630DAB254018231086CB8235114F638F64D0C323C390AA8BD356870948A533770613DA3E6AAE89A10B398465B00A75433D7B3DBADA65CB071F0FA332`
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
[C:\Windows\regedit.exe](regedit.exe-BF5D30514FEA913E25CCC9E546257088.md) | 72
[C:\WINDOWS\SysWOW64\regedit.exe](regedit.exe-01CE651BAE4DB16618DF8FF1A517E6E4.md) | 100
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


