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
MD5 | `1A6DC77B647238046A1F466B72CC271B`
SHA1 | `97180ED11BBB2C39D91D69C80A88376269CF5011`
SHA256 | `E6A113C31ABCAE8845D15E3F3637DD2317DD0268A73BF2688FF6F020C7FE85C9`
SHA384 | `DB0EB093A248BEFA5CD534425651FA02A5A66807EFDC99AD26836004FC25A744C62DB9FC1DCA6B91B6B2AC66482CBBB6`
SHA512 | `B21C8166CCCC2589EA4E783FC6C770100E9FB9DFB234EE731572CF9E4BD87D76A2A44BE036FA0A80636EE978B5C2FE76F082CE7043D1025AE2F17327E118FD11`
SSDEEP | `24576:VywnRG0Nq1jwZMDW+zfh9yptQHZ7RHegR:7UB+P+TaQ5dH9`

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


## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Windows\system32\sdclt.exe](sdclt.exe-4685EDEA02ED044779578CE2AB9505FF.md) | 99
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


