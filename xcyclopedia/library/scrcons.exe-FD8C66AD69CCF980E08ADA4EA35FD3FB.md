﻿---
title: scrcons.exe | WMI Standard Event Consumer - scripting
excerpt: What is scrcons.exe?
---

# scrcons.exe 

* File Path: `C:\Windows\system32\wbem\scrcons.exe`
* Description: WMI Standard Event Consumer - scripting

## Hashes

Type | Hash
-- | --
MD5 | `FD8C66AD69CCF980E08ADA4EA35FD3FB`
SHA1 | `0102A12E468DCC2B40681252E311B6AFA3C6DAB0`
SHA256 | `F96C187199362265FAC87ADB337DB242D24F9B313407646F89DA62A1ED12B6D9`
SHA384 | `83F0E50AAFBA9BD059A42EC8680A1DEA22ACB08BF042BF0A608500D73FD22AEE856442586F49470F8958429B78CC84F2`
SHA512 | `69414794881801B43855A6880159E61B0D412B192F57066D8AE820267F43D5255D2660C69A4B98F7924083DE8FC66920E67EE0AFBF3C3C780147213C876A3177`
SSDEEP | `1536:5K7eR5nv5HMyhDuihPLrFj3tkj069tuNdXSnNdGjQBBBfA1bUIzB21+nFFifj:5nnv5HMyVuiHj3tgBfUbUIV21+nFQ`
IMP | `33D9F246D162F5E1E1312E28E566A69E`
PESHA1 | `06B6A53B58BD62CC5FCDFDED693F806C941226A1`
PE256 | `8864A7B69CB55FA75466F2A5260277B2088C29498A42DADD6DF95679B96B98DD`

## Runtime Data

### Usage (stdout):
```cmhg
Cannot run standalone

```

### Loaded Modules:

Path |
-- |
C:\Windows\System32\combase.dll |
C:\Windows\System32\GDI32.dll |
C:\Windows\System32\gdi32full.dll |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\System32\msvcp_win.dll |
C:\Windows\System32\msvcrt.dll |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\OLEAUT32.dll |
C:\Windows\System32\RPCRT4.dll |
C:\Windows\System32\ucrtbase.dll |
C:\Windows\System32\USER32.dll |
C:\Windows\system32\wbem\scrcons.exe |
C:\Windows\System32\win32u.dll |


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: ScrCons
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/75
* VirusTotal Link: https://www.virustotal.com/gui/file/f96c187199362265fac87adb337db242d24f9b313407646f89da62a1ed12b6d9/detection


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


