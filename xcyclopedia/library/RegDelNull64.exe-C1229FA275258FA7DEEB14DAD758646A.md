---
title: RegDelNull64.exe | Delete Registry keys with embedded Nulls
excerpt: What is RegDelNull64.exe?
---

# RegDelNull64.exe 

* File Path: `C:\SysinternalsSuite\RegDelNull64.exe`
* Description: Delete Registry keys with embedded Nulls

## Hashes

Type | Hash
-- | --
MD5 | `C1229FA275258FA7DEEB14DAD758646A`
SHA1 | `331EBD7F0708224B32E41E26C8B32DF3B2C607A3`
SHA256 | `F80D7E9727A1BE93DFA035BF0427FB2DEACD01CBE97CD75E218E1E772E21DF10`
SHA384 | `8B4AF0BA19A4A191ACFB9DC6CCCB1A83FDB49C2B0E9D850D0A43641BA73A71856867F461C628F55AC18ADD2F49E9EDCF`
SHA512 | `9634BA901F8AF642928F18F8115E237C525CA722F560A966C2A427CDDFA37E2C8BA181BAC901A6B6FF108D3102EC4F7FC7437581FECB5780F0E5881D1331A52C`
SSDEEP | `12288:Wq5zKzktS3HMmU5XPf98XlVnXB0cTAWpTD:WOm2SHMmU5XPf98XTnXBjT/TD`
IMP | `C58F62F2683389DEB81E1A7A9C1BB05E`
PESHA1 | `3604D0F4F8A12A198D0D90FB607B30C8A93F6A0E`
PE256 | `16AC570CCC857E7ED168106940D428EB211EC05D3973FB4A1EB798E333C75860`

## Runtime Data

### Usage (stdout):
```cmhg

RegDelNull v1.11 - Delete Registry keys with embedded Nulls
Copyright (C) 2005-2016 Mark Russinovich
Sysinternals - www.sysinternals.com

Usage: regdelnull <path> [-s]
  path    Registry path e.g. hklm\software
  -s      Recurse into subkeys
  -y      Suppress prompting for confirmation before deleting null-embedded keys.
  -nobanner
          Do not display the startup banner and copyright message.

Example: regdelnull -s hklm
This command scans all keys under HKLM.


```

### Usage (stderr):
```cmhg
The handle is invalid.

```

### Loaded Modules:

Path |
-- |
C:\SysinternalsSuite\RegDelNull64.exe |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\SYSTEM32\ntdll.dll |


## Signature

* Status: Signature verified.
* Serial: `3300000187721772155940C709000000000187`
* Thumbprint: `2485A7AFA98E178CB8F30C9838346B514AEA4769`
* Issuer: CN=Microsoft Code Signing PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Corporation, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: RegDelNull.exe
* Product Name: Sysinternals RegDelNull
* Company Name: Sysinternals - www.sysinternals.com
* File Version: 1.11
* Product Version: 1.11
* Language: English (United States)
* Legal Copyright: Copyright (C) 2005-2016 Mark Russinovich
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/67
* VirusTotal Link: https://www.virustotal.com/gui/file/f80d7e9727a1be93dfa035bf0427fb2deacd01cbe97cd75e218e1e772e21df10/detection/





MIT License. Copyright (c) 2020-2021 Strontic.


