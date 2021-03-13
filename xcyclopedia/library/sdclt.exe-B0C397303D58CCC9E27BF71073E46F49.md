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
MD5 | `B0C397303D58CCC9E27BF71073E46F49`
SHA1 | `AEE738CF3F4D541BD0964D065BED7F00CA443B65`
SHA256 | `1558A9DC9D6749DDA20A1846CD26887486AF40C569C9A1DEB911C43A78A61978`
SHA384 | `69A5EFF1D3406293C8F35B0DFCDB20CF52A99C2F2FBEBF051571F42FCD780DA273EBD495BA79B0EA568F1F494C79CBFB`
SHA512 | `DD661785D2CD88F5C0B0AD3D0BD2CA619D7AC402AB0034B002F4713231A3B4499BB2AA08EEC3B4C8F98AA262D21C1C691B40D11466689A61ED52ECFFE0404C26`
SSDEEP | `24576:MJjr1lDybzUNu/oCexLLIh9yptQHZ7RHegR:I9N2oHL0aQ5dH9`
IMP | `1F4349F0C287A904C0483B5CD434DF28`
PESHA1 | `4F85C7D7D15E8ACC1AB02AEB6B69225EF2ABF0BB`
PE256 | `24DA4585652C7E758CFCE71E432EC00D65DA3944F79BBF3D4851040B07D41CCF`

## Runtime Data

### Loaded Modules:

Path |
-- |
C:\Windows\System32\advapi32.dll |
C:\Windows\system32\bcd.dll |
C:\Windows\System32\bcrypt.dll |
C:\Windows\system32\Cabinet.dll |
C:\Windows\System32\combase.dll |
C:\Windows\System32\CRYPT32.dll |
C:\Windows\system32\DPAPI.DLL |
C:\Windows\System32\GDI32.dll |
C:\Windows\System32\gdi32full.dll |
C:\Windows\System32\imagehlp.dll |
C:\Windows\System32\IMM32.DLL |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\system32\MPR.dll |
C:\Windows\System32\msvcp_win.dll |
C:\Windows\System32\msvcrt.dll |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\ole32.dll |
C:\Windows\System32\OLEAUT32.dll |
C:\Windows\system32\ReAgent.dll |
C:\Windows\System32\RPCRT4.dll |
C:\Windows\system32\sdclt.exe |
C:\Windows\System32\sechost.dll |
C:\Windows\System32\SHELL32.dll |
C:\Windows\System32\SHLWAPI.dll |
C:\Windows\system32\SPP.dll |
C:\Windows\system32\SspiCli.dll |
C:\Windows\System32\ucrtbase.dll |
C:\Windows\System32\USER32.dll |
C:\Windows\system32\UxTheme.dll |
C:\Windows\system32\VSSAPI.DLL |
C:\Windows\system32\VssTrace.DLL |
C:\Windows\system32\wer.dll |
C:\Windows\System32\win32u.dll |
C:\Windows\System32\WS2_32.dll |
C:\Windows\system32\WTSAPI32.dll |
C:\Windows\WinSxS\amd64_microsoft.windows.common-controls_6595b64144ccf1df_6.0.19041.488_none_ca04af081b815d21\COMCTL32.dll |


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

* VirusTotal Detections: 0/76
* VirusTotal Link: https://www.virustotal.com/gui/file/1558a9dc9d6749dda20a1846cd26887486af40c569c9a1deb911c43a78a61978/detection

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Windows\system32\sdclt.exe](sdclt.exe-1A6DC77B647238046A1F466B72CC271B.md) | 50
[C:\Windows\system32\sdclt.exe](sdclt.exe-34B64D8A4316A9C97E56C0DFCFCEC3C6.md) | 96
[C:\Windows\system32\sdclt.exe](sdclt.exe-4685EDEA02ED044779578CE2AB9505FF.md) | 50
[C:\WINDOWS\system32\sdclt.exe](sdclt.exe-F96744B10792C70426608E670C0E39DB.md) | 52

## Possible Misuse

*The following table contains possible examples of `sdclt.exe` being misused. While `sdclt.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_comhijack_sdclt.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/registry_event/sysmon_comhijack_sdclt.yml) | `title: COM Hijack via Sdclt`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_comhijack_sdclt.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/registry_event/sysmon_comhijack_sdclt.yml) | `- http://blog.sevagas.com/?Yet-another-sdclt-UAC-bypass`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_uac_bypass_sdclt.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/registry_event/sysmon_uac_bypass_sdclt.yml) | `title: UAC Bypass via Sdclt`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_uac_bypass_sdclt.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/registry_event/sysmon_uac_bypass_sdclt.yml) | `- https://enigma0x3.net/2017/03/17/fileless-uac-bypass-using-sdclt-exe/`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[malware-ioc](https://github.com/eset/malware-ioc) | [misp_invisimole.json](https://github.com/eset/malware-ioc/blob/master/invisimole/misp_invisimole.json) | `"https://enigma0x3.net/2017/03/17/fileless-uac-bypass-using-sdclt-exe/"`{:.highlight .language-cmhg} | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [index.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Indexes-Markdown/index.md) | - Atomic Test #7: Bypass UAC using sdclt DelegateExecute [windows] | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [windows-index.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Indexes-Markdown/windows-index.md) | - Atomic Test #7: Bypass UAC using sdclt DelegateExecute [windows] | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1548.002.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1548.002/T1548.002.md) | - [Atomic Test #7 - Bypass UAC using sdclt DelegateExecute](#atomic-test-7---bypass-uac-using-sdclt-delegateexecute) | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1548.002.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1548.002/T1548.002.md) | ## Atomic Test #7 - Bypass UAC using sdclt DelegateExecute | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1548.002.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1548.002/T1548.002.md) | Upon successful execution, sdclt.exe will spawn cmd.exe to spawn notepad.exe | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1548.002.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1548.002/T1548.002.md) | [Reference - sevagas.com](http://blog.sevagas.com/?Yet-another-sdclt-UAC-bypass) | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1548.002.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1548.002/T1548.002.md) | Start-Process -FilePath $env:windir\system32\sdclt.exe | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)



MIT License. Copyright (c) 2020-2021 Strontic.


