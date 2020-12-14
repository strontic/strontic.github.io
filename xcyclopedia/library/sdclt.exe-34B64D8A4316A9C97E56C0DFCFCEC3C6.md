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
MD5 | `34B64D8A4316A9C97E56C0DFCFCEC3C6`
SHA1 | `893E91C7E9437BFB701E3168B2273EBBFF63A0D6`
SHA256 | `58DD58A15DA129E44CA5116E2DA71A913ABD08C7DE7F3D2F3A843F867108F9A9`
SHA384 | `AED5E20BF06F172C07E72351B908729A75CDE0E625FB03F51E8D36D3A665E2B9D0CAEAB15650FA3666124367AB766D52`
SHA512 | `CE88C272CFDF74496E472B43107A62B24809B2E8168B78B3141EDCB417B8748243175610CEB922EB41F5509249F17797D552F10F6E9C034CCB5D0FB7BA095E44`
SSDEEP | `24576:sJjr1lDybzUNu/oCexZLIh9yptQHZ7RHegR:o9N2oHZ0aQ5dH9`
IMP | `1F4349F0C287A904C0483B5CD434DF28`
PESHA1 | `DD19610935D3258507BC19AC4019EAA7B900B434`
PE256 | `ED4DA34405E051AFE8741B8CD83FE2AEC37A58B240DFCBCBE2C241BE36F335BF`

## Runtime Data

### Loaded Modules:

Path |
-- |
C:\Windows\System32\combase.dll |
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
C:\Windows\system32\SPP.dll |
C:\Windows\System32\ucrtbase.dll |
C:\Windows\System32\USER32.dll |
C:\Windows\System32\win32u.dll |


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
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

* VirusTotal Detections: 0/75
* VirusTotal Link: https://www.virustotal.com/gui/file/58dd58a15da129e44ca5116e2da71a913abd08c7de7f3d2f3a843f867108f9a9/detection

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Windows\system32\sdclt.exe](sdclt.exe-1A6DC77B647238046A1F466B72CC271B.md) | 50
[C:\Windows\system32\sdclt.exe](sdclt.exe-4685EDEA02ED044779578CE2AB9505FF.md) | 50
[C:\Windows\system32\sdclt.exe](sdclt.exe-B0C397303D58CCC9E27BF71073E46F49.md) | 96
[C:\WINDOWS\system32\sdclt.exe](sdclt.exe-F96744B10792C70426608E670C0E39DB.md) | 50

## Possible Misuse

*The following table contains possible examples of `sdclt.exe` being misused. While `sdclt.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_comhijack_sdclt.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/registry_event/sysmon_comhijack_sdclt.yml) | `title: COM Hijack via Sdclt` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_comhijack_sdclt.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/registry_event/sysmon_comhijack_sdclt.yml) | `- http://blog.sevagas.com/?Yet-another-sdclt-UAC-bypass` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_uac_bypass_sdclt.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/registry_event/sysmon_uac_bypass_sdclt.yml) | `title: UAC Bypass via Sdclt` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_uac_bypass_sdclt.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/registry_event/sysmon_uac_bypass_sdclt.yml) | `- https://enigma0x3.net/2017/03/17/fileless-uac-bypass-using-sdclt-exe/` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[malware-ioc](https://github.com/eset/malware-ioc) | [misp_invisimole.json](https://github.com/eset/malware-ioc/blob/master/invisimole/misp_invisimole.json) | `"https://enigma0x3.net/2017/03/17/fileless-uac-bypass-using-sdclt-exe/"` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [index.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Indexes-Markdown/index.md) | - Atomic Test #7: Bypass UAC using sdclt DelegateExecute [windows] | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [windows-index.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Indexes-Markdown/windows-index.md) | - Atomic Test #7: Bypass UAC using sdclt DelegateExecute [windows] | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1548.002.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1548.002/T1548.002.md) | - [Atomic Test #7 - Bypass UAC using sdclt DelegateExecute](#atomic-test-7---bypass-uac-using-sdclt-delegateexecute) | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1548.002.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1548.002/T1548.002.md) | ## Atomic Test #7 - Bypass UAC using sdclt DelegateExecute | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1548.002.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1548.002/T1548.002.md) | Upon successful execution, sdclt.exe will spawn cmd.exe to spawn notepad.exe | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1548.002.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1548.002/T1548.002.md) | [Reference - sevagas.com](http://blog.sevagas.com/?Yet-another-sdclt-UAC-bypass) | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1548.002.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1548.002/T1548.002.md) | Start-Process -FilePath $env:windir\system32\sdclt.exe | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)



MIT License. Copyright (c) 2020 Strontic.


