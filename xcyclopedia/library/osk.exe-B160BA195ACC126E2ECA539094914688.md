---
title: osk.exe | Accessibility On-Screen Keyboard
excerpt: What is osk.exe?
---

# osk.exe 

* File Path: `C:\Windows\system32\osk.exe`
* Description: Accessibility On-Screen Keyboard

## Screenshot

![osk.exe](screenshots/osk.exe-745F2DF5BEED97B8C751DF83938CB418-1.png)

## Hashes

Type | Hash
-- | --
MD5 | `B160BA195ACC126E2ECA539094914688`
SHA1 | `80BB21B6B77A671765219517D0D8E064E22396E2`
SHA256 | `79C62BDE821FBB73CCD72621E4EDDFF3D5DAE7B915BB7620084FA72E324B3CC0`
SHA384 | `43C20D2783F395B86D98065837ADE6932B900AE41EC55C0597CD19F4935C68E1AA9908C84E699F408300E95934A93521`
SHA512 | `579CD2E5A17F35D7A2487B229D3018D974A7A44D3380F2D697061B54D81E72FA472D8AEA59006F15FFB688E1C17E2CF9FC5E6CCA7A9072A59EEBB6DA10D1201B`
SSDEEP | `6144:Yb/lKGivRTnrr1hf7Wc1OcvH3AdKy9HGeofJgDEvr6slnCUGw/xIRLtxIRLuovZ:I9KGMRTXQjmNwzaoo`
IMP | `43F678788A11C4B7A238705AFC2BE436`
PESHA1 | `39623A1092AF6297730BBEC201290E2E00D5165E`
PE256 | `EBB2599536EF8C4810FC3A8191F64F56156E81ACB7A5EA730924661CA2A6FB92`

## Signature

* Status: Signature verified.
* Serial: `33000001C422B2F79B793DACB20000000001C4`
* Thumbprint: `AE9C1AE54763822EEC42474983D8B635116C8452`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: osk.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.17763.1 (WinBuild.160101.0800)
* Product Version: 10.0.17763.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/68
* VirusTotal Link: https://www.virustotal.com/gui/file/79c62bde821fbb73ccd72621e4eddff3d5dae7b915bb7620084fa72e324b3cc0/detection/

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\windows\system32\osk.exe](osk.exe-17BD0C6AA822D5957EF63E3884CF5BC2.md) | 50
[C:\WINDOWS\system32\osk.exe](osk.exe-1B72421A2AD1B293DBF91C94BC886E17.md) | 69
[C:\Windows\system32\osk.exe](osk.exe-745F2DF5BEED97B8C751DF83938CB418.md) | 72
[C:\WINDOWS\system32\osk.exe](osk.exe-9237BD6C14767145300EA58ACC2F20F9.md) | 66
[C:\Windows\system32\osk.exe](osk.exe-C6012DC3DBF49FBD67DBF57F1DE35E35.md) | 72
[C:\windows\SysWOW64\osk.exe](osk.exe-8519218ECB3C67B13A7CCAD4453B6012.md) | 65
[C:\Windows\SysWOW64\osk.exe](osk.exe-D49B6A24B175D6377AD62E9C6690E75B.md) | 72

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


