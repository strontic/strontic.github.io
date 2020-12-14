---
title: wbemdisp.dll | WMI Scripting
excerpt: What is wbemdisp.dll?
---

# wbemdisp.dll 

* File Path: `C:\Windows\system32\wbem\wbemdisp.dll`
* Description: WMI Scripting

## Hashes

Type | Hash
-- | --
MD5 | `756DF8BEAF018E982E2383702D905729`
SHA1 | `52D825876F257692538BF9950C07D7F38786A60A`
SHA256 | `59F90D11BD50CAD4617151BAEA43BCF878CADC5FB0DA5D07F461B2C2657B9EE1`
SHA384 | `6BB0C536F145F36353856E90A95883E47CD494F6B9F23138B7E773EE17211BBC08FE9A5D37E3BF83A787DD4A672B365C`
SHA512 | `1CE48DFCDFEDD8FF5E9972854C8AC44E20087B73C0571197358AA173F6BE0B88418693C03B5D88FE6E7F47271B1B16788089612D539BA73F92470EC99EC98D1A`
SSDEEP | `6144:437AlCACCnkxsq3XpxObD7brwguhVgbvhZ4dGN1k:8TsqnpxO73PvPr`
IMP | `2D4030DF9BFE15ED583A3C0A5F1B63E7`
PESHA1 | `9E1DEE34D92221BFAE2A037DF5C19F353A97D088`
PE256 | `F6B9F7BE6919BBF304FBED7FFD511131C6578ED48A145BC1B3EDCEF929102877`

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

* Original Filename: WBEMDISP.DLL
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/68
* VirusTotal Link: https://www.virustotal.com/gui/file/59f90d11bd50cad4617151baea43bcf878cadc5fb0da5d07f461b2c2657b9ee1/detection/


## Possible Misuse

*The following table contains possible examples of `wbemdisp.dll` being misused. While `wbemdisp.dll` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_susp_winword_wmidll_load.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/image_load/sysmon_susp_winword_wmidll_load.yml) | `- '*\wbemdisp.dll'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020 Strontic.


