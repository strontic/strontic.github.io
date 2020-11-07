---
title: verclsid.exe | Extension CLSID Verification Host
excerpt: What is verclsid.exe?
---

# verclsid.exe 

* File Path: `C:\Windows\system32\verclsid.exe`
* Description: Extension CLSID Verification Host

## Hashes

Type | Hash
-- | --
MD5 | `81D41E225B8B55748FFB0D8747FE8BAC`
SHA1 | `B8359399F1751FF1AFFC4A3A9F90F890CB17C9ED`
SHA256 | `AC6E1F614CB902C0ABE4297646E21C70590624B652A080BFBB8407B1AB52609D`
SHA384 | `1A10576F99F7927D3C30D5EC3031BF226BAA3E650BC6C3844DA759D4A40C51F4D7F29AF93128AE29AFDCD01E47BDFDBE`
SHA512 | `495B57077F2E50247D8CB041405A39B6B8459A794AC3A801DF5CCF6EB1C2A8AFCCA668920A7039A6199B91C8895A2FCB7D70CB1955C69E0D31E4C4CDCD81AC0E`
SSDEEP | `192:1S1rPu2/TzyyIDWm8ZdFN2y9qnWJ8VaZGuJG+WfCkXWSNW:1S17uezxm8vL2PWJqOGuUCoWSNW`
IMP | `FA65D753209C7382631265744DE49154`
PESHA1 | `1DE0E12F0D8BEC5CFD749CC24901367A305AD1CB`
PE256 | `F37FCB07032841EB2FFE0A88884A4712B1A217E71EAC6B9653834ED58F2D09F4`

## Runtime Data

### Loaded Modules:

Path |
-- |
C:\Windows\System32\combase.dll |
C:\Windows\System32\GDI32.dll |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\System32\msvcrt.dll |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\ole32.dll |
C:\Windows\System32\RPCRT4.dll |
C:\Windows\System32\ucrtbase.dll |
C:\Windows\system32\verclsid.exe |
C:\Windows\System32\win32u.dll |


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: verclsid.exe
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/75
* VirusTotal Link: https://www.virustotal.com/gui/file/ac6e1f614cb902c0abe4297646e21c70590624b652a080bfbb8407b1ab52609d/detection


## Possible Misuse

*The following table contains possible examples of `verclsid.exe` being misused. While `verclsid.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_malware_verclsid_shellcode.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_access/sysmon_malware_verclsid_shellcode.yml) | `title: Malware Shellcode in Verclsid Target Process` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_malware_verclsid_shellcode.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_access/sysmon_malware_verclsid_shellcode.yml) | `description: Detects a process access to verclsid.exe that injects shellcode from a Microsoft Office application / VBA macro` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_malware_verclsid_shellcode.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_access/sysmon_malware_verclsid_shellcode.yml) | `TargetImage: '*\verclsid.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Verclsid.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Verclsid.yml) | `Name: Verclsid.exe` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Verclsid.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Verclsid.yml) | `- Command: verclsid.exe /S /C {CLSID}` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Verclsid.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Verclsid.yml) | `- Path: C:\Windows\System32\verclsid.exe` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Verclsid.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Verclsid.yml) | `- Path: C:\Windows\SysWOW64\verclsid.exe` | 



MIT License. Copyright (c) 2020 Strontic.


