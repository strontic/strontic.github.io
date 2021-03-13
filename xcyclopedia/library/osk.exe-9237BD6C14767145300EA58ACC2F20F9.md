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
MD5 | `9237BD6C14767145300EA58ACC2F20F9`
SHA1 | `697D4D6DF64A252540EE32CE56B93EC8EFE3F462`
SHA256 | `53809B7DDDB65CE004076B282A039CA682F68CD3211A48237A71C2CCB0DC7003`
SHA384 | `A69DE3F453CC1F594F3B121B6E6C5402DFDDE756D20463575CDCA62A1BC1A3DE814A78ED52D82AE02F9828824DC2DB66`
SHA512 | `FA43B46827996840E1E4FCDC550009E804A028F15D40432C8F521BB0FB97EECC33B4E92454F0D4A7F84E4BBBDD57A55E919CF2E527703E19244C881DB1F9DAA4`
SSDEEP | `6144:B2Ra26o168mOoqzetK32tr7HHc1OcvH3AdKy9HGeofJgDEvr6slnCUGw/xIRLtxM:TRo1Bm3qzetyqftjmNwzaoo`

## Signature

* Status: Signature verified.
* Serial: `330000023241FB59996DCC4DFF000000000232`
* Thumbprint: `FF82BC38E1DA5E596DF374C53E3617F7EDA36B06`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: osk.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.18362.1 (WinBuild.160101.0800)
* Product Version: 10.0.18362.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.


## File Similarity (ssdeep match)

File | Score
-- | --
[C:\windows\system32\osk.exe](osk.exe-17BD0C6AA822D5957EF63E3884CF5BC2.md) | 52
[C:\Windows\system32\osk.exe](osk.exe-745F2DF5BEED97B8C751DF83938CB418.md) | 65
[C:\Windows\system32\osk.exe](osk.exe-B160BA195ACC126E2ECA539094914688.md) | 66
[C:\Windows\system32\osk.exe](osk.exe-C6012DC3DBF49FBD67DBF57F1DE35E35.md) | 61
[C:\windows\SysWOW64\osk.exe](osk.exe-8519218ECB3C67B13A7CCAD4453B6012.md) | 61
[C:\Windows\SysWOW64\osk.exe](osk.exe-D49B6A24B175D6377AD62E9C6690E75B.md) | 61

## Possible Misuse

*The following table contains possible examples of `osk.exe` being misused. While `osk.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_install_reg_debugger_backdoor.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_install_reg_debugger_backdoor.yml) | `- '*\CurrentVersion\Image File Execution Options\osk.exe*'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_stickykey_like_backdoor.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/registry_event/sysmon_stickykey_like_backdoor.yml) | `- '*\SOFTWARE\Microsoft\Windows NT\CurrentVersion\Image File Execution Options\osk.exe\Debugger'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_stickykey_like_backdoor.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/registry_event/sysmon_stickykey_like_backdoor.yml) | `- '*cmd.exe osk.exe *'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Wmic.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Wmic.yml) | `- Command: wmic.exe process call create "C:\Windows\system32\reg.exe add \"HKLM\SOFTWARE\Microsoft\Windows NT\CurrentVersion\Image File Execution Options\osk.exe\" /v \"Debugger\" /t REG_SZ /d \"cmd.exe\" /f"`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Wmic.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Wmic.yml) | `Description: Add cmd.exe as a debugger for the osk.exe process. Each time osk.exe is run, cmd.exe will be run as well.`{:.highlight .language-yaml} | 
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1546.008.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1546.008/T1546.008.md) | * On-Screen Keyboard: <code>C:\Windows\System32\osk.exe</code> | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1546.008.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1546.008/T1546.008.md) | Upon successful execution, powershell will modify the registry and swap osk.exe with cmd.exe. | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1546.008.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1546.008/T1546.008.md) | \| parent_list \| Comma separated list of system binaries to which you want to attach each #{attached_process}. Default: "osk.exe" \| String \| osk.exe, sethc.exe, utilman.exe, magnify.exe, narrator.exe, DisplaySwitch.exe, atbroker.exe\| | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[signature-base](https://github.com/Neo23x0/signature-base) | [thor_inverse_matches.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/thor_inverse_matches.yar) | description = "Abnormal osk.exe (On Screen Keyboard) - typical strings not found in file" | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [thor_inverse_matches.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/thor_inverse_matches.yar) | filename == "osk.exe" | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)



MIT License. Copyright (c) 2020-2021 Strontic.


