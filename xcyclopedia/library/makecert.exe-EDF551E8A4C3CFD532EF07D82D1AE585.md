---
title: makecert.exe | ECM MakeCert
excerpt: What is makecert.exe?
---

# makecert.exe 

* File Path: `C:\Program Files (x86)\Windows Kits\10\bin\10.0.19041.0\x86\makecert.exe`
* Description: ECM MakeCert

## Hashes

Type | Hash
-- | --
MD5 | `EDF551E8A4C3CFD532EF07D82D1AE585`
SHA1 | `80BD88B98EAF8A812202F2DDB4CBFF2ACA49AF38`
SHA256 | `808E43AC6BF1A5C21C6DD3CBDCF32B8C9CAAE2C078D57080CD11BF564ED16242`
SHA384 | `FECEDD480548E06AB8816675CED121FF1FFA84D432B056D9ED87902C987534F5CDFDAA0FD050BE2DCDDE36FB35F905D3`
SHA512 | `EB8D252B0ACAE2B932F242E813884D16B2572C4F6A1DAACE49963CAC24AC67BB14704C90FA05E7CF47BD4037F6E080CEC728A16028CB5308B2A31773F40FF97D`
SSDEEP | `768:ZQIAghcfXUQaWHze4FIvh1DxkKpQYGLTJayaarFdTeORUXMdZQ:ZQkhUzTRehZx78LTJayaarFdCOlQ`
IMP | `2D1E4981855D954BA7C83771BDED9BC2`
PESHA1 | `039C0E93F760D5B7691C725B31B2980CCF9EACD0`
PE256 | `4453AC55F7B33F653A84D37EB03CEB5AC6775FD55BDDE44AE187FFB4DC2F93DA`

## Runtime Data

### Usage (stdout):
```cmhg
Usage: MakeCert [ basic|extended options] [outputCertificateFile]
Basic Options
 -sk  <keyName>      Subject's key container name; To be created if not present
 -pe                 Mark generated private key as exportable
 -ss  <store>        Subject's certificate store name that stores the output 
                     certificate
 -sr  <location>     Subject's certificate store location.
                        <CurrentUser|LocalMachine>.  Default to 'CurrentUser'
 -#   <number>       Serial Number from 1 to 2^31-1.  Default to be unique
 -$   <authority>    The signing authority of the certificate
                        <individual|commercial>
 -n   <X509name>     Certificate subject X500 name (eg: CN=Fred Dews)
 -?                  Return a list of basic options
 -!                  Return a list of extended options

```

### Loaded Modules:

Path |
-- |
C:\Program Files (x86)\Windows Kits\10\bin\10.0.19041.0\x86\makecert.exe |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\wow64.dll |
C:\Windows\System32\wow64cpu.dll |
C:\Windows\System32\wow64win.dll |


## Signature

* Status: Signature verified.
* Serial: `33000002CF6D2CC57CAA65A6D80000000002CF`
* Thumbprint: `1A221B3B4FEF088B17BA6704FD088DF192D9E0EF`
* Issuer: CN=Microsoft Code Signing PCA 2010, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Corporation, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: MAKECERT.EXE
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/76
* VirusTotal Link: https://www.virustotal.com/gui/file/808e43ac6bf1a5c21c6dd3cbdcf32b8c9caae2c078d57080cd11bf564ed16242/detection

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Program Files (x86)\Windows Kits\10\bin\10.0.19041.0\arm64\makecert.exe](makecert.exe-1618A3DB4F98DF42A0FC19403B9088FA.md) | 43
[C:\Program Files (x86)\Windows Kits\10\bin\10.0.19041.0\x64\makecert.exe](makecert.exe-B643D954F3731DC049458F9FA235B493.md) | 36




MIT License. Copyright (c) 2020 Strontic.


