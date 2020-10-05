---
title: libiconv.dll | 
excerpt: What is libiconv.dll?
---

# libiconv.dll 

* File Path: `C:\Program Files\Wireshark\libiconv.dll`

## Hashes

Type | Hash
-- | --
MD5 | `0B3611DDB2375D79907E504D32042367`
SHA1 | `2C0E5AC74EE930434606DC73CDE07FC73A8C788B`
SHA256 | `DD294A1DB8568E9B7592157E8A66399588E9510C4E20D3305EE8EC46A0582170`
SHA384 | `237C147329004501E94716511C8CB667DC7FE58039E669E18FDBA31D5BC71FB65DDD337988E964D18F7461347F1690C1`
SHA512 | `BF14CA0D8AB2CCD5589A4037A559B8932F12FCC0E135089AC786F6FC5DE4D1DC82E2923BFF3FE40A1EEC5CD8ECD3A6F29377D66C594755451CCCBA626C97F77D`
SSDEEP | `24576:K7/XfxLfylEru8Gavkg3Nys3bbTqLGBAUZLYJA:undwEru8GaXrGLGBAUZLYC`
IMP | `E354DADC97E03CD7A5A2AAD26BB923BB`
PESHA1 | `CD59D4DF95B2F46CEC6607F17D2524A11C4682F0`
PE256 | `24969DDCE5DBBEEA178878A3E72E81362ACB9B14AEAF0F5317F545CF2630ECB7`

## DLL Exports:

Function Name | Ordinal | Type
-- | -- | --
`libiconv_open_into` | 6 | Exported Function
`libiconv_open` | 5 | Exported Function
`libiconvlist` | 8 | Exported Function
`libiconvctl` | 7 | Exported Function
`iconv_canonicalize` | 2 | Exported Function
`_libiconv_version` | 1 | Exported Function
`libiconv_close` | 4 | Exported Function
`libiconv` | 3 | Exported Function


## Signature

* Status: Signature verified.
* Serial: `02CCD99F7D556C13CE8710C69D09B31A`
* Thumbprint: `E8EF7325044D018B0C0DCD8CBA4190B155857F3B`
* Issuer: CN=Sectigo RSA Code Signing CA, O=Sectigo Limited, L=Salford, S=Greater Manchester, C=GB
* Subject: CN="Wireshark Foundation, Inc.", O="Wireshark Foundation, Inc.", STREET=711 4th street, L=Davis, S=CA, PostalCode=95616, C=US

## File Metadata

* Original Filename: 
* Product Name: 
* Company Name: 
* File Version: 
* Product Version: 
* Language: 
* Legal Copyright: 
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/67
* VirusTotal Link: https://www.virustotal.com/gui/file/dd294a1db8568e9b7592157e8a66399588e9510c4e20d3305ee8ec46a0582170/detection/

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Users\user\AppData\Local\GitHubDesktop\app-2.5.3\resources\app\git\usr\bin\sh.exe](sh.exe-CD721CF3000FE9CFD4E072AF57C8FD4B.md) | 27
[C:\Users\user\AppData\Local\GitHubDesktop\app-2.5.4\resources\app\git\usr\bin\sh.exe](sh.exe-0049E1D78AFDE220B5931F1969EBAD94.md) | 30

## Possible Misuse

*The following table contains possible examples of `libiconv.dll` being misused. While `libiconv.dll` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[malware-ioc](https://github.com/eset/malware-ioc) | [windigo_signatures.pl](https://github.com/eset/malware-ioc/blob/master/sshdoor/windigo_signatures.pl) | `'/usr/lib/libiconv.so.0'             => 0,` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)



MIT License. Copyright (c) 2020 Strontic.


