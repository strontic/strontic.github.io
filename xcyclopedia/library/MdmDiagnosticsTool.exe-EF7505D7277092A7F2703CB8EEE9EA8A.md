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
MD5 | `EF7505D7277092A7F2703CB8EEE9EA8A`
SHA1 | `D500207160D929D9D9D9B73828EB204EB825F7A0`
SHA256 | `9B0A7EA1EE9C9BC427DCEEFC394361D74E7FB7A597A09439C3768CC689301D48`
SHA384 | `1036236CA1F9E33297D0E530CAC1B60C1846FD7FDD8114228E3AECDB02F144A76960291FCFA60BD81A8411961779B71C`
SHA512 | `3204E7883CB60E6D24F6663D4727A9DB784E0104CBB6447871984A33E7A1B306AD90C4E3ED715F3BBC900DB1A940E4ADE5C060D1502129411EC4712D91FBE15B`
SSDEEP | `1536:aA+3nEATZklqlsCmHlnry0R3BTcl+GdGnqcweYb:YHAy0RRYl+GdGqcxYb`
IMP | `C2629DC74DBE9DD271C4A59A43BF4896`
PESHA1 | `48C991AFC350A4B753D54566D5BC61E846D1C9A5`
PE256 | `8773D8BCC4DBDE66FE0643EFE992F4998EF89E961AFDE5EB1612DFF3576EEA46`

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
C:\Windows\System32\bcryptPrimitives.dll |
C:\Windows\System32\combase.dll |
C:\Windows\System32\CRYPT32.dll |
C:\Windows\System32\CRYPTSP.dll |
C:\Windows\system32\DMCmnUtils.dll |
C:\Windows\system32\iri.dll |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\system32\MdmDiagnosticsTool.exe |
C:\Windows\System32\MSASN1.dll |
C:\Windows\System32\msvcp_win.dll |
C:\Windows\system32\msvcp110_win.dll |
C:\Windows\System32\msvcrt.dll |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\OLEAUT32.dll |
C:\Windows\system32\omadmapi.dll |
C:\Windows\System32\RPCRT4.dll |
C:\Windows\System32\sechost.dll |
C:\Windows\System32\ucrtbase.dll |


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: MdmDiagnosticsTool.exe
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.17763.1282 (WinBuild.160101.0800)
* Product Version: 10.0.17763.1282
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/64
* VirusTotal Link: https://www.virustotal.com/gui/file/9b0a7ea1ee9c9bc427dceefc394361d74e7fb7a597a09439c3768cc689301d48/detection/





MIT License. Copyright (c) 2020 Strontic.


