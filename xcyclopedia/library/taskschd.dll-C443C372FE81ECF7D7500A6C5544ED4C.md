---
title: taskschd.dll | Task Scheduler COM API
excerpt: What is taskschd.dll?
---

# taskschd.dll 

* File Path: `C:\Windows\SysWOW64\taskschd.dll`
* Description: Task Scheduler COM API

## Hashes

Type | Hash
-- | --
MD5 | `C443C372FE81ECF7D7500A6C5544ED4C`
SHA1 | `5D01808F5CD280DF35207628D4DE55EC24858519`
SHA256 | `A0C8DB818EB745D9BF684A21DA6AFFEF134FDA83914AA9E2D30876EE11F850B2`
SHA384 | `93AB74598DDB0F3FA5372B0C58BF5372B46399AB67B87FCFCF536D3686835CCE2871F0F62AB640E622EF7D95E0AF1D94`
SHA512 | `928B6D2799510CA8C8F2589CB8FC91A5D635AAE1EB06E61914EF9694A45D7824DFE8274DF006E889DA950A1BA9274395E9C02AED2F9BF5812025BF0DD98B8792`
SSDEEP | `6144:7vRCBwkOa/DNSHnVpdS7ZUtquzo1WxTowTjK0N0w3VDVrTX/onLJwLNMOv/Z:7voev0gH3dS7Souzbowq03dXOCx`
IMP | `40B780ACDA4573D699DA823B85748B9F`
PESHA1 | `969BA5D51F0539C29CD244906606A5373E301E4F`
PE256 | `1192392F9B66E3D8EB00AB8446D19D905326CE7BEF4E38C05D79FE581E7B5061`

## DLL Exports:

Function Name | Ordinal | Type
-- | -- | --
`DllRegisterServer` | 3 | Exported Function
`DllUnregisterServer` | 4 | Exported Function
`DllCanUnloadNow` | 1 | Exported Function
`DllGetClassObject` | 2 | Exported Function


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: taskschd.dll.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/68
* VirusTotal Link: https://www.virustotal.com/gui/file/a0c8db818eb745d9bf684a21da6affef134fda83914aa9e2d30876ee11f850b2/detection/


## Possible Misuse

*The following table contains possible examples of `taskschd.dll` being misused. While `taskschd.dll` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_cn_reddelta.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_cn_reddelta.yar) | $s1 = "Taskschd.dll" ascii fullword | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)



MIT License. Copyright (c) 2020 Strontic.


