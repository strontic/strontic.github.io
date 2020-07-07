---
title: FXSSVC.exe | Fax Service
---

# FXSSVC.exe 

* File Path: `C:\Windows\system32\FXSSVC.exe`
* Description: Fax Service
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `448D27130A927F933E9B283A165300A3`
SHA1 | `EFC95DA195E18AE1F9852C2F693266F296E31867`
SHA256 | `D70CB3598AF18E75DB858ACCB6D3E7B4D6F6D8F68E50673BF28A45CEA1658701`
SHA384 | `CA2F30F3A85DC42BE9AADE1DA2906A165F50295C6C3AAE6B0178CA1105BA5107DA46C05C9B109AC6BAE123E7CBC6A52C`
SHA512 | `F4188CE6DAFA48775819EC6387F781357C39BFBCA1D733FDBFA6E5D880DE2E8C7D8F78046076CA5D5CBDEE6FAEB9B705FC297EF3A08DBFDDD9C03B1E184C3707`
SSDEEP | `12288:+uFG/3iJDrhVn43HRo4vRWQQkXBphGBnghhNBeELURZT7A/:91JDrhpexobkXrhGBg9gRZg/`

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

* Original Filename: FXSSVC.EXE
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.


## Possible Misuse

*The following table contains possible examples of `FXSSVC.exe` being misused. While `FXSSVC.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_susp_fax_dll.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/image_load/sysmon_susp_fax_dll.yml) | `        - fxssvc.exe` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1543.003.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1543.003/T1543.003.md) | sc config Fax binPath= "C:\WINDOWS\system32\fxssvc.exe" >nul 2>&1 | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)



MIT License. Copyright (c) 2020 Strontic.


