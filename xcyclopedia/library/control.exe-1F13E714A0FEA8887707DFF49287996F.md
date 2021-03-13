---
title: control.exe | Windows Control Panel
excerpt: What is control.exe?
---

# control.exe 

* File Path: `C:\Windows\SysWOW64\control.exe`
* Description: Windows Control Panel

## Hashes

Type | Hash
-- | --
MD5 | `1F13E714A0FEA8887707DFF49287996F`
SHA1 | `176B874D0C163C9561E35C0CF7EE4D5A56292877`
SHA256 | `CF19EAFF8AE1D6A4AB70A2E2CE996F49D3AFDC193EE8F69AEF881E5727BC8F38`
SHA384 | `93901F13FBA747693FD5E84E008511137BC5EE719D025F6EC2AE1D18D1EE95B725A27B7F534BCC6800DB322D80AD4A01`
SHA512 | `625221290EBDD98F75022A9FBFED9E4218A13B7F1CF062E9B4BC1FB48678E41B3C6A1FE7BFE9AC882245C86E4471E751765BA1F886BA605E348701E9A5CE09B8`
SSDEEP | `1536:pDhE4VlBe/qzSpZ3r1q6QkjfkQUk8+k6kawM1x8Dkf8dani25imK:lpzB7Sp5+1k12b/Af885RK`
IMP | `A3EBCFE0050EB5B2420A836D354C33A7`
PESHA1 | `0ED80D5F18920094D365BBC0090175181CCC42C9`
PE256 | `DED6B1CC2903F554CD0427153323658EF9BB4169D736594C7DD2B064726502E5`

## Runtime Data

### Loaded Modules:

Path |
-- |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\wow64.dll |
C:\Windows\System32\wow64cpu.dll |
C:\Windows\System32\wow64win.dll |
C:\Windows\SysWOW64\control.exe |


## Signature

* Status: Signature verified.
* Serial: `33000001C422B2F79B793DACB20000000001C4`
* Thumbprint: `AE9C1AE54763822EEC42474983D8B635116C8452`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: CONTROL.EXE
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.17763.1 (WinBuild.160101.0800)
* Product Version: 10.0.17763.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/71
* VirusTotal Link: https://www.virustotal.com/gui/file/cf19eaff8ae1d6a4ab70a2e2ce996f49d3afdc193ee8f69aef881e5727bc8f38/detection/

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Windows\system32\control.exe](control.exe-3011923664DA91ED45B0FA6AE852DD1A.md) | 66
[C:\windows\system32\control.exe](control.exe-4B605DF70C49B6B9D65652879ACAEE32.md) | 85
[C:\WINDOWS\system32\control.exe](control.exe-62D970D8B60F75C12D21C740F2D8A5DA.md) | 86
[C:\Windows\system32\control.exe](control.exe-88EA810385F455C74306D71C4879C61C.md) | 85
[C:\Windows\system32\control.exe](control.exe-924219B426830FF7476AF7D22AE91DE1.md) | 85
[C:\Windows\system32\control.exe](control.exe-D7D596CA323E67AAE7F8752BD9B45A1E.md) | 83
[C:\Windows\SysWOW64\control.exe](control.exe-359DE40504BF90EFD590C248B71C8B81.md) | 85
[C:\Windows\SysWOW64\control.exe](control.exe-4DBD69D4C9DA5AAAC731F518EF8EBEA0.md) | 63
[C:\WINDOWS\SysWOW64\control.exe](control.exe-C7C91F18B0F90ABE6C09D3CEAA895E83.md) | 85
[C:\Windows\SysWOW64\control.exe](control.exe-C8FA632CEF3B25E6AAD2C3ACFCF98E59.md) | 86
[C:\windows\SysWOW64\control.exe](control.exe-F74B09C54E47526BB0679F8F0967AD0E.md) | 86

## Possible Misuse

*The following table contains possible examples of `control.exe` being misused. While `control.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_control_dll_load.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_control_dll_load.yml) | `description: Detects suspicious Rundll32 execution from control.exe as used by Equation Group and Exploit Kits`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_control_dll_load.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_control_dll_load.yml) | `ParentImage: '*\System32\control.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Control.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Control.yml) | `Name: Control.exe`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Control.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Control.yml) | `- Command: control.exe c:\windows\tasks\file.txt:evil.dll`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Control.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Control.yml) | `- Path: C:\Windows\System32\control.exe`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Control.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Control.yml) | `- Path: C:\Windows\SysWOW64\control.exe`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Control.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Control.yml) | `- IOC: Control.exe executing files from alternate data streams.`{:.highlight .language-yaml} | 
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1218.002.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1218.002/T1218.002.md) | <blockquote>Adversaries may abuse control.exe to proxy execution of malicious payloads. The Windows Control Panel process binary (control.exe) handles execution of Control Panel items, which are utilities that allow users to view and adjust computer settings. | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1218.002.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1218.002/T1218.002.md) | This test simulates an adversary leveraging control.exe | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1218.002.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1218.002/T1218.002.md) | control.exe #{cpl_file_path} | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)



MIT License. Copyright (c) 2020-2021 Strontic.


