---
title: MdmDiagnosticsTool.exe | MdmDiagnosticsTool
excerpt: What is MdmDiagnosticsTool.exe?
---

# MdmDiagnosticsTool.exe 

* File Path: `C:\WINDOWS\system32\MdmDiagnosticsTool.exe`
* Description: MdmDiagnosticsTool

## Hashes

Type | Hash
-- | --
MD5 | `7B730B5DCA93C4FFBB312979A7A3071A`
SHA1 | `1205605CA528F59B00BAF644BFA9891662689A19`
SHA256 | `564A21B03503A35E32D452D4BE891DB6F1916E78D8B41F2ADC52253133C31B11`
SHA384 | `B5A4CA53AA4DB80C31E86E82FAB79A4A4AE85473F7852966D0B964E93EAD35670D51A2CF499487DD8037ABA921EE939A`
SHA512 | `CC8C805F4DAC6EB744EB5C793FD67984DABFFD85B9DA34C760A4E63AECCC779C3844C52A3C4D0A9D98384F605AB1D5E03091F1FAC8155E2876B2B74ABF2BB17A`
SSDEEP | `1536:erNRDoza3bG2+ZqXeFpCT6nzzUzvAl6OPhj+W1dmlrMzU:Skei2zmpBzzUzv8Zj+odmlAw`
IMP | `48596E6EDF0A19C3B95D96D28C2C1F0B`
PESHA1 | `70C424E61FC8A69F7E65B0BFF18F94590AD99C88`
PE256 | `C2C9294E5631C5C0CBBA60E82B65DFC5E69BACD55E63BE42F03740EE34686B4F`

## Runtime Data

### Usage (stdout):
```cmhg

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

  Usage5: C:\WINDOWS\system32\MdmDiagnosticsTool.exe -clean
      * Cleans up all the diagnostic log files collected. 


```

### Loaded Modules:

Path |
-- |
C:\WINDOWS\System32\KERNEL32.DLL |
C:\WINDOWS\System32\KERNELBASE.dll |
C:\WINDOWS\system32\MdmDiagnosticsTool.exe |
C:\WINDOWS\SYSTEM32\ntdll.dll |


## Signature

* Status: Signature verified.
* Serial: `33000002ED2C45E4C145CF48440000000002ED`
* Thumbprint: `312860D2047EB81F8F58C29FF19ECDB4C634CF6A`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: MdmDiagnosticsTool.exe
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.22000.1 (WinBuild.160101.0800)
* Product Version: 10.0.22000.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/73
* VirusTotal Link: https://www.virustotal.com/gui/file/564a21b03503a35e32d452d4be891db6f1916e78d8b41f2adc52253133c31b11/detection





MIT License. Copyright (c) 2020-2021 Strontic.


