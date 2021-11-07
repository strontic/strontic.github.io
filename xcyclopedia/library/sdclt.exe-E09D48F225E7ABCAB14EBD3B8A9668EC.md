---
title: sdclt.exe | Microsoft Windows Backup
excerpt: What is sdclt.exe?
---

# sdclt.exe 

* File Path: `C:\Windows\system32\sdclt.exe`
* Description: Microsoft Windows Backup

## Hashes

Type | Hash
-- | --
MD5 | `E09D48F225E7ABCAB14EBD3B8A9668EC`
SHA1 | `1C5B9322B51C09A407D182DF481609F7CB8C425D`
SHA256 | `EFD238EA79B93D07852D39052F1411618C36E7597E8AF0966C4A3223F0021DC3`
SHA384 | `9B50676CAB56A4225F62A4490960CE39A0EE87D612A297F9E04F85B6558E6CCBD62D87F64758F3AD50E5790C1EBA7AA1`
SHA512 | `384D606B90C4803E5144B4DE24EDC537CB22DD59336A18A58D229500ED36AEC92C8467CAE6D3F326647BD044D8074931DA553C7809727FB70227E99C257DF0B4`
SSDEEP | `24576:VK0ddqA6u5zrIlGjck1iPh9yptQHZ7RHegR:RHrmjk1iPaQ5dH9`
IMP | `1F4349F0C287A904C0483B5CD434DF28`
PESHA1 | `FD235C37B554BFF1E0BAC1C85E5E2758B4C6370A`
PE256 | `D8CB97E4036DF66FC36B8720F2B0C381510B3D63D5D3FF31356B97B65C33EBCC`

## Runtime Data

### Child Processes:
RdpSa.exe

### Loaded Modules:

Path |
-- |
C:\Windows\System32\advapi32.dll |
C:\Windows\System32\combase.dll |
C:\Windows\System32\CRYPT32.dll |
C:\Windows\System32\GDI32.dll |
C:\Windows\System32\gdi32full.dll |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\System32\msvcp_win.dll |
C:\Windows\System32\msvcrt.dll |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\OLEAUT32.dll |
C:\Windows\system32\ReAgent.dll |
C:\Windows\System32\RPCRT4.dll |
C:\Windows\system32\sdclt.exe |
C:\Windows\System32\sechost.dll |
C:\Windows\system32\SPP.dll |
C:\Windows\System32\ucrtbase.dll |
C:\Windows\System32\USER32.dll |
C:\Windows\system32\VSSAPI.DLL |
C:\Windows\system32\wer.dll |
C:\Windows\System32\win32u.dll |


## Signature

* Status: Signature verified.
* Serial: `33000002EC6579AD1E670890130000000002EC`
* Thumbprint: `F7C2F2C96A328C13CDA8CDB57B715BDEA2CBD1D9`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: sdclt.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/73
* VirusTotal Link: https://www.virustotal.com/gui/file/efd238ea79b93d07852d39052f1411618c36e7597e8af0966c4a3223f0021dc3/detection

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Windows\system32\sdclt.exe](sdclt.exe-1A6DC77B647238046A1F466B72CC271B.md) | 54
[C:\Windows\system32\sdclt.exe](sdclt.exe-34B64D8A4316A9C97E56C0DFCFCEC3C6.md) | 47
[C:\Windows\system32\sdclt.exe](sdclt.exe-4685EDEA02ED044779578CE2AB9505FF.md) | 50
[C:\Windows\system32\sdclt.exe](sdclt.exe-B0C397303D58CCC9E27BF71073E46F49.md) | 47
[C:\WINDOWS\system32\sdclt.exe](sdclt.exe-F96744B10792C70426608E670C0E39DB.md) | 47

## Possible Misuse

*The following table contains possible examples of `sdclt.exe` being misused. While `sdclt.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_high_integrity_sdclt.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/sysmon_high_integrity_sdclt.yml) | `title: High Integrity Sdclt Process`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_high_integrity_sdclt.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/sysmon_high_integrity_sdclt.yml) | `description: A General detection for sdclt being spawned as an elevated process. This could be an indicator of sdclt being used for bypass UAC techniques.`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_high_integrity_sdclt.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/sysmon_high_integrity_sdclt.yml) | `Image\|endswith: 'sdclt.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_sdclt_child_process.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/sysmon_sdclt_child_process.yml) | `title: Sdclt Child Processes`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_sdclt_child_process.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/sysmon_sdclt_child_process.yml) | `description: A General detection for sdclt spawning new processes. This could be an indicator of sdclt being used for bypass UAC techniques.`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_sdclt_child_process.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/sysmon_sdclt_child_process.yml) | `ParentImage\|endswith: '\sdclt.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_comhijack_sdclt.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/registry_event/sysmon_comhijack_sdclt.yml) | `title: COM Hijack via Sdclt`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_comhijack_sdclt.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/registry_event/sysmon_comhijack_sdclt.yml) | `- http://blog.sevagas.com/?Yet-another-sdclt-UAC-bypass`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_uac_bypass_sdclt.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/registry_event/sysmon_uac_bypass_sdclt.yml) | `title: UAC Bypass via Sdclt`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_uac_bypass_sdclt.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/registry_event/sysmon_uac_bypass_sdclt.yml) | `description: Detects the pattern of UAC Bypass using registry key manipulation of sdclt.exe (e.g. UACMe 53)`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_uac_bypass_sdclt.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/registry_event/sysmon_uac_bypass_sdclt.yml) | `- https://enigma0x3.net/2017/03/17/fileless-uac-bypass-using-sdclt-exe/`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[malware-ioc](https://github.com/eset/malware-ioc) | [misp_invisimole.json](https://github.com/eset/malware-ioc/blob/master/invisimole/misp_invisimole.json) | `"https://enigma0x3.net/2017/03/17/fileless-uac-bypass-using-sdclt-exe/"`{:.highlight .language-cmhg} | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [index.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Indexes-Markdown/index.md) | - Atomic Test #7: Bypass UAC using sdclt DelegateExecute [windows] | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [windows-index.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Indexes-Markdown/windows-index.md) | - Atomic Test #7: Bypass UAC using sdclt DelegateExecute [windows] | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1548.002.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1548.002/T1548.002.md) | - [Atomic Test #7 - Bypass UAC using sdclt DelegateExecute](#atomic-test-7---bypass-uac-using-sdclt-delegateexecute) | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1548.002.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1548.002/T1548.002.md) | ## Atomic Test #7 - Bypass UAC using sdclt DelegateExecute | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1548.002.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1548.002/T1548.002.md) | Upon successful execution, sdclt.exe will spawn cmd.exe to spawn notepad.exe | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1548.002.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1548.002/T1548.002.md) | [Reference - sevagas.com](http://blog.sevagas.com/?Yet-another-sdclt-UAC-bypass) | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1548.002.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1548.002/T1548.002.md) | Start-Process -FilePath $env:windir\system32\sdclt.exe | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1548.002.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1548.002/T1548.002.md) | Target:	\system32\sdclt.exe | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)



MIT License. Copyright (c) 2020-2021 Strontic.


