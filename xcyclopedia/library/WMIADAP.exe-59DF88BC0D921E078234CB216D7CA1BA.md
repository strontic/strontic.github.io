---
title: WMIADAP.exe | WMI Reverse Performance Adapter Maintenance Utility
excerpt: What is WMIADAP.exe?
---

# WMIADAP.exe 

* File Path: `C:\Windows\system32\wbem\WMIADAP.exe`
* Description: WMI Reverse Performance Adapter Maintenance Utility

## Hashes

Type | Hash
-- | --
MD5 | `59DF88BC0D921E078234CB216D7CA1BA`
SHA1 | `530C1B30493DB6DF5D0F41656C2DD03E591ED3B6`
SHA256 | `82E17F81FEF57BCE805A857C840D96B498C3B8E1394D2B249016B9CEEF05D0E6`
SHA384 | `DBBB33A5BAA74761C4D15510A48E4DA328BE0BDCCB411AD1E172986C2885C5235CA664C74AAAA199F97B16F36A242A08`
SHA512 | `FA630A62CF95BAFA2D3A9CB2F9AFD742F440BF00CA24CB808B746E3474735746147B9AB938ED2005034A22FA5E339F87A4D4B9B6982100DF3FEDC8305FC18285`
SSDEEP | `3072:RGrchxbfGbfOF8oIbdp+q5e2ufvhSRs+oW+/fT6ru:9Lb+b+8bbDqSRs+bAfT6r`
IMP | `367D299428703C9A9715504BFE071C97`
PESHA1 | `23C3BDA968298D2967E5475D09CF9AD3387D4769`
PE256 | `05F00513FD4311CA8951D9410DD1D32402A071D0518422DAFD331762792EE43C`

## Runtime Data

### Loaded Modules:

Path |
-- |
C:\Windows\System32\combase.dll |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\System32\msvcrt.dll |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\ucrtbase.dll |
C:\Windows\system32\wbem\WMIADAP.exe |


## Signature

* Status: Signature verified.
* Serial: `330000026551AE1BBD005CBFBD000000000265`
* Thumbprint: `E168609353F30FF2373157B4EB8CD519D07A2BFF`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: wmicookr.dll
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/66
* VirusTotal Link: https://www.virustotal.com/gui/file/82e17f81fef57bce805a857c840d96b498c3b8e1394d2b249016b9ceef05d0e6/detection/


## Possible Misuse

*The following table contains possible examples of `WMIADAP.exe` being misused. While `WMIADAP.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_wmi_module_load.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/image_load/sysmon_wmi_module_load.yml) | `- '\windows\system32\wbem\WMIADAP.exe'  # https://github.com/SigmaHQ/sigma/issues/1871`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020-2021 Strontic.


