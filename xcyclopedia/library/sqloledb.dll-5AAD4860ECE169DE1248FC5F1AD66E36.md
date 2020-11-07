---
title: sqloledb.dll | OLE DB Provider for SQL Server
excerpt: What is sqloledb.dll?
---

# sqloledb.dll 

* File Path: `C:\Program Files (x86)\Common Files\System\Ole DB\sqloledb.dll`
* Description: OLE DB Provider for SQL Server

## Hashes

Type | Hash
-- | --
MD5 | `5AAD4860ECE169DE1248FC5F1AD66E36`
SHA1 | `0A437225228DF3A32881A286C16B1087189F391A`
SHA256 | `37F1F05D5BDEAC4298833D7D2E04C87D84E23FFA56806AF5CB4C49714F989BE7`
SHA384 | `3BB9A94566121BAD12C755371BB135D3AE959C1F3326B9A37D15C6102AB60F195BB479B5B250E67F557162415FD3F161`
SHA512 | `5C8A0B58CC0C1DBA70A1312A150E16B10EA2E45D0B434B73472139F64D8226E232C8D483DB8BC2353F38D8F2E0E6A479A9F8ACAADCAF6FF63F43F942EB1D9897`
SSDEEP | `12288:Nqo59nBHBAIi20O9B8m5oXl692OvWnuBHd4HYy1Nu:AoHkIiU9BHoXI92qWnu3biNu`
IMP | `C22D12BE4A0F91B5212F1DC83812FC2F`
PESHA1 | `3460EBF4928BE6EB1E98B292DBEE35561629E923`
PE256 | `9D5A57C908ABE2AD3DA059459EEF1C639F64677C1BF2626E4B1FF46B838D5AFD`

## DLL Exports:

Function Name | Ordinal | Type
-- | -- | --
`DllCanUnloadNow` | 14 | Exported Function
`DllGetClassObject` | 15 | Exported Function
`DllMain` | 12 | Exported Function
`DllRegisterServer` | 16 | Exported Function
`DllUnregisterServer` | 17 | Exported Function
`SQLDebug` | 13 | Exported Function


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: sqloledb.dll
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/72
* VirusTotal Link: https://www.virustotal.com/gui/file/37f1f05d5bdeac4298833d7d2e04c87d84e23ffa56806af5cb4c49714f989be7/detection/

## Possible Misuse

*The following table contains possible examples of `sqloledb.dll` being misused. While `sqloledb.dll` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[signature-base](https://github.com/Neo23x0/signature-base) | [thor-hacktools.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/thor-hacktools.yar) | $s14 = "SELECT * FROM OPENROWSET('SQLOLEDB','Trusted_Connection=Yes;Data Source=myserver" ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)



MIT License. Copyright (c) 2020 Strontic.


