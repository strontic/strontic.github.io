---
title: services.exe | Services and Controller app
---

# services.exe 

* File Path: `C:\windows\system32\services.exe`
* Description: Services and Controller app
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `DB896369FB58241ADF28515E3765C514`
SHA1 | `617A0A0BAAB180541DB739C4A6851D784943C317`
SHA256 | `A2E369DF26C88015FE1F97C7542D6023B5B1E4830C25F94819507EE5BCB1DFCC`
SHA384 | `E725F9E26419C4708AFEA2350A3D3EDF0B968DAF1FDAE6F12822BD08F6305E74779A3B06688392BF31CB6A1182A69D7D`
SHA512 | `C47F469E3ED2D358C51E8B804A6E1DB37C6B33543919BEE938279902D01D44F171E132C29D2A36EC3B4369E1441F597993E727CE2F2D087A4AB384ACE345C959`
SSDEEP | `12288:EBcEZkiKFRQVcO09OEIXXfHx0q6BgQP/pA9cY2l1JlmruvjXT2C57p3XewSH9uLi:OcAkiKFscODvnfH+OQXyaY2lPT6gFXen`

## Runtime Data

### Usage (stdout):
```Batchfile

```

### Usage (stderr):
```Batchfile

```

### Child Processes:


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: services.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.17763.1 (WinBuild.160101.0800)
* Product Version: 10.0.17763.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.


## Possible Misuse

*The following table contains possible examples of `services.exe` being misused. While `services.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_creation_system_file.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/file_event/sysmon_creation_system_file.yml) | `            - '*\services.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_impacket_lateralization.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_impacket_lateralization.yml) | `        #   parent is services.exe` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_impacket_lateralization.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_impacket_lateralization.yml) | `            - '*\services.exe'  # smbexec` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_meterpreter_or_cobaltstrike_getsystem_service_start.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_meterpreter_or_cobaltstrike_getsystem_service_start.yml) | `        ParentImage\|endswith: '\services.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_proc_wrong_parent.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_proc_wrong_parent.yml) | `            - '*\services.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_execution_path_webserver.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_execution_path_webserver.yml) | `            - '*\services.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_powershell_parent_process.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_powershell_parent_process.yml) | `            - '\services.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_svchost.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_svchost.yml) | `            - '*\services.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_system_exe_anomaly.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_system_exe_anomaly.yml) | `            - '*\services.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_hack_wce.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/registry_event/sysmon_hack_wce.yml) | `        ParentImage\|endswith: '\services.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_creation_system_file.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/sysmon/sysmon_creation_system_file.yml) | `            - '*\services.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_hack_wce.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/sysmon/sysmon_hack_wce.yml) | `        ParentImage\|endswith: '\services.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1569.002.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1569.002/T1569.002.md) | <blockquote>Adversaries may abuse the Windows service control manager to execute malicious commands or payloads. The Windows service control manager (<code>services.exe</code>) is an interface to manage and manipulate services.(Citation: Microsoft Service Control Manager) The service control manager is accessible to users via GUI components as well as system utilities such as <code>sc.exe</code> and [Net](https://attack.mitre.org/software/S0039). | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)



MIT License. Copyright (c) 2020 Strontic.


