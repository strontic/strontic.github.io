---
title: adpcmencode3.exe | ADPCM encoding and decoding utility
excerpt: What is adpcmencode3.exe?
---

# adpcmencode3.exe 

* File Path: `C:\Program Files (x86)\Windows Kits\10\bin\10.0.19041.0\x64\adpcmencode3.exe`
* Description: ADPCM encoding and decoding utility

## Hashes

Type | Hash
-- | --
MD5 | `12FFEE959BBC29D544DD6387E63981D4`
SHA1 | `A43EC313DA7B09AB9F4CFF757FE6A43162FE9487`
SHA256 | `CFC7FC6B150839C6E4591CAB1E4E518492FCDE547B5D41ACAEBC541251AD397D`
SHA384 | `BC28D210D52BEA9F2AA44E82B9C655A23C0C242F38FE97BF8C19AB7DD903BA8906D45FFBF469667CD93BB7F781B83687`
SHA512 | `32B8128CAD269895623A359840A8957616D3D6B4604940E671B4D927FF7406CBBDFE1CEED4C56FF7F57D7E99D153535E12DCC87ED8921C14DA53084646785541`
SSDEEP | `6144:eE/K3CrvjZ72vj5bU8d5SfKJ1xBFa3D2Au7qbUxG3M1:eE/K3Crv9yJ15sW/azNQQM1`
IMP | `0E2AE90C14F52662C701EB6CA9C81166`
PESHA1 | `D7FD0DA81DAC7FA28EFCEC1048706D2D13C31CEE`
PE256 | `CA33CD590FCC8BF7BB4FD5761F7353EDACC9943F32657EE979AEC2E36A1D8B8D`

## Runtime Data

### Usage (stdout):
```cmhg
Copyright (C) 2012 Microsoft Corporation. All rights reserved.

Usage: ADPCMENCODE [-b <N>] [-f <N>] <INPUTFILE>.wav <OUTPUTFILE>.wav

If the input file is PCM, it is encoded to an ADPCM file;
if the input file is ADPCM, it is decoded to a PCM file.

Input PCM files must be int8, int16 or float32, mono or stereo,
with at least 128 samples of audio and no loop regions shorter
than 128 samples.

Options:
	-b <32|64|128|256|512>: Number of samples per encoded ADPCM block (default 128)
	-f <N>: Bits per sample in decoded PCM file (8, 16, or 32; default 16)

Unrecognized flag "--"

```

### Loaded Modules:

Path |
-- |
C:\Program Files (x86)\Windows Kits\10\bin\10.0.19041.0\x64\adpcmencode3.exe |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\SYSTEM32\ntdll.dll |


## Signature

* Status: Signature verified.
* Serial: `33000002CF6D2CC57CAA65A6D80000000002CF`
* Thumbprint: `1A221B3B4FEF088B17BA6704FD088DF192D9E0EF`
* Issuer: CN=Microsoft Code Signing PCA 2010, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Corporation, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: AdpcmEncode.exe
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: Unknown
* VirusTotal Link: n/a

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Program Files (x86)\Windows Kits\10\bin\10.0.19041.0\x86\adpcmencode3.exe](adpcmencode3.exe-1390AAF9893E6224845F89C45EC874F4.md) | 52
[C:\Windows\system32\dsound.dll](dsound.dll-E6A43513FF267EAF7A112F94A403A5A5.md) | 38
[C:\Windows\system32\MFWMAAEC.DLL](MFWMAAEC.DLL-9AFF52024F094A99E9CF00419554F897.md) | 40
[C:\Windows\system32\RESAMPLEDMO.DLL](RESAMPLEDMO.DLL-DAFBFA941F1D5AF65C296A2B22D0EC7A.md) | 65
[C:\Windows\SysWOW64\RESAMPLEDMO.DLL](RESAMPLEDMO.DLL-9C05809E9338FE9D71A1E7C699FA06A0.md) | 50




MIT License. Copyright (c) 2020 Strontic.


