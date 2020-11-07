---
title: FXSST.dll | Fax Service
excerpt: What is FXSST.dll?
---

# FXSST.dll 

* File Path: `C:\Windows\system32\FXSST.dll`
* Description: Fax Service

## Hashes

Type | Hash
-- | --
MD5 | `805DA5DFA15387C0528B441B9EE8C4E4`
SHA1 | `219CC30C4E10F1C3F215C16978F9F53306D73165`
SHA256 | `3846C1E801053F36EB6FCD99E424A50D4145535276BEFA11ACA78CB4A94FEA87`
SHA384 | `CD4B70B3EA95CD3BE25899888FE5DD3A02417D6DAE4BD996EEB90A0DF12B8F920F94005733A6F628764B859D6E4EB502`
SHA512 | `7E0E266F65510BD9FC9CC82A2CBCB1E8D102FD2D01F92A97FD964A962FC2E361EE4C8CF6E25641172C73DD72F91587E3F5C3865941DC792C6725A50A5E87326C`
SSDEEP | `6144:QPCv0cvK/pXbjcSbcY+CaQdaFOY4iGFYtRdzzoyYxJA:QaE/dbz+xt4vFeF`
IMP | `15B248A0580B24BD54BF1CFDEE59C572`
PESHA1 | `64E3333358864CE9F57536C513A856FB4AD61673`
PE256 | `F9E0ADA55D37B2F387C2C47CAED1D058EC29C73CED3D6348026434E027C66AFF`

## DLL Exports:

Function Name | Ordinal | Type
-- | -- | --
`DllMain` | 1 | Exported Function
`FaxMonitorShutdown` | 2 | Exported Function
`FaxMonitorStartup` | 3 | Exported Function
`IsFaxMessage` | 4 | Exported Function


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: FXSST.DLL
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/70
* VirusTotal Link: https://www.virustotal.com/gui/file/3846c1e801053f36eb6fcd99e424a50d4145535276befa11aca78cb4a94fea87/detection/

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Windows\system32\WFS.exe](WFS.exe-7C1E8C5382FF4F55BF242B0377DA3EC5.md) | 25
[C:\WINDOWS\system32\WFS.exe](WFS.exe-7D05DBCCB67C329AD2F2E5FCAEE84260.md) | 32
[C:\Windows\system32\WFS.exe](WFS.exe-8E8507B0C0C16F1698A24BFD038EA54D.md) | 30
[C:\Windows\system32\WFS.exe](WFS.exe-EECE3DAFAF89C27DE21E23F1D9A27B55.md) | 25
[C:\Windows\system32\WFSR.dll](WFSR.dll-2917EDF18AB86F81951DE976B6B98AC7.md) | 49

## Possible Misuse

*The following table contains possible examples of `FXSST.dll` being misused. While `FXSST.dll` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_apt17_malware.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_apt17_malware.yar) | description = "Detects Samples related to APT17 activity - file FXSST.DLL" | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_apt17_malware.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_apt17_malware.yar) | $x2 = "fxsst.dll" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)



MIT License. Copyright (c) 2020 Strontic.


