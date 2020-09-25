---
title: movefile.exe | Creates pending movefile operations
excerpt: What is movefile.exe?
---

# movefile.exe 

* File Path: `C:\SysinternalsSuite\movefile.exe`
* Description: Creates pending movefile operations

## Hashes

Type | Hash
-- | --
MD5 | `892B25C16DA4069763DE468B2963568D`
SHA1 | `731ED45EEF687415935EE3B3F6162CC38DEDB77D`
SHA256 | `B1778554BEE9C009176A3FE3C69C5F72B2ADDD7A439F6CCE9851D4F631235B25`
SHA384 | `DFC0FAECD05A5724B998B347E4C7E3BF8DD9FE3AE1DABDFBE28E0F11FAAF5FF4064203FF1FB9F4805EF94707F55B110D`
SHA512 | `89693ABB6EA45DA8172C53CF86D32BFCC12D027F92A8E3F0B56782DEDD06F75471C3DABC25273DDDB61A0A6A2B61CE8D96A337AAC47625BB26F4FC3DD7F84128`
SSDEEP | `6144:Hfjub9or3kJYPKvo5E54yNZVq+cHU+tVQFXFubdhoOr:Hqb9U3kJYivyE5JfVDcLn/oOr`
IMP | `58CB6D6C0C404F2663C74B01F9277912`
PESHA1 | `E193269865D5396F296067AD91FC60B7ED5292DB`
PE256 | `FAA460445354DC71F2BC5433813C30677AB9D5ACAF59F4A05874E7D5C34ED5E0`

## Runtime Data

### Usage (stdout):
```cmhg

MoveFile v1.02 - Creates pending movefile operations
Copyright (C) 2001-2016 Mark Russinovich
Sysinternals - www.sysinternals.com

usage: movefile [/nobanner] [source] [dest]

Specifying an empty destination ("") deletes the source at boot.
/nobanner    Do not display the startup banner and copyright message.


```

### Loaded Modules:

Path |
-- |
C:\SysinternalsSuite\movefile.exe |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\wow64.dll |
C:\Windows\System32\wow64cpu.dll |
C:\Windows\System32\wow64win.dll |


## Signature

* Status: Signature verified.
* Serial: `3300000187721772155940C709000000000187`
* Thumbprint: `2485A7AFA98E178CB8F30C9838346B514AEA4769`
* Issuer: CN=Microsoft Code Signing PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Corporation, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: movefile
* Product Name: movefile
* Company Name: Sysinternals - www.sysinternals.com
* File Version: 1.02
* Product Version: 1.02
* Language: English (United States)
* Legal Copyright: Copyright (C) 2001-2016 Mark Russinovich
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/71
* VirusTotal Link: https://www.virustotal.com/gui/file/b1778554bee9c009176a3fe3c69c5f72b2addd7a439f6cce9851d4f631235b25/detection/


## Possible Misuse

*The following table contains possible examples of `movefile.exe` being misused. While `movefile.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_keyboys.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_keyboys.yar) | $s7 = "Start MoveFile %s -> %s" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [gen_sysinternals_anomaly.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/gen_sysinternals_anomaly.yar) | $nfp3 = "usage: movefile [source] [dest]" wide | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)



MIT License. Copyright (c) 2020 Strontic.


