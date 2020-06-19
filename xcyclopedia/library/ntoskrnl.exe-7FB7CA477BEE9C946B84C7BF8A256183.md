
# ntoskrnl.exe 

* File Path: `C:\Windows\system32\ntoskrnl.exe`
* Description: NT Kernel & System
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `7FB7CA477BEE9C946B84C7BF8A256183`
SHA1 | `9624B1DFC65D4053ABC6313F0816EFC8D0ED8A2E`
SHA256 | `7E50D19B89B4B29259625B58F5EB4696B37EEF69820C2227AB2A19457187F836`
SHA384 | `48B7C14E5EBC12407A56D88A2C3E63F8D7C98573945269DDF328CC720C5F93EEEAC2E15C224AEAD3C1659EEAD6FBD371`
SHA512 | `ECD4E83CD72719F5B8F40F4173D2B08E6E56C50CC7D8F71171A524251B6562B51663125A1872735865C1B09CD447B696FA46EAFADC7D43E579E41A0447ED7823`
SSDEEP | `98304:BgHF7AG/Ci96g1OMezQ3ux5EHFQqQyLDPQXT:B2FX/jAcOMeU3uAHFQqQMoXT`

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
* File Version: 10.0.14393.3686 (rs1_release.200504-1524)
* Product Version: 10.0.14393.3686
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.


## Possible Misuse

*The following table contains possible examples of `ntoskrnl.exe` being misused. While this file is **not** malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1106.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1106/T1106.md) | <blockquote>Adversaries may interact with the native Windows application programming interface (API) to execute behaviors. Similar to the system call interface on UNIX systems, the Windows native API provides a controlled means to calling low-level OS services within the kernel, such as those involving hardware/devices, memory, and processes. The native API is leveraged by the OS during system boot (when other system components are not yet initialized) but is also exposed to user-mode applications via ntdll.dll and ntoskrnl.exe.(Citation: Microsoft NativeAPI) | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)



MIT License. Copyright (c) 2020 Strontic.


