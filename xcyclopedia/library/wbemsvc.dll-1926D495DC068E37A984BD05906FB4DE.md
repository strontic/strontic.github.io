---
title: wbemsvc.dll | WMI
excerpt: What is wbemsvc.dll?
---

# wbemsvc.dll 

* File Path: `C:\Windows\system32\wbem\wbemsvc.dll`
* Description: WMI

## Hashes

Type | Hash
-- | --
MD5 | `1926D495DC068E37A984BD05906FB4DE`
SHA1 | `D129ADAA809ADAB440A7AAE016F43DAFF22086EB`
SHA256 | `A3D4B0B36CB9A553FCBCF1ED9FE87489DACD786CF9AC94DCC4AA5043AF61DCA0`
SHA384 | `5A21F852CDEFB5232F28722739E1611B7D3026E89E84C4641973B29E05C0E058F0682E743F321FC3B64C09EAB14B9277`
SHA512 | `862B2D09D6E5A3231CD24B65290E43682AE18E3493DCFA99269380F23344FB52C50A864015B0904288978A337E1C920EFF5F92A7E747D3B393908AF0CA17385E`
SSDEEP | `768:TliuOLCpovSiZv6kZjqegLIIfJmjOY0jN:Tljl+vSkv6kTcIIfsjOYmN`
IMP | `1CF44754B099F8487ECC57BDB08B3B52`
PESHA1 | `BBC2897B72ED5F23C46FCCABE8804053C8A2F56D`
PE256 | `6B09FDD0B4F17A4200297C910701A393ABFA552E7481C3FFB86BBC2ACC0070FF`

## DLL Exports:

Function Name | Ordinal | Type
-- | -- | --
`DllRegisterServer` | 3 | Exported Function
`DllUnregisterServer` | 4 | Exported Function
`DllCanUnloadNow` | 1 | Exported Function
`DllGetClassObject` | 2 | Exported Function


## Signature

* Status: Signature verified.
* Serial: `330000026551AE1BBD005CBFBD000000000265`
* Thumbprint: `E168609353F30FF2373157B4EB8CD519D07A2BFF`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: wbemsvc.dll
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/69
* VirusTotal Link: https://www.virustotal.com/gui/file/a3d4b0b36cb9a553fcbcf1ed9fe87489dacd786cf9ac94dcc4aa5043af61dca0/detection/


## Possible Misuse

*The following table contains possible examples of `wbemsvc.dll` being misused. While `wbemsvc.dll` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_susp_winword_wmidll_load.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/image_load/sysmon_susp_winword_wmidll_load.yml) | `- '*\wbemsvc.dll'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_wmi_module_load.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/image_load/sysmon_wmi_module_load.yml) | `- '\wbemsvc.dll'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020 Strontic.


