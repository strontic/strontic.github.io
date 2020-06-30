---
title: OpenWith.exe | Pick an app
---

# OpenWith.exe 

* File Path: `C:\Windows\SysWOW64\OpenWith.exe`
* Description: Pick an app
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `64148E3F7B8519DCB04FE5E96D5F1184`
SHA1 | `06A08438ABDB64FE3AE0C80FB432F0A0DC66A14A`
SHA256 | `39289ABE68243EAA414BB59F3F918BEFD358FA8465EE83A50BA93E33F8F9AF64`
SHA384 | `954868D78889BAF20B5CBDD3ECC7F685A3B2464DE225EF26BE18FE0377E43785A0ACD46A14DBD8E298E1894B04B0E827`
SHA512 | `F50F43B553D98B1C175CAFA635EE3DFD698B726A8D61DA7A3DD558D35FFDA83E49D550AA153554DE63FDAD019C8DBB90CAFB7C2A7A7DB73B54E951FD22469210`
SSDEEP | `1536:qx2TCjRqyegzTJ8VcJQyAO50aimJ1JsaeQyrFI0fKQTzBNer+CE+Ge+MgTqXPTQ:pTCjHPJQymaex6orer+CE+GW7Q`

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

* Original Filename: OpenWith.exe
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Windows\system32\OpenWith.exe](OpenWith.exe-2CBE77C5FE6617C174954532A0C189BB.md) | 40
[C:\Windows\system32\OpenWith.exe](OpenWith.exe-49371805F24C419A1362A6672F0A8A76.md) | 41
[C:\WINDOWS\system32\OpenWith.exe](OpenWith.exe-C9B3F7E1EB1970A715FA56AB076A260B.md) | 43
[C:\Windows\system32\OpenWith.exe](OpenWith.exe-FEAEEC585FEA59A316DDDD6C8505DA8D.md) | 43
[C:\Windows\SysWOW64\OpenWith.exe](OpenWith.exe-A633739DA182E75C0D6741119A902A0B.md) | 46
[C:\Windows\SysWOW64\OpenWith.exe](OpenWith.exe-C6CEF89904DEC9404CCCD414E353C344.md) | 46
[C:\WINDOWS\SysWOW64\OpenWith.exe](OpenWith.exe-FADC6187E347B4820DA5B907B45F6024.md) | 50

## Possible Misuse

*The following table contains possible examples of `OpenWith.exe` being misused. While `OpenWith.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_openwith.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_openwith.yml) | `title: OpenWith.exe Executes Specified Binary` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_openwith.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_openwith.yml) | `description: The OpenWith.exe executes other binary` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_openwith.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_openwith.yml) | `    - https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/LOLUtilz/OSBinaries/Openwith.yml` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_openwith.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_openwith.yml) | `        Image\|endswith: '\OpenWith.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_openwith.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_openwith.yml) | `    - Legitimate use of OpenWith.exe by legitimate user` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Openwith.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/LOLUtilz/OSBinaries/Openwith.yml) | `Name: Openwith.exe` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Openwith.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/LOLUtilz/OSBinaries/Openwith.yml) | `  - Command: OpenWith.exe /c C:\test.hta` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Openwith.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/LOLUtilz/OSBinaries/Openwith.yml) | `  - Command: OpenWith.exe /c C:\testing.msi` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Openwith.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/LOLUtilz/OSBinaries/Openwith.yml) | `  - c:\windows\system32\Openwith.exe` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Openwith.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/LOLUtilz/OSBinaries/Openwith.yml) | `  - c:\windows\sysWOW64\Openwith.exe` | 



MIT License. Copyright (c) 2020 Strontic.


