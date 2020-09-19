---
title: control.exe | Windows Control Panel
---

# control.exe 

* File Path: `C:\Windows\SysWOW64\control.exe`
* Description: Windows Control Panel

## Hashes

Type | Hash
-- | --
MD5 | `359DE40504BF90EFD590C248B71C8B81`
SHA1 | `4361E1B498CA3025E641280FC4F71BF93AE5201C`
SHA256 | `76D741C6FEDC2426483EBEE82AED4193F1DFFEC531154BC5EAD024BE1119A564`
SHA384 | `3C49A4FB7E8907D45B5539875EDEA5EFD3A1F081A67BCDCE2214D9B7F259AA8D6F1AAB735A732AA2E1E15F3584D8E3B4`
SHA512 | `02D4CF8A0E3569E562A4A63A179AD1567FA3DFD9DA1E2A332DF7F03B8574DCE318FA5D4D1B5EDE4EF56A5811BAB263B28218ADBBB76AE179D128AE12AF001461`
SSDEEP | `1536:dvJSk5ae/qzSpZ3r1q6QkjfkQUk8+k6kawM1x8Dkf8dani25imKvM:Ska7Sp5+1k12b/Af885RKv`

## Signature

* Status: Signature verified.
* Serial: `33000000BCE120FDD27CC8EE930000000000BC`
* Thumbprint: `E85459B23C232DB3CB94C7A56D47678F58E8E51E`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: CONTROL.EXE
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.14393.0 (rs1_release.160715-1616)
* Product Version: 10.0.14393.0
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Windows\system32\control.exe](control.exe-3011923664DA91ED45B0FA6AE852DD1A.md) | 66
[C:\windows\system32\control.exe](control.exe-4B605DF70C49B6B9D65652879ACAEE32.md) | 82
[C:\WINDOWS\system32\control.exe](control.exe-62D970D8B60F75C12D21C740F2D8A5DA.md) | 83
[C:\Windows\system32\control.exe](control.exe-88EA810385F455C74306D71C4879C61C.md) | 80
[C:\Windows\system32\control.exe](control.exe-924219B426830FF7476AF7D22AE91DE1.md) | 85
[C:\Windows\system32\control.exe](control.exe-D7D596CA323E67AAE7F8752BD9B45A1E.md) | 82
[C:\Windows\SysWOW64\control.exe](control.exe-1F13E714A0FEA8887707DFF49287996F.md) | 85
[C:\Windows\SysWOW64\control.exe](control.exe-4DBD69D4C9DA5AAAC731F518EF8EBEA0.md) | 66
[C:\WINDOWS\SysWOW64\control.exe](control.exe-C7C91F18B0F90ABE6C09D3CEAA895E83.md) | 86
[C:\Windows\SysWOW64\control.exe](control.exe-C8FA632CEF3B25E6AAD2C3ACFCF98E59.md) | 85
[C:\windows\SysWOW64\control.exe](control.exe-F74B09C54E47526BB0679F8F0967AD0E.md) | 85

## Possible Misuse

*The following table contains possible examples of `control.exe` being misused. While `control.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_control_dll_load.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_control_dll_load.yml) | `description: Detects suspicious Rundll32 execution from control.exe as used by Equation Group and Exploit Kits` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_control_dll_load.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_control_dll_load.yml) | `ParentImage: '*\System32\control.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Control.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Control.yml) | `Name: Control.exe` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Control.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Control.yml) | `- Command: control.exe c:\windows\tasks\file.txt:evil.dll` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Control.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Control.yml) | `- Path: C:\Windows\System32\control.exe` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Control.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Control.yml) | `- Path: C:\Windows\SysWOW64\control.exe` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Control.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Control.yml) | `- IOC: Control.exe executing files from alternate data streams.` | 
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1218.002.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1218.002/T1218.002.md) | <blockquote>Adversaries may abuse control.exe to proxy execution of malicious payloads. The Windows Control Panel process binary (control.exe) handles execution of Control Panel items, which are utilities that allow users to view and adjust computer settings. Control Panel items are registered executable (.exe) or Control Panel (.cpl) files, the latter are actually renamed dynamic-link library (.dll) files that export a <code>CPlApplet</code> function. (Citation: Microsoft Implementing CPL) (Citation: TrendMicro CPL Malware Jan 2014) Control Panel items can be executed directly from the command line, programmatically via an application programming interface (API) call, or by simply double-clicking the file. (Citation: Microsoft Implementing CPL) (Citation: TrendMicro CPL Malware Jan 2014) (Citation: TrendMicro CPL Malware Dec 2013) | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1218.002.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1218.002/T1218.002.md) | This test simulates an adversary leveraging control.exe | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1218.002.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1218.002/T1218.002.md) | control.exe #{cpl_file_path} | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)



MIT License. Copyright (c) 2020 Strontic.


