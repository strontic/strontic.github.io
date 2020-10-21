---
title: taskschd.dll | Task Scheduler COM API
excerpt: What is taskschd.dll?
---

# taskschd.dll 

* File Path: `C:\Windows\system32\taskschd.dll`
* Description: Task Scheduler COM API

## Hashes

Type | Hash
-- | --
MD5 | `63971DE5EDAE01DAEA665D23F2715FDA`
SHA1 | `58EB9CBDDE570D4F702D9515E97904154ADE563C`
SHA256 | `906BCC87EF1B194133A3CF3D20E6EA5334DA1336A1DBE06AB0F1155010CCE57E`
SHA384 | `268B3522098293D1A58834ABA215F70B867B8A5BA693A1396861DA259A7757F42CC8943C9DD0C82495B216720BBFCFB0`
SHA512 | `5B122E90B958CCBD0AF88AB41E162CD8255B6B82781D84CCA2E96A7D91D431E5E54D01F7F53D8D533097532F767811F2C11A8384385BDE8713148F60230295DF`
SSDEEP | `12288:80kLBRCVkyR+pvVWQNXf335IrEPvukBo2+ptipdvizKSWJ6I6:8DxfHGawi/iuSis`
IMP | `6AE7AB84BE271D954A76D015AA8FF849`
PESHA1 | `1AEF1F061358AB9181AE9A8CD8DDCBA93211E0D8`
PE256 | `CC606609A3B78C400E770EC753F86707CED52875F8B00702BA2460E4FB94B836`

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

* Original Filename: taskschd.dll.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/68
* VirusTotal Link: https://www.virustotal.com/gui/file/906bcc87ef1b194133a3cf3d20e6ea5334da1336a1dbe06ab0f1155010cce57e/detection/


## Possible Misuse

*The following table contains possible examples of `taskschd.dll` being misused. While `taskschd.dll` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_cn_reddelta.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_cn_reddelta.yar) | $s1 = "Taskschd.dll" ascii fullword | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)



MIT License. Copyright (c) 2020 Strontic.


