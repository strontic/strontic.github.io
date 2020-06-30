---
title: mavinject.exe | Microsoft Application Virtualization Injector
---

# mavinject.exe 

* File Path: `C:\Windows\system32\mavinject.exe`
* Description: Microsoft Application Virtualization Injector
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `73E25B03C4DF5277BAF67004D53FC241`
SHA1 | `E486E7F49173DC2A98B90485BDC378952DBA91CB`
SHA256 | `1C1A5BF6BC7EC24C67F2A13E5C8EB71C927927545F8EB7A75F1A4EA893604C38`
SHA384 | `2064ECC639B4C7E90C1077F743F8DA4D516A65951973F1A3C424DF766BA3B8F9130BC1AADF8EC54E05B866CCD473345B`
SHA512 | `3DAAFA6ECF338B6DC466626FC28C4A3D61464C0D43BA831721A15E7D0C1B0613A7568881D21707105B7F7DE70B45A613B40B888A8147F71C05815DD41B463DBC`
SSDEEP | `3072:gWVGVpG7Ykw0khibT4PiFWGNU6ITL2pj+9wW:Z5Mk9JTuiFWGNU6ITL2pg`

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
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: mavinject64.exe
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Windows\system32\AppVDllSurrogate.exe](AppVDllSurrogate.exe-2F8BF990BEDECF1974DC4189E24F709D.md) | 29
[C:\WINDOWS\system32\AppVDllSurrogate.exe](AppVDllSurrogate.exe-4564AEECEED25F34A2A6156A355C09B6.md) | 43
[C:\Windows\system32\AppVDllSurrogate.exe](AppVDllSurrogate.exe-EAA5FF4ED735D3D1FE292600A9E3DEC6.md) | 41
[C:\Windows\system32\AppVNice.exe](AppVNice.exe-47C060EF467EB3E4461D26BCBC858377.md) | 41
[C:\Windows\system32\AppVNice.exe](AppVNice.exe-E4CC15631219560406D2CE920CB2C133.md) | 47
[C:\WINDOWS\system32\AppVNice.exe](AppVNice.exe-E805EC74A53B64CE1D9D6739B8055579.md) | 40
[C:\Windows\system32\AppVShNotify.exe](AppVShNotify.exe-3E705409974662FD944B65C3B9ADAC31.md) | 40
[C:\Windows\system32\AppVShNotify.exe](AppVShNotify.exe-422209DBC6879722C59054DBFBCDA152.md) | 43
[C:\WINDOWS\system32\AppVShNotify.exe](AppVShNotify.exe-9252AC3912987BB99FA84EF48C00440D.md) | 41
[C:\Windows\system32\mavinject.exe](mavinject.exe-3196E7F92E0B4367444A185B5A4E757D.md) | 38
[C:\Windows\system32\mavinject.exe](mavinject.exe-72D5E2A3FF5D88C891E0DF1AA28B6422.md) | 44
[C:\WINDOWS\system32\mavinject.exe](mavinject.exe-80EAEBA49FFD53712F4304A442C95F0D.md) | 43

## Possible Misuse

*The following table contains possible examples of `mavinject.exe` being misused. While `mavinject.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_mavinject_proc_inj.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_mavinject_proc_inj.yml) | `title: MavInject Process Injection` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_mavinject_proc_inj.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_mavinject_proc_inj.yml) | `    - https://reaqta.com/2017/12/mavinject-microsoft-injector/` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Mavinject.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Mavinject.yml) | `Name: Mavinject.exe` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Mavinject.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Mavinject.yml) | `  - Command: MavInject.exe 3110 /INJECTRUNNING c:\folder\evil.dll` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Mavinject.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Mavinject.yml) | `  - Command: Mavinject.exe 4172 /INJECTRUNNING "c:\ads\file.txt:file.dll"` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Mavinject.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Mavinject.yml) | `  - Path: C:\Windows\System32\mavinject.exe` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Mavinject.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Mavinject.yml) | `  - Path: C:\Windows\SysWOW64\mavinject.exe` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Mavinject.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Mavinject.yml) | ` - IOC: mavinject.exe should not run unless APP-v is in use on the workstation` | 
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [index.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Indexes-Markdown/index.md) |   - Atomic Test #1: Process Injection via mavinject.exe [windows] | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [index.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Indexes-Markdown/index.md) |   - Atomic Test #1: mavinject - Inject DLL into running process [windows] | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [windows-index.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Indexes-Markdown/windows-index.md) |   - Atomic Test #1: Process Injection via mavinject.exe [windows] | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [windows-index.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Indexes-Markdown/windows-index.md) |   - Atomic Test #1: mavinject - Inject DLL into running process [windows] | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1055.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1055/T1055.md) | - [Atomic Test #1 - Process Injection via mavinject.exe](#atomic-test-1---process-injection-via-mavinjectexe) | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1055.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1055/T1055.md) | ## Atomic Test #1 - Process Injection via mavinject.exe | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1055.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1055/T1055.md) | Upon successful execution, powershell.exe will download T1055.dll to disk. Powershell will then spawn mavinject.exe to perform process injection in T1055.dll. | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1055.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1055/T1055.md) | mavinject $mypid /INJECTRUNNING #{dll_payload} | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1056.004.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1056.004/T1056.004.md) | mavinject $pid /INJECTRUNNING #{file_name} | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1218.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1218/T1218.md) | - [Atomic Test #1 - mavinject - Inject DLL into running process](#atomic-test-1---mavinject---inject-dll-into-running-process) | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1218.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1218/T1218.md) | ## Atomic Test #1 - mavinject - Inject DLL into running process | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1218.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1218/T1218.md) | mavinject.exe #{process_id} /INJECTRUNNING #{dll_payload} | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)



MIT License. Copyright (c) 2020 Strontic.


