---
title: rasautou.exe | Remote Access Dialer
excerpt: What is rasautou.exe?
---

# rasautou.exe 

* File Path: `C:\Windows\SysWOW64\rasautou.exe`
* Description: Remote Access Dialer

## Hashes

Type | Hash
-- | --
MD5 | `414104C05AE2D915EC2D7524AC8510F9`
SHA1 | `4952842970718AB140CF7CEB632C36D87CDEE277`
SHA256 | `2E8D13D56FB667876CE3351DBEF145850C710698EDD9F9FBD9CDA87B62730CB0`
SHA384 | `ACAD550CEA8E57041826747946DBB5D78D6AD3731E461B24F332DCDDAD46332386CA79C5D1063D86529192ECD8EFEBD3`
SHA512 | `8BAB8BC59FB95A2F0F3B788A8A6A1B65A40C310F10163E3D9A9E515FEDDF08913ED869F5E0F4D5313B4732ED3F3D5843E830883B8D43158084CCB7816D99E7EA`
SSDEEP | `384:jx9Lr6ulwPhwS+Xsm07G2/W/trZuNpqWoBW:P6uS6SNmiGqKCNpE`

## Runtime Data

### Usage (stdout):
```cmhg
Usage: rasautou [-f phonebook] [-a address] [-e entry] [-s]

```

## Signature

* Status: Signature verified.
* Serial: `33000000BCE120FDD27CC8EE930000000000BC`
* Thumbprint: `E85459B23C232DB3CB94C7A56D47678F58E8E51E`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: rasdlui.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.14393.0 (rs1_release.160715-1616)
* Product Version: 10.0.14393.0
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.



## Possible Misuse

*The following table contains possible examples of `rasautou.exe` being misused. While `rasautou.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Rasautou.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Rasautou.yml) | `Name: Rasautou.exe`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Rasautou.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Rasautou.yml) | `- Command: rasautou -d powershell.dll -p powershell -a a -e e `{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Rasautou.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Rasautou.yml) | `- Path: C:\Windows\System32\rasautou.exe`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Rasautou.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Rasautou.yml) | `- IOC: rasautou.exe command line containing -d and -p`{:.highlight .language-yaml} | 



MIT License. Copyright (c) 2020-2021 Strontic.


