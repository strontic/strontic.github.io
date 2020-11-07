---
title: consent.exe | Consent UI for administrative applications
excerpt: What is consent.exe?
---

# consent.exe 

* File Path: `C:\Windows\system32\consent.exe`
* Description: Consent UI for administrative applications

## Hashes

Type | Hash
-- | --
MD5 | `E3D1802FA8697E9E761F6D501E45BF0A`
SHA1 | `C8B5B30FFEE0EFC22A2B6F8E81A9CC9C97A1ED43`
SHA256 | `BAF527D2F09EC003BB3E399347056A3EE2AD60F4E07E4010CE858ECCE697EC75`
SHA384 | `45DE5763DEA25181F69A5CE51BA300EA7D1E24A18DD02F1234D1DE0DB51C552CAF0677341864A31D34082476D5F53E6C`
SHA512 | `B96A0B98226E47F322A62922952A6DACD821D19E8DB070B14E238032C351B2656CC494054C35477428955F6D52E88F62CF8555EE4CAE70EB651FBF3DC51373AD`
SSDEEP | `3072:C8m2NJJZ3SiT6P6Yfdj+6ir9ORhsjz+gE:C8mAFrTrYfdj+6nROjz6`
IMP | `ACAFC223D6C3FCAE537D9630A0021EFD`
PESHA1 | `25EDAA786E00B3316CA4CF31F8E21A583E41A986`
PE256 | `F7D7C6D2226A17282149496B21EB29F9125BDC2B7B112C25D0A8F9B505DF1477`

## Runtime Data

### Loaded Modules:

Path |
-- |
C:\Windows\SYSTEM32\Amsi.dll |
C:\Windows\System32\combase.dll |
C:\Windows\system32\consent.exe |
C:\Windows\System32\CRYPT32.dll |
C:\Windows\System32\GDI32.dll |
C:\Windows\System32\gdi32full.dll |
C:\Windows\System32\IMM32.dll |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\System32\MSCTF.dll |
C:\Windows\SYSTEM32\MsCtfMonitor.DLL |
C:\Windows\SYSTEM32\MSIMG32.dll |
C:\Windows\system32\MSUTB.dll |
C:\Windows\System32\msvcp_win.dll |
C:\Windows\System32\msvcrt.dll |
C:\Windows\SYSTEM32\netutils.dll |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\OLEAUT32.dll |
C:\Windows\System32\RPCRT4.dll |
C:\Windows\SYSTEM32\samcli.dll |
C:\Windows\System32\sechost.dll |
C:\Windows\SYSTEM32\SspiCli.dll |
C:\Windows\System32\ucrtbase.dll |
C:\Windows\System32\USER32.dll |
C:\Windows\SYSTEM32\USERENV.dll |
C:\Windows\System32\win32u.dll |
C:\Windows\system32\WINSTA.dll |
C:\Windows\SYSTEM32\WMsgAPI.dll |
C:\Windows\SYSTEM32\WTSAPI32.dll |
C:\Windows\WinSxS\amd64_microsoft.windows.common-controls_6595b64144ccf1df_6.0.19041.488_none_ca04af081b815d21\COMCTL32.dll |


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: consent.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/76
* VirusTotal Link: https://www.virustotal.com/gui/file/baf527d2f09ec003bb3e399347056a3ee2ad60f4e07e4010ce858ecce697ec75/detection


## Possible Misuse

*The following table contains possible examples of `consent.exe` being misused. While `consent.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_exploit_cve_2019_1388.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_exploit_cve_2019_1388.yml) | `description: Detects an explotation attempt in which the UAC consent dialogue is used to invoke an Internet Explorer process running as LOCAL_SYSTEM` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_exploit_cve_2019_1388.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_exploit_cve_2019_1388.yml) | `ParentImage: '*\consent.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1134.004.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1134.004/T1134.004.md) | <blockquote>Adversaries may spoof the parent process identifier (PPID) of a new process to evade process-monitoring defenses or to elevate privileges. New processes are typically spawned directly from their parent, or calling, process unless explicitly specified. One way of explicitly assigning the PPID of a new process is via the <code>CreateProcess</code> API call, which supports a parameter that defines the PPID to use.(Citation: DidierStevens SelectMyParent Nov 2009) This functionality is used by Windows features such as User Account Control (UAC) to correctly set the PPID after a requested elevated process is spawned by SYSTEM (typically via <code>svchost.exe</code> or <code>consent.exe</code>) rather than the current user context.(Citation: Microsoft UAC Nov 2018) | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[signature-base](https://github.com/Neo23x0/signature-base) | [exploit_cve_2015_5119.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/exploit_cve_2015_5119.yar) | yaraexchange = "No distribution without author's consent" | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)



MIT License. Copyright (c) 2020 Strontic.


