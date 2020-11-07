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
MD5 | `4685EDEA02ED044779578CE2AB9505FF`
SHA1 | `8B51E9E17F377A59DB2F89DCEB8B9EF4C7FFB9E8`
SHA256 | `F6BE29F4CFFABB00B95B7DE577E1138A34D1FBBBC4CE122536792276273E75DA`
SHA384 | `84D8D4F217B4F73CE90156B7D95B75BA7ED8765B5E82671C793DDA369D7A2EA725556A58DACDDD2A4E262954076240F7`
SHA512 | `6A35D9ED01600F5C04221DEB4A162A80C143385044458A30627014BC6D4B0DD9207F41335869498D526C3326A547B21ABCAEED80FFEB1E04C661C5A099653F20`
SSDEEP | `24576:2ywnRG0Nq1jwZMDW+zfh9yptQHZ7RHegR:WUB+P+TaQ5dH9`
IMP | `FF5971B8CA7F60994822E545275A6C4E`
PESHA1 | `A50CAAEB8737A7A5FF8E1BE7DBF097BDF7744CAE`
PE256 | `DC642C1BC9A04F39531246AE2D6387CB99992BD4D4A9F8A522589170BF16BDEE`

## Runtime Data

### Loaded Modules:

Path |
-- |
C:\Windows\System32\GDI32.dll |
C:\Windows\System32\gdi32full.dll |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\System32\msvcp_win.dll |
C:\Windows\System32\msvcrt.dll |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\system32\sdclt.exe |
C:\Windows\System32\ucrtbase.dll |
C:\Windows\System32\USER32.dll |
C:\Windows\System32\win32u.dll |


## Signature

* Status: Signature verified.
* Serial: `330000026551AE1BBD005CBFBD000000000265`
* Thumbprint: `E168609353F30FF2373157B4EB8CD519D07A2BFF`
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

* VirusTotal Detections: 0/68
* VirusTotal Link: https://www.virustotal.com/gui/file/f6be29f4cffabb00b95b7de577e1138a34d1fbbbc4ce122536792276273e75da/detection/

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Windows\system32\sdclt.exe](sdclt.exe-1A6DC77B647238046A1F466B72CC271B.md) | 99
[C:\Windows\system32\sdclt.exe](sdclt.exe-B0C397303D58CCC9E27BF71073E46F49.md) | 50
[C:\WINDOWS\system32\sdclt.exe](sdclt.exe-F96744B10792C70426608E670C0E39DB.md) | 46

## Possible Misuse

*The following table contains possible examples of `sdclt.exe` being misused. While `sdclt.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

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


