---
title: wimserv.exe | Wimfltr v2 extractor
excerpt: What is wimserv.exe?
---

# wimserv.exe 

* File Path: `C:\Windows\system32\wimserv.exe`
* Description: Wimfltr v2 extractor

## Hashes

Type | Hash
-- | --
MD5 | `2FE2558908359D6F5486FC8D9FFFDF35`
SHA1 | `C6F5ED4140FF9FCDD637E8D34CCBE6C88C4646D3`
SHA256 | `A1A78BE49FCD562B96AB1994046BE20B0B2FE2DE328E5FDBFB40C17E5A447334`
SHA384 | `C2E2002AB8C969A811F3D08E1AFCD7879BCAEBEE066BD84150EE98536C3BED1964515C8799B6F86D2EBCA4B1C7204623`
SHA512 | `077AE0551D555B7CC091B20E2A80F8F155D8E40408CAFB5035BD8202C888408B48F3F681266495B6D2E7B65F0671F2D315C6DBEBBCFD31ECE8C68693C7E91BA6`
SSDEEP | `12288:DboiZqnHJ29mi+DfW+wdEhN8SqQn8vNwz:LZCHHC+KEhrevNwz`
IMP | `5D3CE5F7734974F8EBB48E7CF80E941A`
PESHA1 | `0C0EECA6910032A216C078DE91E21D2F736C2891`
PE256 | `4B114DEFE04BD798F79B630848F1CDB58DD818DD2A95F3387BD460A89DD31B17`

## Runtime Data

### Loaded Modules:

Path |
-- |
C:\Windows\System32\bcrypt.dll |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\System32\msvcrt.dll |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\RPCRT4.dll |
C:\Windows\system32\wimserv.exe |


## Signature

* Status: Signature verified.
* Serial: `330000026551AE1BBD005CBFBD000000000265`
* Thumbprint: `E168609353F30FF2373157B4EB8CD519D07A2BFF`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: extractr.exe
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.423 (WinBuild.160101.0800)
* Product Version: 10.0.19041.423
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/67
* VirusTotal Link: https://www.virustotal.com/gui/file/a1a78be49fcd562b96ab1994046be20b0b2fe2de328e5fdbfb40c17e5a447334/detection/

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Windows\system32\wimserv.exe](wimserv.exe-88FEB4547F8965A9685CF44B1593CEA3.md) | 94

## Possible Misuse

*The following table contains possible examples of `wimserv.exe` being misused. While `wimserv.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_user_driver_loaded.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/builtin/win_user_driver_loaded.yml) | `- '*\Windows\System32\wimserv.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020 Strontic.


