---
title: CompatTelRunner.exe | Microsoft Compatibility Telemetry
---

# CompatTelRunner.exe 

* File Path: `C:\windows\system32\CompatTelRunner.exe`
* Description: Microsoft Compatibility Telemetry

## Hashes

Type | Hash
-- | --
MD5 | `F3C4479D5AC4E943381049640E628993`
SHA1 | `9916B5CF58F62099CE1F3BFA0DF880E124FE800B`
SHA256 | `F38EA7112FEA4E469883EF0935C9B47E31386E6A992494EAC12F1067BB45E86A`
SHA384 | `3D48C4418ED9614B7DB20A50F439456F17C994C4D6180C91843F43FC321C1F887799B5D9D0C67D2CAA37C276F6F2C1AE`
SHA512 | `70DBFE721603C7BA849049ADE4D071699D4D765F89596C02E69DFF97FF0DAE52B3FF899FFE6CBAE126A9232942F49DDE0C5AF105A8B5122ED02ADBC08C7CF0A2`
SSDEEP | `3072:S17mRucu5IfDAZp+dBYE6lDgQr9hbwwBr5cxQ+VBD4nax79UkJvmRItLJ2wkLk0Z:87mRuc0IfDUoBCge9hbwwBtaQH6ukMRp`

## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
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
[C:\WINDOWS\system32\CompatTelRunner.exe](CompatTelRunner.exe-1E79615EF9946EB8A28D15584B21DB2F.md) | 96
[C:\windows\system32\CompatTelRunner.exe](CompatTelRunner.exe-4BDD8E93D7A5E57BEA22B18BF9675021.md) | 32
[C:\Windows\system32\CompatTelRunner.exe](CompatTelRunner.exe-E261809228A9C7DDD17E7E0B5E23704C.md) | 96

## Possible Misuse

*The following table contains possible examples of `CompatTelRunner.exe` being misused. While `CompatTelRunner.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_wmi_module_load.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/image_load/sysmon_wmi_module_load.yml) | `            - '\CompatTelRunner.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_raw_disk_access_using_illegitimate_tools.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/sysmon/sysmon_raw_disk_access_using_illegitimate_tools.yml) | `            - '\compattelrunner.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020 Strontic.


