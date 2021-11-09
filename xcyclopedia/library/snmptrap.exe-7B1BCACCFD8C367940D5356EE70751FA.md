---
title: snmptrap.exe | SNMP Trap
excerpt: What is snmptrap.exe?
---

# snmptrap.exe 

* File Path: `C:\WINDOWS\system32\snmptrap.exe`
* Description: SNMP Trap

## Hashes

Type | Hash
-- | --
MD5 | `7B1BCACCFD8C367940D5356EE70751FA`
SHA1 | `FD4ACE41D289723F5D76EB04AECC31F0DC2899C3`
SHA256 | `FBEA9B370C6682EEA5159CDD554D8A567725BA567C5E0F4FE8158BB004EC37B2`
SHA384 | `E02979427B3079FD54083D4E258F14F7311102D038D4623B7E30700A5F74FD7B9EF31F1819598E2B9830EF5EEF1D8D4C`
SHA512 | `1C7687BB4F4AC42F5E5D7CF74B278B32F0096C9D290FB94EC7B83650D5662A07BF33348C284758AD979C9F66DB3206E1DFD21780208785BBF5792D240EB99311`
SSDEEP | `384:mUctzahhoh/qtuTxmiDQIfOybaiYqWWyW:mPxuuTxmyQIflm5S`
IMP | `C2C94366EB9868AA74167BBE2B51AA0A`
PESHA1 | `D78D5DD212B9BB218BC10F819CF463986E01AC47`
PE256 | `A420E145C7BC5BAD371FE3E2997A7AB74FD047D6DAD06BD65C8B719C86535F72`

## Runtime Data

### Loaded Modules:

Path |
-- |
C:\WINDOWS\SYSTEM32\ntdll.dll |
C:\WINDOWS\system32\snmptrap.exe |


## Signature

* Status: Signature verified.
* Serial: `33000002ED2C45E4C145CF48440000000002ED`
* Thumbprint: `312860D2047EB81F8F58C29FF19ECDB4C634CF6A`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: snmptrap.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.22000.1 (WinBuild.160101.0800)
* Product Version: 10.0.22000.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/73
* VirusTotal Link: https://www.virustotal.com/gui/file/fbea9b370c6682eea5159cdd554d8a567725ba567c5e0f4fe8158bb004ec37b2/detection


## Possible Misuse

*The following table contains possible examples of `snmptrap.exe` being misused. While `snmptrap.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[stockpile](https://github.com/mitre/stockpile) | [52771610-2322-44cf-816b-a7df42b4c086.yml](https://github.com/mitre/stockpile/blob/master/data/abilities/persistence/52771610-2322-44cf-816b-a7df42b4c086.yml) | `This is an example technique. snmptrap.exe should be changed in the command`{:.highlight .language-yaml} | [Apache-2.0](https://github.com/mitre/stockpile/blob/master/LICENSE)
[stockpile](https://github.com/mitre/stockpile) | [52771610-2322-44cf-816b-a7df42b4c086.yml](https://github.com/mitre/stockpile/blob/master/data/abilities/persistence/52771610-2322-44cf-816b-a7df42b4c086.yml) | `Copy-Item -Path "C:\Windows\System32\snmptrap.exe" -Destination $path`{:.highlight .language-yaml} | [Apache-2.0](https://github.com/mitre/stockpile/blob/master/LICENSE)



MIT License. Copyright (c) 2020-2021 Strontic.


