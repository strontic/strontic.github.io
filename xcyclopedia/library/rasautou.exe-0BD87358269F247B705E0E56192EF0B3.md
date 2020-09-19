---
title: rasautou.exe | Remote Access Dialer
---

# rasautou.exe 

* File Path: `C:\windows\SysWOW64\rasautou.exe`
* Description: Remote Access Dialer

## Hashes

Type | Hash
-- | --
MD5 | `0BD87358269F247B705E0E56192EF0B3`
SHA1 | `59F1E76A96CEF1086D439F803811DE3746CBA62E`
SHA256 | `971EF57FE7A61F62CBE81857525206BF03E59DF1377A6C6DE700DC7856FCC089`
SHA384 | `E8EB61CD7CB5BCD14EC9AE044FB845B7CF4C34CE702DA5C6EC4FC8A9FBD04DE0CA4D634745AF2703CBCA9B3404A7DFD6`
SHA512 | `67C1D60302FE230A36FA93686E8D10F64E59CBA1789ADCA81C7332DDF2AC39F8BB35FAC60570A15EA4DAF18EA5941EDA790ECB8FD60EFC8998613F0C83D82E7F`
SSDEEP | `384:o0DV9Llp0PyAtGmaXnmOl+sh6SdoV0rbhSW1BWaa:o0pKyoGmymDsMEPhBI`

## Signature

* Status: The file C:\windows\SysWOW64\rasautou.exe is not digitally signed. You cannot run this script on the current system. For more information about running scripts and setting execution policy, see about_Execution_Policies at http://go.microsoft.com/fwlink/?LinkID=135170
* Serial: ``
* Thumbprint: ``
* Issuer: 
* Subject: 

## File Metadata

* Original Filename: rasdlui.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 6.3.9600.16384 (winblue_rtm.130821-1623)
* Product Version: 6.3.9600.16384
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.


## Possible Misuse

*The following table contains possible examples of `rasautou.exe` being misused. While `rasautou.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Rasautou.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Rasautou.yml) | `Name: Rasautou.exe` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Rasautou.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Rasautou.yml) | `- Command: rasautou -d powershell.dll -p powershell -a a -e e ` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Rasautou.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Rasautou.yml) | `- Path: C:\Windows\System32\rasautou.exe` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Rasautou.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Rasautou.yml) | `- IOC: rasautou.exe command line containing -d and -p` | 



MIT License. Copyright (c) 2020 Strontic.


