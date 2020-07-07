---
title: smss.exe | Windows Session Manager
---

# smss.exe 

* File Path: `C:\Windows\system32\smss.exe`
* Description: Windows Session Manager
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `725EC50D4B0F607BF5B45B5E0115770B`
SHA1 | `C9C133660468FD1D9905F598F5052DBB01F42EEA`
SHA256 | `56881BCAEAC350107A6453F38F020FE0E284DBE2E8A6F37ED482985E0DD98EA7`
SHA384 | `942456F642AA614BBE5D3598E88E488E378ADA5FD214947B2EDC38DF43F00F7DA3362486262EE0D6442552640B3DC63C`
SHA512 | `591977951CB2A2057B7888B0A25AACB15D4D822B187AFF1AED3FC66D383871D81100324B21D72B46194D483BF9350CD6399065AC61E09F5A1E0E88B09ED7FE94`
SSDEEP | `3072:KY/96LhnveimVXP4R43aYuHH5ybCPgisSZvSFhkRa2E:KYV6LhnvfYGHAbCYi/NSEE`

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

* Original Filename: smss.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.14393.0 (rs1_release.160715-1616)
* Product Version: 10.0.14393.0
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.


## Possible Misuse

*The following table contains possible examples of `smss.exe` being misused. While `smss.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_creation_system_file.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/file_event/sysmon_creation_system_file.yml) | `            - '*\smss.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_system_exe_anomaly.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_system_exe_anomaly.yml) | `            - '*\smss.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_raw_disk_access_using_illegitimate_tools.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/sysmon/sysmon_raw_disk_access_using_illegitimate_tools.yml) | `            - '\smss.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[malware-ioc](https://github.com/eset/malware-ioc) | [nukesped_lazarus](https://github.com/eset/malware-ioc/blob/master/nukesped_lazarus/README.adoc) | `.`smss.exe`` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)



MIT License. Copyright (c) 2020 Strontic.


