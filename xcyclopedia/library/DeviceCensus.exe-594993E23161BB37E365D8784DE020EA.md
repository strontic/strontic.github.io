---
title: DeviceCensus.exe | Device Census
---

# DeviceCensus.exe 

* File Path: `C:\Windows\system32\DeviceCensus.exe`
* Description: Device Census
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `594993E23161BB37E365D8784DE020EA`
SHA1 | `72B068446C47C606A257E6BFC43EDD3BE211F2DA`
SHA256 | `D26DEFA5D3E01EAC5E4CCADD9BA79F21C6B044EB2381642043A1BE34B14C0599`
SHA384 | `882D57486B73504764362C152CD861601283E793B7B80D57DF7AF9A2C6D38599B25791824FFFE0B57D7C6CB37F763362`
SHA512 | `3130A62B76DA644A1142F26A4B8FC1644E0F74A6903194296C9E6278D63DC1CB9BA9361E6F3406AF8E209E5D73E80613285BDD70BE1C6CBBA0EFAB8C9D44CA57`
SSDEEP | `768:g6RydRhNvtP2x3zmCil09N8kdyXXdauXXNI1PRCy:LRy3DFELi+v5cXXcEXKPJ`

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

* Original Filename: DeviceCensus.exe
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.


## Possible Misuse

*The following table contains possible examples of `DeviceCensus.exe` being misused. While `DeviceCensus.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_wmi_module_load.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/image_load/sysmon_wmi_module_load.yml) | `            - '\DeviceCensus.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020 Strontic.


