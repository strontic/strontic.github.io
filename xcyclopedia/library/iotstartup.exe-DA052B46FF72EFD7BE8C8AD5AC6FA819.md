---
title: iotstartup.exe | IotStartup
excerpt: What is iotstartup.exe?
---

# iotstartup.exe 

* File Path: `C:\WINDOWS\system32\iotstartup.exe`
* Description: IotStartup

## Hashes

Type | Hash
-- | --
MD5 | `DA052B46FF72EFD7BE8C8AD5AC6FA819`
SHA1 | `75E1124F0FE509803049D0594B97419F1012FD7E`
SHA256 | `E06C166D7CFBEFCD87D6A3D84C7342CD849CE198BCD62DFAE20636BAB50783E5`
SHA384 | `17A39CDDB2D3937FD2BDE7698554829EEE9689268EB159B0192D3670D58E498A7CED4E7A6085CD35733D34379CF381A7`
SHA512 | `3EFBF4F58D0BD7C9DD87E4E4BB4CE49FF5EDBD63DFAD099D32BFCB5387785419ED78484A317FFA3DA5BAAAE349C6159627CBA6B3D900B6BBF40C9BACAA516DA3`
SSDEEP | `3072:GsopdMc3JkXXDfAURFGlmglqA1YN4eAnBvIa1c1dgjrzEfNogA:Gsofz58zAURFGl5PYN9E+ac16jrzEq`
IMP | `E6C0D2232E02D1C9093402618A3DDCE0`
PESHA1 | `EC91CE69D3738C5AECB21E4254E54BD8CB5681F0`
PE256 | `77218D379EB19FDEC8A5C0F4678CF4D9C925E2A29544CC981BD0476C860BE65A`

## Runtime Data

### Usage (stdout):
```cmhg
Usage:
  IotStartup [list|add|remove|startup] ([headed|headless]) (suppress) (std::regex regular expression with implied ^ prepended)
  IotStartup [run|stop] (std::regex regular expression with implied ^ prepended)
  IotStartup [help|-?|-h|--help]

Examples:
  IotStartup list                   // list installed applications
  IotStartup list headed            // list installed headed applications
  IotStartup list headless          // list installed headless applications
  IotStartup list MyApp             // list installed applications that match pattern MyApp

  IotStartup add headed MyApp       // add headed application that matches pattern MyApp.  Pattern must match only one application.
  IotStartup add headless Task1     // add headless applications that match pattern Task1

  IotStartup remove headless Task1  // remove headless applications that match pattern Task1
  IotStartup remove headless suppress Task1  // remove headless applications that match pattern Task1 and suppress WNF notification

  IotStartup startup                // list headed and headless applications registered for startup
  IotStartup startup MyApp          // list headed and headless applications registered for startup that match pattern MyApp
  IotStartup startup headed MyApp   // list headed applications registered for startup that match MyApp
  IotStartup startup headless Task1 // list headless applications registered for startup that match Task1

  IotStartup run MyApp              // Start app identified by MyApp (see 'iotstartup list')
  IotStartup stop MyApp             // Stop app identified by MyApp (see 'iotstartup list')


```

### Loaded Modules:

Path |
-- |
C:\WINDOWS\system32\iotstartup.exe |
C:\WINDOWS\System32\KERNEL32.DLL |
C:\WINDOWS\System32\KERNELBASE.dll |
C:\WINDOWS\SYSTEM32\ntdll.dll |


## Signature

* Status: Signature verified.
* Serial: `33000002ED2C45E4C145CF48440000000002ED`
* Thumbprint: `312860D2047EB81F8F58C29FF19ECDB4C634CF6A`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: iotstartup.exe
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.22000.1 (WinBuild.160101.0800)
* Product Version: 10.0.22000.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/73
* VirusTotal Link: https://www.virustotal.com/gui/file/e06c166d7cfbefcd87d6a3d84c7342cd849ce198bcd62dfae20636bab50783e5/detection





MIT License. Copyright (c) 2020-2021 Strontic.


