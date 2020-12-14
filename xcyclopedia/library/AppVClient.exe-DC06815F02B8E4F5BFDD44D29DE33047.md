---
title: AppVClient.exe | Microsoft Application Virtualization Client Service
excerpt: What is AppVClient.exe?
---

# AppVClient.exe 

* File Path: `C:\Windows\system32\AppVClient.exe`
* Description: Microsoft Application Virtualization Client Service

## Hashes

Type | Hash
-- | --
MD5 | `DC06815F02B8E4F5BFDD44D29DE33047`
SHA1 | `6303B330F72D0E2DDF0A8561ED9133850C750C8E`
SHA256 | `03BC40C526BA6C67474DF13A61D724F7E01C39342D66C5F4BE7FC3F8A0F5A662`
SHA384 | `564D2BD90F9DEF1F8320EC9306249C01140598728F587A69B4BCD643C67ACC0D0D87C8339546B66280A83172C028B758`
SHA512 | `61A84E54EB5B2D65B400BF67E2CAE5687139EE5B2B25B6BE3758D973F6CA56CBA2DFAA54CE3192CE69393B128249A6D13FD2048C0E7FF7FEE43A33DC4CF71F37`
SSDEEP | `12288:5ph5FaYjJB0ZFLyFrwGZxW6jSYwdFBqJGNUbTpqGCICumH83M2X:f7F5f0ZJyFrwGvW6jSNdFBqTqGCICumK`
IMP | `A4529EE3A1660DAF1F914304A5C7333E`
PESHA1 | `BD652FA52F06ACFB80623C7D514F21B41BF55B18`
PE256 | `DBE422333C1C6097085B993829AA24919B01AD3CBF4CABC085C778DD0D896B6B`

## Runtime Data

### Loaded Modules:

Path |
-- |
C:\Windows\system32\AppVClient.exe |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\SYSTEM32\ntdll.dll |


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: AppVClient.exe
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.84 (WinBuild.160101.0800)
* Product Version: 10.0.19041.84
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/69
* VirusTotal Link: https://www.virustotal.com/gui/file/03bc40c526ba6c67474df13a61d724f7e01c39342d66c5f4be7fc3f8a0f5a662/detection


## Possible Misuse

*The following table contains possible examples of `AppVClient.exe` being misused. While `AppVClient.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_wmi_spwns_powershell.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_wmi_spwns_powershell.yml) | `- AppvClient` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020 Strontic.


