---
title: WmiApRpl.dll | WMI Performance Reverse Adapter
excerpt: What is WmiApRpl.dll?
---

# WmiApRpl.dll 

* File Path: `C:\Windows\system32\wbem\WmiApRpl.dll`
* Description: WMI Performance Reverse Adapter

## Hashes

Type | Hash
-- | --
MD5 | `9494286BEAD4A0A3282B74DAC24745EC`
SHA1 | `E55ABD90557482C2FA342FF94D1C7FBDA71AE5FC`
SHA256 | `B4C8927C2E7C8DD89470C3601B66C38D1EF6C91AA5C56DDBFF6322D22278A9A9`
SHA384 | `03FC430CE53098FA3C35B75066DD237A706B828B190147F0E51AD4898CC9CD3F982BC2318161A296CD10E7ACE3753FB7`
SHA512 | `DE6846F6558B2F1EB0B49D75E1963820A9119172175D74FCCE326CA0646FFECAB41FA7C2567CF251A53A64396B3D736083B50724CD03A2C60F4A5CE0B470EAFB`
SSDEEP | `3072:Qdvd0xWhbJjUf7wblHiPzdDhRb2h+nlSc41qoOLZ:GCxWVJji7ydi5DhlYvc6qoO`
IMP | `9286D05217B25BA1E569B0CCF50102E5`
PESHA1 | `532FDEFA18B008AB19FE0F173D522ED39102679C`
PE256 | `721C9E1C60C01B22315BD5AB8036D09DD2FC3ADCE02CB6DD6C71A50A04203946`

## DLL Exports:

Function Name | Ordinal | Type
-- | -- | --
`DllRegisterServer` | 4 | Exported Function
`DllUnregisterServer` | 5 | Exported Function
`WmiClosePerfData` | 1 | Exported Function
`WmiCollectPerfData` | 2 | Exported Function
`WmiOpenPerfData` | 3 | Exported Function


## Signature

* Status: Signature verified.
* Serial: `330000026551AE1BBD005CBFBD000000000265`
* Thumbprint: `E168609353F30FF2373157B4EB8CD519D07A2BFF`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: WMIApRpl.dll.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/65
* VirusTotal Link: https://www.virustotal.com/gui/file/b4c8927c2e7c8dd89470c3601b66c38d1ef6c91aa5c56ddbff6322d22278a9a9/detection/


## Possible Misuse

*The following table contains possible examples of `WmiApRpl.dll` being misused. While `WmiApRpl.dll` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_wmi_module_load.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/image_load/sysmon_wmi_module_load.yml) | `- '\WmiApRpl.dll'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020 Strontic.


