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
MD5 | `B98C95BFDF2404A12D77AFBA3C8C1A59`
SHA1 | `267A457FABFE3493B9F93E99A410067BCC0728AA`
SHA256 | `D79729B2A955AE829D58A9F78EB0610F2E2014F52625A1E214D444FD45EE90DE`
SHA384 | `9CEE6B33F018FDE4FE2FF2905EBAF652990AD349388E99BC5E49F7A7D1F4DB0A3D45DF63F672894682040635DFF8FB1D`
SHA512 | `D64B4543B1CA7309C96AE594775D295653C3BA13A0178B882F04F8A77408ADB49538AEF7E2339975195560BEC16E94C995AA65BBE53C4EC29E378C752A34074A`
SSDEEP | `6144:nuGk5kSnyukXc+Po+S3VREHZK+WaeWTlaz9dOKhd7MezMvlAhgD8uAra12pr83sA:uGk5kXXcZzt00hM2ggZraMjt7+5M4`
IMP | `2D430AF2F5D536907F1205720822457A`
PESHA1 | `FF90D8C0574F6982B9268D42CC057DD6C069C824`
PE256 | `DD69C8710386F562E786C1752D7490487A69D0F4DB1662A228431DD4FED624CF`

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
* VirusTotal Link: https://www.virustotal.com/gui/file/d79729b2a955ae829d58a9f78eb0610f2e2014f52625a1e214d444fd45ee90de/detection


## Possible Misuse

*The following table contains possible examples of `Spectrum.exe` being misused. While `Spectrum.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [Atomic_Friday.md](https://github.com/redcanaryco/atomic-red-team/blob/master/ARTifacts/Atomic_Friday/2020-06-05/Atomic_Friday.md) | - https://posts.specterops.io/detection-spectrum-198a0bfb9302 | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [index.md](https://github.com/redcanaryco/atomic-red-team/blob/master/docs/index.md) | testing their defenses against a broad spectrum of attacks. | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)



MIT License. Copyright (c) 2020 Strontic.


