---
title: scrcons.exe | WMI Standard Event Consumer - scripting
excerpt: What is scrcons.exe?
---

# scrcons.exe 

* File Path: `C:\windows\system32\wbem\scrcons.exe`
* Description: WMI Standard Event Consumer - scripting

## Hashes

Type | Hash
-- | --
MD5 | `1F118E2EFF2EBDF244F97E8CCE5910E2`
SHA1 | `2A91C9C105B778FF99FE280F6E917858CB15DC03`
SHA256 | `7D0BA1A011EC2C2C392A86D1C5EBAF20F5615142ED3DE4ED5CD603F60E520345`
SHA384 | `ACF3447B8EB88D1F61CFCC7BF2F45E148B2A6611C0A88FD2AE8C41B446B7D154BE868D1B3724A07B06C4822EC5130437`
SHA512 | `A7776DEFA9885E692639E75901FE3BAAE2A691DFE71ADA0A5BA2872AFF4F588F19E1196AEF4E75D0F32FBC939F732190DA16B0B5A4CC3C230323D3025D9FEDCD`
SSDEEP | `768:GTiff1Pzo3VOyP1xhHjcai2qNBEFg/PlWyHtke0qu0+d3MiDjGfEqq7ntns0YLd0:G+ff1STMx3lWeT0quRd3jkEqq7ntR80`

## Signature

* Status: The file C:\windows\system32\wbem\scrcons.exe is not digitally signed. You cannot run this script on the current system. For more information about running scripts and setting execution policy, see about_Execution_Policies at http://go.microsoft.com/fwlink/?LinkID=135170
* Serial: ``
* Thumbprint: ``
* Issuer: 
* Subject: 

## File Metadata

* Original Filename: ScrCons
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 6.3.9600.16384 (winblue_rtm.130821-1623)
* Product Version: 6.3.9600.16384
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.



## Possible Misuse

*The following table contains possible examples of `scrcons.exe` being misused. While `scrcons.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [godmode_sigma_rule.yml](https://github.com/Neo23x0/sigma/blob/master/other/godmode_sigma_rule.yml) | `- '*\scrcons.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_wmi_persistence_script_event_consumer_write.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/file_event/sysmon_wmi_persistence_script_event_consumer_write.yml) | `Image: 'C:\WINDOWS\system32\wbem\scrcons.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_office_shell.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_office_shell.yml) | `- '*\scrcons.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_wmi_persistence_script_event_consumer.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_wmi_persistence_script_event_consumer.yml) | `Image: C:\WINDOWS\system32\wbem\scrcons.exe` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020 Strontic.


