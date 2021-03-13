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
MD5 | `F8C5CF8A518FAFE5E2577CBC2E6D1820`
SHA1 | `00F131BD0D5408A2DA70D86CFC30527C0B39E230`
SHA256 | `FF7895DDC7D4DFB528B431B95001C6AD44178ED697FA5C29A77BFD033D73800C`
SHA384 | `6355BB8C5200997AE8848E22A35E6A85CFE6754AA4BAC1F15C10D0A23222E459C4E30E3D4F5D508D1D38EAF3EC49F6CB`
SHA512 | `401A526A8A6BF9E5660B72F7586080C73B4E9B9E810F42C4C73F7D8CB96313B489C426875016A9A2819B16D3F39BAD9B9D89B6C98D8B81B2F4F1D0A7799E95F1`
SSDEEP | `1536:v5Z744D9cRcB/ZMpG7LkJ83vjQ0hDwltMLwRassjdIh4b7uFe:vGRqCXWkOwltywRKdIhQh`

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
                     Generates a diagnostic report of system sleep transitions.

  /SYSTEMPOWERREPORT Generates a diagnostic system power transition report.

  /POWERTHROTTLING   Control power throttling for an application.



```

### Usage (stderr):
```cmhg
Invalid Parameters -- try "/?" for help

```

## Signature

* Status: Signature verified.
* Serial: `330000023241FB59996DCC4DFF000000000232`
* Thumbprint: `FF82BC38E1DA5E596DF374C53E3617F7EDA36B06`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: PowerCfg.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.18362.1 (WinBuild.160101.0800)
* Product Version: 10.0.18362.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.






MIT License. Copyright (c) 2020-2021 Strontic.


