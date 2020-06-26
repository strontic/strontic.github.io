---
title: ntoskrnl.exe | NT Kernel & System
---

# ntoskrnl.exe 

* File Path: `C:\WINDOWS\system32\ntoskrnl.exe`
* Description: NT Kernel & System
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `E876B427E3F116CC37EA3BA758FCB00D`
SHA1 | `AEB320E8897708BC7A808C1A369038DC463DDC2D`
SHA256 | `CCCFDA078A89D2ADB3BD6E93F30A031B24FD37FBF2CAF3D2A6BB39F2E790D13B`
SHA384 | `55E261C9BFAD147957B90FEBB2F854DD390FCCF30694AEFB5652C4C3F55FBDE51C8EBD4BA9B44D0A3631D684E5D189ED`
SHA512 | `1D240FD30158A7E919345FD214266DC212CFA84200941061B33C291691AD1DCC0A9F450D9BA00A168A5A3163F0F7FBFA1AC08BAB1DFE3B10E88D3022537841F9`
SSDEEP | `98304:DO8HiadPoQXojOqRg+iaoyYEA0oa8xNOu7nNI8JijYkPcZ:7xBiBRgyfYw8fOu7nvUjYkPcZ`

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
* File Version: 10.0.18362.836 (WinBuild.160101.0800)
* Product Version: 10.0.18362.836
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.


## Possible Misuse

*The following table contains possible examples of `ntoskrnl.exe` being misused. While `ntoskrnl.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1106.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1106/T1106.md) | <blockquote>Adversaries may interact with the native Windows application programming interface (API) to execute behaviors. Similar to the system call interface on UNIX systems, the Windows native API provides a controlled means to calling low-level OS services within the kernel, such as those involving hardware/devices, memory, and processes. The native API is leveraged by the OS during system boot (when other system components are not yet initialized) but is also exposed to user-mode applications via ntdll.dll and ntoskrnl.exe.(Citation: Microsoft NativeAPI) | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)



MIT License. Copyright (c) 2020 Strontic.


