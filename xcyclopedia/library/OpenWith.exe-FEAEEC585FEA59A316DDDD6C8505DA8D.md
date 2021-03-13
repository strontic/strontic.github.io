---
title: OpenWith.exe | Pick an app
excerpt: What is OpenWith.exe?
---

# OpenWith.exe 

* File Path: `C:\Windows\system32\OpenWith.exe`
* Description: Pick an app

## Hashes

Type | Hash
-- | --
MD5 | `FEAEEC585FEA59A316DDDD6C8505DA8D`
SHA1 | `6E075F557DD34F8A7BBA911FFA972279414EAF66`
SHA256 | `E9F8EBA1F42F60AACEC65BC346AF51A649F8C9BF625AB9493F17D98F4C6C22D9`
SHA384 | `E72B5A43CB8E3188B34F76D8628F32A3DBE37041023FE59B463361CB0AA1A24F061ECCE370497AED10E5379CE8B1487E`
SHA512 | `F8AAA2386D37C6028BA524F76997698DED4231762408EAEFC667A999E17566EB47C6D01C36FE37B59C7EC5D5D4CF5B20B220F526A9147C7FA362D408E332C670`
SSDEEP | `1536:PhuNoJDGys4JLd9P14GqBaUfKQTzBNer+CE+Ge+JPVW:fhFXd7qMIrer+CE+GXNW`

## Signature

* Status: Signature verified.
* Serial: `33000000BCE120FDD27CC8EE930000000000BC`
* Thumbprint: `E85459B23C232DB3CB94C7A56D47678F58E8E51E`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: OpenWith.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.14393.0 (rs1_release.160715-1616)
* Product Version: 10.0.14393.0
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.


## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Windows\system32\OpenWith.exe](OpenWith.exe-0234BF822C4D6070819403F1BEF37F14.md) | 44
[C:\windows\system32\OpenWith.exe](OpenWith.exe-2C56E3290BED2E82AE666EEA01843073.md) | 49
[C:\Windows\system32\OpenWith.exe](OpenWith.exe-2CBE77C5FE6617C174954532A0C189BB.md) | 44
[C:\Windows\system32\OpenWith.exe](OpenWith.exe-49371805F24C419A1362A6672F0A8A76.md) | 46
[C:\WINDOWS\system32\OpenWith.exe](OpenWith.exe-C9B3F7E1EB1970A715FA56AB076A260B.md) | 46
[C:\windows\SysWOW64\OpenWith.exe](OpenWith.exe-1DFE1ED0A9EF0FA4FFE8D08DFB00F121.md) | 54
[C:\Windows\SysWOW64\OpenWith.exe](OpenWith.exe-53E3F9F13C4C20B32CDA36FDEE865890.md) | 43
[C:\Windows\SysWOW64\OpenWith.exe](OpenWith.exe-64148E3F7B8519DCB04FE5E96D5F1184.md) | 43
[C:\Windows\SysWOW64\OpenWith.exe](OpenWith.exe-A633739DA182E75C0D6741119A902A0B.md) | 54
[C:\Windows\SysWOW64\OpenWith.exe](OpenWith.exe-C6CEF89904DEC9404CCCD414E353C344.md) | 44
[C:\WINDOWS\SysWOW64\OpenWith.exe](OpenWith.exe-FADC6187E347B4820DA5B907B45F6024.md) | 47

## Possible Misuse

*The following table contains possible examples of `OpenWith.exe` being misused. While `OpenWith.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_openwith.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_openwith.yml) | `title: OpenWith.exe Executes Specified Binary`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_openwith.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_openwith.yml) | `description: The OpenWith.exe executes other binary`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_openwith.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_openwith.yml) | `- https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/LOLUtilz/OSBinaries/Openwith.yml`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_openwith.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_openwith.yml) | `Image\|endswith: '\OpenWith.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_openwith.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_openwith.yml) | `- Legitimate use of OpenWith.exe by legitimate user`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Openwith.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/LOLUtilz/OSBinaries/Openwith.yml) | `Name: Openwith.exe`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Openwith.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/LOLUtilz/OSBinaries/Openwith.yml) | `- Command: OpenWith.exe /c C:\test.hta`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Openwith.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/LOLUtilz/OSBinaries/Openwith.yml) | `- Command: OpenWith.exe /c C:\testing.msi`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Openwith.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/LOLUtilz/OSBinaries/Openwith.yml) | `- c:\windows\system32\Openwith.exe`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Openwith.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/LOLUtilz/OSBinaries/Openwith.yml) | `- c:\windows\sysWOW64\Openwith.exe`{:.highlight .language-yaml} | 



MIT License. Copyright (c) 2020-2021 Strontic.


