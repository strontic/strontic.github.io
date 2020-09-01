---
title: SIHClient.exe | SIH Client
---

# SIHClient.exe 

* File Path: `C:\WINDOWS\system32\SIHClient.exe`
* Description: SIH Client

## Hashes

Type | Hash
-- | --
MD5 | `373C3A47ECA082D4F65D7CE0C97F864F`
SHA1 | `0A971DFB0D33E3236110A84540207F33CFC748C7`
SHA256 | `274A9E80A5848D339C1FDB308EF67B255841B698E680719A5A9BEE893F0E34F0`
SHA384 | `BB9DE260207AC33EE505CF40B98E85C51329BBCEA750A420683E0EAD66DC5EE2039CA44E2D655E7A511947661FC6B809`
SHA512 | `6EB27D12E3319A9748216421549CEDB4C034823437E656C1A939D6F34080EC234CAA21FF4E29346D70C9D38122A4579D83AE6467CC479B49AA1775D4A7D6D67D`
SSDEEP | `6144:GwFdARhZVyuF3VJkcZFMV9giqkbVDbZGiM6lxH:Gw/038B9giqkpbZJ9lF`

### Loaded Modules:

Path |
-- |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\system32\sigverif.exe |


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: sihclient.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.18362.1 (WinBuild.160101.0800)
* Product Version: 10.0.18362.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.


## Possible Misuse

*The following table contains possible examples of `SIHClient.exe` being misused. While `SIHClient.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_wmi_module_load.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/image_load/sysmon_wmi_module_load.yml) | `            - '\SIHClient.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020 Strontic.


