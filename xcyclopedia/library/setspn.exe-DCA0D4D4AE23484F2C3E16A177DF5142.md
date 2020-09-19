---
title: setspn.exe | Query or reset the computer's SPN attribute
---

# setspn.exe 

* File Path: `C:\WINDOWS\system32\setspn.exe`
* Description: Query or reset the computer's SPN attribute

## Hashes

Type | Hash
-- | --
MD5 | `DCA0D4D4AE23484F2C3E16A177DF5142`
SHA1 | `7B4CCE01ADD3B561CDE2363CE1B9D8889F1FF82A`
SHA256 | `B67DFB0B0BFE472ED2C047D3FA4C8D462DFFE3A309741D3F5F616213DC3EC2ED`
SHA384 | `1F82D28167BE10F298084335A1EC97AB30FD1C6EFBCA573EB1EA964BB0E0F1146C4F30361758501F77C00998C7EF1300`
SHA512 | `B29B2A73F966BB73F2AD80C2509C5C81138D4C09E8B0BE61E43CB5EEF8A96F98A0DD54F0D4DE0099F7FE3298A0B0E03BC63D643D962D848BE1EE478413AC1372`
SSDEEP | `384:fUz5ZiDavb8kNdtc5O451IHkntAu7d0T8bJNzcX82oXIqzvnYim+TIWOaW:f9aADOgqknt77d0T8v4RoYqzYkU`

## Runtime Data

### Usage (stdout):
```cmhg
Usage: C:\WINDOWS\system32\setspn.exe [modifiers switch] [accountname] 
  Where "accountname" can be the name or domain\name
  of the target computer or user account

  Edit Mode Switches:
   -R = reset HOST ServicePrincipalName
    Usage:   setspn -R accountname
   -S = add arbitrary SPN after verifying no duplicates exist
    Usage:   setspn -S SPN accountname
   -D = delete arbitrary SPN
    Usage:   setspn -D SPN accountname
   -L = list SPNs registered to target account
    Usage:   setspn [-L] accountname   

  Edit Mode Modifiers:
   -C = specify that accountname is a computer account
   -U = specify that accountname is a user account
   
    Note: -C and -U are exclusive.  If neither is specified, the tool
     will interpret accountname as a computer name if such a computer
     exists, and a user name if it does not.

  Query Mode Switches:
   -Q = query for existence of SPN
    Usage:   setspn -Q SPN 
   -X = search for duplicate SPNs
    Usage:   setspn -X 

    Note: searching for duplicates, especially forestwide, can take
     a long period of time and a large amount of memory.  -Q will execute
     on each target domain/forest.  -X will return duplicates that exist
     across all targets. SPNs are not required to be unique across forests,
     but duplicates can cause authentication issues when authenticating
     cross-forest.

  Query Mode Modifiers:
   -P = suppresses progress to the console and can be used when redirecting
    output to a file or when used in an unattended script.  There will be no
    output until the command is complete.
   -F = perform queries at the forest, rather than domain level
   -T = perform query on the speicified domain or forest (when -F is also used)
    Usage:   setspn -T domain (switches and other parameters)
     "" or * can be used to indicate the current domain or forest.

    Note: these modifiers can be used with the -S switch in order to specify
     where the check for duplicates should be performed before adding the SPN.
    Note: -T can be specified multiple times.

Examples: 
setspn -R daserver1 
   It will register SPN "HOST/daserver1" and "HOST/{DNS of daserver1}" 
setspn -S http/daserver daserver1 
   It will register SPN "http/daserver" for computer "daserver1" 
    if no such SPN exists in the domain
setspn -D http/daserver daserver1 
   It will delete SPN "http/daserver" for computer "daserver1" 
setspn -F -S http/daserver daserver1 
   It will register SPN "http/daserver" for computer "daserver1"
    if no such SPN exists in the forest
setspn -U -S http/daserver dauser 
   It will register SPN "http/daserver" for user account "dauser" 
    if no such SPN exists in the domain
setspn -T * -T bar -X
   It will report all duplicate registration of SPNs in this domain and bar
setspn -T bar -F -Q */daserver
   It will find all SPNs of the form */daserver registered in the forest to
    which bar belongs

```

### Usage (stderr):
```cmhg
FindDomainForAccount: Call to DsGetDcNameWithAccountW failed with return value 0x0000054B
Could not find account help

```

## Signature

* Status: Signature verified.
* Serial: `330000023241FB59996DCC4DFF000000000232`
* Thumbprint: `FF82BC38E1DA5E596DF374C53E3617F7EDA36B06`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: setspn.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.18362.1 (WinBuild.160101.0800)
* Product Version: 10.0.18362.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.


## Possible Misuse

*The following table contains possible examples of `setspn.exe` being misused. While `setspn.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_spn_enum.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_spn_enum.yml) | `Image: '*\setspn.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1558.003.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1558.003/T1558.003.md) | Service principal names (SPNs) are used to uniquely identify each instance of a Windows service. To enable authentication, Kerberos requires that SPNs be associated with at least one service logon account (an account specifically tasked with running a service(Citation: Microsoft Detecting Kerberoasting Feb 2018)).(Citation: Microsoft SPN)(Citation: Microsoft SetSPN)(Citation: SANS Attacking Kerberos Nov 2014)(Citation: Harmj0y Kerberoast Nov 2016) | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)



MIT License. Copyright (c) 2020 Strontic.


