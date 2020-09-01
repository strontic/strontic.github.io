---
title: setspn.exe | Query or reset the computer's SPN attribute
---

# setspn.exe 

* File Path: `C:\windows\SysWOW64\setspn.exe`
* Description: Query or reset the computer's SPN attribute

## Hashes

Type | Hash
-- | --
MD5 | `F49B7307D15DC63A4F4848C17383E655`
SHA1 | `B951E525098F8032E0AA26291D1D10E6CF7BDCF9`
SHA256 | `84B7B28DB52AE454CABA76B134895EB3244295CB3A45EC40ACB9B5D653C96553`
SHA384 | `DB450537480A83240A3505DF833BEBD3C72D9397BBE5FF6496BFDCBD508322CB1027B1E87AC3501B5E13A10E2629B396`
SHA512 | `5DEDF00A5C320DE1496BB2D2C9165242F6460AB4472895D4299F620C0D04BEB7DCA50E7621004344B9977FEC746852C3FBB289148EDA136506E726242D4AF5EB`
SSDEEP | `384:Klb7NApubbjTyH7Mc3NQELSj0TXc3D23U531edYWxaWPlUI:gb7NApQ3TyH7zy+wT31SnW`

### Loaded Modules:

Path |
-- |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\SysWOW64\setspn.exe |


## Signature

* Status: The file C:\windows\SysWOW64\setspn.exe is not digitally signed. You cannot run this script on the current system. For more information about running scripts and setting execution policy, see about_Execution_Policies at http://go.microsoft.com/fwlink/?LinkID=135170
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
[sigma](https://github.com/Neo23x0/sigma) | [win_spn_enum.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_spn_enum.yml) | `        Image: '*\setspn.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1558.003.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1558.003/T1558.003.md) | Service principal names (SPNs) are used to uniquely identify each instance of a Windows service. To enable authentication, Kerberos requires that SPNs be associated with at least one service logon account (an account specifically tasked with running a service(Citation: Microsoft Detecting Kerberoasting Feb 2018)).(Citation: Microsoft SPN)(Citation: Microsoft SetSPN)(Citation: SANS Attacking Kerberos Nov 2014)(Citation: Harmj0y Kerberoast Nov 2016) | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)



MIT License. Copyright (c) 2020 Strontic.


