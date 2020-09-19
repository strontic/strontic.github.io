---
title: setspn.exe | Query or reset the computer's SPN attribute
---

# setspn.exe 

* File Path: `C:\windows\system32\setspn.exe`
* Description: Query or reset the computer's SPN attribute

## Hashes

Type | Hash
-- | --
MD5 | `C729DEA1888B1B047F51844BA5BD875F`
SHA1 | `3B8C77CC25CF382D51B418CB9738BA99C3FDBAA9`
SHA256 | `E3B06217D90BD1A2C12852398EA0E85C12E58F0ECBA35465E3DC60AC29AC0DC9`
SHA384 | `227EC7147BD922E67946AB4C21B00A5373510F8D8BAB334EB97A44E67F045A2E5983FC40C5D8078E67C7DB5E78486C4A`
SHA512 | `6F6C4010C0015C1DC7EF794974D1349015EFAFF49066DCFAD990FE12C42B0161C16E329B64BD301ACD431C11E26A456F56B4D58091D492ADC34DEB4B966C0EC4`
SSDEEP | `768:jakNYMFafaTKvRNLAnCqI7UaW0pTikvPOlFf8VYn:+khuaE04lbOUyn`

## Signature

* Status: The file C:\windows\system32\setspn.exe is not digitally signed. You cannot run this script on the current system. For more information about running scripts and setting execution policy, see about_Execution_Policies at http://go.microsoft.com/fwlink/?LinkID=135170
* Serial: ``
* Thumbprint: ``
* Issuer: 
* Subject: 

## File Metadata

* Original Filename: setspn.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 6.3.9600.16384 (winblue_rtm.130821-1623)
* Product Version: 6.3.9600.16384
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.


## Possible Misuse

*The following table contains possible examples of `setspn.exe` being misused. While `setspn.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_spn_enum.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_spn_enum.yml) | `Image: '*\setspn.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1558.003.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1558.003/T1558.003.md) | Service principal names (SPNs) are used to uniquely identify each instance of a Windows service. To enable authentication, Kerberos requires that SPNs be associated with at least one service logon account (an account specifically tasked with running a service(Citation: Microsoft Detecting Kerberoasting Feb 2018)).(Citation: Microsoft SPN)(Citation: Microsoft SetSPN)(Citation: SANS Attacking Kerberos Nov 2014)(Citation: Harmj0y Kerberoast Nov 2016) | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)



MIT License. Copyright (c) 2020 Strontic.


