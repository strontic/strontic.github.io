---
title: SndVol.exe | Volume Mixer
excerpt: What is SndVol.exe?
---

# SndVol.exe 

* File Path: `C:\Windows\system32\SndVol.exe`
* Description: Volume Mixer

## Screenshot

![SndVol.exe](screenshots/SndVol.exe-7D7D5466FCDCD28976A004B5B08864E3-1.png)

## Hashes

Type | Hash
-- | --
MD5 | `C5D939AC3F9D885C8355884199E36433`
SHA1 | `B8F277549C23953E8683746E225E7AF1C193AD70`
SHA256 | `68B6CED01F5DFC2BC9556B005F4FFF235A3D02449AD9F9E4DE627C0E1424D605`
SHA384 | `44044BEA2BC31BAE0E5D41586C217076A7DC06E6BCD8040DFC932BECCA30BC49830A3F3CFC4F323D31CA084868E9CE6D`
SHA512 | `8488E7928E53085C00DF096AF2315490CD4B22CE2CE196B157DC0FBB820C5399A9DBD5DEAD40B24B99A4A32B6DE66B4EDC28339D7BACD9C1E7D5936604D1A4F0`
SSDEEP | `6144:nrkBmbgoYgyIwYk1UxnHfstd1WzBk+yuq2rzI5PcWoy10:wBCTJy/Yk1Ud0tzWOoy`
IMP | `C9F852C96B7C3A52C280EB97D52DA386`
PESHA1 | `7081C7A9A3C7965FA3092769AE52C1A864C612CE`
PE256 | `C34344CBE11619DC47029359EECA2D6EC70B6EE90D8C40765379C6248001871D`

## Runtime Data

### Window Title:
Volume Mixer - Remote Audio

### Open Handles:

Path | Type
-- | --
(R-D)   C:\Windows\Fonts\StaticCache.dat | File
(R-D)   C:\Windows\System32\en-US\sndvol.exe.mui | File
(R-D)   C:\Windows\System32\en-US\user32.dll.mui | File
(R-D)   C:\Windows\System32\en-US\wdmaud.drv.mui | File
(RW-)   C:\Users\user | File
(RW-)   C:\Windows\WinSxS\amd64_microsoft.windows.common-controls_6595b64144ccf1df_6.0.19041.1110_none_60b5254171f9507e | File
(RW-)   C:\Windows\WinSxS\amd64_microsoft.windows.gdiplus_6595b64144ccf1df_1.1.19041.1320_none_91a11828cc8ae445 | File
\BaseNamedObjects\__ComCatalogCache__ | Section
\BaseNamedObjects\C:\*ProgramData\*Microsoft\*Windows\*Caches\*{6AF0698E-D558-4F6E-9B3C-3716689AF493}.2.ver0x0000000000000002.db | Section
\BaseNamedObjects\C:\*ProgramData\*Microsoft\*Windows\*Caches\*{DDF571F2-BE98-426D-8288-1A9A39C3FDA2}.2.ver0x0000000000000002.db | Section
\BaseNamedObjects\C:\*ProgramData\*Microsoft\*Windows\*Caches\*cversions.2 | Section
\BaseNamedObjects\NLS_CodePage_1252_3_2_0_0 | Section
\BaseNamedObjects\NLS_CodePage_437_3_2_0_0 | Section
\Sessions\1\Windows\Theme449731986 | Section
\Windows\Theme1396518710 | Section


### Loaded Modules:

Path |
-- |
C:\Windows\System32\GDI32.dll |
C:\Windows\System32\gdi32full.dll |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\System32\msvcp_win.dll |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\system32\SndVol.exe |
C:\Windows\System32\ucrtbase.dll |
C:\Windows\System32\win32u.dll |


## Signature

* Status: Signature verified.
* Serial: `33000002EC6579AD1E670890130000000002EC`
* Thumbprint: `F7C2F2C96A328C13CDA8CDB57B715BDEA2CBD1D9`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: SndVol.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/73
* VirusTotal Link: https://www.virustotal.com/gui/file/68b6ced01f5dfc2bc9556b005f4fff235a3d02449ad9f9e4de627c0e1424d605/detection


## Possible Misuse

*The following table contains possible examples of `SndVol.exe` being misused. While `SndVol.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[signature-base](https://github.com/Neo23x0/signature-base) | [thor_inverse_matches.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/thor_inverse_matches.yar) | description = "Anomaly rule looking for certain strings in a system file (maybe false positive on certain systems) - file SndVol.exe" | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [thor_inverse_matches.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/thor_inverse_matches.yar) | filename == "sndvol.exe" | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)



MIT License. Copyright (c) 2020-2021 Strontic.


