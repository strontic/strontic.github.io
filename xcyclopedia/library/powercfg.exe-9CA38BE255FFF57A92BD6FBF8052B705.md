---
title: powercfg.exe | Power Settings Command-Line Tool
---

# powercfg.exe 

* File Path: `C:\Windows\system32\powercfg.exe`
* Description: Power Settings Command-Line Tool
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `9CA38BE255FFF57A92BD6FBF8052B705`
SHA1 | `9ADB16A18ED1650F5F5A7E6BD83DBD3DFD1963E1`
SHA256 | `CB2459971A56CEE45A30346281FF3B0ECCEA0C2BEE1AE6B8477712404D2E6AE1`
SHA384 | `1CF1AB7D192FBF96726C5AC655A57E308AC2A4B27D18EB47795BB01417EBE7939053284E7FA42F0861E0F5A7ED55D4ED`
SHA512 | `7746A3232C82C1C0850A7FC3507B872CB73E86E4C90E45F6B80855CB2509D9C0F824995E7DB0534816A424FC7D4DC414E98196BA664870E6B6741F1E2E268E68`
SSDEEP | `1536:IP++GkfoF8OF3R9Jz1+GidH27gYqXwkNUFmhBwU9LLVHhdeTdDze4yx34QvZj:I50b3R9JBZGuVqRN/wUhhB0Nzejv`

## Runtime Data

### Usage (stdout):
```Batchfile

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
```Batchfile
Invalid Parameters -- try "/?" for help

```

### Child Processes:


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: PowerCfg.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.





MIT License. Copyright (c) 2020 Strontic.


