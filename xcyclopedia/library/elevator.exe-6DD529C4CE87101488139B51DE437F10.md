---
title: elevator.exe | Winamp Elevator
excerpt: What is elevator.exe?
---

# elevator.exe 

* File Path: `C:\Program Files (x86)\Winamp\elevator.exe`
* Description: Winamp Elevator

## Hashes

Type | Hash
-- | --
MD5 | `6DD529C4CE87101488139B51DE437F10`
SHA1 | `FD84787617E724541367DB78352FB7AA05C95322`
SHA256 | `961144FC083132D5FCBAFB87F69D0E3D5CD559F0E69C5692B10EC266F87259F9`
SHA384 | `70E05E85AEBE23613FDD6D92346762B81A2F6D0FD9ABBF3F353E2D6E5B80B35347BB48EA210D09FF5DF6B2B30AD5791D`
SHA512 | `5E9F7D59237E606926FD6FB0C7597B06BE22027FB75E99E8F67F486EA1A84CF7F6C08BC3F39E9BB1794D6F536EAE4F9F64415C51FDA23F9E24722EBA36B2963D`
SSDEEP | `1536:48hVJ6v66ZL3xfOgzWWxVz7MW/UXVue/mMnl:48rtWzxfOgzWy57elue/mMnl`
IMP | `0B05EA66BD9167B4E62A28AA889C2D57`
PESHA1 | `AC5D45BE82E7A2AC5707E81CAF7E6F19D726D7F8`
PE256 | `083AB8C111DEAACFBB555F829F182765E29A85BDBCD1DAB0FE73BEA42CA0D73E`

## Runtime Data

### Loaded Modules:

Path |
-- |
C:\Program Files (x86)\Winamp\elevator.exe |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\wow64.dll |
C:\Windows\System32\wow64cpu.dll |
C:\Windows\System32\wow64win.dll |


## Signature

* Status: Signature verified.
* Serial: `3BA0DE68EE9CCED6F60B4FCD75203C05`
* Thumbprint: `C334E08D86580284EAA279348DA89415E917D660`
* Issuer: CN=thawte SHA256 Code Signing CA, O="thawte, Inc.", C=US
* Subject: CN=Winamp SA, O=Winamp SA, L=Bruxelles, C=BE

## File Metadata

* Original Filename: Elevator.exe
* Product Name: Winamp
* Company Name: Winamp SA
* File Version: 5,8,0,3660
* Product Version: 5,8,0,3660
* Language: English (United States)
* Legal Copyright: Copyright  2008-2019 Winamp SA
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/69
* VirusTotal Link: https://www.virustotal.com/gui/file/961144fc083132d5fcbafb87f69d0e3d5cd559f0e69c5692b10ec266f87259f9/detection/

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Program Files (x86)\Winamp\winampa.exe](winampa.exe-56FAF648C545FA927C1F3838306AB27E.md) | 49

## Possible Misuse

*The following table contains possible examples of `elevator.exe` being misused. While `elevator.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_hackingteam_rules.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_hackingteam_rules.yar) | description = "Hacking Team Disclosure Sample - file elevator.dll" | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_hackingteam_rules.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_hackingteam_rules.yar) | $s5 = "elevator.dll" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_hackingteam_rules.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_hackingteam_rules.yar) | description = "Hacking Team Disclosure Sample - file elevator.exe" | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_hackingteam_rules.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_hackingteam_rules.yar) | reference = "Hacking Team Disclosure elevator.c" | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_hackingteam_rules.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_hackingteam_rules.yar) | $s7 = "elevator.obj" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)



MIT License. Copyright (c) 2020-2021 Strontic.


