---
title: MdmDiagnosticsTool.exe | MdmDiagnosticsTool
excerpt: What is MdmDiagnosticsTool.exe?
---

# MdmDiagnosticsTool.exe 

* File Path: `C:\Windows\system32\MdmDiagnosticsTool.exe`
* Description: MdmDiagnosticsTool

## Hashes

Type | Hash
-- | --
MD5 | `A2F880F75CD7EB1E9FEF1D5D8653C81D`
SHA1 | `5431835B05FFD3A13A9F15B3EE937745712731FE`
SHA256 | `BB2961E1A7568F390D75654546FD6E7AD6DE6A921EF8AC334843E1B3020880ED`
SHA384 | `34CE05B763F9F3F8FD175087D994C85435ACFBC92BA0D1918ED175F6FA6EE4E55AF5B916AA174C4EF839495747A28EAD`
SHA512 | `FFD4D5BD1E7690DF7044F169C2DFD38C9589C0FAB26E8E79616D660A12EA13D174179453ACDDBE919A309C33CB9D4EDE055B805B2F46DB011A8B8C3DAA86B759`
SSDEEP | `1536:n8QDjEI47aX44vUxLBiYWnEoWAOcI+6LdfDyqTP3:n5BX44vMLBiFEoocI+idfLb3`
IMP | `20CFC62666DE4666A0E7B71CA8895503`
PESHA1 | `DC779AB82601785B9365247E9693A230432D186F`
PE256 | `A05983A86E5F2C788D3ED6C86A298EDECBC808B667F067698B86B7A6FE7D6142`

## Runtime Data

### Usage (stdout):
```cmhg

  Usage1: C:\Windows\system32\MdmDiagnosticsTool.exe -out <output folder path>
      * Output MDM diagnostics info only to given folder path specified in -out parameter.
      eg: C:\Windows\system32\MdmDiagnosticsTool.exe -out c:\temp\outputfolder

  Usage2: C:\Windows\system32\MdmDiagnosticsTool.exe -area <area name(s)> -cab <output cab file path>
      * Collect predefined area logs and create a log cab to given cab file.
      * Supported area name example:
          Autopilot
          DeviceProvisioning
          Tpm
      * It also supports multiple areas, separated by ';', example:
          Autopilot;DeviceEnrollment;Tpm
      * Please find all possible areas in registry under:
          HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\MdmDiagnostics\Area
      eg: C:\Windows\system32\MdmDiagnosticsTool.exe -area Autopilot;Tpm -cab c:\temp\AutopilotDiag.cab
  Usage3: C:\Windows\system32\MdmDiagnosticsTool.exe -area <area name(s)> -zip <output zip file path>
      * Collect predefined area logs and create a log zip to given zip file. Areas supported are the same as Usage2 for creating cab
  Usage4: C:\Windows\system32\MdmDiagnosticsTool.exe -xml <xml file of information to gather> -zip <output zip file path> -server <MDM Server to alert>
      * Collect information specified in the xml and create a log zip to given zip file. 


```

### Loaded Modules:

Path |
-- |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\system32\MdmDiagnosticsTool.exe |
C:\Windows\SYSTEM32\ntdll.dll |


## Signature

* Status: Signature verified.
* Serial: `33000002EC6579AD1E670890130000000002EC`
* Thumbprint: `F7C2F2C96A328C13CDA8CDB57B715BDEA2CBD1D9`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: MdmDiagnosticsTool.exe
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1023 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1023
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/73
* VirusTotal Link: https://www.virustotal.com/gui/file/bb2961e1a7568f390d75654546fd6e7ad6de6a921ef8ac334843e1b3020880ed/detection





MIT License. Copyright (c) 2020-2021 Strontic.


