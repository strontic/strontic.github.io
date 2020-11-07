---
title: wimserv.exe | Wimfltr v2 extractor
excerpt: What is wimserv.exe?
---

# wimserv.exe 

* File Path: `C:\Windows\system32\wimserv.exe`
* Description: Wimfltr v2 extractor

## Hashes

Type | Hash
-- | --
MD5 | `1E310C46056ACE8AE3C3E947B465DB05`
SHA1 | `C8A710EF9DD598B802EDB0E342C997E8CF992E3F`
SHA256 | `39BA7611E151D75D55DB784ADC001EF23BA88474A4FC223ECEA3F21312D15737`
SHA384 | `23BF41CF6FE97E3C07D3856C6779AF64896839DCAA10D1CAF7BECD419E35B1DCC26A2D8B8AF8DE6D95E668B9CE1302D2`
SHA512 | `8B4438CB3EB0C1DC9A585CE6D6AFEA260718A4F0E47E307D65D7C62BAA3D2371A373FB25FE1A842E48422DEB0497100CB283C25439FAD77056C3BEC4FBCC082A`
SSDEEP | `12288:7RWf4MEyIeF19bnpfE7DqJBimXiUHvNm2:l1xeZ+PqHim5HvNm2`
IMP | `D664C5CCBA7A8DE3C26390C871325E60`
PESHA1 | `3702CF6C39AA4427A7E1E278E4182329E85AC408`
PE256 | `2C0297587D2B17D1D52AB7E8754B116B04B987B3173A8E2648347C4C5F218BD0`

## Runtime Data

### Loaded Modules:

Path |
-- |
C:\Windows\System32\bcrypt.dll |
C:\Windows\system32\Cabinet.dll |
C:\Windows\system32\FLTLIB.DLL |
C:\Windows\System32\GDI32.dll |
C:\Windows\System32\gdi32full.dll |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\System32\msvcp_win.dll |
C:\Windows\System32\msvcrt.dll |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\RPCRT4.dll |
C:\Windows\System32\ucrtbase.dll |
C:\Windows\System32\user32.dll |
C:\Windows\system32\wimserv.exe |
C:\Windows\System32\win32u.dll |


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: extractr.exe
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.572 (WinBuild.160101.0800)
* Product Version: 10.0.19041.572
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/76
* VirusTotal Link: https://www.virustotal.com/gui/file/39ba7611e151d75d55db784adc001ef23ba88474a4fc223ecea3f21312d15737/detection


## Possible Misuse

*The following table contains possible examples of `wimserv.exe` being misused. While `wimserv.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_user_driver_loaded.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/builtin/win_user_driver_loaded.yml) | `- '*\Windows\System32\wimserv.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020 Strontic.


