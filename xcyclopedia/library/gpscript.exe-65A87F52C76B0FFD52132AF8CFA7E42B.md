---
title: gpscript.exe | Group Policy Script Application
excerpt: What is gpscript.exe?
---

# gpscript.exe 

* File Path: `C:\windows\system32\gpscript.exe`
* Description: Group Policy Script Application

## Hashes

Type | Hash
-- | --
MD5 | `65A87F52C76B0FFD52132AF8CFA7E42B`
SHA1 | `C9CC716EBC728FBBDFF9F8CB127E4198E34FAD6C`
SHA256 | `FF6A8DCE772EE184086311E08588A4D8BC1202996B0E315BB83156025D54B526`
SHA384 | `C64AA6A29BB7AB2E4F2438DA697A6F0E0E11E3E62B7052E73C73FCB9AA772D0742131A2335AC9F92B207993F26A6E1C9`
SHA512 | `12428B52BA7DD9CC308A91993BBABE4D66C493E93EA6166E160FAB0E43362DCDB6EFA71CB300FE08E87A29B8C4311ECC4735CDF461D7CF1F5163846D18A5CCF4`
SSDEEP | `384:xQ8x0HsmAN1pl3UqpGXDvjKLXFPGUpOm5K7yt5WHSfTu0DDGRAx+Nmtv5rdQsqps:i8x0HlvKPROjuRflGhNmnp8V094bhr`

## Signature

* Status: The file C:\windows\system32\gpscript.exe is not digitally signed. You cannot run this script on the current system. For more information about running scripts and setting execution policy, see about_Execution_Policies at http://go.microsoft.com/fwlink/?LinkID=135170
* Serial: ``
* Thumbprint: ``
* Issuer: 
* Subject: 

## File Metadata

* Original Filename: GPSCRIPT.EXE
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 6.3.9600.17415 (winblue_r4.141028-1500)
* Product Version: 6.3.9600.17415
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.



## Possible Misuse

*The following table contains possible examples of `gpscript.exe` being misused. While `gpscript.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Gpscript.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Gpscript.yml) | `Name: Gpscript.exe` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Gpscript.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Gpscript.yml) | `- Command: Gpscript /logon` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Gpscript.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Gpscript.yml) | `- Command: Gpscript /startup` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Gpscript.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Gpscript.yml) | `- Path: C:\Windows\System32\gpscript.exe` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Gpscript.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Gpscript.yml) | `- Path: C:\Windows\SysWOW64\gpscript.exe` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Gpscript.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Gpscript.yml) | `- IOC: Execution of Gpscript.exe after logon` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Gpscript.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Gpscript.yml) | `- Link: https://oddvar.moe/2018/04/27/gpscript-exe-another-lolbin-to-the-list/` | 



MIT License. Copyright (c) 2020 Strontic.


