---
title: MdmDiagnosticsTool.exe | MdmDiagnosticsTool
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

## Runtime Data

### Usage (stdout):
```Batchfile

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
C:\Windows\SYSTEM32\ntdll.dll |


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





MIT License. Copyright (c) 2020 Strontic.


