---
title: smss.exe | Windows Session Manager
---

# smss.exe 

* File Path: `C:\WINDOWS\system32\smss.exe`
* Description: Windows Session Manager
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `858E3DA84C5389952E1AD3701E410F61`
SHA1 | `9F768C0D0774407564F098145B64565CFFDD8DC4`
SHA256 | `5F48638E3397204C2C63D7B76D025D62302D0E45FC5055C0A692B0BBC7E6B337`
SHA384 | `CDF1B503FC281B7D5160DB64DAC05BEC3AD5111F7FD4031427DEB601386334C21D7A93889BE1276BF68C52F6D71D2AC3`
SHA512 | `729FBF4FEE059706EC5E77DD6C3326840E0BC255B7C50C1F77AD9DAC5A2B9579D91264DC5C2252C39F6A2D92EC60E1FCAB34B7ACCE44AF9816BBC1F7B7521891`
SSDEEP | `3072:GQPiKMyrlh1jouZDDw5U0KZDHbVBpHSKbkdjv2Ylt:5iKMy9jfnpyxzR`

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
* Serial: `330000023241FB59996DCC4DFF000000000232`
* Thumbprint: `FF82BC38E1DA5E596DF374C53E3617F7EDA36B06`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: smss.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.18362.1 (WinBuild.160101.0800)
* Product Version: 10.0.18362.1
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


