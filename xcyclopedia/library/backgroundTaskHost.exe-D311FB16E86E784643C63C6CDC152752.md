---
title: backgroundTaskHost.exe | Background Task Host
---

# backgroundTaskHost.exe 

* File Path: `C:\windows\SysWOW64\backgroundTaskHost.exe`
* Description: Background Task Host

## Hashes

Type | Hash
-- | --
MD5 | `D311FB16E86E784643C63C6CDC152752`
SHA1 | `EBBC9B12A3712321D48268077A39A76744A2A16E`
SHA256 | `5587CEA38B44259178BBC4FC45FEDBEF86F0273BF662EEBDF397C9E58C168954`
SHA384 | `ED65241BBBF09A4992241B1AF1AFA8772094852A03511FBEEC78CC824219412503FC7DCABC8BA71DC01E5F4B53FA3B54`
SHA512 | `CF5BAE3252DE875A84C9EABBCDB0EC5068026C01D6878CE9D1FD4AC53D84BCC3D119221DBE56CA8FDCA48706B7CDDE063F4C0C210C5EFE87CF121DD020A6F4CB`
SSDEEP | `192:HVRKqXbuA6ujT4TaiUjidB9eLiSQO28BWpeGWe:HFXbu90KaVYkwO2UWMGW`

### Loaded Modules:

Path |
-- |
C:\Windows\system32\backgroundTaskHost.exe |
C:\Windows\System32\combase.dll |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\System32\msvcrt.dll |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\RPCRT4.dll |
C:\Windows\System32\ucrtbase.dll |


## Signature

* Status: The file C:\windows\SysWOW64\backgroundTaskHost.exe is not digitally signed. You cannot run this script on the current system. For more information about running scripts and setting execution policy, see about_Execution_Policies at http://go.microsoft.com/fwlink/?LinkID=135170
* Serial: ``
* Thumbprint: ``
* Issuer: 
* Subject: 

## File Metadata

* Original Filename: backgroundTaskHost.exe
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 6.3.9600.17415 (winblue_r4.141028-1500)
* Product Version: 6.3.9600.17415
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.


## Possible Misuse

*The following table contains possible examples of `backgroundTaskHost.exe` being misused. While `backgroundTaskHost.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_abusing_azure_browser_sso.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/sysmon/sysmon_abusing_azure_browser_sso.yml) | `         - BackgroundTaskHost.exe` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020 Strontic.


