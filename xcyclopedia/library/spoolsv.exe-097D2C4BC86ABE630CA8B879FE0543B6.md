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
MD5 | `097D2C4BC86ABE630CA8B879FE0543B6`
SHA1 | `17C8C7C153B869FB626183ED33ED2CFCBE97FB87`
SHA256 | `120DA7561842AB914590EBA1A13E2F1A8171198C47FA0543C5FFF9948A2372C0`
SHA384 | `39A36BC09C8C9D904F2D42EA339BB48EAA16F0C236A40E237A1FD8AD16B6A71FE6A66660958BEABFD6DDA9CC0B256FD9`
SHA512 | `DF5F755629BDBC6F4CAA14128B2FE5E897FC95856CB64E9108E5E83D30F840A5EA05E9F99DF79C83935724B24B86EF9A22CEC8F148E53F01370D9ACE2A4809C0`
SSDEEP | `24576:eRaOT7uuhdzDLt4UImXsfeCUqj8tSBY5QChg32NbF05KT:eRrTiuhdzDLt4UImXsfeCUqj8tSBY5QE`

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
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.



## Possible Misuse

*The following table contains possible examples of `spoolsv.exe` being misused. While `spoolsv.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_creation_system_file.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/file_event/sysmon_creation_system_file.yml) | `- '*\spoolsv.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_system_exe_anomaly.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_system_exe_anomaly.yml) | `- '*\spoolsv.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_suspicious_remote_thread.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/sysmon/sysmon_suspicious_remote_thread.yml) | `- '\spoolsv.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1489.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1489/T1489.md) | This technique was used by WannaCry. Upon execution, if the spoolsv service was running "SUCCESS: The process "spoolsv.exe" with PID 2316 has been terminated." | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1489.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1489/T1489.md) | will be displayed. If the service was not running "ERROR: The process "spoolsv.exe" not found." will be displayed and it can be | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1489.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1489/T1489.md) | \| process_name \| Name of a process to kill \| String \| spoolsv.exe\| | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[signature-base](https://github.com/Neo23x0/signature-base) | [generic_anomalies.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/generic_anomalies.yar) | description = "Detects uncommon file size of spoolsv.exe" | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [generic_anomalies.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/generic_anomalies.yar) | and filename == "spoolsv.exe" | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)



MIT License. Copyright (c) 2020-2021 Strontic.


