---
title: mDNSResponder.exe | Bonjour Service
excerpt: What is mDNSResponder.exe?
---

# mDNSResponder.exe 

* File Path: `C:\Program Files (x86)\Bonjour\mDNSResponder.exe`
* Description: Bonjour Service

## Hashes

Type | Hash
-- | --
MD5 | `5EA9C80F18CBC393EA7D9A2991DED4B5`
SHA1 | `B8917C5AE45D1BA5CA534058F1386FAC92F5DA63`
SHA256 | `7E5EB1CE44FEBE93686174058D51581FA00BDFF0EBB84BD74BC08F6386019253`
SHA384 | `08CF5BFADB2FF3A020BFABCAB1539C07D78A16EC50379AA758F3AB0127A361805306A09909EC734768175D81BBF8983A`
SHA512 | `7FD949B792A40630CA385DD2BC88DB9673F9106975B9F55481E2382F67986DD75B03CDF0FBF59846B513A8DEF0C506AC6561F6BA658775286F11D761B575513A`
SSDEEP | `6144:jM7ikzziBIyqD14tJYfxPWh8U0TdKDDFPrDNRUNkS4/HaXlFHCe9oK28ruyLwoMm:rwzi2D1JfxPWNIEFzDNRkkSDaYaS`
IMP | `87F3680DE715E7D989A5FE0369FAE5CC`
PESHA1 | `EDC3B001DC6F3622666A9C488C6D05A673EB2739`
PE256 | `F27F7073CBC3D912886C889E68088D9916132374E835EE97D6398BC2B74F36C6`

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
C:\Program Files (x86)\Bonjour\mDNSResponder.exe |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\wow64.dll |
C:\Windows\System32\wow64cpu.dll |
C:\Windows\System32\wow64win.dll |


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
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/69
* VirusTotal Link: https://www.virustotal.com/gui/file/7e5eb1ce44febe93686174058d51581fa00bdff0ebb84bd74bc08f6386019253/detection/


## Possible Misuse

*The following table contains possible examples of `mDNSResponder.exe` being misused. While `mDNSResponder.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_suspicious_remote_thread.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/sysmon/sysmon_suspicious_remote_thread.yml) | `- '\mDNSResponder.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020 Strontic.


