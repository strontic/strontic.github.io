---
title: audiodg.exe | Windows Audio Device Graph Isolation 
---

# audiodg.exe 

* File Path: `C:\Windows\system32\audiodg.exe`
* Description: Windows Audio Device Graph Isolation 
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `30CE6C6D6DAD15411223A127C0405BE4`
SHA1 | `53FDE264C601BCF91E6806E46065A2EAEE43A6F6`
SHA256 | `18D496289E7992AA65D733715146597421EBAC179BEB593905AB42963043A0E1`
SHA384 | `9A7F7D711F1EBAF5CE1A08A77943EAFCFF8A2078B99E710399907E7DDFAD6EB251861AD90FF4CCC816C8CE061E6BDC68`
SHA512 | `517F8F0DAF061AAE28AFDD2606854A30AFB12A92C192146B2839BCDF2EA518D251EAA85B4D159CB67DD4E7534EB5A4C116D1BDC157FA6C402D0EEC2418521DBC`
SSDEEP | `12288:n+R8p4PptSXiRtfP68HJMbBLccXNSRLKmHYZbxwYlr:n+RzPptS2HiLccQLdYl5p`

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

* Original Filename: audioadg.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.17763.1 (WinBuild.160101.0800)
* Product Version: 10.0.17763.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.


## Possible Misuse

*The following table contains possible examples of `audiodg.exe` being misused. While `audiodg.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_creation_system_file.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/file_event/sysmon_creation_system_file.yml) | `            - '*\audiodg.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_system_exe_anomaly.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_system_exe_anomaly.yml) | `            - '*\audiodg.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_creation_system_file.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/sysmon/sysmon_creation_system_file.yml) | `            - '*\audiodg.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020 Strontic.


