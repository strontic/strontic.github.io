---
title: rasautou.exe | Remote Access Dialer
---

# rasautou.exe 

* File Path: `C:\windows\system32\rasautou.exe`
* Description: Remote Access Dialer
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `33AA72B1C83985F0FE3F51E1E0C8C5DF`
SHA1 | `BC228FD0EDF7E3E2E07DE9325FD4BB6E76EC2AE7`
SHA256 | `F9A9DB182517C828FC9E23EA1FDC9902C07BAD260DD4FD34086446BD9C109B70`
SHA384 | `3E851178181C9BA16B0F60B9B8196DBC05725A4CD83EE1EB259911F7C6814658F691A72A5A774EFA656445F2A0745379`
SHA512 | `EF5855018AA76FD6D36D78B53AEC28337D2D708E7EF85C83D92E07E3D29390C3B5B318B149EFFE25C1205FBFEEEE0D2CD9C529866C1111A49CEAE3621EE971C4`
SSDEEP | `384:/v5URAsJftvOTs27O++QETwRLRxkWMBW:XFSt4Y+bfx6`

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
* Serial: `33000001C422B2F79B793DACB20000000001C4`
* Thumbprint: `AE9C1AE54763822EEC42474983D8B635116C8452`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: rasdlui.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.17763.1 (WinBuild.160101.0800)
* Product Version: 10.0.17763.1
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


