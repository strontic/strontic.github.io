---
title: CompatTelRunner.exe | Microsoft Compatibility Telemetry
---

# CompatTelRunner.exe 

* File Path: `C:\Windows\system32\CompatTelRunner.exe`
* Description: Microsoft Compatibility Telemetry

## Hashes

Type | Hash
-- | --
MD5 | `D106A29E1A787A673ACBB11968EFDFF5`
SHA1 | `992AAAB7A56C5447A2D5209D3135E1F9494A97D5`
SHA256 | `D4C583BC6EFD5F24ADF5C70421BA3FDCF6A53B010BC6A0D96147A6C7C3ADBC0C`
SHA384 | `33A5D8054A54D1307B3A7CD1C7AC4B21FE62E4A135619553984B8DBE50CF40C6556145BFAE85BC06D89D2E447F6BF6AF`
SHA512 | `392737C08A8BE420561D3189BDB64714D265D23C10C00915CA8E6C471BCFDBE0C6501C955608F3CF6C907C4E9D630EE847A0A5027E45D01F624C13CFCBBF506F`
SSDEEP | `3072:emQNq9Gqo0bp/59ziXK4z2fuukK+NqD2n6f9UkaVxR8t3J2wPFr:ejNq95o0l/59ziXK4zkNA5k8R8dV`

## Runtime Data

### Loaded Modules:

Path |
-- |
C:\Windows\system32\CompatTelRunner.exe |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\SYSTEM32\ntdll.dll |


## Signature

* Status: Signature verified.
* Serial: `330000026551AE1BBD005CBFBD000000000265`
* Thumbprint: `E168609353F30FF2373157B4EB8CD519D07A2BFF`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: CompatTelRunner.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.


## Possible Misuse

*The following table contains possible examples of `CompatTelRunner.exe` being misused. While `CompatTelRunner.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_wmi_module_load.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/image_load/sysmon_wmi_module_load.yml) | `            - '\CompatTelRunner.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_raw_disk_access_using_illegitimate_tools.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/sysmon/sysmon_raw_disk_access_using_illegitimate_tools.yml) | `            - '\compattelrunner.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020 Strontic.


