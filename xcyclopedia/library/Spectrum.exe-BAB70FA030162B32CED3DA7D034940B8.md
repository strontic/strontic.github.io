---
title: Spectrum.exe | Windows Perception Service
excerpt: What is Spectrum.exe?
---

# Spectrum.exe 

* File Path: `C:\Windows\system32\Spectrum.exe`
* Description: Windows Perception Service

## Hashes

Type | Hash
-- | --
MD5 | `BAB70FA030162B32CED3DA7D034940B8`
SHA1 | `AE54F026D1B121017FF4F6080342C1270E90E2B9`
SHA256 | `AFF3D4AB8B126FA099E6B7C6899C0C7FCCD04401C5AC1890C96C689A65CD16B1`
SHA384 | `BED72835D0D959663E09ABCAD23B2B0EF8C9226ACA2C2FEEF80EC142DAF6C89571765BBD64F8BD9428C25DB7E257E007`
SHA512 | `C51ACCFF8BA45244200A27ADE5B44B85134E874B8D1A1244A4D5903968614AB545081DCB4B4893F7150ECC081F15E0F2870B44A1DC0D73DE229F86DA3B538B40`
SSDEEP | `6144:rIEp1wJUYJpBb+qkysObJiMzTv5J54tTeXMbNyV7dNJQMlX5Hq62ZCLOJ6RF7FMO:rdp1mNE+lJR3v1aeZtQ+K62cxFkrS`
IMP | `2D430AF2F5D536907F1205720822457A`
PESHA1 | `BAE24C2A99210F458CA885448CE7D49C87C95CF9`
PE256 | `5343AEFFCFBAFAC96147A8A20FD74EB5305DEC59710B4CFD93FB1CB9F192B5CD`

## Runtime Data

### Usage (stdout):
```cmhg
Unrecognized parameter: --help
Parameters:
 /debug             to run the service executable in debug mode
 /safemode          to set up the service to run in safe mode
 /safemode:off      to disable safe mode if enabled

```

### Loaded Modules:

Path |
-- |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\system32\Spectrum.exe |


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: Spectrum.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/76
* VirusTotal Link: https://www.virustotal.com/gui/file/aff3d4ab8b126fa099e6b7c6899c0c7fccd04401c5ac1890c96c689a65cd16b1/detection


## Possible Misuse

*The following table contains possible examples of `Spectrum.exe` being misused. While `Spectrum.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [Atomic_Friday.md](https://github.com/redcanaryco/atomic-red-team/blob/master/ARTifacts/Atomic_Friday/2020-06-05/Atomic_Friday.md) | - https://posts.specterops.io/detection-spectrum-198a0bfb9302 | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [index.md](https://github.com/redcanaryco/atomic-red-team/blob/master/docs/index.md) | testing their defenses against a broad spectrum of attacks. | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)



MIT License. Copyright (c) 2020-2021 Strontic.


