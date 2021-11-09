---
title: powercfg.exe | Power Settings Command-Line Tool
excerpt: What is powercfg.exe?
---

# powercfg.exe 

* File Path: `C:\WINDOWS\SysWOW64\powercfg.exe`
* Description: Power Settings Command-Line Tool

## Hashes

Type | Hash
-- | --
MD5 | `74E8B770C8C9DF711F36AFCA98EA49D6`
SHA1 | `C30F07AA271AE5C2CCA4F18AB60263C9A4209313`
SHA256 | `4906337EFD205F5AC2527F6E6A84E4A252B78D220990A9BA39B4A9A4648AA203`
SHA384 | `47BFC0358E6A255E1ECCEFFF7903F16762E7AC52A563EAF9AFF181717B2C216A43430148C7872576943564933687FB5E`
SHA512 | `D010D605F2082B75116FC9A8C1476086B099F762A98F4572160236574A1C2FEDC82FF93F79B36F7673830BDBC71784ABEBEE372783D2CA44A2D3446FC32B8784`
SSDEEP | `1536:ID58wQGBDWjE6kIeSnbPa7c45B1Bbf6nH0mB4js99t:DwQCuRk6F4b1NiUmBxB`
IMP | `198C1A66E629A660FA06ABEEB865D628`
PESHA1 | `ADFD1A685B59371582FF7F8A898B013EE8B96DE9`
PE256 | `03355FD37F9F65FE4B9C1002FDD8DCFA353D5D90776BB5C7E57B46C4F6780140`

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
C:\WINDOWS\SYSTEM32\ntdll.dll |
C:\WINDOWS\System32\wow64.dll |
C:\WINDOWS\System32\wow64base.dll |
C:\WINDOWS\System32\wow64con.dll |
C:\WINDOWS\System32\wow64cpu.dll |
C:\WINDOWS\System32\wow64win.dll |
C:\WINDOWS\SysWOW64\powercfg.exe |


## Signature

* Status: Signature verified.
* Serial: `33000002ED2C45E4C145CF48440000000002ED`
* Thumbprint: `312860D2047EB81F8F58C29FF19ECDB4C634CF6A`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: PowerCfg.exe
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.22000.1 (WinBuild.160101.0800)
* Product Version: 10.0.22000.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/74
* VirusTotal Link: https://www.virustotal.com/gui/file/4906337efd205f5ac2527f6e6a84e4a252b78d220990a9ba39b4a9a4648aa203/detection





MIT License. Copyright (c) 2020-2021 Strontic.


