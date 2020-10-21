---
title: SIHClient.exe | SIH Client
excerpt: What is SIHClient.exe?
---

# SIHClient.exe 

* File Path: `C:\Windows\system32\SIHClient.exe`
* Description: SIH Client

## Hashes

Type | Hash
-- | --
MD5 | `01AB9A5EB2137F371CE2E30013599F78`
SHA1 | `F8A6BAF69AD4BC962B4C35DD476C413E1C41EFCE`
SHA256 | `FE7054C47862CA79944FAE4F6892CB75000D4196DC9B739993B052817B89D688`
SHA384 | `B29BAFA5F3B3CBD9A40932229044193C2429297EF5FAB6AD4F521CCAD78F52F4CE89AE11F37F8233FE0DFB78AA36DF55`
SHA512 | `A82AA563A5DAA0FD6CFDD4C310E6DA05FE04D574E96DF4A70F8143A4511C1C8CAC3F9A9B0690B534E2A1661CB868E50F90DF051ED0FC2AD71B6700226AA70D50`
SSDEEP | `6144:DwyRLJHU5DASaLGBHCWm+Of/vlyoJdr4M5aT9Z:DwQJ+IGBin+UltTE8a9Z`
IMP | `6F6CDE46652EF17415C88C40F3A26CEB`
PESHA1 | `4ACE42DE9F59B9F1E1BDFF2AC471069F121DA5EE`
PE256 | `3757680290C6C977F11CDFF1DD72B188403C0B199F1A20577D4FF669A8AC9A72`

## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: sihclient.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.17763.1 (WinBuild.160101.0800)
* Product Version: 10.0.17763.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/71
* VirusTotal Link: https://www.virustotal.com/gui/file/fe7054c47862ca79944fae4f6892cb75000d4196dc9b739993b052817b89d688/detection/


## Possible Misuse

*The following table contains possible examples of `SIHClient.exe` being misused. While `SIHClient.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_wmi_module_load.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/image_load/sysmon_wmi_module_load.yml) | `- '\SIHClient.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020 Strontic.


