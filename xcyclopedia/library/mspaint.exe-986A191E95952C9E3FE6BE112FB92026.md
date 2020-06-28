---
title: mspaint.exe | Paint
---

# mspaint.exe 

* File Path: `C:\Windows\SysWOW64\mspaint.exe`
* Description: Paint
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `986A191E95952C9E3FE6BE112FB92026`
SHA1 | `1E2A48F1088CA5AB78617A7EEB8AA5F62ABD4846`
SHA256 | `8BD3C3D2A3E6285D004AFD50262D80939FA588B39C5ECB404D12D364216E73B2`
SHA384 | `05DCA8E9021857F4AC731191D0DDEE1972DB016DFDAE6914FF91F783D211ABAB02287C883C054ADFC76E5F88DBE8ADBF`
SHA512 | `044294049FED0C5165D2C204D4DFEF8DDC65CBC872D499531A2D4F179E3AE2345142510FFC9C12C32E0C316EAC3250D60B0B316A74A3D7D31B0A9699DC8529F7`
SSDEEP | `12288:fk4MXNLmDguv3NU+5cqI648Hd+qKoN26/XtqG/OqNj+mJ5Fw9qF6fDKog0+QLkR:6XNLmDguF7/4899KoN2OqG/5j15Fw9qb`

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

* Original Filename: MSPAINT.EXE.MUI
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.


## Possible Misuse

*The following table contains possible examples of `mspaint.exe` being misused. While `mspaint.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_suspicious_remote_thread.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/sysmon/sysmon_suspicious_remote_thread.yml) | `            - '\mspaint.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[malware-ioc](https://github.com/eset/malware-ioc) | [nukesped_lazarus](https://github.com/eset/malware-ioc/blob/master/nukesped_lazarus/README.adoc) | `.`mspaint.exe (a 2009 file)`` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [nukesped_lazarus](https://github.com/eset/malware-ioc/blob/master/nukesped_lazarus/README.adoc) | `.`mspaint.exe`` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)



MIT License. Copyright (c) 2020 Strontic.


