---
title: csrss.exe | Client Server Runtime Process
---

# csrss.exe 

* File Path: `C:\windows\system32\csrss.exe`
* Description: Client Server Runtime Process
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `7D64128BC1EECE41196858897596EBC8`
SHA1 | `779B8AFC3FA2528B090F400EF3D592E0E2775955`
SHA256 | `FB40ED0FFA6BC795923A941DAB6B7D6B43583D0F152A6DF4D8953D2C1A0CB417`
SHA384 | `2826B9684B1297FB729AD0A964CB6FD08FC5EAFC7DE521E9FFB02151A55985F123CBB9F3FA26D692141CFD762FE35D36`
SHA512 | `23E87A86B1D0B206047DD24ABD053F6C5472CD969A870EEBE7DBF01F0FA3237F77D3AA5D5526D6165DAA21F6ADCE7449E1B838F64AE129B0829CF8B82D40090D`
SSDEEP | `192:rnbFaItc7IqC+DlmHW5nnWELKN7OwDBQABJtW7KKEaeqnaj8mOgp22PM:sDUHW5nnWFNHDBRJw/Zell22PM`

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
* Serial: `33000001C422B2F79B793DACB20000000001C4`
* Thumbprint: `AE9C1AE54763822EEC42474983D8B635116C8452`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: CSRSS.Exe.MUI
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.17763.1 (WinBuild.160101.0800)
* Product Version: 10.0.17763.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\WINDOWS\system32\csrss.exe](csrss.exe-23019322FFECB179746210BE52D6DE60.md) | 57
[C:\Windows\system32\csrss.exe](csrss.exe-955E9227AA30A08B7465C109B863B886.md) | 46
[C:\Windows\SysWOW64\backgroundTaskHost.exe](backgroundTaskHost.exe-8B50BFD5811304543479B20D0A281C56.md) | 33

## Possible Misuse

*The following table contains possible examples of `csrss.exe` being misused. While `csrss.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_lsass_dump_generic.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/builtin/win_susp_lsass_dump_generic.yml) | `            - '\csrss.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_creation_system_file.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/file_event/sysmon_creation_system_file.yml) | `            - '*\csrss.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_cred_dump_lsass_access.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_access/sysmon_cred_dump_lsass_access.yml) | `            - '\csrss.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_proc_wrong_parent.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_proc_wrong_parent.yml) | `            - '*\csrss.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_system_exe_anomaly.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_system_exe_anomaly.yml) | `            - '*\csrss.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_creation_system_file.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/sysmon/sysmon_creation_system_file.yml) | `            - '*\csrss.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_cred_dump_lsass_access.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/sysmon/sysmon_cred_dump_lsass_access.yml) | `            - '\csrss.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_raw_disk_access_using_illegitimate_tools.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/sysmon/sysmon_raw_disk_access_using_illegitimate_tools.yml) | `            - '\csrss.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[malware-ioc](https://github.com/eset/malware-ioc) | [glupteba.misp-event.json](https://github.com/eset/malware-ioc/blob/master/glupteba/glupteba.misp-event.json) | `                "value": "csrss.exe\|1645ad8468a2fb54763c0ebeb766dfd8c643f3db",` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [glupteba](https://github.com/eset/malware-ioc/blob/master/glupteba/README.adoc) | `\|`1645AD8468A2FB54763C0EBEB766DFD8C643F3DB`\|csrss.exe   \|Win32/Agent.SVE` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [nukesped_lazarus](https://github.com/eset/malware-ioc/blob/master/nukesped_lazarus/README.adoc) | `.`csrss.exe`` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [rtm](https://github.com/eset/malware-ioc/blob/master/rtm/README.adoc) | `csrss.exe` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)



MIT License. Copyright (c) 2020 Strontic.


