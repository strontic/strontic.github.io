---
title: backgroundTaskHost.exe | Background Task Host
---

# backgroundTaskHost.exe 

* File Path: `C:\Windows\SysWOW64\backgroundTaskHost.exe`
* Description: Background Task Host

## Hashes

Type | Hash
-- | --
MD5 | `C05E66B02405E6C3C5508F95AEEFFB0E`
SHA1 | `952CD05DD7790CB037B24EAE401266E0FACDCDEF`
SHA256 | `655D6B2ADCFB5F1CABD60607616D234F8C0D89682D8357A2475467E90C778613`
SHA384 | `8831D6BDEC7E1CF9E5C999411C0E6C9A2A1252D630C366C4F7A733BF61858E81A6C8933F648E0296AFBD4FFF82D096D3`
SHA512 | `15ACA7B95F6A6B825BC6B8B3B2EE3CF9094BAF3011213FD3CCACC79DA98443A869AD74B53160873FF981C53FB0083F7E3088AFF4B32D29D327E904AB739BAE50`
SSDEEP | `192:Y/tRaHXbq0eTY1iSji1to2Ac1XQOIHhW2eGWBxloIlWt8RDBQABJnqnajltsLh01:LXbqFY13soHOIBWhGWNoIlRDBRJnlghs`

### Loaded Modules:

Path |
-- |
C:\Windows\system32\backgroundTaskHost.exe |
C:\Windows\System32\combase.dll |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\System32\msvcrt.dll |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\RPCRT4.dll |
C:\Windows\System32\ucrtbase.dll |


## Signature

* Status: Signature verified.
* Serial: `33000000BCE120FDD27CC8EE930000000000BC`
* Thumbprint: `E85459B23C232DB3CB94C7A56D47678F58E8E51E`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: backgroundTaskHost.exe
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.14393.0 (rs1_release.160715-1616)
* Product Version: 10.0.14393.0
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.


## Possible Misuse

*The following table contains possible examples of `backgroundTaskHost.exe` being misused. While `backgroundTaskHost.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_abusing_azure_browser_sso.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/sysmon/sysmon_abusing_azure_browser_sso.yml) | `         - BackgroundTaskHost.exe` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020 Strontic.


