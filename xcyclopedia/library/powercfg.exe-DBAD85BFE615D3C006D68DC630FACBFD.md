---
title: powercfg.exe | Power Settings Command-Line Tool
---

# powercfg.exe 

* File Path: `C:\Windows\SysWOW64\powercfg.exe`
* Description: Power Settings Command-Line Tool
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `DBAD85BFE615D3C006D68DC630FACBFD`
SHA1 | `BF12D59B5A3335C9E4EFD2ADB9A6F3F411DEBA5D`
SHA256 | `65944EEF8ABAA6FA30150B17589A78DDE595E96BAE581E99166E8835E95801B6`
SHA384 | `201767BA3C1BECAEC596CAC323F4D050CA4149E246DD640D3F57DA617BAFFE7E1F9D9529EAA8C57E454EB5660E484C85`
SHA512 | `83351674E56978D9CB7F5FE0C56722D11F569E34200AF8AF9C3F105CF1C1A2D346674102BCB60DA89BA607C3ADCFD09F4678D0DC6EC57CDBEEE049C6AC832278`
SSDEEP | `1536:L4EqDN3DVIdnIhcN1i60GK/5j8d4IQIYWHqYTT:DqDN3DGyKhK5SQIYVQT`

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

  /SYSTEMSLEEPDIAGNOSTICS
                     Generates a diagnostic report of system sleep transitions.



```

### Usage (stderr):
```Batchfile
Invalid Parameters -- try "/?" for help

```

### Child Processes:


## Signature

* Status: Signature verified.
* Serial: `33000001733031072665B8B9B3000000000173`
* Thumbprint: `14590DC5C3AAF238FCFD7785B4B93F4071402C34`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: PowerCfg.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.14393.351 (rs1_release_inmarket.161014-1755)
* Product Version: 10.0.14393.351
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.





MIT License. Copyright (c) 2020 Strontic.


