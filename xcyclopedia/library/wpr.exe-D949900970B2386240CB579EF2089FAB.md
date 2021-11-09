---
title: wpr.exe | Microsoft Windows Performance Recorder
excerpt: What is wpr.exe?
---

# wpr.exe 

* File Path: `C:\WINDOWS\system32\wpr.exe`
* Description: Microsoft Windows Performance Recorder

## Hashes

Type | Hash
-- | --
MD5 | `D949900970B2386240CB579EF2089FAB`
SHA1 | `FA2724F1C196AE08603026F735FA50E26205F857`
SHA256 | `FB10E998BA94E4F569442DC4F0A1CC19F647D42D01E679541F49DEE85EA0A3D2`
SHA384 | `78D6C411C70781F4781D0F9C3F01718804E9BA1C80A8C3B72EB0BE489F9B25300892403FF8F15D24ACA5D469A00B2913`
SHA512 | `9AF46F666484E060949CA6CB6A80A8F910D80DF37092B23AFA2D62E31EB43B60D6FDBD3668956B7C4414F9A1C275BA4724CCEEB5FC57FEB24A227E8E6B3DC998`
SSDEEP | `6144:VP+9qCAJmJXQBA44xRtyGpC7+eOay9EmttplJkKPVWeBOE7V:V6kBARdC7+eeL7V`
IMP | `E1F2950769FC7DC6502F4A8AC757C099`
PESHA1 | `3344A6FF0FA0D3A4D7B2F0CC3BCDF04F87C04767`
PE256 | `CDF1EC956CFB8F158AAD861056C1339178C1D71FA11AEBF7FC6C905BA788C235`

## Runtime Data

### Usage (stdout):
```cmhg

Microsoft Windows Performance Recorder Version 10.0.22000 (CoreSystem)
Copyright (c) 2021 Microsoft Corporation. All rights reserved.

	Usage: wpr options ...

	-help start		 - for trace start command
	-help stop		 - for trace stop commands
	-help status		 - for trace status command
	-help profiles		 - for profiles commands
	-help providers		 - for providers command
	-help tracing		 - for in trace commands
	-help boottrace		 - for boot trace (autologger) commands
	-help heap		 - for heap tracing commands
	-help hardwarecounter	 - for hardware counter configuration commands
	-help advanced		 - for advanced trace commands

```

### Usage (stderr):
```cmhg

	Invalid command syntax.

	Error code: 0xc5600602
	Invalid option: --help

```

### Loaded Modules:

Path |
-- |
C:\WINDOWS\System32\KERNEL32.DLL |
C:\WINDOWS\System32\KERNELBASE.dll |
C:\WINDOWS\SYSTEM32\ntdll.dll |
C:\WINDOWS\system32\wpr.exe |


## Signature

* Status: Signature verified.
* Serial: `33000002ED2C45E4C145CF48440000000002ED`
* Thumbprint: `312860D2047EB81F8F58C29FF19ECDB4C634CF6A`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: WPR.exe
* Product Name: Microsoft Windows Performance Recorder
* Company Name: Microsoft Corporation
* File Version: 10.0.22000.1 (WinBuild.160101.0800)
* Product Version: 10.0.22000.1
* Language: English (United States)
* Legal Copyright:  2021 Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/73
* VirusTotal Link: https://www.virustotal.com/gui/file/fb10e998ba94e4f569442dc4f0a1cc19f647d42d01e679541f49dee85ea0a3d2/detection


## Possible Misuse

*The following table contains possible examples of `wpr.exe` being misused. While `wpr.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[signature-base](https://github.com/Neo23x0/signature-base) | [thor-hacktools.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/thor-hacktools.yar) | description = "Windows Password Recovery - file wpr.exe" | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [thor-hacktools.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/thor-hacktools.yar) | $s1 = "WPR.exe" fullword wide | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)



MIT License. Copyright (c) 2020-2021 Strontic.


