---
title: control.exe | Windows Control Panel
---

# control.exe 

* File Path: `C:\Windows\system32\control.exe`
* Description: Windows Control Panel
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `88EA810385F455C74306D71C4879C61C`
SHA1 | `391FF1F690C0912C217B3CF625900D4F50128867`
SHA256 | `4774A931C9D97828323C9E829917D82C27A05DAB9FEA6A0CEF9EBBA59942231F`
SHA384 | `2D51CBBBEA71C5A687265880F9217579E944B4B2FD674EFF2084346B091B17F0837AA760802D1B7DDC40735BD10B7E45`
SHA512 | `D816977F9B9B147050937DF7663BE074FD44AA6DBFF608A0E673BC2739FC1A1DBEE506668A252D0A3A0B7E430A9B084502A9E7F7D4BB5EE69621FEFE861D5646`
SSDEEP | `1536:trl0+A4FF/P4yXBe/qzSpZ3r1q6QkjfkQUk8+k6kawM1x8Dkf8dani25imK:tyt43/g4B7Sp5+1k12b/Af885RK`

## Runtime Data

### Usage (stdout):
```Batchfile

```

### Usage (stderr):
```Batchfile

```

### Child Processes:


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

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\WINDOWS\system32\control.exe](control.exe-62D970D8B60F75C12D21C740F2D8A5DA.md) | 83
[C:\Windows\system32\control.exe](control.exe-924219B426830FF7476AF7D22AE91DE1.md) | 77
[C:\Windows\system32\control.exe](control.exe-D7D596CA323E67AAE7F8752BD9B45A1E.md) | 79
[C:\Windows\SysWOW64\control.exe](control.exe-1F13E714A0FEA8887707DFF49287996F.md) | 85
[C:\Windows\SysWOW64\control.exe](control.exe-359DE40504BF90EFD590C248B71C8B81.md) | 80
[C:\WINDOWS\SysWOW64\control.exe](control.exe-C7C91F18B0F90ABE6C09D3CEAA895E83.md) | 82
[C:\Windows\SysWOW64\control.exe](control.exe-C8FA632CEF3B25E6AAD2C3ACFCF98E59.md) | 83

## Possible Misuse

*The following table contains possible examples of `control.exe` being misused. While `control.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_control_dll_load.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_control_dll_load.yml) | `description: Detects suspicious Rundll32 execution from control.exe as used by Equation Group and Exploit Kits` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_control_dll_load.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_control_dll_load.yml) | `        ParentImage: '*\System32\control.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Control.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Control.yml) | `Name: Control.exe` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Control.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Control.yml) | `  - Command: control.exe c:\windows\tasks\file.txt:evil.dll` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Control.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Control.yml) | `  - Path: C:\Windows\System32\control.exe` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Control.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Control.yml) | `  - Path: C:\Windows\SysWOW64\control.exe` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Control.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Control.yml) | ` - IOC: Control.exe executing files from alternate data streams.` | 
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1218.002.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1218.002/T1218.002.md) | <blockquote>Adversaries may abuse control.exe to proxy execution of malicious payloads. The Windows Control Panel process binary (control.exe) handles execution of Control Panel items, which are utilities that allow users to view and adjust computer settings. Control Panel items are registered executable (.exe) or Control Panel (.cpl) files, the latter are actually renamed dynamic-link library (.dll) files that export a <code>CPlApplet</code> function. (Citation: Microsoft Implementing CPL) (Citation: TrendMicro CPL Malware Jan 2014) Control Panel items can be executed directly from the command line, programmatically via an application programming interface (API) call, or by simply double-clicking the file. (Citation: Microsoft Implementing CPL) (Citation: TrendMicro CPL Malware Jan 2014) (Citation: TrendMicro CPL Malware Dec 2013) | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1218.002.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1218.002/T1218.002.md) | This test simulates an adversary leveraging control.exe | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1218.002.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1218.002/T1218.002.md) | control.exe #{cpl_file_path} | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)



MIT License. Copyright (c) 2020 Strontic.


