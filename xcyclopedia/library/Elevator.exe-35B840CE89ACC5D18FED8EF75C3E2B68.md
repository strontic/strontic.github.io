---
title: Elevator.exe | AIMP Access Rights Elevator
---

# Elevator.exe 

* File Path: `C:\program files (x86)\AIMP3\Elevator.exe`
* Description: AIMP Access Rights Elevator
* Comments: Made in Russia


## Hashes

Type | Hash
-- | --
MD5 | `35B840CE89ACC5D18FED8EF75C3E2B68`
SHA1 | `563EB9844BBB353039DEA5A68D0B4B816F176BCF`
SHA256 | `3B1D02A3CAF0BC5F411A151D3C578244D98ADDF269D23BE0B0C082C2A73DD3A9`
SHA384 | `7739670ABF447FA29D6231904ED68427D57163D9A47F96B5DAA7CF0452D254990F862340E27F9E0FB5A3B4502F49BDD0`
SHA512 | `29085F2B2112000F9C4A1021AA82E1E2529FE77C511ED799665D0D7D14064D75B70A7E1A80B03DFC98DB1809A1A06419A546055BEA3A96B3998EB83793CB6B56`
SSDEEP | `3072:w3AIwIWusj+1QBJglawlamCdivORLPVk/Bivm2So1XAykTIV7gkt2iFYiYd:wYIWuUttk/ib0tiFYiYd`

## Runtime Data

### Loaded Modules:

Path |
-- |
C:\program files (x86)\AIMP3\Elevator.exe |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\wow64.dll |
C:\Windows\System32\wow64cpu.dll |
C:\Windows\System32\wow64win.dll |


## Signature

* Status: Signature verified.
* Serial: `329300D599016067A3E86CED`
* Thumbprint: `E1782EA4E44A003BFA5D98B4F6F912ACDF9B3DD1`
* Issuer: CN=GlobalSign CodeSigning CA - SHA256 - G3, O=GlobalSign nv-sa, C=BE
* Subject: E=support@aimp.ru, CN=IP Izmaylov Artem Andreevich, O=IP Izmaylov Artem Andreevich, L=Tula, S=Tula oblast, C=RU

## File Metadata

* Original Filename: 
* Product Name: AIMP
* Company Name: AIMP DevTeam
* File Version: 4.70.2224.0
* Product Version: 4.70.2224.0
* Language: Russian (Russia)
* Legal Copyright: Artem Izmaylov


## Possible Misuse

*The following table contains possible examples of `Elevator.exe` being misused. While `Elevator.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_hackingteam_rules.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_hackingteam_rules.yar) | 		description = "Hacking Team Disclosure Sample - file elevator.dll" | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_hackingteam_rules.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_hackingteam_rules.yar) | 		$s5 = "elevator.dll" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_hackingteam_rules.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_hackingteam_rules.yar) | 		description = "Hacking Team Disclosure Sample - file elevator.exe" | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_hackingteam_rules.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_hackingteam_rules.yar) | 		reference = "Hacking Team Disclosure elevator.c" | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_hackingteam_rules.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_hackingteam_rules.yar) | 		$s7 = "elevator.obj" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)



MIT License. Copyright (c) 2020 Strontic.


