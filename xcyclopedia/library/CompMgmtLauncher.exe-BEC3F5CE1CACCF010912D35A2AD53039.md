---
title: CompMgmtLauncher.exe | Computer Management Snapin Launcher
excerpt: What is CompMgmtLauncher.exe?
---

# CompMgmtLauncher.exe 

* File Path: `C:\WINDOWS\system32\CompMgmtLauncher.exe`
* Description: Computer Management Snapin Launcher

## Hashes

Type | Hash
-- | --
MD5 | `BEC3F5CE1CACCF010912D35A2AD53039`
SHA1 | `6EDD0AFB318FE23ACDD6A632D0EEAF0C44AD94B6`
SHA256 | `5324F9F709D3BF362784D79C9CA366E665FB2FC4BEAD13F82A23CF409F4E3064`
SHA384 | `32292C70F4EE1F914D3F29AA811AC099CE3405589582DA198D5F2A9E40DAF95ECB411C5B4460D07ED306488D4BDD3319`
SHA512 | `2D65A94DF83EC458083D24F2306881C22360963C29E7817AB5AE6D00D40486B8FF2964B72DDC5D0DF24F29381453186E26BD681E31A0475E096224B7AC53F091`
SSDEEP | `1536:+4yWplUNwJqZDM/KSiobRmaAhaAtdddddddddZEUlOo+vi6Uf:+klUKJq1M/DiAmaAhlWUco+Q`
IMP | `538A832DEFC229579607486BF4D9D0AD`
PESHA1 | `7A7FE312B0409CECE272F5929E998D2DFE3C4736`
PE256 | `0B4A38874B1C895A133898ACA04A449525912416E7181FB6008D676FA529B151`

## Runtime Data

### Child Processes:
mmc.exe

### Loaded Modules:

Path |
-- |
C:\WINDOWS\system32\CompMgmtLauncher.exe |
C:\WINDOWS\System32\KERNEL32.DLL |
C:\WINDOWS\System32\KERNELBASE.dll |
C:\WINDOWS\System32\msvcp_win.dll |
C:\WINDOWS\SYSTEM32\ntdll.dll |
C:\WINDOWS\System32\SHELL32.dll |
C:\WINDOWS\System32\ucrtbase.dll |
C:\WINDOWS\System32\USER32.dll |


## Signature

* Status: Signature verified.
* Serial: `33000002ED2C45E4C145CF48440000000002ED`
* Thumbprint: `312860D2047EB81F8F58C29FF19ECDB4C634CF6A`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: CompMgmtLauncher.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.22000.1 (WinBuild.160101.0800)
* Product Version: 10.0.22000.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/70
* VirusTotal Link: https://www.virustotal.com/gui/file/5324f9f709d3bf362784d79c9ca366e665fb2fc4bead13f82a23cf409f4e3064/detection

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Windows\system32\CompMgmtLauncher.exe](CompMgmtLauncher.exe-28317A51B8F874BCF5220872269FEC2C.md) | 38
[C:\WINDOWS\system32\CompMgmtLauncher.exe](CompMgmtLauncher.exe-E0861FA9E0A4B441C6A11405D12D0C30.md) | 33
[C:\Windows\system32\CompMgmtLauncher.exe](CompMgmtLauncher.exe-ED3867E805501925E10070A1430E13DF.md) | 29
[C:\windows\system32\CompMgmtLauncher.exe](CompMgmtLauncher.exe-EF0DB115967BFB1996403434AA3C9D7E.md) | 33
[C:\Windows\system32\CompMgmtLauncher.exe](CompMgmtLauncher.exe-FF9690925244473ECC4C2E5B535B8599.md) | 32
[C:\Windows\system32\ServerManagerLauncher.exe](ServerManagerLauncher.exe-984C9F7202A43577C2A3D52A1300FFE7.md) | 35
[C:\Windows\system32\ServerManagerLauncher.exe](ServerManagerLauncher.exe-CA3A931A56D4B2429A39871131964101.md) | 38
[C:\windows\system32\ServerManagerLauncher.exe](ServerManagerLauncher.exe-CF83A07EECB55210ADAA65EF8B4C75D8.md) | 40

## Possible Misuse

*The following table contains possible examples of `CompMgmtLauncher.exe` being misused. While `CompMgmtLauncher.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[malware-ioc](https://github.com/eset/malware-ioc) | [win_apt_invisimole_uac_bypass.yml](https://github.com/eset/malware-ioc/blob/master/invisimole/sigma/win_apt_invisimole_uac_bypass.yml) | `- '\CompMgmtLauncher.exe'`{:.highlight .language-yaml} | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)



MIT License. Copyright (c) 2020-2021 Strontic.


