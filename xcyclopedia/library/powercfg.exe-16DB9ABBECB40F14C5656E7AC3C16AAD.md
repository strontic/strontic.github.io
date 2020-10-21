---
title: powercfg.exe | Power Settings Command-Line Tool
excerpt: What is powercfg.exe?
---

# powercfg.exe 

* File Path: `C:\Windows\system32\powercfg.exe`
* Description: Power Settings Command-Line Tool

## Hashes

Type | Hash
-- | --
MD5 | `16DB9ABBECB40F14C5656E7AC3C16AAD`
SHA1 | `B4AC55C4E13D62C666DF689F3D77F721D66B85B4`
SHA256 | `A6E1A555D365AB5F57DE1B077012B2B7AF65D7D9DD2500E6354CE47448EE7A1A`
SHA384 | `D71B972A49AAF797DD7562E67DE150D09AD963683A4BF8ACA577B343D16A2236A7E158362763B44F1F9372A375A6B5DC`
SHA512 | `6CFD3BDE155F330DA9BF65F9835C835BF78B5AA82D7F00D01D07FED90DDC9B45FE9729CFF552DB19F7458B0B1D724236CBFADAC11F3044E5876A6029FA29DEA4`
SSDEEP | `1536:FIatr7fAY77qstV4fZ/WIhDwltMPjl+3n3CW4GGt3mPI:FnA81aVjwlt25+HCWra3r`
IMP | `AFD7A8191DAF440071BC428C20F25CC4`
PESHA1 | `04B5EC5E1B7F977DBB42AA1DC61A666D4B3FCF96`
PE256 | `24CAF0B8A05D9CA378312396B4EBD4F27180BC2C05136E5226BD1F599AAB55BD`

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

  /SYSTEMSLEEPDIAGNOSTICS
                     Generates a diagnostic report of system sleep transitions.

  /SYSTEMPOWERREPORT Generates a diagnostic system power transition report.

  /POWERTHROTTLING   Control power throttling for an application.



```

### Usage (stderr):
```cmhg
Invalid Parameters -- try "/?" for help

```

### Loaded Modules:

Path |
-- |
C:\Windows\System32\advapi32.dll |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\System32\msvcrt.dll |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\system32\powercfg.exe |
C:\Windows\System32\powrprof.dll |
C:\Windows\System32\RPCRT4.dll |
C:\Windows\System32\sechost.dll |
C:\Windows\System32\ucrtbase.dll |


## Signature

* Status: Signature verified.
* Serial: `33000001C422B2F79B793DACB20000000001C4`
* Thumbprint: `AE9C1AE54763822EEC42474983D8B635116C8452`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: PowerCfg.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.17763.1 (WinBuild.160101.0800)
* Product Version: 10.0.17763.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/73
* VirusTotal Link: https://www.virustotal.com/gui/file/a6e1a555d365ab5f57de1b077012b2b7af65d7d9dd2500e6354ce47448ee7a1a/detection/





MIT License. Copyright (c) 2020 Strontic.


