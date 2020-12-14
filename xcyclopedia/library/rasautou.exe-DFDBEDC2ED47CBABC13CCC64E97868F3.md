---
title: rasautou.exe | Remote Access Dialer
excerpt: What is rasautou.exe?
---

# rasautou.exe 

* File Path: `C:\Windows\SysWOW64\rasautou.exe`
* Description: Remote Access Dialer

## Hashes

Type | Hash
-- | --
MD5 | `DFDBEDC2ED47CBABC13CCC64E97868F3`
SHA1 | `39972920EC8353749ADB37F185E691FD09AB6FDC`
SHA256 | `51B2F4F5B5CFB55143113B3071BB62FECD4015BAAB59315CFFF5EA8BE4A4B3B4`
SHA384 | `2CC7DD3E248CB18B9E8657BA584B0E8A124A51BEC2F84CC576C209EB8AC0A4045CB5038A93F002BD40676F375A2DABE6`
SHA512 | `8063B28D6DF6CA9C58783E2CF65763140954371D1B6155398992DA5F7C44EC0033727BF80C28DFA2C539A7D3B3B8C40EBCF5A42C9F56F61DEFD017EEFE23F08D`
SSDEEP | `192:bqNL4VbTTSWOqEpitQ3xFey4zNq3jzoGoDY0FZOGZPWGTp+p43KWHBWn0:uNLfqElBFDPzoGGZOGZuct3KWHBW`
IMP | `6FD6CB5E209EBD24A870B74D8EE7F599`
PESHA1 | `8170E7F325AF70ED3C7BD16BAE6B46563FCEB0B7`
PE256 | `3F4185EC0A074D00CF8C0AA70E75F783D48407E9E59F66327ED100C56A5281EC`

## Runtime Data

### Usage (stdout):
```cmhg
Usage: rasautou [-f phonebook] [-a address] [-e entry] [-s]

```

### Loaded Modules:

Path |
-- |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\wow64.dll |
C:\Windows\System32\wow64cpu.dll |
C:\Windows\System32\wow64win.dll |
C:\Windows\SysWOW64\rasautou.exe |


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: rasdlui.exe
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.546 (WinBuild.160101.0800)
* Product Version: 10.0.19041.546
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/76
* VirusTotal Link: https://www.virustotal.com/gui/file/51b2f4f5b5cfb55143113b3071bb62fecd4015baab59315cfff5ea8be4a4b3b4/detection

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Windows\SysWOW64\rasautou.exe](rasautou.exe-81A6467E638E5C15C0C0ABB4DA13DEAD.md) | 79
[C:\WINDOWS\SysWOW64\rasautou.exe](rasautou.exe-BA2347843ED36587134C3B8AF434EC8C.md) | 57

## Possible Misuse

*The following table contains possible examples of `rasautou.exe` being misused. While `rasautou.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Rasautou.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Rasautou.yml) | `Name: Rasautou.exe` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Rasautou.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Rasautou.yml) | `- Command: rasautou -d powershell.dll -p powershell -a a -e e ` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Rasautou.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Rasautou.yml) | `- Path: C:\Windows\System32\rasautou.exe` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Rasautou.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Rasautou.yml) | `- IOC: rasautou.exe command line containing -d and -p` | 



MIT License. Copyright (c) 2020 Strontic.


