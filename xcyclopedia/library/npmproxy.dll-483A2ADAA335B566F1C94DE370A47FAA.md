---
title: npmproxy.dll | Network List Manager Proxy
excerpt: What is npmproxy.dll?
---

# npmproxy.dll 

* File Path: `C:\Windows\SysWOW64\npmproxy.dll`
* Description: Network List Manager Proxy

## Hashes

Type | Hash
-- | --
MD5 | `483A2ADAA335B566F1C94DE370A47FAA`
SHA1 | `65CA865F092D0354191B25308B0369B78BF989E4`
SHA256 | `B7FABD4735521D38A023B26545833D00D6CE571AEDF818870AAB5773FD296A4C`
SHA384 | `329F10CA1FC02D0B20E21823844A19022AE737EC074510DA5B10D30596551509D0F3E741185744222F8C5408D8A6FE74`
SHA512 | `3396F5736F23E19E9F8F120672FDA24FE2D5EDE19FE0090CE7F679EEA54801ACE4A4B9D54D4D034BAE2F232D3804CA19A97264C9BF0277A649099A95462CAC6D`
SSDEEP | `384:veK0O9W7lA6JwugTuqJIZjmPCrB6rlcaWNNWSuj:veXO9GAEwNiquPMBchvO`
IMP | `E003A5FFE01E4F1EA100CA35120D34B8`
PESHA1 | `FB88D884DDA5C634D6E8C83D040E0984743D3328`
PE256 | `60F1275909F72ED6D3DCD0A0B87F1AE73D1313D98035DFDE2EA8FA6896402FC0`

## DLL Exports:

Function Name | Ordinal | Type | Address | Relative Address
-- | -- | -- | -- | --
`DllCanUnloadNow` | 1 (0x1) | Exported Function | 0x10004000 | 0x00004000
`DllGetClassObject` | 2 (0x2) | Exported Function | 0x10003fc0 | 0x00003fc0
`DllRegisterServer` | 3 (0x3) | Exported Function | 0x10005060 | 0x00005060
`DllUnregisterServer` | 4 (0x4) | Exported Function | 0x10005090 | 0x00005090
`GetProxyDllInfo` | 5 (0x5) | Exported Function | 0x100050c0 | 0x000050c0


## Signature

* Status: Signature verified.
* Serial: `330000026551AE1BBD005CBFBD000000000265`
* Thumbprint: `E168609353F30FF2373157B4EB8CD519D07A2BFF`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: npfproxy.dll
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.117 (WinBuild.160101.0800)
* Product Version: 10.0.19041.117
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/71
* VirusTotal Link: https://www.virustotal.com/gui/file/b7fabd4735521d38a023b26545833d00d6ce571aedf818870aab5773fd296a4c/detection/


## Possible Misuse

*The following table contains possible examples of `npmproxy.dll` being misused. While `npmproxy.dll` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_sofacy.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_sofacy.yar) | $s1 = "w%SystemRoot%\\System32\\npmproxy.dll" fullword wide | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)



MIT License. Copyright (c) 2020 Strontic.


