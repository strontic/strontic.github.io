---
title: WmiApSrv.exe | WMI Performance Reverse Adapter
excerpt: What is WmiApSrv.exe?
---

# WmiApSrv.exe 

* File Path: `C:\Windows\system32\wbem\WmiApSrv.exe`
* Description: WMI Performance Reverse Adapter

## Hashes

Type | Hash
-- | --
MD5 | `9A48D32D7DBA794A40BF030DA500603B`
SHA1 | `B04BE2BC0273784270D04F53F2A064507DF21F73`
SHA256 | `CBF60ED17A5B9CF79523F1493BCCD52B3C39632C4C83DE1FD49CFD2B70F01530`
SHA384 | `21801FC249ECD82C774041EA648C827AEA100BB944C7CF29E72734B2C742C68AB9D63152BBC371CFA666309557E1EDB6`
SHA512 | `C47A1633F5A9842BA4B567001ABCB87615E0B386A8E6CC4FE2680A93B14F430DCD9D9D8B4D05AC2D3624A30B5E1D556D7F1215B763029289D70012DE187EF6F9`
SSDEEP | `3072:bAiSyaIRNc6IQqHNOQpwLs2Z0PpEXcjZl+719nbJQORvpe:bwyaIRNcLDtOPo2Z0Ryc1lenWORvp`
IMP | `E91C5A3E92623E396D79A8A599CF25A9`
PESHA1 | `6851D07D9433AEFCCBE880F5A052C97E98F97ED9`
PE256 | `3F43CDD8F38097064625FCA6D25FAB7522CDAC9DECD55A6872A863A3A9284672`

## Runtime Data

### Loaded Modules:

Path |
-- |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\System32\msvcrt.dll |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\system32\wbem\WmiApSrv.exe |
C:\Windows\SYSTEM32\wbemcomn.dll |


## Signature

* Status: Signature verified.
* Serial: `33000002EC6579AD1E670890130000000002EC`
* Thumbprint: `F7C2F2C96A328C13CDA8CDB57B715BDEA2CBD1D9`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: WmiApSrv.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/73
* VirusTotal Link: https://www.virustotal.com/gui/file/cbf60ed17a5b9cf79523f1493bccd52b3c39632c4c83de1fd49cfd2b70f01530/detection

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Windows\system32\wbem\WmiApSrv.exe](WmiApSrv.exe-6389D05C6AAE73AD218CDC8153647CBB.md) | 88

## Possible Misuse

*The following table contains possible examples of `WmiApSrv.exe` being misused. While `WmiApSrv.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_wmi_module_load.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/image_load/sysmon_wmi_module_load.yml) | `- '\WmiApSrv.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020-2021 Strontic.


