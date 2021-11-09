---
title: TCPSVCS.EXE | TCP/IP Services Application
excerpt: What is TCPSVCS.EXE?
---

# TCPSVCS.EXE 

* File Path: `C:\WINDOWS\SysWOW64\TCPSVCS.EXE`
* Description: TCP/IP Services Application

## Hashes

Type | Hash
-- | --
MD5 | `C1CC1783129334CEEB503102D7493FEA`
SHA1 | `0C4301A6F4E4095E191E83C773692DA3E4583BEA`
SHA256 | `55E71C60F11F319107E6677DE60611FFBC992DC0C8A136C28DF77A318539F2D1`
SHA384 | `3BBFD9AFB41A076B7B04E145E1F68D2F11E298B0A601E0D1329BAFEDD7F9903F6219944CA7C4925F03002BFC44170810`
SHA512 | `22B11B8A1C54D5416EE738FBCD2CED916BDB154AF1837B016EC9371F5191357DD4F072A8025FDE7C407A4E472C047910EF2A6E62EBE5415200268D6FEEE3DD3F`
SSDEEP | `192:DB6F0o+HRlb/lnGFPYgSbduCfL6//1vK8W9/WHT0:oF0oER1/lnG3SJB6//Q8W9/WH`
IMP | `7EC53FBE050A90703B67A98FCB8BCFCC`
PESHA1 | `36F273EF31C06A4A52D3D505F4887AAFCAEF5015`
PE256 | `9F55D2934EA651F1ACBF9C888DBC2CA9B396153233253AA31DFCDDEDAEB54845`

## Runtime Data

### Loaded Modules:

Path |
-- |
C:\WINDOWS\SYSTEM32\ntdll.dll |
C:\WINDOWS\System32\wow64.dll |
C:\WINDOWS\System32\wow64base.dll |
C:\WINDOWS\System32\wow64con.dll |
C:\WINDOWS\System32\wow64cpu.dll |
C:\WINDOWS\System32\wow64win.dll |
C:\WINDOWS\SysWOW64\TCPSVCS.EXE |


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
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/73
* VirusTotal Link: https://www.virustotal.com/gui/file/55e71c60f11f319107e6677de60611ffbc992dc0c8a136c28df77a318539f2d1/detection

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Windows\SysWOW64\TCPSVCS.EXE](TCPSVCS.EXE-73905DB831B4F37F0673D2DD5BBF7779.md) | 44
[C:\WINDOWS\SysWOW64\TCPSVCS.EXE](TCPSVCS.EXE-8734D9D66C1EC67332CCA130C5A393F6.md) | 43

## Possible Misuse

*The following table contains possible examples of `TCPSVCS.EXE` being misused. While `TCPSVCS.EXE` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[signature-base](https://github.com/Neo23x0/signature-base) | [thor-hacktools.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/thor-hacktools.yar) | $s2 = "tcpsvcs.exe" fullword wide | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)



MIT License. Copyright (c) 2020-2021 Strontic.


