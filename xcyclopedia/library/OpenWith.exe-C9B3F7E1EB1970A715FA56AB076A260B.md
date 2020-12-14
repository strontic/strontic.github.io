---
title: OpenWith.exe | Pick an app
excerpt: What is OpenWith.exe?
---

# OpenWith.exe 

* File Path: `C:\WINDOWS\system32\OpenWith.exe`
* Description: Pick an app

## Hashes

Type | Hash
-- | --
MD5 | `C9B3F7E1EB1970A715FA56AB076A260B`
SHA1 | `5D94ED57AE017D90E48449A7DE0A64B1A3620120`
SHA256 | `7F1231BBCB8B271ABA5F6781C08C5CD43A1692FD72D9E3A51EE7DB24EF27B28A`
SHA384 | `6CFA5466B9EB474A780E2771DFC0D47F31F7CD8399445A7ECEE6613C9266C75BC703F227CA6824A6E215F8E8D124BB04`
SHA512 | `56FC8749D12A09C6D877524F228D891F947BFBA86EAC4DBF95BA64D47014DB2E190F5B2DDAC03688F4B64250A71F614742819146330455B34781C2742CE41324`
SSDEEP | `1536:c4TlRoYQuigA7yfSJopqs4V5wqBoqJSTlXXyfzEEfKQTzBNer+CE+Ge+iP2b:1oYQN7epqhNShSY4rer+CE+GcOb`

## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: OpenWith.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.18362.1 (WinBuild.160101.0800)
* Product Version: 10.0.18362.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.


## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Windows\system32\OpenWith.exe](OpenWith.exe-0234BF822C4D6070819403F1BEF37F14.md) | 44
[C:\windows\system32\OpenWith.exe](OpenWith.exe-2C56E3290BED2E82AE666EEA01843073.md) | 44
[C:\Windows\system32\OpenWith.exe](OpenWith.exe-2CBE77C5FE6617C174954532A0C189BB.md) | 41
[C:\Windows\system32\OpenWith.exe](OpenWith.exe-49371805F24C419A1362A6672F0A8A76.md) | 50
[C:\Windows\system32\OpenWith.exe](OpenWith.exe-FEAEEC585FEA59A316DDDD6C8505DA8D.md) | 46
[C:\windows\SysWOW64\OpenWith.exe](OpenWith.exe-1DFE1ED0A9EF0FA4FFE8D08DFB00F121.md) | 44
[C:\Windows\SysWOW64\OpenWith.exe](OpenWith.exe-53E3F9F13C4C20B32CDA36FDEE865890.md) | 41
[C:\Windows\SysWOW64\OpenWith.exe](OpenWith.exe-64148E3F7B8519DCB04FE5E96D5F1184.md) | 43
[C:\Windows\SysWOW64\OpenWith.exe](OpenWith.exe-A633739DA182E75C0D6741119A902A0B.md) | 44
[C:\Windows\SysWOW64\OpenWith.exe](OpenWith.exe-C6CEF89904DEC9404CCCD414E353C344.md) | 40
[C:\WINDOWS\SysWOW64\OpenWith.exe](OpenWith.exe-FADC6187E347B4820DA5B907B45F6024.md) | 46

## Possible Misuse

*The following table contains possible examples of `OpenWith.exe` being misused. While `OpenWith.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_openwith.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_openwith.yml) | `title: OpenWith.exe Executes Specified Binary` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_openwith.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_openwith.yml) | `description: The OpenWith.exe executes other binary` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_openwith.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_openwith.yml) | `- https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/LOLUtilz/OSBinaries/Openwith.yml` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_openwith.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_openwith.yml) | `Image\|endswith: '\OpenWith.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_openwith.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_openwith.yml) | `- Legitimate use of OpenWith.exe by legitimate user` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Openwith.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/LOLUtilz/OSBinaries/Openwith.yml) | `Name: Openwith.exe` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Openwith.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/LOLUtilz/OSBinaries/Openwith.yml) | `- Command: OpenWith.exe /c C:\test.hta` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Openwith.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/LOLUtilz/OSBinaries/Openwith.yml) | `- Command: OpenWith.exe /c C:\testing.msi` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Openwith.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/LOLUtilz/OSBinaries/Openwith.yml) | `- c:\windows\system32\Openwith.exe` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Openwith.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/LOLUtilz/OSBinaries/Openwith.yml) | `- c:\windows\sysWOW64\Openwith.exe` | 



MIT License. Copyright (c) 2020 Strontic.


