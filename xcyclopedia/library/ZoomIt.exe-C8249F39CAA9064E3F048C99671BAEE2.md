---
title: ZoomIt.exe | Sysinternals Screen Magnifier
excerpt: What is ZoomIt.exe?
---

# ZoomIt.exe 

* File Path: `C:\SysinternalsSuite\ZoomIt.exe`
* Description: Sysinternals Screen Magnifier

## Hashes

Type | Hash
-- | --
MD5 | `C8249F39CAA9064E3F048C99671BAEE2`
SHA1 | `E7DC294878ADDFA837ADAF779C09D6A7121F7CCF`
SHA256 | `4EC4CE141CDBF021A519DA833F10B904C2923F43648785777932510D056BF788`
SHA384 | `C94B9C8C34F3EFE9E0796632082C87EF254394A2C43373E86EE37B914770739E28FFE514C2CCD8EE9FBCDB33FBD36B67`
SHA512 | `A747F56D2AB1A712CDC554CEC025560EB4D50DE95270B36781835D41825B27C6379D5453BDC8163640F4192D23DCD5644E2D883F9F30B629A590154E5010D7F6`
SSDEEP | `24576:uzgkZP/Wd2wGfE2MlLBRPMS8/N2rAJ+mMx:uzggWd2wQ/N4AJ+3x`
IMP | `AAB6A36D2561253EBB244B26627BB34D`
PESHA1 | `C65494F7E19F3EADF7C1D03B4B6E756F2FB500E4`
PE256 | `723ED627E48915709B177156F041F621031AA034FA93981BE8C0C19B0194C457`

## Runtime Data

### Child Processes:
ZoomIt64.exe

### Open Handles:

Path | Type
-- | --
(RW-)   C:\Windows | File
(RW-)   C:\Windows\WinSxS\x86_microsoft.windows.common-controls_6595b64144ccf1df_6.0.19041.488_none_11b1e5df2ffd8627 | File
(RW-)   C:\Windows\WinSxS\x86_microsoft.windows.gdiplus_6595b64144ccf1df_1.1.19041.508_none_429cdbca8a8ffa94 | File
(RW-)   C:\xCyclopedia | File
\BaseNamedObjects\NLS_CodePage_1252_3_2_0_0 | Section
\BaseNamedObjects\NLS_CodePage_437_3_2_0_0 | Section


### Loaded Modules:

Path |
-- |
C:\SysinternalsSuite\ZoomIt.exe |
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

* Original Filename: ZoomIt.exe
* Product Name: Sysinternals ZoomIt
* Company Name: Sysinternals - www.sysinternals.com
* File Version: 4.52
* Product Version: 4.52
* Language: English (United States)
* Legal Copyright: Copyright  2006-2019 Mark Russinovich
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/71
* VirusTotal Link: https://www.virustotal.com/gui/file/4ec4ce141cdbf021a519da833f10b904c2923f43648785777932510d056bf788/detection/

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\SysinternalsSuite\ZoomIt64.exe](ZoomIt64.exe-5FF026E5FE0E820E50D53BDDE9B714EC.md) | 77

## Possible Misuse

*The following table contains possible examples of `ZoomIt.exe` being misused. While `ZoomIt.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[signature-base](https://github.com/Neo23x0/signature-base) | [crime_goldeneye.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/crime_goldeneye.yar) | $s1 = "ZoomIt - Sysinternals: www.sysinternals.com" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)



MIT License. Copyright (c) 2020 Strontic.


