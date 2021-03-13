---
title: adpcmencode3.exe | ADPCM encoding and decoding utility
excerpt: What is adpcmencode3.exe?
---

# adpcmencode3.exe 

* File Path: `C:\Program Files (x86)\Windows Kits\10\bin\10.0.19041.0\x86\adpcmencode3.exe`
* Description: ADPCM encoding and decoding utility

## Hashes

Type | Hash
-- | --
MD5 | `1390AAF9893E6224845F89C45EC874F4`
SHA1 | `5F072BFD5BFA3C77B4C6A2EA9B253665BC55CE9F`
SHA256 | `E848E0A5384E2A0B0FF8B871598132D7A04BB809A35A9ED274F3F0FBF2ADAD3D`
SHA384 | `60D023BFB1ED66FFFC6569EA5DC42BAA03C960487D02E53FE045B46EB60DC968DADD1EFCBC9DDF853B2B34E637F30BF8`
SHA512 | `28C6882A5ADF0995409F81C6145DFF913BDC7973458C138969094EB68FF1B03C89932D7ADACA5C8513A6194F74206EC074EA5EA9E3B6A5E02DE3183A35D09334`
SSDEEP | `6144:lp5ZU8d5SfqJ1xBFa3D2Au7qbUx3+XbKtpCxCBMD8BeEjqkkd6mCOv:lJ15s2/azNQdSKtW3v`
IMP | `AD4D2D13AF2C3FD9E81859ADC25AD651`
PESHA1 | `15C3AF7A8C6C0A89B671BFE35D6A76C754965330`
PE256 | `073165442A80619129AA5AE56577A130D08697E90E4CB60B27FEC7F53A0E6355`

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
C:\Program Files (x86)\Windows Kits\10\bin\10.0.19041.0\x86\adpcmencode3.exe |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\wow64.dll |
C:\Windows\System32\wow64cpu.dll |
C:\Windows\System32\wow64win.dll |


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
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: Unknown

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Program Files (x86)\Windows Kits\10\bin\10.0.19041.0\x64\adpcmencode3.exe](adpcmencode3.exe-12FFEE959BBC29D544DD6387E63981D4.md) | 52
[C:\Windows\system32\RESAMPLEDMO.DLL](RESAMPLEDMO.DLL-DAFBFA941F1D5AF65C296A2B22D0EC7A.md) | 57
[C:\Windows\SysWOW64\dsound.dll](dsound.dll-ABD7791A43B6C56891BFC5D4EE0063D2.md) | 36
[C:\Windows\SysWOW64\MFWMAAEC.DLL](MFWMAAEC.DLL-3FA8077C9C6A769B3BD88800E818BDF6.md) | 40
[C:\Windows\SysWOW64\RESAMPLEDMO.DLL](RESAMPLEDMO.DLL-9C05809E9338FE9D71A1E7C699FA06A0.md) | 55
[C:\Windows\SysWOW64\Windows.Media.Audio.dll](Windows.Media.Audio.dll-AEF1FAF596F549314AED6400BD708759.md) | 29




MIT License. Copyright (c) 2020-2021 Strontic.


