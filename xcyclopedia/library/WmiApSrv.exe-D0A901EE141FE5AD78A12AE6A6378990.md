---
title: WmiApSrv.exe | WMI Performance Reverse Adapter
---

# WmiApSrv.exe 

* File Path: `C:\Windows\system32\wbem\WmiApSrv.exe`
* Description: WMI Performance Reverse Adapter

## Hashes

Type | Hash
-- | --
MD5 | `D0A901EE141FE5AD78A12AE6A6378990`
SHA1 | `CDB1CAF9EB1EDF441375F320450C0CA7D637D63F`
SHA256 | `DBA5D56949BA383DAB17C3AB95EAC8B3F1B693729676D1A5637790F6E7F01ABD`
SHA384 | `D85D4A64A723131ABF5E236E6C9825E0C6FE15E89B7DD8C7B751E332BC287E0BDDF58F4CD4831709C77A3A0129CE9FC1`
SHA512 | `F4C856FF4C0A6D307CDEA5951E63A39D9E6F636DB7D73ED65B06D1ADFDB60BAE4AA8DDC0A66E7F06A1B5C2C777D297BE7F2E07BBD67AC653E11B79A764B99427`
SSDEEP | `3072:4jTP38cDpi9I/yt5ynxcXK4y4lDh3DU5YbYK7jZWSMTwrlT:OTPscti9Ig4gy4r3o5g7jZWSMTwr`

## Runtime Data

### Loaded Modules:

Path |
-- |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\system32\wbem\WmiApSrv.exe |


## Signature

* Status: Signature verified.
* Serial: `330000026551AE1BBD005CBFBD000000000265`
* Thumbprint: `E168609353F30FF2373157B4EB8CD519D07A2BFF`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: WmiApSrv.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.17763.1 (WinBuild.160101.0800)
* Product Version: 10.0.17763.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.


## Possible Misuse

*The following table contains possible examples of `WmiApSrv.exe` being misused. While `WmiApSrv.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_wmi_module_load.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/image_load/sysmon_wmi_module_load.yml) | `            - '\WmiAPsrv.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020 Strontic.


