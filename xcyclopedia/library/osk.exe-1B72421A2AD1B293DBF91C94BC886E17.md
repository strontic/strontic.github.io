---
title: osk.exe | Accessibility On-Screen Keyboard
excerpt: What is osk.exe?
---

# osk.exe 

* File Path: `C:\WINDOWS\system32\osk.exe`
* Description: Accessibility On-Screen Keyboard

## Screenshot

![osk.exe](screenshots/osk.exe-745F2DF5BEED97B8C751DF83938CB418-1.png)

## Hashes

Type | Hash
-- | --
MD5 | `1B72421A2AD1B293DBF91C94BC886E17`
SHA1 | `5C5654DB530C2578288B066B4B717EA73A33B3DC`
SHA256 | `FD323D368264F51AC8A762C6A164DE8E780BF4CCF28C98F938139FE13530D21D`
SHA384 | `628548B1915624D3F29E4CCAD2041C8E45CB8C8F7128C3C0873F26AD5258999AA20F485349705DC73D52C6F17E8BFA10`
SHA512 | `C260DD8136A346910BC663F16CE93C882252AD4C2EC3EE29D28FD199FEB1361DE3D391041998C95629D2CF3521C22576C76B57B33CB876F7DFFD2FB0B7EC37B3`
SSDEEP | `6144:e9GRJ0wNLUrGOepuMPtxEOIc1OcvH3AdKy9HGeofJgDEvr6slnCUGw/xIRLtxIRR:9ROkUrGPsjmNwzaoo`
IMP | `7ABC6B524143B385A4A2A788AA31BBE7`
PESHA1 | `D4CA22307CBAF15F4F0C863B35CD726C3DA9360D`
PE256 | `D1F68B50A090C1EC2F9EE994E832880B726A47EF81B84DB31A8577A3AE12A632`

## Signature

* Status: Signature verified.
* Serial: `33000002ED2C45E4C145CF48440000000002ED`
* Thumbprint: `312860D2047EB81F8F58C29FF19ECDB4C634CF6A`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: osk.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.22000.1 (WinBuild.160101.0800)
* Product Version: 10.0.22000.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/74
* VirusTotal Link: https://www.virustotal.com/gui/file/fd323d368264f51ac8a762c6a164de8e780bf4ccf28c98f938139fe13530d21d/detection

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\windows\system32\osk.exe](osk.exe-17BD0C6AA822D5957EF63E3884CF5BC2.md) | 50
[C:\Windows\system32\osk.exe](osk.exe-745F2DF5BEED97B8C751DF83938CB418.md) | 68
[C:\WINDOWS\system32\osk.exe](osk.exe-9237BD6C14767145300EA58ACC2F20F9.md) | 66
[C:\Windows\system32\osk.exe](osk.exe-B160BA195ACC126E2ECA539094914688.md) | 69
[C:\Windows\system32\osk.exe](osk.exe-C6012DC3DBF49FBD67DBF57F1DE35E35.md) | 65
[C:\windows\SysWOW64\osk.exe](osk.exe-8519218ECB3C67B13A7CCAD4453B6012.md) | 61
[C:\Windows\SysWOW64\osk.exe](osk.exe-D49B6A24B175D6377AD62E9C6690E75B.md) | 65

## Possible Misuse

*The following table contains possible examples of `osk.exe` being misused. While `osk.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [file_event_uac_bypass_wmp.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/file_event/file_event_uac_bypass_wmp.yml) | `TargetFilename: 'C:\Program Files\Windows Media Player\osk.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [process_creation_stickykey_like_backdoor.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/process_creation_stickykey_like_backdoor.yml) | `- 'osk.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_install_reg_debugger_backdoor.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_install_reg_debugger_backdoor.yml) | `- 'osk.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_uac_bypass_wmp.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_uac_bypass_wmp.yml) | `Image: 'C:\Program Files\Windows Media Player\osk.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [registry_event_stickykey_like_backdoor.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/registry_event/registry_event_stickykey_like_backdoor.yml) | `- '\SOFTWARE\Microsoft\Windows NT\CurrentVersion\Image File Execution Options\osk.exe\Debugger'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [registry_event_uac_bypass_wmp.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/registry_event/registry_event_uac_bypass_wmp.yml) | `TargetObject\|endswith: '\SOFTWARE\Microsoft\Windows NT\CurrentVersion\AppCompatFlags\Compatibility Assistant\Store\C:\Program Files\Windows Media Player\osk.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Wmic.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Wmic.yml) | `- Command: wmic.exe process call create "C:\Windows\system32\reg.exe add \"HKLM\SOFTWARE\Microsoft\Windows NT\CurrentVersion\Image File Execution Options\osk.exe\" /v \"Debugger\" /t REG_SZ /d \"cmd.exe\" /f"`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Wmic.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Wmic.yml) | `Description: Add cmd.exe as a debugger for the osk.exe process. Each time osk.exe is run, cmd.exe will be run as well.`{:.highlight .language-yaml} | 
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1546.008.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1546.008/T1546.008.md) | * On-Screen Keyboard: <code>C:\Windows\System32\osk.exe</code> | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1546.008.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1546.008/T1546.008.md) | Upon successful execution, powershell will modify the registry and swap osk.exe with cmd.exe. | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1546.008.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1546.008/T1546.008.md) | \| parent_list \| Comma separated list of system binaries to which you want to attach each #{attached_process}. Default: "osk.exe" \| String \| osk.exe, sethc.exe, utilman.exe, magnify.exe, narrator.exe, DisplaySwitch.exe, atbroker.exe\| | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[signature-base](https://github.com/Neo23x0/signature-base) | [thor_inverse_matches.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/thor_inverse_matches.yar) | description = "Abnormal osk.exe (On Screen Keyboard) - typical strings not found in file" | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [thor_inverse_matches.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/thor_inverse_matches.yar) | filename == "osk.exe" | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)



MIT License. Copyright (c) 2020-2021 Strontic.


