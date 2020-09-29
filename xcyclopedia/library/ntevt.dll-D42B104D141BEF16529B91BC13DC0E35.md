---
title: ntevt.dll | WMI Event Log Provider
excerpt: What is ntevt.dll?
---

# ntevt.dll 

* File Path: `C:\Windows\system32\wbem\ntevt.dll`
* Description: WMI Event Log Provider

## Hashes

Type | Hash
-- | --
MD5 | `D42B104D141BEF16529B91BC13DC0E35`
SHA1 | `DFA442A6989360FC02CC01C07A0B524581D78C6B`
SHA256 | `27C3D1287C45EA8B8D75FEE2DDFCF585A860196BBE64F8EABC318AEB077BBB4B`
SHA384 | `83BB4B5A672D092C3D3D2A01E1250058F747D5164CD574306C3ADBAB3F83445885FB1A5237DF1D42436257C3DA888EC3`
SHA512 | `CE8C32C40271456E3C6B11FD7821D42992B834C970418A1FE8419B04A5A0EDBC07D0DFB1B06F0ED6F639490366A0C322C18CD15EC3CA6FC6E8E655E6FA9588EB`
SSDEEP | `6144:eX6zAPLrtZlAjGLXMXUpoEjnf6S0TGSsWs:eRLrLlAjGLXDd/0Txs`
IMP | `AE36C552799CAB0581B54BF6A865189D`
PESHA1 | `26D187E6B9DB727FCC6BBE54050CD8FAF95AF7DE`
PE256 | `9446288135E61B2CB53E453456E1F857FC70901BDE5CBEA4F0B83DAB8910971D`

## DLL Exports:

Function Name | Ordinal | Type | Address | Relative Address
-- | -- | -- | -- | --
`DllCanUnloadNow` | 1 (0x1) | Exported Function | 0x00000001800088c0 | 0x000088c0
`DllGetClassObject` | 2 (0x2) | Exported Function | 0x00000001800062d0 | 0x000062d0
`DllRegisterServer` | 3 (0x3) | Exported Function | 0x00000001800105b0 | 0x000105b0
`DllUnregisterServer` | 4 (0x4) | Exported Function | 0x00000001800115b0 | 0x000115b0


## Signature

* Status: Signature verified.
* Serial: `330000026551AE1BBD005CBFBD000000000265`
* Thumbprint: `E168609353F30FF2373157B4EB8CD519D07A2BFF`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: ntevt.dll.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/71
* VirusTotal Link: https://www.virustotal.com/gui/file/27c3d1287c45ea8b8d75fee2ddfcf585a860196bbe64f8eabc318aeb077bbb4b/detection/


## Possible Misuse

*The following table contains possible examples of `ntevt.dll` being misused. While `ntevt.dll` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_eqgrp.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_eqgrp.yar) | description = "EquationGroup Malware - file ntevt.sys" | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_eqgrp.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_eqgrp.yar) | $s1 = "ntevt.sys" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_eqgrp.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_eqgrp.yar) | $s2 = "c:\\ntevt.pdb" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_eqgrp_apr17.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_eqgrp_apr17.yar) | $x1 = "c:\\ntevt.pdb" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)



MIT License. Copyright (c) 2020 Strontic.


