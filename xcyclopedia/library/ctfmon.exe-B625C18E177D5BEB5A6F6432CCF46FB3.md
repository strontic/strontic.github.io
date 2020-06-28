---
title: ctfmon.exe | CTF Loader
---

# ctfmon.exe 

* File Path: `C:\Windows\system32\ctfmon.exe`
* Description: CTF Loader
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `B625C18E177D5BEB5A6F6432CCF46FB3`
SHA1 | `ABB864E1911C59F785B0E1822701B9A5AB31BA1E`
SHA256 | `484FED5F039F429ED933931BA607B7EFDA7D1A343D79CFAB60910E1843147012`
SHA384 | `837300F82D6F1419643D369B7350C16D08BA4768D3875DA3D6BA3970C6A43DB01F9F18F70E20B7191454DF352D9D15C9`
SHA512 | `D908BBDC26504B7BF6527C6F436D1BA0EDFD9D2D09981ECE411551BB3C5E1CFD046675A09A98438C5C59A2A4D9BA689FB0F1DD017190DF6705EA088F11CC0C7F`
SSDEEP | `96:09AOfIKFb3nPWsv+5g3U2QD6S1EswBm5R00hTTpTq6mmyJfLODJVpRKLsLEWhgWq:AX3DPWsD7DS1EswEnp5q6mmy1CMWhgW`

## Runtime Data

### Usage (stdout):
```Batchfile

```

### Usage (stderr):
```Batchfile

```

### Child Processes:


## Signature

* Status: Signature verified.
* Serial: `330000023241FB59996DCC4DFF000000000232`
* Thumbprint: `FF82BC38E1DA5E596DF374C53E3617F7EDA36B06`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: CTFMON.EXE.MUI
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.


## Possible Misuse

*The following table contains possible examples of `ctfmon.exe` being misused. While `ctfmon.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[malware-ioc](https://github.com/eset/malware-ioc) | [amavaldo](https://github.com/eset/malware-ioc/blob/master/amavaldo/README.adoc) | `\| `6C04499F7406E270B590374EF813C4012530273E` \| ctfmon.exe       \| Abused legitimate application \| Clean file                             \|` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)



MIT License. Copyright (c) 2020 Strontic.


