---
title: LsaIso.exe | Credential Guard & Key Guard
excerpt: What is LsaIso.exe?
---

# LsaIso.exe 

* File Path: `C:\Windows\system32\LsaIso.exe`
* Description: Credential Guard & Key Guard

## Hashes

Type | Hash
-- | --
MD5 | `8B1A7347222A11C41F777A5782F3EEE1`
SHA1 | `5A9E5FFE14352CBEC1A1F70318866FC35756AF72`
SHA256 | `D66ADB00F5EB0C5A08E7D844288D5ACDBB38294830D5370D0B1395171382C87F`
SHA384 | `456AE3F7106ED0387ED7190BCDEFC543E3F80A7189EAAFBD73517C1A9481EA2CB77ACA465E8F6D14710BA22069EEE75B`
SHA512 | `FF7FA268D4291A4F1E14D4884AE8297D190B1FC20F8754CEE009B67595EB9FE3312B3F5528898DD4B0C82B2CB44D4FBA09FF8527BE58CDE7BFBE82056EA3CA41`
SSDEEP | `6144:2dVV1+DhcBM2IvUqNvlTjw3PVscKS6ItXh:jd1XNv89jR`
IMP | `4DE439CBF6EAF63C94456970B7FE7CEB`
PESHA1 | `0FE8742A12036E40E9FB141A9ED8267EA615B24D`
PE256 | `45166C7960B4415D00E3EC125BD6DCB09EE981159DA54C25B799838374DEC0BA`

## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: LsaIso.exe
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.17763.1192 (WinBuild.160101.0800)
* Product Version: 10.0.17763.1192
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/68
* VirusTotal Link: https://www.virustotal.com/gui/file/d66adb00f5eb0c5a08e7d844288d5acdbb38294830d5370d0b1395171382c87f/detection/


## Possible Misuse

*The following table contains possible examples of `LsaIso.exe` being misused. While `LsaIso.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_proc_wrong_parent.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_proc_wrong_parent.yml) | `- '*\lsaiso.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020 Strontic.


