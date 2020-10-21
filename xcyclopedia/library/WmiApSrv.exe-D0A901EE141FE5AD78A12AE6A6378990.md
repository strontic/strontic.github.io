---
title: WmiApSrv.exe | WMI Performance Reverse Adapter
excerpt: What is WmiApSrv.exe?
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
IMP | `6BC4858696E88B947919D50200792509`
PESHA1 | `2928AD0A6B472D45F300DE24886B8446C95455D1`
PE256 | `74B8EA4441F86956AE2FF6DF3B759FF5D3BD1A50CEE571D2A805288E4EE20EB6`

## Runtime Data

### Loaded Modules:

Path |
-- |
C:\Windows\System32\bcrypt.dll |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\System32\msvcrt.dll |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\RPCRT4.dll |
C:\Windows\System32\sechost.dll |
C:\Windows\system32\wbem\WmiApSrv.exe |
C:\Windows\SYSTEM32\wbemcomn.dll |
C:\Windows\System32\WS2_32.dll |


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
* File Version: 10.0.17763.1 (WinBuild.160101.0800)
* Product Version: 10.0.17763.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/70
* VirusTotal Link: https://www.virustotal.com/gui/file/dba5d56949ba383dab17c3ab95eac8b3f1b693729676d1a5637790f6e7f01abd/detection/


## Possible Misuse

*The following table contains possible examples of `WmiApSrv.exe` being misused. While `WmiApSrv.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_wmi_module_load.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/image_load/sysmon_wmi_module_load.yml) | `- '\WmiAPsrv.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020 Strontic.


