---
title: rasdial.exe | Remote Access Command Line Dial UI
---

# rasdial.exe 

* File Path: `C:\windows\SysWOW64\rasdial.exe`
* Description: Remote Access Command Line Dial UI

## Hashes

Type | Hash
-- | --
MD5 | `E14D17FB0C2E3EFA7E6825A530FD323D`
SHA1 | `3A056438B91A00DBED30661DB077A01CB74B7C78`
SHA256 | `71DC30513EB3DCB8C84AA1DBF8D2A985477AE7A3D12921EDD2B7B1DB8EAE11FB`
SHA384 | `0E1D92C47DB4F96524068CCE4395A10BA3BA2E90A91E8BFC0EE01593BFE167B4E13F511F26573ED7B87538D170016BDF`
SHA512 | `23D3763664BFB21F0DEA6E08461CE74E2DD427BFE6AEEF21BF759F4734C75485414956BB93C176C9225331AE150B453A0BAAC9972136EB94320EA19E9933B9E7`
SSDEEP | `192:JxCsL3FV8+TZ1haPg41lHzjk9VK5HMeTXzC/tTbajtcV9MDnkeeEW5VW7oLY:zDHt1h+g41xzouHMEXzC5Ggn6W5VW7o`

## Signature

* Status: The file C:\windows\SysWOW64\rasdial.exe is not digitally signed. You cannot run this script on the current system. For more information about running scripts and setting execution policy, see about_Execution_Policies at http://go.microsoft.com/fwlink/?LinkID=135170
* Serial: ``
* Thumbprint: ``
* Issuer: 
* Subject: 

## File Metadata

* Original Filename: RASDIAL.EXE.MUI
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 6.3.9600.16384 (winblue_rtm.130821-1623)
* Product Version: 6.3.9600.16384
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.


## Possible Misuse

*The following table contains possible examples of `rasdial.exe` being misused. While `rasdial.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_rasdial_activity.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_rasdial_activity.yml) | `title: Suspicious RASdial Activity` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_rasdial_activity.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_rasdial_activity.yml) | `description: Detects suspicious process related to rasdial.exe` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_rasdial_activity.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_rasdial_activity.yml) | `            - rasdial.exe` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020 Strontic.


