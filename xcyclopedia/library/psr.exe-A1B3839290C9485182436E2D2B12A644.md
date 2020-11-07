---
title: psr.exe | Steps Recorder
excerpt: What is psr.exe?
---

# psr.exe 

* File Path: `C:\Windows\SysWOW64\psr.exe`
* Description: Steps Recorder

## Hashes

Type | Hash
-- | --
MD5 | `A1B3839290C9485182436E2D2B12A644`
SHA1 | `2842A3C8875BD3C214633554DDE47AC401EFE559`
SHA256 | `7D944CE0DFE4FAB3D6D56D7D30F2AF8615C6E4CF4311B589022C3BBAFB3B7411`
SHA384 | `125EE29982914E1BF9264FA2B11DFA4DD55ACBAADE7D8BA5A673CF5B0D24C6C7B20919991AA32D9E2CFA244915782A1D`
SHA512 | `18F5C1273D6F23EE73F1E3CF81A015888C48FCA469C4607120C376D1D310851F6C3C01204F5A22273FA30F6F80C0B49AF835D3F83F773CF51DC374C24061DB57`
SSDEEP | `6144:XskrYkkRu4JYf/DDVrkv2tde70JAVcD8LPhSiWofQr2k5l8BmMxowi/EH1qf:/hc9oLDVw2fucD8pellpco//EH1`
IMP | `712ABE6C53B8E8EA9FE1C6BA6DB384D2`
PESHA1 | `974EE29D5F7A0E30C3E69D260477A2869DA0F192`
PE256 | `99D6C5EE8309E81F2E2F00BBBECC90C391A421612F1B9E0B738F2E1779476773`

## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: psr.exe
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.17763.1282 (WinBuild.160101.0800)
* Product Version: 10.0.17763.1282
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/72
* VirusTotal Link: https://www.virustotal.com/gui/file/7d944ce0dfe4fab3d6d56d7d30f2af8615c6e4cf4311b589022c3bbafb3b7411/detection/

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Windows\system32\psr.exe](psr.exe-402F1EFF59C025CF3BB134B27CB1E729.md) | 60
[C:\windows\system32\psr.exe](psr.exe-4ABD52BC6FF33F33C8B930A8EB78D591.md) | 58
[C:\Windows\system32\psr.exe](psr.exe-93F9974E3ED1946C71D823925F6AC60E.md) | 58
[C:\windows\SysWOW64\psr.exe](psr.exe-61B53950F13B05BDA1653B0007C75F93.md) | 65
[C:\Windows\SysWOW64\psr.exe](psr.exe-D1D04E03BE76897B60E4CF5500007CAE.md) | 71

## Possible Misuse

*The following table contains possible examples of `psr.exe` being misused. While `psr.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_psr_capture_screenshots.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_psr_capture_screenshots.yml) | `title: Psr.exe Capture Screenshots` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_psr_capture_screenshots.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_psr_capture_screenshots.yml) | `description: The psr.exe captures desktop screenshots and saves them on the local machine` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_psr_capture_screenshots.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_psr_capture_screenshots.yml) | `Image\|endswith: '\Psr.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Psr.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/LOLUtilz/OSBinaries/Psr.yml) | `Name: Psr.exe` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Psr.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/LOLUtilz/OSBinaries/Psr.yml) | `- Command: psr.exe /start /gui 0 /output c:\users\user\out.zip` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Psr.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/LOLUtilz/OSBinaries/Psr.yml) | `- Command: psr.exe /start /maxsc 100 /gui 0 /output c:\users\user\out.zip` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Psr.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/LOLUtilz/OSBinaries/Psr.yml) | `- Command: psr.exe /stop` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Psr.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/LOLUtilz/OSBinaries/Psr.yml) | `- C:\Windows\System32\Psr.exe` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Psr.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/LOLUtilz/OSBinaries/Psr.yml) | `- C:\Windows\SysWOW64\Psr.exe` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Psr.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Psr.yml) | `Name: Psr.exe` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Psr.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Psr.yml) | `- Command: psr.exe /start /output D:\test.zip /sc 1 /gui 0` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Psr.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Psr.yml) | `Description: Record a user screen without creating a GUI. You should use "psr.exe /stop" to stop recording and create output file.` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Psr.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Psr.yml) | `- Path: c:\windows\system32\psr.exe` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Psr.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Psr.yml) | `- Path: c:\windows\syswow64\psr.exe` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Psr.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Psr.yml) | `- IOC: psr.exe spawned` | 
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1113.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1113/T1113.md) | Use Psr.exe binary to collect screenshots of user display. Test will do left mouse click to simulate user behaviour | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1113.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1113/T1113.md) | cmd /c start /b psr.exe /start /output #{output_file} /sc 1 /gui 0 /stopevent 12 | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1113.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1113/T1113.md) | cmd /c "timeout #{recording_time} > NULL && psr.exe /stop" | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)



MIT License. Copyright (c) 2020 Strontic.


