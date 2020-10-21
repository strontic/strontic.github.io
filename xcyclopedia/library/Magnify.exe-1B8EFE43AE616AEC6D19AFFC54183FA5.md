---
title: Magnify.exe | Microsoft Screen Magnifier
excerpt: What is Magnify.exe?
---

# Magnify.exe 

* File Path: `C:\Windows\system32\Magnify.exe`
* Description: Microsoft Screen Magnifier

## Hashes

Type | Hash
-- | --
MD5 | `1B8EFE43AE616AEC6D19AFFC54183FA5`
SHA1 | `51E6426C2CD901332F48913ABF281711F71E8FA1`
SHA256 | `C4C643F6F8BBD577F3D108B8DFD14DD72DF32BF96A87C811F60D4240F7CA7306`
SHA384 | `62C2151E01C32AFBD4C5865A24358F9182FCBBE5B5A4999AA614904E7E6D12561F6B1D2DB79F15F1515F9C910D435440`
SHA512 | `6AF1129B4418F5DF1C738EE23757B20E4B714E4B19AB3D0C1CFFFB872729B631FDFA28B11B2E9360AEB44B89835853772F88CE81DD166295C7B3E88B33222151`
SSDEEP | `6144:gSbS7BH6ALCOX1VRJ1GdyGdTY/qbbVBDxra1xr4t9Mykz5gzNOx8XA08bAhMWUyJ:/bcBPnYdTYcfWGMtt8XOykpyk`
IMP | `89B08BB1E1A7820A0B6AF3CD06248264`
PESHA1 | `FD26E8B60859D42F0F01495D99F28821F4F67E01`
PE256 | `817FF08BF1351C2A5BF48B68061AEBFE04DFB2844D1712F64B55B6349453EAD7`

## Signature

* Status: Signature verified.
* Serial: `33000001C422B2F79B793DACB20000000001C4`
* Thumbprint: `AE9C1AE54763822EEC42474983D8B635116C8452`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: ScreenMagnifier.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.17763.1 (WinBuild.160101.0800)
* Product Version: 10.0.17763.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/70
* VirusTotal Link: https://www.virustotal.com/gui/file/c4c643f6f8bbd577f3d108b8dfd14dd72df32bf96a87c811f60d4240f7ca7306/detection/

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Windows\SysWOW64\Magnify.exe](Magnify.exe-FF2AF01E03CCD707B9DD937E49436F3F.md) | 43

## Possible Misuse

*The following table contains possible examples of `Magnify.exe` being misused. While `Magnify.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_install_reg_debugger_backdoor.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_install_reg_debugger_backdoor.yml) | `- '*\CurrentVersion\Image File Execution Options\magnify.exe*'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_stickykey_like_backdoor.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/registry_event/sysmon_stickykey_like_backdoor.yml) | `- '*\SOFTWARE\Microsoft\Windows NT\CurrentVersion\Image File Execution Options\Magnify.exe\Debugger'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_stickykey_like_backdoor.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/registry_event/sysmon_stickykey_like_backdoor.yml) | `- '*cmd.exe Magnify.exe *'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1546.008.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1546.008/T1546.008.md) | * Magnifier: <code>C:\Windows\System32\Magnify.exe</code> | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1546.008.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1546.008/T1546.008.md) | \| parent_list \| Comma separated list of system binaries to which you want to attach each #{attached_process}. Default: "osk.exe" \| String \| osk.exe, sethc.exe, utilman.exe, magnify.exe, narrator.exe, DisplaySwitch.exe, atbroker.exe\| | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[signature-base](https://github.com/Neo23x0/signature-base) | [thor_inverse_matches.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/thor_inverse_matches.yar) | description = "Abnormal magnify.exe (Magnifier) - typical strings not found in file" | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [thor_inverse_matches.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/thor_inverse_matches.yar) | $winxp = "Software\\Microsoft\\Magnify" wide | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [thor_inverse_matches.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/thor_inverse_matches.yar) | filename =="magnify.exe" | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)



MIT License. Copyright (c) 2020 Strontic.


