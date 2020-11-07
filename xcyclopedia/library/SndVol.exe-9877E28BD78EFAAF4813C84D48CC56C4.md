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
MD5 | `9877E28BD78EFAAF4813C84D48CC56C4`
SHA1 | `56F9639C87C4D9E08C92D115F4EF7955697FE77D`
SHA256 | `5BE12686C75A1F034EAC11031A7440EA40731298DF5F7296B2C5462028793BF3`
SHA384 | `3498A8467E84A6FA53064C97A79B09E2E5933416AF3DBDDDEF02D37DB1CEF84411BDC979C9289B4EF38423EE8CC2EE00`
SHA512 | `B6E504BC4E8336D4FD8733594DEB8CE6165DB48E978DB1C1538AE23C5F17AA24DAAABE6F3DF2819BCE950618B59AE0115F6C37F7A9841D1FF38D471B56397AF8`
SSDEEP | `6144:M/k6mogoeAAVpq4jpExOd3n3u8Ggu0kr/2rzIBqncyXy10X:r6pTjA7q4jpEcX3upgvXyM`
IMP | `C9F852C96B7C3A52C280EB97D52DA386`
PESHA1 | `520734A2AD986A81109CDA0CFE288BF73669F784`
PE256 | `2BE10F4FC1DC3E6202C0F765B848E2DD4AD3A9299AF8A419E52125B31D739E59`

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
(RW-)   C:\Windows\WinSxS\amd64_microsoft.windows.common-controls_6595b64144ccf1df_6.0.19041.488_none_ca04af081b815d21 | File
(RW-)   C:\Windows\WinSxS\amd64_microsoft.windows.gdiplus_6595b64144ccf1df_1.1.19041.572_none_fae9a23b76193bbb | File
\BaseNamedObjects\__ComCatalogCache__ | Section
\BaseNamedObjects\C:\*ProgramData\*Microsoft\*Windows\*Caches\*{6AF0698E-D558-4F6E-9B3C-3716689AF493}.2.ver0x0000000000000002.db | Section
\BaseNamedObjects\C:\*ProgramData\*Microsoft\*Windows\*Caches\*{DDF571F2-BE98-426D-8288-1A9A39C3FDA2}.2.ver0x0000000000000002.db | Section
\BaseNamedObjects\C:\*ProgramData\*Microsoft\*Windows\*Caches\*cversions.2 | Section
\BaseNamedObjects\NLS_CodePage_1252_3_2_0_0 | Section
\BaseNamedObjects\NLS_CodePage_437_3_2_0_0 | Section
\Sessions\1\Windows\Theme1800662698 | Section
\Windows\Theme722103516 | Section


### Loaded Modules:

Path |
-- |
C:\Windows\System32\bcryptPrimitives.dll |
C:\Windows\System32\combase.dll |
C:\Windows\system32\dwmapi.dll |
C:\Windows\System32\GDI32.dll |
C:\Windows\System32\gdi32full.dll |
C:\Windows\System32\IMM32.dll |
C:\Windows\SYSTEM32\kernel.appcore.dll |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\System32\MSCTF.dll |
C:\Windows\System32\msvcp_win.dll |
C:\Windows\System32\msvcrt.dll |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\ole32.dll |
C:\Windows\System32\OLEAUT32.dll |
C:\Windows\System32\RPCRT4.dll |
C:\Windows\System32\sechost.dll |
C:\Windows\System32\shcore.dll |
C:\Windows\System32\SHELL32.dll |
C:\Windows\System32\SHLWAPI.dll |
C:\Windows\system32\SndVol.exe |
C:\Windows\System32\ucrtbase.dll |
C:\Windows\System32\USER32.dll |
C:\Windows\system32\UxTheme.dll |
C:\Windows\System32\win32u.dll |
C:\Windows\WinSxS\amd64_microsoft.windows.common-controls_6595b64144ccf1df_6.0.19041.488_none_ca04af081b815d21\COMCTL32.dll |
C:\Windows\WinSxS\amd64_microsoft.windows.gdiplus_6595b64144ccf1df_1.1.19041.572_none_fae9a23b76193bbb\gdiplus.dll |


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
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

* VirusTotal Detections: 0/76
* VirusTotal Link: https://www.virustotal.com/gui/file/5be12686c75a1f034eac11031a7440ea40731298df5f7296b2c5462028793bf3/detection


## Possible Misuse

*The following table contains possible examples of `SndVol.exe` being misused. While `SndVol.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[signature-base](https://github.com/Neo23x0/signature-base) | [thor_inverse_matches.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/thor_inverse_matches.yar) | description = "Anomaly rule looking for certain strings in a system file (maybe false positive on certain systems) - file SndVol.exe" | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [thor_inverse_matches.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/thor_inverse_matches.yar) | filename == "sndvol.exe" | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)



MIT License. Copyright (c) 2020 Strontic.


