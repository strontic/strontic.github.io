---
title: MdmDiagnosticsTool.exe | MdmDiagnosticsTool
---

# MdmDiagnosticsTool.exe 

* File Path: `C:\Windows\system32\MdmDiagnosticsTool.exe`
* Description: MdmDiagnosticsTool

## Hashes

Type | Hash
-- | --
MD5 | `F20ECB94071A09A82E77D6C6EC812EE2`
SHA1 | `17456B841F099D2CAFCA796AAB5A1A282B72C93E`
SHA256 | `AAFAD4DB7AAB9E9A140DF4E6B0A53DC7067E22C65CAD1616E3B79CCC3252EC71`
SHA384 | `54DB7A6AA16494461F9A49E10304DAE5C9EFAB59021B415463A619269505C9059E7295F6ECECA192A05F2560730BB7B5`
SHA512 | `0DD696DFD4AF5F88A9C42B1FCF04A2AFF0E05B2C3552CB3AB1D1786977193A895E7A1823580BDE4F2237E4AFBF8924B213E1176E05A28147757DB00F3FF323EE`
SSDEEP | `1536:N7L5ewNt3W0wWBPt+KWmfVev4+6PdHvpuebu:lYuW0wqt+LyVo4+GdHBDbu`

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
* File Version: 10.0.19041.329 (WinBuild.160101.0800)
* Product Version: 10.0.19041.329
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.





MIT License. Copyright (c) 2020 Strontic.


