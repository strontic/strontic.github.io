---
title: TCPSVCS.EXE | TCP/IP Services Application
excerpt: What is TCPSVCS.EXE?
---

# TCPSVCS.EXE 

* File Path: `C:\WINDOWS\system32\TCPSVCS.EXE`
* Description: TCP/IP Services Application

## Hashes

Type | Hash
-- | --
MD5 | `64E1D313AAC88D04E142F0A501FE1755`
SHA1 | `E2CF96F4CA0B75F668135F230963E3C698560358`
SHA256 | `29B182634136616994C493EADD526F8195BC5BD7DDDCD7BBED28D241128AC5DA`
SHA384 | `0D01710EAF25868C485DA61F0B8846CB480E420DC9DA8A90665AC7949BA02F31728ED9B86265C6F8A19B74199287C347`
SHA512 | `D0FFA09A2F3F934D7BFA3761216F1672B6B2D7C1A2A41BF0FD46BF04D64C60196512947366E9E627AE083F77486FE231E46E4B03FEFFE44310ED7ED2196E7478`
SSDEEP | `192:kXXD5FznLd7O3eaN6QcGtHl0o+kt6Osjt4b4uZ4afL6//1o5w0W9/W:85VnLVQ6Cl0obWGLOm6//+i0W9/W`
IMP | `5FB43D31195A81197A7053C4A202BCED`
PESHA1 | `0097E4A7B9BCC50F4E3193DBC791753D57D577B3`
PE256 | `52A5BC5C9B2ED3E37A04AF195645D0DE630A55A5DBC38AE72A990B0609F62246`

## Runtime Data

### Loaded Modules:

Path |
-- |
C:\WINDOWS\System32\KERNEL32.DLL |
C:\WINDOWS\System32\KERNELBASE.dll |
C:\WINDOWS\SYSTEM32\ntdll.dll |
C:\WINDOWS\system32\TCPSVCS.EXE |


## Signature

* Status: Signature verified.
* Serial: `33000002ED2C45E4C145CF48440000000002ED`
* Thumbprint: `312860D2047EB81F8F58C29FF19ECDB4C634CF6A`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: TCPSVCS.EXE
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.22000.1 (WinBuild.160101.0800)
* Product Version: 10.0.22000.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/71
* VirusTotal Link: https://www.virustotal.com/gui/file/29b182634136616994c493eadd526f8195bc5bd7dddcd7bbed28d241128ac5da/detection


## Possible Misuse

*The following table contains possible examples of `TCPSVCS.EXE` being misused. While `TCPSVCS.EXE` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[signature-base](https://github.com/Neo23x0/signature-base) | [thor-hacktools.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/thor-hacktools.yar) | $s2 = "tcpsvcs.exe" fullword wide | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)



MIT License. Copyright (c) 2020-2021 Strontic.


