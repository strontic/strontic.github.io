---
title: WmiApSrv.exe | WMI Performance Reverse Adapter
---

# WmiApSrv.exe 

* File Path: `C:\Windows\system32\wbem\WmiApSrv.exe`
* Description: WMI Performance Reverse Adapter

## Hashes

Type | Hash
-- | --
MD5 | `F07050509BBF408A56A3B33068C68815`
SHA1 | `C3727E6F4B7EE761E525AD5E7488F5C0C589D8D4`
SHA256 | `501358930C93C66C40A5A865CFB7BBC827A6882D504C2C1A6D8EF22E85631D8F`
SHA384 | `F92F10D2F6ADFCB9A2D4801FD485F7BBFBBBCE2CB060E34733DCAC33A464002A4290612C3280AA14981A4C107B8237BE`
SHA512 | `BFFA3C950529DF8FBD5288E00F87DA22346EB01C0140DB0DD936D5D33521FDB6537939E56E8738FEC68C155934D0BFEDF5DB9D626CF7FBE023EC2DB0F6FF24B0`
SSDEEP | `3072:a9iragTO+slHsJgGgiy86xq2U6RB4lcDLCMhKS0CwIDS6IxmX:5ragTO+slMJgfiyRMsUULuvIDS`

## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: WmiApSrv.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.14393.0 (rs1_release.160715-1616)
* Product Version: 10.0.14393.0
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.


## Possible Misuse

*The following table contains possible examples of `WmiApSrv.exe` being misused. While `WmiApSrv.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_wmi_module_load.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/image_load/sysmon_wmi_module_load.yml) | `- '\WmiAPsrv.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020 Strontic.


