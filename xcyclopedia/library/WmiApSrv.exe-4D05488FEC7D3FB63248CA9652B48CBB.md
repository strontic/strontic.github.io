---
title: WmiApSrv.exe | WMI Performance Reverse Adapter
---

# WmiApSrv.exe 

* File Path: `C:\Windows\system32\wbem\WmiApSrv.exe`
* Description: WMI Performance Reverse Adapter
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `4D05488FEC7D3FB63248CA9652B48CBB`
SHA1 | `5877F71C48AE3F5F36F77E78EC86E4C7A7F1FBA7`
SHA256 | `5D51A62E14BE8F6A6894E8184CFD036EDAFC906D958E162FC9AC48462C6B2248`
SHA384 | `CCFE3A14FC514667DC8D1ED8CEC4851802F0B5F4414B564B1D769344B7BF0AC65BCADF4535BACA4C60DC63C47C7D0A7C`
SHA512 | `88C4E8A7B76196E91419CCD88A76DDA812E1642A5755220696D65A39CB64D7E2B901603603D109E72EED1727D9FFA5C7C5E9EB56C9D2FE36F374AD3BCFEB8FA6`
SSDEEP | `3072:InYyy1k/pQ64B/Od9OwOYw4s6pRPZ03sBPy+7mOErEFRRMRZJ1:u41k/pQ7BW/OLv6pRhiEPyzrEFMRZJ`

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

* Original Filename: WmiApSrv.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.


## Possible Misuse

*The following table contains possible examples of `WmiApSrv.exe` being misused. While `WmiApSrv.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_wmi_module_load.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/image_load/sysmon_wmi_module_load.yml) | `            - '\WmiAPsrv.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_wmi_module_load.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/sysmon/sysmon_wmi_module_load.yml) | `            - '\WmiAPsrv.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020 Strontic.


