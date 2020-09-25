---
title: notmyfaultc.exe | Driver Bug Test Program
excerpt: What is notmyfaultc.exe?
---

# notmyfaultc.exe 

* File Path: `C:\SysinternalsSuite\notmyfaultc.exe`
* Description: Driver Bug Test Program

## Hashes

Type | Hash
-- | --
MD5 | `0975FC4DBAAF10595742969CE2431D2E`
SHA1 | `F2C63100F617C92C5DEE8C2857800C5AE40ADAAA`
SHA256 | `E357AE1A7505BFDB79972A2A7EDCAF9BF78591B482E91F7D179D3C087A2324A9`
SHA384 | `4AA2C34EF313452BEBA6628312C816503FCD0D6B32D7F31A95448B00490C04A12078FBE556332C86F1C43705228086BF`
SHA512 | `B3F9DF75C6B9681ACE0C596558423A65C9C4AD4BB53ADB5D1DB9CCD848319E4209FC533F1169BE0CB6572ACE1820DE85DFC22DC93C45AA85076DBFB49EE27B2B`
SSDEEP | `6144:UypuxEiu29FS0HnvRCvYkYO7Vrsqs7ASy4kRqrb7XdOkIJGqCjO0fJ:UxED29FSQnvYvYkYqVFscSyhc7XWwh`
IMP | `8C038480EA7E48E91507A22BD69FF6A6`
PESHA1 | `E4060A80A5656F1938C92F4D062069BE07E7F9F1`
PE256 | `A4CDA07B93C545B326DAADABB0547872D87B9ED70A06FD0D7C3C6A37F2D25B1C`

## Runtime Data

### Usage (stdout):
```cmhg

Sysinternals NotMyfault v4.20 - Driver Bug Test Program
Copyright (C) 2002-2019 Mark Russinovich
Sysinternals - www.sysinternals.com


NotMyFault is a tool used in the Windows Internals books to show how common device driver bugs affect a system.
This is the console version of NotMyFault.

Usage:
    notmyfaultc.exe [/wait] /crash crash_type_num

    crash type:
      0x01: High IRQL fault (Kernel-mode)
      0x02: Buffer overflow
      0x03: Code overwrite
      0x04: Stack trash
      0x05: High IRQL fault (User-mode)
      0x06: Stack overflow
      0x07: Hardcoded breakpoint
      0x08: Double Free
    wait:
      wait until named event NOTMYFAULT is set


Or  notmyfaultc.exe /hang hang_type_num

    hang type:
      0x01: Hang with IRP
      0x02: Hang with DPC
      0x03: Deadlock


Or  notmyfaultc.exe /leak leak_type_num [/rate KB/s] [/duration seconds]

    leak type:
      0x01: Paged Leak
      0x02: Nonpaged Leak
    rate:
      default value is 1000 KB/s
    duration:
      default value is 30s

Or  notmyfaultc.exe bugcheck id


Or  notmyfaultc.exe /getdumptype
    notmyfaultc.exe /setdumptype [full|kernel|active]


```

### Loaded Modules:

Path |
-- |
C:\SysinternalsSuite\notmyfaultc.exe |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\wow64.dll |
C:\Windows\System32\wow64cpu.dll |
C:\Windows\System32\wow64win.dll |


## Signature

* Status: Signature verified.
* Serial: `33000001B1DDEDBA54E965B85F0001000001B1`
* Thumbprint: `9DC17888B5CFAD98B3CB35C1994E96227F061675`
* Issuer: CN=Microsoft Code Signing PCA, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Corporation, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: NotMyfault.exe
* Product Name: Sysinternals NotMyfault
* Company Name: Sysinternals - www.sysinternals.com
* File Version: 4.20
* Product Version: 4.20
* Language: English (United States)
* Legal Copyright: Copyright (C) 2002-2019 Mark Russinovich
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/73
* VirusTotal Link: https://www.virustotal.com/gui/file/e357ae1a7505bfdb79972a2a7edcaf9bf78591b482e91f7d179d3c087a2324a9/detection/





MIT License. Copyright (c) 2020 Strontic.


