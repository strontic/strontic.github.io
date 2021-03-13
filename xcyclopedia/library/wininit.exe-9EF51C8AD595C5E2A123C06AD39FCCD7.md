---
title: wininit.exe | Windows Start-Up Application
excerpt: What is wininit.exe?
---

# wininit.exe 

* File Path: `C:\Windows\system32\wininit.exe`
* Description: Windows Start-Up Application

## Hashes

Type | Hash
-- | --
MD5 | `9EF51C8AD595C5E2A123C06AD39FCCD7`
SHA1 | `915EA28BDAA9A2230CE52080693D7F7E27620ED5`
SHA256 | `268CA325C8F12E68B6728FF24D6536030AAB6E05603D0179033B1E51D8476D86`
SHA384 | `E267C1B8B959EDD16781940503F8ACC7DDD5CAF58C7D759C87834C79ED27CA8A3457B2821A823E08DB372686B3A2CD16`
SHA512 | `E1D92DD51C840C6A9001B31C40D89DADAA2048ABA6201845C8B5B48A63A46D0E861AB91DB53757A9AEB6CB5CF9A4253CCD47DC4ADF1E9EAC4C48D0282598A486`
SSDEEP | `6144:CV7PELsqQmhwqpRxTtkNnWriIEOrDmrMyoYc2SbAdO7pQM1HZRXLCQ+JKTEs:CV7EEmhwqLzKnWriHOrDmoy+X81lKTEs`
IMP | `5DD14AFAB46B0C83EA7A6093D7355FA9`
PESHA1 | `576E660FF4918B7A10E38A8B7F0826B5DC029E81`
PE256 | `E6859386D3535C70585958835D6BF02675453DA58D5BEC69B214FA778980B621`

## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: WinInit.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/76
* VirusTotal Link: https://www.virustotal.com/gui/file/268ca325c8f12e68b6728ff24d6536030aab6e05603d0179033b1e51d8476d86/detection


## Possible Misuse

*The following table contains possible examples of `wininit.exe` being misused. While `wininit.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_lsass_dump_generic.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/builtin/win_susp_lsass_dump_generic.yml) | `- '\wininit.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_creation_system_file.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/file_event/sysmon_creation_system_file.yml) | `- '*\wininit.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_cred_dump_lsass_access.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_access/sysmon_cred_dump_lsass_access.yml) | `- '\wininit.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_proc_wrong_parent.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_proc_wrong_parent.yml) | `- '*\wininit.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_system_exe_anomaly.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_system_exe_anomaly.yml) | `- '*\wininit.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_raw_disk_access_using_illegitimate_tools.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/sysmon/sysmon_raw_disk_access_using_illegitimate_tools.yml) | `- '\wininit.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[malware-ioc](https://github.com/eset/malware-ioc) | [misp-xdspy-event.json](https://github.com/eset/malware-ioc/blob/master/xdspy/misp-xdspy-event.json) | `"value": "%APPDATA%\\WINinit\\WINlogon.exe",`{:.highlight .language-cmhg} | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [xdspy](https://github.com/eset/malware-ioc/blob/master/xdspy/README.adoc) | `* `++%APPDATA%\WINinit\WINlogon.exe++``{:.highlight .language-cmhg} | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [generic_anomalies.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/generic_anomalies.yar) | description = "Detects uncommon file size of wininit.exe" | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [generic_anomalies.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/generic_anomalies.yar) | and filename == "wininit.exe" | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [thor_inverse_matches.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/thor_inverse_matches.yar) | description = "Anomaly rule looking for certain strings in a system file (maybe false positive on certain systems) - file wininit.exe" | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [thor_inverse_matches.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/thor_inverse_matches.yar) | filename == "wininit.exe" | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)



MIT License. Copyright (c) 2020-2021 Strontic.


