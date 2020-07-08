---
title: vds.exe | Virtual Disk Service
---

# vds.exe 

* File Path: `C:\Windows\system32\vds.exe`
* Description: Virtual Disk Service

## Hashes

Type | Hash
-- | --
MD5 | `8845765B4D416FD2835C27C58A15E99E`
SHA1 | `50CE4B4441661CBB0617A8D39476F9712FD31B4C`
SHA256 | `8A0AA93F17FEE2C816D57ADB6B6BE38D195D87A3CDCFBDDB78E0AF0D5452BC5E`
SHA384 | `7C0A8683387E1F62226AAE6DE5B64ACA50FE42ACEF8C9108D76014230E43962A17D584841D38AABB4F42B5E80F4AC56B`
SHA512 | `B965C1891027276A5299F854C45AC5A3155821B78C448562126BB9F79C5F6C2DADD1EDDA151653AE434A20D9281D804603892B930C6E36A00D1DB8F88C02E47A`
SSDEEP | `6144:TOKzUfSIW1onAtgXx/moIs8hxVR+7F7eYaj4se0LxQdxJ:T0AtgXx7Is8bCtVA4T8M`

## Signature

* Status: Signature verified.
* Serial: `330000023241FB59996DCC4DFF000000000232`
* Thumbprint: `FF82BC38E1DA5E596DF374C53E3617F7EDA36B06`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: vds.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.


## Possible Misuse

*The following table contains possible examples of `vds.exe` being misused. While `vds.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_raw_disk_access_using_illegitimate_tools.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/sysmon/sysmon_raw_disk_access_using_illegitimate_tools.yml) | `            - '\vds.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020 Strontic.


