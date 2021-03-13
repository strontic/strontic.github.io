---
title: makecert.exe | ECM MakeCert
excerpt: What is makecert.exe?
---

# makecert.exe 

* File Path: `C:\Program Files (x86)\Windows Kits\10\bin\10.0.19041.0\x64\makecert.exe`
* Description: ECM MakeCert

## Hashes

Type | Hash
-- | --
MD5 | `B643D954F3731DC049458F9FA235B493`
SHA1 | `C96DE03D7CDE8098649627AA5EA5909FC4D3EE45`
SHA256 | `2A3FCA2FDD446417C877479210E6A3095C2F996669A0DF86C2A865E1EE6E0B51`
SHA384 | `77CEDAA58F1A6B147464144DC5BD11385F4592081D4B8AB56261F57AB1C98E81D31AE0CD32E0603AFD5900A1730BDB0D`
SHA512 | `7326EAD57C72EAE9DB8F368F01FCF20DC47682A03306EADF527A455F0D6AC64D97C7DFCB285F3C215266AA1BB515B149A6A4DE15754545C4B687578534C8A7E5`
SSDEEP | `1536:ZsfdschFlHWPl13B3BOc6qwUEwPvbTJayaarFdq:8XFlHqjOchTESTJayaeq`
IMP | `9F00F41A6B62080B1DEFB3B42F19F265`
PESHA1 | `5440B72B8F5D99EE9EC128C6D96870F47807A07A`
PE256 | `DC05AD13736D569E9013D4543B344A82374C5FE9B8161549945CD913651324FE`

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
C:\Program Files (x86)\Windows Kits\10\bin\10.0.19041.0\x64\makecert.exe |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\SYSTEM32\ntdll.dll |


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
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: Unknown

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Program Files (x86)\Windows Kits\10\bin\10.0.19041.0\arm64\makecert.exe](makecert.exe-1618A3DB4F98DF42A0FC19403B9088FA.md) | 41
[C:\Program Files (x86)\Windows Kits\10\bin\10.0.19041.0\x86\makecert.exe](makecert.exe-EDF551E8A4C3CFD532EF07D82D1AE585.md) | 36




MIT License. Copyright (c) 2020-2021 Strontic.


