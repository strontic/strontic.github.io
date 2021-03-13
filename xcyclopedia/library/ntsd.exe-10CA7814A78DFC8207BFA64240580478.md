---
title: ntsd.exe | Symbolic Debugger for Windows
excerpt: What is ntsd.exe?
---

# ntsd.exe 

* File Path: `C:\Program Files (x86)\Windows Kits\10\Debuggers\arm64\ntsd.exe`
* Description: Symbolic Debugger for Windows

## Screenshot

![ntsd.exe](screenshots/ntsd.exe-329FBD3549A7D0FB1BF3A250ED8BDFB7-1.png)
![ntsd.exe](screenshots/ntsd.exe-329FBD3549A7D0FB1BF3A250ED8BDFB7-5.png)
![ntsd.exe](screenshots/ntsd.exe-B5BC3A27E60D60EEA47608C3E2B35FD1-5.png)

## Hashes

Type | Hash
-- | --
MD5 | `10CA7814A78DFC8207BFA64240580478`
SHA1 | `0AE0DB47527EEF74AB88C56760F59C6AF0ACE938`
SHA256 | `BB00E51E6E6611E03464E640D31ABB3DED6ED9FEF6C65756B2341B4F39AD9776`
SHA384 | `FCB50398E0BC6FD2BB1981D544445C74E24C4446FE2E0EA157BB74872DC74388AEEEA431CCEA1F4C0BD61C693E2F8362`
SHA512 | `B74B6E3158B88D0BC91C0CE09C34404703FC491C6F56A7D807BEA1D02B29DD749BE48925B59EB7097053669D26FC3E645A506AF766FD2A8B9956F16E463BE4CD`
SSDEEP | `3072:0rVzuP+Sxcu4YSr/31prVX7MJmpATeKT1zxbFgJX:wVzuP+Sxcu4lvy1bFgx`
IMP | `104A4B4F037EE805C8AB64205777A309`
PESHA1 | `16C37D233A6C70C4F6A1A0B06C19225676CCFC79`
PE256 | `892A31A14D0B983EF54F8CB4550CB05A488DC179C300DB2278B9523FB8E28953`

## Signature

* Status: Signature verified.
* Serial: `33000002B7E8E007A82AEF13150000000002B7`
* Thumbprint: `5A68625F1A516670A744F7EF919500A479D32A5B`
* Issuer: CN=Microsoft Code Signing PCA 2010, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows Kits Publisher, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: NTSD.Exe
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit ARM

## File Scan

* VirusTotal Detections: Unknown


## Possible Misuse

*The following table contains possible examples of `ntsd.exe` being misused. While `ntsd.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1546.012.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1546.012/T1546.012.md) | <blockquote>Adversaries may establish persistence and/or elevate privileges by executing malicious content triggered by Image File Execution Options (IFEO) debuggers. IFEOs enable a developer to attach a debugger to an application. When a process is created, a debugger present in an application’s IFEO will be prepended to the application’s name, effectively launching the new process under the debugger (e.g., <code>C:\dbg\ntsd.exe -g  notepad.exe</code>). (Citation: Microsoft Dev Blog IFEO Mar 2010) | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)



MIT License. Copyright (c) 2020-2021 Strontic.


