---
title: stordiag.exe |  
excerpt: What is stordiag.exe?
---

# stordiag.exe 

* File Path: `C:\Windows\system32\stordiag.exe`
* Description:  

## Hashes

Type | Hash
-- | --
MD5 | `09595FAB75F9764D8BB8D77A02602E9B`
SHA1 | `2035188F2858DEC97D9B9CA8587FB2C109425C2F`
SHA256 | `75CBE3CC080A0C681E925E8A7FA20577524E04E0D7E713DD0E73355ED02AF960`
SHA384 | `98F90AFFCF3D4A6FC77AAA8CCBADCCB39DD5A3F13437664F2DD5705255FDB2E41D928067C7AB56E7F49382F38D232C25`
SHA512 | `2D780DA4B52038526737AEC828417E26A77184938F2C3D9EF08160CED4F381E591E5443449CB8DBB1EEF1D5050E86C23FE8728DF162D9CC6D39F21559D3FE34B`
SSDEEP | `384:En4/E+AWVUClB0a9ETJnbMYI1UzscQN0UNUQAzmynEYfP0Kqhihnhacd4SZqxJ4/:En6rUClB19ilbTYcQlxKhs0N+E`

## Runtime Data

### Usage (stdout):
```cmhg

Collects storage and filesystem diagnostic logs and outputs them to a folder.

StorDiag [-collectEtw] [-out <PATH>]
-collectEtw           Collect a 30-second long ETW trace if run from an elevated session
-checkFSConsistency   Checks for the consistency of the NTFS file system
-out <PATH>           Specify the output path. If not specified, logs are saved to %TEMP%\StorDiag



```

### Child Processes:
conhost.exe systeminfo.exe

## Signature

* Status: Signature verified.
* Serial: `33000000BCE120FDD27CC8EE930000000000BC`
* Thumbprint: `E85459B23C232DB3CB94C7A56D47678F58E8E51E`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: stordiag.exe
* Product Name: Microsoft (R) Windows (R) Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.14393.0
* Product Version: 10.0.14393.0
* Language: Language Neutral
* Legal Copyright: Copyright (c) Microsoft Corporation. All rights reserved.






MIT License. Copyright (c) 2020-2021 Strontic.


