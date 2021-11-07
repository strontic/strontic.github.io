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
MD5 | `81A6467E638E5C15C0C0ABB4DA13DEAD`
SHA1 | `6F3094856E6040A92FAAB8F30B0EC2C6F957CB6D`
SHA256 | `8EC4AA31453BFC331BA80246E8AF378DBA1DB27DDF1F9483A919FA89BFFD2626`
SHA384 | `BD07306DEA53220F396C96FA982A0C9CFC633BB6668ECB10FDC902503681D6F16622DD39912F94C8A586B9DDE6A41F51`
SHA512 | `8A81ABC6891374560CAC983BD8459E9DE3DC888295D6A5E734779746A0DBEFFE375A844593E710DDD0CAE363388C14170E20BE377779A962A18FF77685EB10F3`
SSDEEP | `192:bUNL4V+TSlqEpitQ3xFey4zNq3jzoGoDY0FZsDZPW/pszJkz+ZKWHBWP0:QNLsqElBFDPzoGGZsDZuRsaaZKWHBW`
IMP | `6FD6CB5E209EBD24A870B74D8EE7F599`
PESHA1 | `A5B185C89DE198DDEC40F5DFB8123DC787E0DA4A`
PE256 | `FDC15D502C5837567DE9D8580C5CC28BFD36E50E8401A82C417274CFEE7DB8A8`

## Runtime Data

### Usage (stdout):
```cmhg
Usage: rasautou [-f phonebook] [-a address] [-e entry] [-s]

```

### Loaded Modules:

Path |
-- |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\wow64.dll |
C:\Windows\System32\wow64cpu.dll |
C:\Windows\System32\wow64win.dll |
C:\Windows\SysWOW64\rasautou.exe |


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: rasdlui.exe
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/71
* VirusTotal Link: https://www.virustotal.com/gui/file/8ec4aa31453bfc331ba80246e8af378dba1db27ddf1f9483a919fa89bffd2626/detection/

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\WINDOWS\SysWOW64\rasautou.exe](rasautou.exe-BA2347843ED36587134C3B8AF434EC8C.md) | 55
[C:\Windows\SysWOW64\rasautou.exe](rasautou.exe-DFDBEDC2ED47CBABC13CCC64E97868F3.md) | 79

## Possible Misuse

*The following table contains possible examples of `rasautou.exe` being misused. While `rasautou.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_rasautou_dll_execution.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_rasautou_dll_execution.yml) | `title: DLL Execution via Rasautou.exe`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_rasautou_dll_execution.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_rasautou_dll_execution.yml) | `description: Detects using Rasautou.exe for loading arbitrary .DLL specified in -d option and executes the export specified in -p. `{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_rasautou_dll_execution.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_rasautou_dll_execution.yml) | `- https://lolbas-project.github.io/lolbas/Binaries/Rasautou/`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_rasautou_dll_execution.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_rasautou_dll_execution.yml) | `Image\|endswith: '\rasautou.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Rasautou.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Rasautou.yml) | `Name: Rasautou.exe`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Rasautou.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Rasautou.yml) | `- Command: rasautou -d powershell.dll -p powershell -a a -e e`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Rasautou.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Rasautou.yml) | `- Path: C:\Windows\System32\rasautou.exe`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Rasautou.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Rasautou.yml) | `- IOC: rasautou.exe command line containing -d and -p`{:.highlight .language-yaml} | 



MIT License. Copyright (c) 2020-2021 Strontic.


