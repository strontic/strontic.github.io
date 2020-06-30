---
title: ntoskrnl.exe | NT Kernel & System
---

# ntoskrnl.exe 

* File Path: `C:\Windows\system32\ntoskrnl.exe`
* Description: NT Kernel & System
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `24008EA3B8D893524E2EA138DDC02660`
SHA1 | `5959934B4CBF3F9CE8A3184162564372025D0F48`
SHA256 | `0D72B46A5B1BC55BB7FBE916F3EB2DB5B0E9D75E07F1B8FC3774976695D93327`
SHA384 | `44B32E04A5684408D00F83EA8A2624CE7608E9FCD10ECE8AE8E5030988A39081E09E3CFF32C24D35FAD1E3C9AA17E1EF`
SHA512 | `EC7FBFA1C1DE7475A0BFE091F7C9F7FFFAD56C3D8522F7F65BE1E2963068744AF8A62D888F418F90FC4610562E545BEEB4265D80117626D7F5D8D04C9889D6D1`
SSDEEP | `98304:Fj7yyV3PqGxF11cYQAihz07uskmZVk12yOWzK5CeXE8hFxTIYwmaM:lyyJqGcXBJWA12Sml9hXDwmf`

## Runtime Data

### Usage (stdout):
```Batchfile

```

### Usage (stderr):
```Batchfile

```

### Child Processes:


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: ntkrnlmp.exe
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.17763.1282 (WinBuild.160101.0800)
* Product Version: 10.0.17763.1282
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.


## Possible Misuse

*The following table contains possible examples of `ntoskrnl.exe` being misused. While `ntoskrnl.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1106.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1106/T1106.md) | <blockquote>Adversaries may interact with the native Windows application programming interface (API) to execute behaviors. Similar to the system call interface on UNIX systems, the Windows native API provides a controlled means to calling low-level OS services within the kernel, such as those involving hardware/devices, memory, and processes. The native API is leveraged by the OS during system boot (when other system components are not yet initialized) but is also exposed to user-mode applications via ntdll.dll and ntoskrnl.exe.(Citation: Microsoft NativeAPI) | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)



MIT License. Copyright (c) 2020 Strontic.


