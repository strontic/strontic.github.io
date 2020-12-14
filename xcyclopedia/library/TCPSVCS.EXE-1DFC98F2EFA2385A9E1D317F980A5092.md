---
title: TCPSVCS.EXE | TCP/IP Services Application
excerpt: What is TCPSVCS.EXE?
---

# TCPSVCS.EXE 

* File Path: `C:\Windows\system32\TCPSVCS.EXE`
* Description: TCP/IP Services Application

## Hashes

Type | Hash
-- | --
MD5 | `1DFC98F2EFA2385A9E1D317F980A5092`
SHA1 | `D264115BDCFEAF71A5CB31FE9B83641B59499790`
SHA256 | `FC2BC4B2B115BDE5341C2D40E371A4F50FEEE14D19AAD12EAF5FD0A052BEA403`
SHA384 | `694A46915EC6514CFC4606368C17AA3C6E72C428879FB8EA9B8590226F8B8204B2AB25DAA4C61A60C6DC21FA021A321A`
SHA512 | `A3B6FBF4CD048124C844527457298568458E4126EA5846E1767B4B670FF5E9B899B795A12A028C981E867220F545B573D15E875952B93E59876E6F984FB8E88E`
SSDEEP | `192:v/jrdjk/bpQQ6yZf7BZWrY9U+l0o+qpXKXU5Gjbm9SdeL6//1FcwcW+/W:vdIt/lV7XW0l0oh54q9f6//ZcW+/W`
IMP | `5FB43D31195A81197A7053C4A202BCED`
PESHA1 | `558722FE2EF97E21D2165257E872866D6E688074`
PE256 | `4BAFEA25F5BE00131216064D838A4961E10FEA21737E2263827E4A1628B41F3A`

## Runtime Data

### Loaded Modules:

Path |
-- |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\system32\TCPSVCS.EXE |


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: TCPSVCS.EXE
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: A device attached to the system is not functioning.
* VirusTotal Link: n/a


## Possible Misuse

*The following table contains possible examples of `TCPSVCS.EXE` being misused. While `TCPSVCS.EXE` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[signature-base](https://github.com/Neo23x0/signature-base) | [thor-hacktools.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/thor-hacktools.yar) | $s2 = "tcpsvcs.exe" fullword wide | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)



MIT License. Copyright (c) 2020 Strontic.


