---
title: vds.exe | Virtual Disk Service
---

# vds.exe 

* File Path: `C:\Windows\system32\vds.exe`
* Description: Virtual Disk Service
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `EC0D95737DE497BA0AD2223322B21280`
SHA1 | `2A4E3456AD73E7544F1A5DF14821CC5A659A3A53`
SHA256 | `DE976B547872B0919E16D5A97902B95893AD5B76DE6A11BE5F874EADBCA49F93`
SHA384 | `85C4BD2981DE0BCC984E22A6184392353D476767BB85A416775F6EB24BC241B27C64F305DF46FF625A366E07B85E05DC`
SHA512 | `4B647EBB1534090C9AE40F07E8E99824A8138FF22DB1D3E5C7B768C68E6E9E47931CF40716F9A73B7AA83C804F7BF762A3954C3070FA0B408F05D075E1A0AFEB`
SSDEEP | `6144:sKiWs0U8AJ7Mmz2Xaz4tdBxYVqMBreyVE3kjsOFNQzmsHLcrwFRRVH:MMOJ7AA4puqIrnJeHgo/`

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

* Original Filename: vds.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.14393.0 (rs1_release.160715-1616)
* Product Version: 10.0.14393.0
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.


## Possible Misuse

*The following table contains possible examples of `vds.exe` being misused. While `vds.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_raw_disk_access_using_illegitimate_tools.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/sysmon/sysmon_raw_disk_access_using_illegitimate_tools.yml) | `            - '\vds.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020 Strontic.


