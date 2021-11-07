---
title: taskhostw.exe | Host Process for Windows Tasks
excerpt: What is taskhostw.exe?
---

# taskhostw.exe 

* File Path: `C:\Windows\system32\taskhostw.exe`
* Description: Host Process for Windows Tasks

## Hashes

Type | Hash
-- | --
MD5 | `564E4806AB18F93B93D551CD10C1598E`
SHA1 | `FED4B4A753A9541389AA670C69E624BE07569CCD`
SHA256 | `0322728DBCE3A577C4A13B907AD7375D27E74880B63F7371384F67D19197A0AD`
SHA384 | `E8E0EE7C479169594CB84F08BF7EE71DB5035BFE42FA70C5FF0A736727B08D0B3FF486F692BF2D48207EFA04C78ECDAE`
SHA512 | `93A45009870E62BB413E7A33FC4BCFFC63368666A655F5F379FCF28EBDF5A863BB5C704D68B8BE8788F71E593948BA000995B190BCC796E959A1BABEB6650BBF`
SSDEEP | `1536:u1ZCzBzDm9RGtcpHyxlLfE38VsPPh2mBqXh+MGfv6BirgrKdOcTyP:kEzp1tcJyxlLfE38wP7sXh+HfCogrKdO`
IMP | `3A0C6863CDE566AF997DB2DEFFF9D924`
PESHA1 | `ABE1D88E4F7F04DB390C7B9C0ADFF126F014DB9D`
PE256 | `7F9526E0716D16DAA47C95947D51342B375AC002148D3FD609761E00DE05931F`

## Runtime Data

### Loaded Modules:

Path |
-- |
C:\Windows\System32\combase.dll |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\System32\msvcrt.dll |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\RPCRT4.dll |
C:\Windows\system32\taskhostw.exe |
C:\Windows\System32\ucrtbase.dll |


## Signature

* Status: Signature verified.
* Serial: `33000002EC6579AD1E670890130000000002EC`
* Thumbprint: `F7C2F2C96A328C13CDA8CDB57B715BDEA2CBD1D9`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: taskhostw.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/73
* VirusTotal Link: https://www.virustotal.com/gui/file/0322728dbce3a577c4a13b907ad7375d27e74880b63f7371384f67d19197a0ad/detection

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Windows\system32\taskhostw.exe](taskhostw.exe-536B1BEBA7BF2037BF27CD5BC6654696.md) | 44
[C:\Windows\system32\taskhostw.exe](taskhostw.exe-AF8D8590B0F74A7F514438DF3F1F4C22.md) | 82
[C:\Windows\system32\taskhostw.exe](taskhostw.exe-B2B02A857A2AA316EC17DD3BC73406C3.md) | 94

## Possible Misuse

*The following table contains possible examples of `taskhostw.exe` being misused. While `taskhostw.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_wmi_module_load.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/image_load/sysmon_wmi_module_load.yml) | `- '\windows\system32\taskhostw.exe'  # c:\windows\system32\taskhostw.exe`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_suspicious_vss_ps_load.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/image_load/win_suspicious_vss_ps_load.yml) | `- 'taskhostw.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [index.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Indexes-Markdown/index.md) | - Atomic Test #5: Masquerading - powershell.exe running as taskhostw.exe [windows] | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [windows-index.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Indexes-Markdown/windows-index.md) | - Atomic Test #5: Masquerading - powershell.exe running as taskhostw.exe [windows] | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1036.003.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1036.003/T1036.003.md) | - [Atomic Test #5 - Masquerading - powershell.exe running as taskhostw.exe](#atomic-test-5---masquerading---powershellexe-running-as-taskhostwexe) | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1036.003.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1036.003/T1036.003.md) | ## Atomic Test #5 - Masquerading - powershell.exe running as taskhostw.exe | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1036.003.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1036.003/T1036.003.md) | Copies powershell.exe, renames it, and launches it to masquerade as an instance of taskhostw.exe. | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1036.003.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1036.003/T1036.003.md) | Upon successful execution, powershell.exe is renamed as taskhostw.exe and executed from non-standard path. | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1036.003.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1036.003/T1036.003.md) | copy %windir%\System32\windowspowershell\v1.0\powershell.exe %APPDATA%\taskhostw.exe /Y | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1036.003.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1036.003/T1036.003.md) | cmd.exe /K %APPDATA%\taskhostw.exe | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1036.003.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1036.003/T1036.003.md) | del /Q /F %APPDATA%\taskhostw.exe >nul 2>&1 | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)



MIT License. Copyright (c) 2020-2021 Strontic.


