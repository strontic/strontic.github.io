---
title: Elevator.exe | AIMP Access Rights Elevator
excerpt: What is Elevator.exe?
---

# Elevator.exe 

* File Path: `C:\Program Files (x86)\AIMP3\Elevator.exe`
* Description: AIMP Access Rights Elevator
* Comments: Made in Russia


## Hashes

Type | Hash
-- | --
MD5 | `C316705DF724AE73856E8A3D15FB8FB0`
SHA1 | `4768AB9223C0A73D74A48A2327D0C5EE5039F0AB`
SHA256 | `63B73AA54561CD0320D3A6D977453E2388915DBDB3F09CCE4C5F9C4BA6A1B55F`
SHA384 | `47EC990CA3172600D42FCBAC49B24E774A2467B9E2CB00E4D9BE95CF0F24587D4DBE4726D5C85E89A8BF39DBD4683AC7`
SHA512 | `3FFEB62E16038528B731D7EBF357CF84D7662C97DD82C2F3F2881AF184F37AE5DC95798EDDA232755C1BE6076CA5A10002651994238A252880530AF4680991F2`
SSDEEP | `3072:O3AIwIWusj+1QBJglawlamCdivORLPVk/Bivm2So1XAykTIV7Qkt2iZiciV:OYIWuUttk/ibMtiZiciV`
IMP | `740B14ED2F7669333138A3C0C73D49E0`
PESHA1 | `DDF7F511088E9CEAC03314AD2A195F306B84D546`
PE256 | `A9A597B4EEA9E2036ACFD3D6E30767DAC86ED66FAB68AEA15EEDB9C32B912A16`

## Runtime Data

### Loaded Modules:

Path |
-- |
C:\Program Files (x86)\AIMP3\Elevator.exe |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\wow64.dll |
C:\Windows\System32\wow64cpu.dll |
C:\Windows\System32\wow64win.dll |


## Signature

* Status: Signature verified.
* Serial: `192DAF9B87C9EB436FEEB4F6`
* Thumbprint: `3B2311AD9C090BFF0BEFB91BCD5B9AE298A72F6F`
* Issuer: CN=GlobalSign CodeSigning CA - SHA256 - G3, O=GlobalSign nv-sa, C=BE
* Subject: E=support@aimp.ru, CN=IP Izmaylov Artem Andreevich, O=IP Izmaylov Artem Andreevich, L=Tula, S=Tula Oblast, C=RU

## File Metadata

* Original Filename: 
* Product Name: AIMP
* Company Name: AIMP DevTeam
* File Version: 4.70.2227.0
* Product Version: 4.70.2227.0
* Language: Russian (Russia)
* Legal Copyright: Artem Izmaylov
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/70
* VirusTotal Link: https://www.virustotal.com/gui/file/63b73aa54561cd0320d3a6d977453e2388915dbdb3f09cce4c5f9c4ba6a1b55f/detection/

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\program files (x86)\AIMP3\Elevator.exe](Elevator.exe-35B840CE89ACC5D18FED8EF75C3E2B68.md) | 91

## Possible Misuse

*The following table contains possible examples of `Elevator.exe` being misused. While `Elevator.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_hackingteam_rules.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_hackingteam_rules.yar) | description = "Hacking Team Disclosure Sample - file elevator.dll" | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_hackingteam_rules.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_hackingteam_rules.yar) | $s5 = "elevator.dll" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_hackingteam_rules.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_hackingteam_rules.yar) | description = "Hacking Team Disclosure Sample - file elevator.exe" | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_hackingteam_rules.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_hackingteam_rules.yar) | reference = "Hacking Team Disclosure elevator.c" | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_hackingteam_rules.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_hackingteam_rules.yar) | $s7 = "elevator.obj" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)



MIT License. Copyright (c) 2020 Strontic.


