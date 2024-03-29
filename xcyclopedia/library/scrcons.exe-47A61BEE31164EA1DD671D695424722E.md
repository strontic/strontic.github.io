﻿---
title: scrcons.exe | WMI Standard Event Consumer - scripting
excerpt: What is scrcons.exe?
---

# scrcons.exe 

* File Path: `C:\WINDOWS\system32\wbem\scrcons.exe`
* Description: WMI Standard Event Consumer - scripting

## Hashes

Type | Hash
-- | --
MD5 | `47A61BEE31164EA1DD671D695424722E`
SHA1 | `73D90A07D1A547BADD814A3A0E0D19C3C8490FD3`
SHA256 | `6C02D54AFE705D7DF7DB7EE94D92AFDEFB2FB91F9D1805C970126A096DF52786`
SHA384 | `3E3EDDF71737F7748A306BEDD1A0520450D93C8B848CF4C21BA613730ACB2E4E887A01F912AC07CF390A429107BB6187`
SHA512 | `CC5CA984988CF57FF897C0D2F59ED5E85D77C3A1E31A5F1CE9FB0BCEDBA6A2D402A6F0398A56ED5DE47A3A846AB87C95F640F44B9966408E22CDFA641973A84E`
SSDEEP | `1536:S5yZTlWQg7Pvzgaf51FnRurL+nEFvyeu:SgRWQg7PvJfrFncrL+nEJq`

## Runtime Data

### Usage (stdout):
```cmhg
Cannot run standalone

```

## Signature

* Status: Signature verified.
* Serial: `330000023241FB59996DCC4DFF000000000232`
* Thumbprint: `FF82BC38E1DA5E596DF374C53E3617F7EDA36B06`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: ScrCons
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.18362.1 (WinBuild.160101.0800)
* Product Version: 10.0.18362.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.



## Possible Misuse

*The following table contains possible examples of `scrcons.exe` being misused. While `scrcons.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [godmode_sigma_rule.yml](https://github.com/Neo23x0/sigma/blob/master/other/godmode_sigma_rule.yml) | `- '*\scrcons.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_scrcons_remote_wmi_scripteventconsumer.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/builtin/win_scrcons_remote_wmi_scripteventconsumer.yml) | `ProcessName\|endswith: 'scrcons.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_wmi_persistence_script_event_consumer_write.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/file_event/sysmon_wmi_persistence_script_event_consumer_write.yml) | `Image: 'C:\WINDOWS\system32\wbem\scrcons.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_scrcons_imageload_wmi_scripteventconsumer.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/image_load/sysmon_scrcons_imageload_wmi_scripteventconsumer.yml) | `description: Detects signs of the WMI script host process %SystemRoot%\system32\wbem\scrcons.exe functionality being used via images being loaded by a process.`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_scrcons_imageload_wmi_scripteventconsumer.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/image_load/sysmon_scrcons_imageload_wmi_scripteventconsumer.yml) | `Image\|endswith: '\scrcons.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_susp_wmi_consumer_namedpipe.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/pipe_created/sysmon_susp_wmi_consumer_namedpipe.yml) | `description: Detects the WMI Event Consumer service scrcons.exe creating a named pipe`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_susp_wmi_consumer_namedpipe.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/pipe_created/sysmon_susp_wmi_consumer_namedpipe.yml) | `Image\|endswith: '\scrcons.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_office_shell.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_office_shell.yml) | `- '\scrcons.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_script_event_consumer_spawn.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_script_event_consumer_spawn.yml) | `description: Detects a suspicious child process of Script Event Consumer (scrcons.exe).`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_script_event_consumer_spawn.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_script_event_consumer_spawn.yml) | `- https://docs.paloaltonetworks.com/cortex/cortex-xdr/cortex-xdr-analytics-alert-reference/cortex-xdr-analytics-alert-reference/scrcons-exe-rare-child-process.html`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_script_event_consumer_spawn.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_script_event_consumer_spawn.yml) | `- '\scrcons.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_wmi_persistence_script_event_consumer.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_wmi_persistence_script_event_consumer.yml) | `Image: C:\WINDOWS\system32\wbem\scrcons.exe`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020-2021 Strontic.


