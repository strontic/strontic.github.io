---
title: CompatTelRunner.exe | Microsoft Compatibility Telemetry
---

# CompatTelRunner.exe 

* File Path: `C:\windows\system32\CompatTelRunner.exe`
* Description: Microsoft Compatibility Telemetry
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `4BDD8E93D7A5E57BEA22B18BF9675021`
SHA1 | `ABFBB7D770FF065A025253087F85A23FCA07EFA0`
SHA256 | `5F7B85D4E6AC19E16D3C32042ECDE9EF32CDDE0B4021FE4D609D096EF5DC972F`
SHA384 | `053234EB6D9D11ADE68FC7D7DEFBCDBA3AA73504C8D0547E2425BFD4A6447F1DA220FE886722AB7726274E3C7B80FB94`
SHA512 | `97D03FD67FF311F7D5E98B1D6780ED0843B5B08208C5BE1F813A7807CADEE287BAC93243E0B14DD59ACCEA6F60E2E3A35DD403D3A819BD045AE3053415F345D3`
SSDEEP | `3072:zN432737xQMMR0Lfz5xbSxwx5ObxUrWwmXgtDD+6BD4nax79Uk8WEMdU8MCKR:z232737uMMRUlxrx5+xUrWw1A6ukndUz`

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
* Serial: `33000002CF6D2CC57CAA65A6D80000000002CF`
* Thumbprint: `1A221B3B4FEF088B17BA6704FD088DF192D9E0EF`
* Issuer: CN=Microsoft Code Signing PCA 2010, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Corporation, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: CompatTelRunner.exe
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.18362.1035 (WinBuild.160101.0800)
* Product Version: 10.0.18362.1035
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\WINDOWS\system32\CompatTelRunner.exe](CompatTelRunner.exe-1E79615EF9946EB8A28D15584B21DB2F.md) | 32
[C:\Windows\system32\CompatTelRunner.exe](CompatTelRunner.exe-E261809228A9C7DDD17E7E0B5E23704C.md) | 32
[C:\Windows\system32\CompatTelRunner.exe](CompatTelRunner.exe-F3C4479D5AC4E943381049640E628993.md) | 32

## Possible Misuse

*The following table contains possible examples of `CompatTelRunner.exe` being misused. While `CompatTelRunner.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_wmi_module_load.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/image_load/sysmon_wmi_module_load.yml) | `            - '\CompatTelRunner.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_raw_disk_access_using_illegitimate_tools.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/sysmon/sysmon_raw_disk_access_using_illegitimate_tools.yml) | `            - '\compattelrunner.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_wmi_module_load.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/sysmon/sysmon_wmi_module_load.yml) | `            - '\CompatTelRunner.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020 Strontic.


