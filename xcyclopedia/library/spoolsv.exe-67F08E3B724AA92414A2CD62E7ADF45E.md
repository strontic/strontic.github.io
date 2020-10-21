---
title: spoolsv.exe | Spooler SubSystem App
excerpt: What is spoolsv.exe?
---

# spoolsv.exe 

* File Path: `C:\Windows\system32\spoolsv.exe`
* Description: Spooler SubSystem App

## Hashes

Type | Hash
-- | --
MD5 | `67F08E3B724AA92414A2CD62E7ADF45E`
SHA1 | `1B30CBC2C5778749F72163298FE215B7068DC512`
SHA256 | `5C9CEB1DF468AF22BF96C87ACAEBE58EC2CC936CFC89DCBD18D0684C72C32C78`
SHA384 | `EB7CDED00A624942E129EC5CB6BC541C3B82C64C3438D099CDA9601A4E8F9A6BC04598857319A6281364B94EBA8A53DB`
SHA512 | `7C9A115E2D3D0D867FAFCFEC7239D6D28D967C19FC7820BF8E2B07C2B592223345F7338277DA5F65E9B31B757278C36FE515EFE209A802720EE9343E5DFBA164`
SSDEEP | `12288:NCutTZFac05kb2k0RSdv9xi+su3Xwp+OVGDsocstlUSMOLgK8wyjvOeTMK9hYLxy:N37VYiPdP8wyjvOeTMK9hYLxP1UpzaJc`
IMP | `73C6E22E27C816FF68B618E9C1CEA622`
PESHA1 | `0664B1E9329271D118334C95D283FC4C4DB0FBD2`
PE256 | `2A86C8EE25215716B6B72068E10A1E2598544B7541D31B0222FA93891ABE49BD`

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
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/70
* VirusTotal Link: https://www.virustotal.com/gui/file/5c9ceb1df468af22bf96c87acaebe58ec2cc936cfc89dcbd18d0684c72c32c78/detection/

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Windows\system32\spoolsv.exe](spoolsv.exe-A79E7DCBD8DF7B4F91081B809EDAECC5.md) | 97

## Possible Misuse

*The following table contains possible examples of `spoolsv.exe` being misused. While `spoolsv.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_creation_system_file.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/file_event/sysmon_creation_system_file.yml) | `- '*\spoolsv.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_system_exe_anomaly.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_system_exe_anomaly.yml) | `- '*\spoolsv.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_suspicious_remote_thread.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/sysmon/sysmon_suspicious_remote_thread.yml) | `- '\spoolsv.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1489.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1489/T1489.md) | This technique was used by WannaCry. Upon execution, if the spoolsv service was running "SUCCESS: The process "spoolsv.exe" with PID 2316 has been terminated." | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1489.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1489/T1489.md) | will be displayed. If the service was not running "ERROR: The process "spoolsv.exe" not found." will be displayed and it can be | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1489.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1489/T1489.md) | \| process_name \| Name of a process to kill \| String \| spoolsv.exe\| | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[signature-base](https://github.com/Neo23x0/signature-base) | [generic_anomalies.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/generic_anomalies.yar) | description = "Detects uncommon file size of spoolsv.exe" | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [generic_anomalies.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/generic_anomalies.yar) | and filename == "spoolsv.exe" | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)



MIT License. Copyright (c) 2020 Strontic.


