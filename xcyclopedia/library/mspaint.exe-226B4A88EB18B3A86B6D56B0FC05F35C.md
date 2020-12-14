---
title: mspaint.exe | Paint
excerpt: What is mspaint.exe?
---

# mspaint.exe 

* File Path: `C:\windows\system32\mspaint.exe`
* Description: Paint

## Screenshot

![mspaint.exe](screenshots/mspaint.exe-8A6A020DABFB0024BE80D988C59F8F2A-3.png)

## Hashes

Type | Hash
-- | --
MD5 | `226B4A88EB18B3A86B6D56B0FC05F35C`
SHA1 | `B9AC4ECCA0C4E7962EBBF057E2C354064FB92198`
SHA256 | `DB3516DBF69D16183421429B8005A01AFFAEF361C6D1FA5A06591EA0EB38854E`
SHA384 | `2D770F303E3515E6FABD61284688BC2A65017663FB5A30CC63DB01FFE5BD9F57BE6A59A1FCD32FB9349417D27234743F`
SHA512 | `61FA2C901CCAB1CD295B12D13F73180C7D04B4D4FE0F3E499AD12DA0B4BB9330F118C79A331E7C137A5EB40AF5BBE34885DBEE61FDC787A1A820622C15C65D41`
SSDEEP | `98304:HpEfkx2u7InCEE+wysPM4mlaw0LI60GBGrGrGWAuU7jPLQ:JEC6nTE+wBMHlaw0/U7jPL`

## Signature

* Status: The file C:\windows\system32\mspaint.exe is not digitally signed. You cannot run this script on the current system. For more information about running scripts and setting execution policy, see about_Execution_Policies at http://go.microsoft.com/fwlink/?LinkID=135170
* Serial: ``
* Thumbprint: ``
* Issuer: 
* Subject: 

## File Metadata

* Original Filename: MSPAINT.EXE.MUI
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 6.3.9600.16384 (winblue_rtm.130821-1623)
* Product Version: 6.3.9600.16384
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.


## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Windows\system32\mspaint.exe](mspaint.exe-67C68B11E98970966DF59D2FAD6152BF.md) | 69
[C:\Windows\system32\mspaint.exe](mspaint.exe-A5F69864C0CA8FDC157F3E7EF48F2F10.md) | 93
[C:\windows\SysWOW64\mspaint.exe](mspaint.exe-1B84FBA247447BBF80A0883495823263.md) | 86
[C:\Windows\SysWOW64\mspaint.exe](mspaint.exe-7598568851B293CD82E958C3B9735F7C.md) | 69
[C:\Windows\SysWOW64\mspaint.exe](mspaint.exe-8A6A020DABFB0024BE80D988C59F8F2A.md) | 88

## Possible Misuse

*The following table contains possible examples of `mspaint.exe` being misused. While `mspaint.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_suspicious_remote_thread.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/sysmon/sysmon_suspicious_remote_thread.yml) | `- '\mspaint.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[malware-ioc](https://github.com/eset/malware-ioc) | [nukesped_lazarus](https://github.com/eset/malware-ioc/blob/master/nukesped_lazarus/README.adoc) | `.`mspaint.exe (a 2009 file)`` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [nukesped_lazarus](https://github.com/eset/malware-ioc/blob/master/nukesped_lazarus/README.adoc) | `.`mspaint.exe`` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_codoso.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_codoso.yar) | $s4 = "mspaint.exe" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)



MIT License. Copyright (c) 2020 Strontic.


