---
title: scrcons.exe | WMI Standard Event Consumer - scripting
excerpt: What is scrcons.exe?
---

# scrcons.exe 

* File Path: `C:\Windows\system32\wbem\scrcons.exe`
* Description: WMI Standard Event Consumer - scripting

## Hashes

Type | Hash
-- | --
MD5 | `0E7BCB183DB07DDE6CA7C7D598E66194`
SHA1 | `B9F44CD0096D49726D85598F87900009B1B9EFD0`
SHA256 | `7154B0624717DFE981520581E31AD7E53F3D77BA9EDCEED88BE397AA5E4E9B19`
SHA384 | `9F40A85DF5AD9625C1A52821CE3DC2CFD86ECBD14AF295D20BBCC3513581CEA7C975856A2281AF318D9EA2DE7D8AD177`
SHA512 | `F8DD8D6CCB5997F62A0BE56176FEF4E55C62D860022AFA566944F6D7C2D8F57D3466465CE8142D7B03527B05EF16476579C9A7D7C1A06AC4C4DED645813E65A5`
SSDEEP | `768:9kE3fnX1q73OXNdvKCKIu/6F7EMwrY/I3Pf11c93IQ+n7nQ4JIxzI/GPWT+2J:iIX0QgH61EMwrz3Pf11c9YQ+n7nH+2J`

## Runtime Data

### Usage (stdout):
```cmhg
Cannot run standalone

```

## Signature

* Status: Signature verified.
* Serial: `33000000BCE120FDD27CC8EE930000000000BC`
* Thumbprint: `E85459B23C232DB3CB94C7A56D47678F58E8E51E`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: ScrCons
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.14393.0 (rs1_release.160715-1616)
* Product Version: 10.0.14393.0
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


