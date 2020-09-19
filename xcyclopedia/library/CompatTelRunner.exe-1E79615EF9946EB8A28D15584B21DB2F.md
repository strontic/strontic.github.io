---
title: CompatTelRunner.exe | Microsoft Compatibility Telemetry
---

# CompatTelRunner.exe 

* File Path: `C:\WINDOWS\system32\CompatTelRunner.exe`
* Description: Microsoft Compatibility Telemetry

## Hashes

Type | Hash
-- | --
MD5 | `1E79615EF9946EB8A28D15584B21DB2F`
SHA1 | `9C6A334BAC3122876FCFE3E46CE9A08BC60D6C3A`
SHA256 | `924405FD4DF46B0A1D955AA492F441B938F051CC830AB494E88398DEF701FC1F`
SHA384 | `D0C80B277009A14F9213F72AE3A7A2846C8CF6ED6C962B96F07CFCBEEDCB4D347CCE55861AA3B17FD7B69A16FD1153D8`
SHA512 | `40ECD7B2D273CF088BF0F6161656BC094290FF0148C6277A4D4E966C09CD03C07DD6C39AC814AE23B5BBA77E834385CA7A319F689E2783A6FC92CB8A6F66240B`
SSDEEP | `3072:v17mRucu5IfDAZp+dBYE6lDgQr9hbwwBr5cxQ+VBD4nax79UkJvmRItLJ2wkLkhM:N7mRuc0IfDUoBCge9hbwwBtaQH6ukMRJ`

## Signature

* Status: Signature verified.
* Serial: `330000023241FB59996DCC4DFF000000000232`
* Thumbprint: `FF82BC38E1DA5E596DF374C53E3617F7EDA36B06`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

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
[C:\windows\system32\CompatTelRunner.exe](CompatTelRunner.exe-4BDD8E93D7A5E57BEA22B18BF9675021.md) | 32
[C:\Windows\system32\CompatTelRunner.exe](CompatTelRunner.exe-E261809228A9C7DDD17E7E0B5E23704C.md) | 96
[C:\Windows\system32\CompatTelRunner.exe](CompatTelRunner.exe-F3C4479D5AC4E943381049640E628993.md) | 96

## Possible Misuse

*The following table contains possible examples of `CompatTelRunner.exe` being misused. While `CompatTelRunner.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_wmi_module_load.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/image_load/sysmon_wmi_module_load.yml) | `- '\CompatTelRunner.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_raw_disk_access_using_illegitimate_tools.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/sysmon/sysmon_raw_disk_access_using_illegitimate_tools.yml) | `- '\compattelrunner.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020 Strontic.


