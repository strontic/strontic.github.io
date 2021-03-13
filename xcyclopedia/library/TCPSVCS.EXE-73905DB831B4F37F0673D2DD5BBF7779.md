---
title: TCPSVCS.EXE | TCP/IP Services Application
excerpt: What is TCPSVCS.EXE?
---

# TCPSVCS.EXE 

* File Path: `C:\Windows\SysWOW64\TCPSVCS.EXE`
* Description: TCP/IP Services Application

## Hashes

Type | Hash
-- | --
MD5 | `73905DB831B4F37F0673D2DD5BBF7779`
SHA1 | `C3E6486195CD4AC8C163914A2EA230AB797164E6`
SHA256 | `7D6386A5BEBA7635C8FF0B0E24CEC90A409853440650AF583462C36B8E04971D`
SHA384 | `54CCA84DE9CE58466C0E88658E282ECF9A58984F791E6D4AAF103E2B4BEF2C1870D1175992F614031EFC2308C1D41A63`
SHA512 | `EFE2B9F34D962597372162A184DC05518DE973173823D0D87D02180BA8AEA183348A977DFB7B200B7FCB83DC2797EF60489EFC49B3E3AF253003D9F60DC28B33`
SSDEEP | `192:H8mF0o+XFBax64yNmt2b54rCeL6//1vKkW+/WgC:cmF0o4jax64yM294/6//QkW+/Wv`
IMP | `7EC53FBE050A90703B67A98FCB8BCFCC`
PESHA1 | `33B38F9F3E36B3D73FF205D27C2614301082CF94`
PE256 | `FE2D9B65191C5BBAB047DC7D376828E085A1444C5E49DFA95335D0890F74287F`

## Runtime Data

### Loaded Modules:

Path |
-- |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\wow64.dll |
C:\Windows\System32\wow64cpu.dll |
C:\Windows\System32\wow64win.dll |
C:\Windows\SysWOW64\TCPSVCS.EXE |


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
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/74
* VirusTotal Link: https://www.virustotal.com/gui/file/7d6386a5beba7635c8ff0b0e24cec90a409853440650af583462c36b8e04971d/detection

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\WINDOWS\SysWOW64\TCPSVCS.EXE](TCPSVCS.EXE-8734D9D66C1EC67332CCA130C5A393F6.md) | 63

## Possible Misuse

*The following table contains possible examples of `TCPSVCS.EXE` being misused. While `TCPSVCS.EXE` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[signature-base](https://github.com/Neo23x0/signature-base) | [thor-hacktools.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/thor-hacktools.yar) | $s2 = "tcpsvcs.exe" fullword wide | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)



MIT License. Copyright (c) 2020-2021 Strontic.


