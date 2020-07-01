---
title: wsqmcons.exe | Windows SQM Consolidator
---

# wsqmcons.exe 

* File Path: `C:\windows\system32\wsqmcons.exe`
* Description: Windows SQM Consolidator
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `4B8899882458D96FDD8677D49BD0C5B0`
SHA1 | `B825197181519F279CA6551ACC7A2B88557F17A2`
SHA256 | `7313C269BD76053BD3613D04F7FCFB2B1A6A0537806BFE908D6D89EB8D570941`
SHA384 | `A5358F3EAFA60236BC1B57B5BB19405E806C0C849103A36CD2A497C376C75DE57510D298527E420024D2F3D398FAC123`
SHA512 | `ECE5D25F9B0DE6FD3D0831FCC6271ABB223FF2FE8E70181E46C99423C9A129A733C3066C26797297F4E204FCA6F1C32560257006367E58508321C64BB5B7699B`
SSDEEP | `6144:zDkOC0gIaWL7Nk7DHFfBXmHq61+nQbroYl6PyHp+QwEE5ZXXQEQ5l:3Vddk7DlfBW+ng+yHRQXXNQ5l`

## Runtime Data

### Usage (stdout):
```Batchfile

```

### Usage (stderr):
```Batchfile

```

### Child Processes:


## Signature

* Status: The file C:\windows\system32\wsqmcons.exe is not digitally signed. You cannot run this script on the current system. For more information about running scripts and setting execution policy, see about_Execution_Policies at http://go.microsoft.com/fwlink/?LinkID=135170
* Serial: ``
* Thumbprint: ``
* Issuer: 
* Subject: 

## File Metadata

* Original Filename: wsqmcons.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 6.3.9600.16384 (winblue_rtm.130821-1623)
* Product Version: 6.3.9600.16384
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.


## Possible Misuse

*The following table contains possible examples of `wsqmcons.exe` being misused. While `wsqmcons.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_apt_turla_comrat_may20.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_apt_turla_comrat_may20.yml) | `            - '.WSqmCons))\|iex;'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[malware-ioc](https://github.com/eset/malware-ioc) | [misp-turla-comrat-v4-event.json](https://github.com/eset/malware-ioc/blob/master/turla/misp-turla-comrat-v4-event.json) | `                        "value": "HKLM\\SOFTWARE\\Microsoft\\SQMClient\\Windows.WSqmCons",` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [turla](https://github.com/eset/malware-ioc/blob/master/turla/README.adoc) | `* `++HKLM\SOFTWARE\Microsoft\SQMClient\Windows.WSqmCons++`` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)



MIT License. Copyright (c) 2020 Strontic.


