---
title: powercfg.exe | Power Settings Command-Line Tool
excerpt: What is powercfg.exe?
---

# powercfg.exe 

* File Path: `C:\WINDOWS\system32\powercfg.exe`
* Description: Power Settings Command-Line Tool

## Hashes

Type | Hash
-- | --
MD5 | `B228899B6F9AC3F26E22EACB3503B64C`
SHA1 | `71258E1D1F36B4AD8C10FF6772C93A14AB801211`
SHA256 | `C9C9A9125DF638CCB97167A3C4580C117E6D97CCE6CB55B35DFAE4D7019DC6E8`
SHA384 | `24726795FD64516D512741D82D91F7F90ABFBD7E8BE9DC7AF2F5707C06820BC178D7F6C7025378F823A4CE6032110392`
SHA512 | `72F271A02B77B582A424EAC6DE7CBF34686E19803A85DD5379F1C181B4CD4FE28AF4452932C326BDE260B45276A0631F73E839BC7394AC2A408F10677B0937A8`
SSDEEP | `3072:ZwAKtGTQ1aCNutY5V6JfkwQvKhhag+VBX+0h:CAKyQ1aCgoVI8wQShhag+VBX+0`
IMP | `E85330399B67B18F4577E432CA6CE70D`
PESHA1 | `7E10BD9E0AA16081173897580BDD0C58515C4F4D`
PE256 | `7EB5800E12A6040D61F783F6D2C4356EAED1CC233000D28D0EF1ABC0691ED9F0`

## Runtime Data

### Usage (stdout):
```cmhg

POWERCFG /COMMAND [ARGUMENTS]

Description:
  Enables users to control power settings on a local system.

  For detailed command and option information, run "POWERCFG /? <COMMAND>"

Command List:
  /LIST, /L          Lists all power schemes.

  /QUERY, /Q         Displays the contents of a power scheme.

  /CHANGE, /X        Modifies a setting value in the current power scheme.

  /CHANGENAME        Modifies the name and description of a power scheme.

  /DUPLICATESCHEME   Duplicates a power scheme.

  /DELETE, /D        Deletes a power scheme.

  /DELETESETTING     Deletes a power setting.

  /SETACTIVE, /S     Makes a power scheme active on the system.

  /GETACTIVESCHEME   Retrieves the currently active power scheme.

  /SETACVALUEINDEX   Sets the value associated with a power setting
                     while the system is powered by AC power.

  /SETDCVALUEINDEX   Sets the value associated with a power setting
                     while the system is powered by DC power.

  /IMPORT            Imports all power settings from a file.

  /EXPORT            Exports a power scheme to a file.

  /ALIASES           Displays all aliases and their corresponding GUIDs.

  /GETSECURITYDESCRIPTOR
                     Gets a security descriptor associated with a specified
                     power setting, power scheme, or action.

  /SETSECURITYDESCRIPTOR
                     Sets a security descriptor associated with a
                     power setting, power scheme, or action.

  /HIBERNATE, /H     Enables and disables the hibernate feature.

  /AVAILABLESLEEPSTATES, /A
                     Reports the sleep states available on the system.

  /DEVICEQUERY       Returns a list of devices that meet specified criteria.

  /DEVICEENABLEWAKE  Enables a device to wake the system from a sleep state.

  /DEVICEDISABLEWAKE Disables a device from waking the system from a sleep
                     state.

  /LASTWAKE          Reports information about what woke the system from the
                     last sleep transition.

  /WAKETIMERS        Enumerates active wake timers.

  /REQUESTS          Enumerates application and driver Power Requests.

  /REQUESTSOVERRIDE  Sets a Power Request override for a particular Process,
                     Service, or Driver.

  /ENERGY            Analyzes the system for common energy-efficiency and
                     battery life problems.

  /BATTERYREPORT     Generates a report of battery usage.

  /SLEEPSTUDY        Generates a diagnostic system power transition report.

  /SRUMUTIL          Dumps Energy Estimation data from System Resource Usage
                     Monitor (SRUM).

  /SYSTEMSLEEPDIAGNOSTICS
                     The system sleep diagnostics report has been deprecated and
                     replaced with the system power report. Please use the command
                     "powercfg /systempowerreport" instead.

  /SYSTEMPOWERREPORT Generates a diagnostic system power transition report.

  /POWERTHROTTLING   Control power throttling for an application.

  /PROVISIONINGXML, /PXML    Generate an XML file containing power setting overrides.



```

### Usage (stderr):
```cmhg
Invalid Parameters -- try "/?" for help

```

### Loaded Modules:

Path |
-- |
C:\WINDOWS\System32\KERNEL32.DLL |
C:\WINDOWS\System32\KERNELBASE.dll |
C:\WINDOWS\SYSTEM32\ntdll.dll |
C:\WINDOWS\system32\powercfg.exe |


## Signature

* Status: Signature verified.
* Serial: `33000002ED2C45E4C145CF48440000000002ED`
* Thumbprint: `312860D2047EB81F8F58C29FF19ECDB4C634CF6A`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: PowerCfg.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.22000.1 (WinBuild.160101.0800)
* Product Version: 10.0.22000.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/73
* VirusTotal Link: https://www.virustotal.com/gui/file/c9c9a9125df638ccb97167a3c4580c117e6d97cce6cb55b35dfae4d7019dc6e8/detection





MIT License. Copyright (c) 2020-2021 Strontic.


