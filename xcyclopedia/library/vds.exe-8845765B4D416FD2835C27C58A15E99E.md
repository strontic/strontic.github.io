---
title: vds.exe | Virtual Disk Service
excerpt: What is vds.exe?
---

# vds.exe 

* File Path: `C:\Windows\system32\vds.exe`
* Description: Virtual Disk Service

## Hashes

Type | Hash
-- | --
MD5 | `8845765B4D416FD2835C27C58A15E99E`
SHA1 | `50CE4B4441661CBB0617A8D39476F9712FD31B4C`
SHA256 | `8A0AA93F17FEE2C816D57ADB6B6BE38D195D87A3CDCFBDDB78E0AF0D5452BC5E`
SHA384 | `7C0A8683387E1F62226AAE6DE5B64ACA50FE42ACEF8C9108D76014230E43962A17D584841D38AABB4F42B5E80F4AC56B`
SHA512 | `B965C1891027276A5299F854C45AC5A3155821B78C448562126BB9F79C5F6C2DADD1EDDA151653AE434A20D9281D804603892B930C6E36A00D1DB8F88C02E47A`
SSDEEP | `6144:TOKzUfSIW1onAtgXx/moIs8hxVR+7F7eYaj4se0LxQdxJ:T0AtgXx7Is8bCtVA4T8M`
IMP | `1DED34FA2F4887EC7854C3137A5F180D`
PESHA1 | `DB3505A17AF47608077CFA3542BF87CF4BB7EF9E`
PE256 | `92E371D1EBF466F641C6CC4B220A4438AB6E82499638B2A61172306403764573`

## Runtime Data

### Loaded Modules:

Path |
-- |
C:\Windows\system32\ATL.DLL |
C:\Windows\System32\bcrypt.dll |
C:\Windows\System32\cfgmgr32.dll |
C:\Windows\System32\combase.dll |
C:\Windows\System32\GDI32.dll |
C:\Windows\System32\gdi32full.dll |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\System32\msvcp_win.dll |
C:\Windows\System32\msvcrt.dll |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\OLEAUT32.dll |
C:\Windows\system32\OSUNINST.dll |
C:\Windows\System32\RPCRT4.dll |
C:\Windows\System32\sechost.dll |
C:\Windows\System32\SETUPAPI.dll |
C:\Windows\System32\ucrtbase.dll |
C:\Windows\System32\USER32.dll |
C:\Windows\system32\vds.exe |
C:\Windows\system32\vdsutil.dll |
C:\Windows\System32\win32u.dll |


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: vds.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/76
* VirusTotal Link: https://www.virustotal.com/gui/file/8a0aa93f17fee2c816d57adb6b6be38d195d87a3cdcfbddb78e0af0d5452bc5e/detection


## Possible Misuse

*The following table contains possible examples of `vds.exe` being misused. While `vds.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_raw_disk_access_using_illegitimate_tools.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/raw_access_thread/sysmon_raw_disk_access_using_illegitimate_tools.yml) | `- '\vds.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020-2021 Strontic.


