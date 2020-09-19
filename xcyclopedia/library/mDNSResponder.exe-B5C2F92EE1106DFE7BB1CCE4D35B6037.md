---
title: mDNSResponder.exe | Bonjour Service
---

# mDNSResponder.exe 

* File Path: `C:\program files\Bonjour\mDNSResponder.exe`
* Description: Bonjour Service

## Hashes

Type | Hash
-- | --
MD5 | `B5C2F92EE1106DFE7BB1CCE4D35B6037`
SHA1 | `31070EF84C5355B082873FFC19FF60659637995F`
SHA256 | `E399C390687589194D8AAD385055F0CFA7D52AD9E837D8FF95008B8EB2B34E50`
SHA384 | `2F45FC6DD1F44374622AEC22387B4ECFB15A5E1EB3FE6E61E53F8EDAF94126D284BAB91AFEBB2833545809B6D63C37AE`
SHA512 | `7F82752B271EE35BAD31A8571AE33B8CC83EF48F41937297DFC446F6F9B12DA3D8B8336A527F6BBC5BC3C6627DEADBD38A5F109B16C7D1386A3DB36742C5A9C7`
SSDEEP | `12288:da04bzdSCiwro3AbN54j49LEMjysQPN5Z:da08ZSCRM3qN54j49LEMjy5`

## Runtime Data

### Usage (stderr):
```cmhg

mDNSResponder 1.0d1

    <no args>    Runs the service normally
    -install     Creates the service and starts it
    -remove      Stops the service and deletes it
    -start       Starts the service dispatcher after processing all other arguments
    -server      Runs the service directly as a server (for debugging)
    -q           Toggles Quiet Mode (no events or output)
    -remote      Allow remote connections
    -cache n     Number of mDNS cache entries (defaults to 512)
    -h[elp]      Display Help/Usage


```

### Loaded Modules:

Path |
-- |
C:\program files\Bonjour\mDNSResponder.exe |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\SYSTEM32\ntdll.dll |


## Signature

* Status: Signature verified.
* Serial: `2B20EB3380792AB011F662C064FDB473`
* Thumbprint: `173A28539CA6DAB5AC8C3B995ABAA692F95C5FC4`
* Issuer: CN=VeriSign Class 3 Code Signing 2010 CA, OU=Terms of use at https://www.verisign.com/rpa (c)10, OU=VeriSign Trust Network, O="VeriSign, Inc.", C=US
* Subject: CN=Apple Inc., OU=Digital ID Class 3 - Microsoft Software Validation v2, O=Apple Inc., L=Cupertino, S=California, C=US

## File Metadata

* Original Filename: mDNSResponder.exe
* Product Name: Bonjour
* Company Name: Apple Inc.
* File Version: 3,1,0,1
* Product Version: 3,1,0,1
* Language: English (United States)
* Legal Copyright: Copyright (c) 2003-2015 Apple Inc.


## Possible Misuse

*The following table contains possible examples of `mDNSResponder.exe` being misused. While `mDNSResponder.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_suspicious_remote_thread.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/sysmon/sysmon_suspicious_remote_thread.yml) | `            - '\mDNSResponder.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020 Strontic.


