---
title: MdmDiagnosticsTool.exe | MdmDiagnosticsTool
---

# MdmDiagnosticsTool.exe 

* File Path: `C:\WINDOWS\system32\MdmDiagnosticsTool.exe`
* Description: MdmDiagnosticsTool

## Hashes

Type | Hash
-- | --
MD5 | `09F8366D2E20834D12684E34382E6410`
SHA1 | `5F3E03C0756A3F22FE88A21597429326522D01A6`
SHA256 | `B4D0392A67B386496E7B513C2C4F66C93C9077E1C27A2C223728152D3373F1C4`
SHA384 | `8F6A3BA46869F52B099BE93E799D97973A7393999F4B6325CB1DCF07FF8A4D1902065E9387DFFD0A97E87192FA90FF0F`
SHA512 | `71E3F71BBE8950F64D0C7938B369A078FD8756AB9F6318A582E53937094EB28B2B0CDF52B15C78E2D38D81B9151A7FAFF5BDD4B40A000942BDB6548F202F7C98`
SSDEEP | `1536:hMugb/U0BBxUg1MLNhUXFlErmZRAcD+tdmaaKZXe3k:eSiFlErYRxD+tdmXwu0`

## Runtime Data

### Usage (stdout):
```Batchfile

  Usage1: C:\WINDOWS\system32\MdmDiagnosticsTool.exe -out <output folder path>
      * Output MDM diagnostics info only to given folder path specified in -out parameter.
      eg: C:\WINDOWS\system32\MdmDiagnosticsTool.exe -out c:\temp\outputfolder

  Usage2: C:\WINDOWS\system32\MdmDiagnosticsTool.exe -area <area name(s)> -cab <output cab file path>
      * Collect predefined area logs and create a log cab to given cab file.
      * Supported area name example:
          Autopilot
          DeviceProvisioning
          Tpm
      * It also supports multiple areas, separated by ';', example:
          Autopilot;DeviceEnrollment;Tpm
      * Please find all possible areas in registry under:
          HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\MdmDiagnostics\Area
      eg: C:\WINDOWS\system32\MdmDiagnosticsTool.exe -area Autopilot;Tpm -cab c:\temp\AutopilotDiag.cab
  Usage3: C:\WINDOWS\system32\MdmDiagnosticsTool.exe -area <area name(s)> -zip <output zip file path>
      * Collect predefined area logs and create a log zip to given zip file. Areas supported are the same as Usage2 for creating cab
  Usage4: C:\WINDOWS\system32\MdmDiagnosticsTool.exe -xml <xml file of information to gather> -zip <output zip file path> -server <MDM Server to alert>
      * Collect information specified in the xml and create a log zip to given zip file. 


```

## Signature

* Status: Signature verified.
* Serial: `330000023241FB59996DCC4DFF000000000232`
* Thumbprint: `FF82BC38E1DA5E596DF374C53E3617F7EDA36B06`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: MdmDiagnosticsTool.exe
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.18362.1 (WinBuild.160101.0800)
* Product Version: 10.0.18362.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.





MIT License. Copyright (c) 2020 Strontic.


