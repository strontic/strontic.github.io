﻿---
title: spoolsv.exe | Spooler SubSystem App
excerpt: What is spoolsv.exe?
---

# spoolsv.exe 

* File Path: `C:\windows\system32\spoolsv.exe`
* Description: Spooler SubSystem App

## Hashes

Type | Hash
-- | --
MD5 | `A79E7DCBD8DF7B4F91081B809EDAECC5`
SHA1 | `6D4F104ACEFB40C1A82D74648D0A943A1AD5556B`
SHA256 | `0D7BED96AA8FF03531CFE355936A785CF8694D57F8D8E2906C2ACE83A5A1ED4E`
SHA384 | `FA074F9174F568D2B30C583CBFC8AF3F7A8867A07574889515CF0520A528AFC9EC27D4E5321309128FB993EE3E7FC9B1`
SHA512 | `6EB74BD29C405E49CF585B23BD80E86A8A7C3EB743703D11D9B9FFD1F07D8629FBE7E0F9E835BBC1A4626AF0CD42B469D0012D7979C11BC492558F51A1542A20`
SSDEEP | `12288:lCutTZFac05kb2k0RSdv9xi+su3Xwp+OVGDsocstlUSMOLgK8wyjvOeTMK9hYLxC:l37VYiPdP8wyjvOeTMK9hYLxP1UpzaJc`

## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: spoolsv.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.17763.1 (WinBuild.160101.0800)
* Product Version: 10.0.17763.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.


## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Windows\system32\spoolsv.exe](spoolsv.exe-67F08E3B724AA92414A2CD62E7ADF45E.md) | 97

## Possible Misuse

*The following table contains possible examples of `spoolsv.exe` being misused. While `spoolsv.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_suspicious_remote_thread.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/create_remote_thread/sysmon_suspicious_remote_thread.yml) | `- '\spoolsv.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_cve_2021_1675_printspooler_del.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/file_delete/win_cve_2021_1675_printspooler_del.yml) | `Image\|endswith: 'spoolsv.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_creation_system_file.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/file_event/sysmon_creation_system_file.yml) | `- '\spoolsv.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_spoolsv_dll_load.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/image_load/sysmon_spoolsv_dll_load.yml) | `Image\|endswith: 'spoolsv.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_abusing_debug_privilege.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/sysmon_abusing_debug_privilege.yml) | `- '\spoolsv.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_spoolsv_child_processes.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_spoolsv_child_processes.yml) | `description: Detects suspicious print spool service (spoolsv.exe) child processes.`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_spoolsv_child_processes.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_spoolsv_child_processes.yml) | `spoolsv:`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_spoolsv_child_processes.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_spoolsv_child_processes.yml) | `ParentImage\|endswith: \\spoolsv.exe`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_spoolsv_child_processes.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_spoolsv_child_processes.yml) | `condition: spoolsv and (`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_system_exe_anomaly.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_system_exe_anomaly.yml) | `- '\spoolsv.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1489.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1489/T1489.md) | This technique was used by WannaCry. Upon execution, if the spoolsv service was running "SUCCESS: The process "spoolsv.exe" with PID 2316 has been terminated." | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1489.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1489/T1489.md) | will be displayed. If the service was not running "ERROR: The process "spoolsv.exe" not found." will be displayed and it can be | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1489.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1489/T1489.md) | \| process_name \| Name of a process to kill \| String \| spoolsv.exe\| | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1547.010.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1547.010/T1547.010.md) | <blockquote>Adversaries may use port monitors to run an attacker supplied DLL during system boot for persistence or privilege escalation. A port monitor can be set through the <code>AddMonitor</code> API call to set a DLL to be loaded at startup. (Citation: AddMonitor) This DLL can be located in <code>C:\Windows\System32</code> and will be loaded by the print spooler service, spoolsv.exe, on boot. The spoolsv.exe process also runs under SYSTEM level permissions. (Citation: Bloxham) Alternatively, an arbitrary DLL can be loaded if permissions allow writing a fully-qualified pathname for that DLL to <code>HKLM\SYSTEM\CurrentControlSet\Control\Print\Monitors</code>.  | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1547.010.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1547.010/T1547.010.md) | Add key-value pair to a Windows Port Monitor registry. On the subsequent reboot dll will be execute under spoolsv with NT AUTHORITY/SYSTEM privilege. | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[signature-base](https://github.com/Neo23x0/signature-base) | [generic_anomalies.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/generic_anomalies.yar) | description = "Detects uncommon file size of spoolsv.exe" | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [generic_anomalies.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/generic_anomalies.yar) | and filename == "spoolsv.exe" | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)



MIT License. Copyright (c) 2020-2021 Strontic.


