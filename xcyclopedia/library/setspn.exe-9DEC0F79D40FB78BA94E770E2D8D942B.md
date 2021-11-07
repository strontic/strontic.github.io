---
title: setspn.exe | Query or reset the computer's SPN attribute
excerpt: What is setspn.exe?
---

# setspn.exe 

* File Path: `C:\Windows\system32\setspn.exe`
* Description: Query or reset the computer's SPN attribute

## Hashes

Type | Hash
-- | --
MD5 | `9DEC0F79D40FB78BA94E770E2D8D942B`
SHA1 | `68A1857D6F40FD5F6CBC05D49896F71DB556B16E`
SHA256 | `3EE597FA9B3333AB491807F48AEC985C4429F975E0DABCE2AF0CCAA182628884`
SHA384 | `4521FC148B23BECA34251D704097DDB90AC3C1D5FAEAC00F07A7DE1F67F61172ADEC653FA761C9B8FC9817C4D3FB310D`
SHA512 | `23871330177E9EF9B33CAE1BE74C9A4BFA57496F879880EF7B8502422D3FF9BE6562659E1ECDBBA984BC8B0355BE10198F9C546D7B904D566CDD828802892AF1`
SSDEEP | `768:6tM372OwDBqKg2d8qxQDHpX32A0AQpL4iVI4h0q+YmF:6a372OwdI2OOa123R4iz0RYmF`
IMP | `E6B8038038B9ABF6ACB11E0A8BE9BB84`
PESHA1 | `A9C404CE14B14478355EA450716CE2E4BBF5D9F9`
PE256 | `DD16A1DCEC8291FA987A0F9B99CF7CEF3705158602FA7F8F166371A7EB0B8ACD`

## Runtime Data

### Usage (stdout):
```cmhg
Usage: C:\Windows\system32\setspn.exe [modifiers switch] [accountname] 
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

### Loaded Modules:

Path |
-- |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\system32\setspn.exe |


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: setspn.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/75
* VirusTotal Link: https://www.virustotal.com/gui/file/3ee597fa9b3333ab491807f48aec985c4429f975e0dabce2af0ccaa182628884/detection


## Possible Misuse

*The following table contains possible examples of `setspn.exe` being misused. While `setspn.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_spn_enum.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_spn_enum.yml) | `Image\|endswith: '\setspn.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [index.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Indexes-Markdown/index.md) | - Atomic Test #3: Extract all accounts in use as SPN using setspn [windows] | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [windows-index.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Indexes-Markdown/windows-index.md) | - Atomic Test #3: Extract all accounts in use as SPN using setspn [windows] | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1558.003.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1558.003/T1558.003.md) | Service principal names (SPNs) are used to uniquely identify each instance of a Windows service. To enable authentication, Kerberos requires that SPNs be associated with at least one service logon account (an account specifically tasked with running a service(Citation: Microsoft Detecting Kerberoasting Feb 2018)).(Citation: Microsoft SPN)(Citation: Microsoft SetSPN)(Citation: SANS Attacking Kerberos Nov 2014)(Citation: Harmj0y Kerberoast Nov 2016) | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1558.003.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1558.003/T1558.003.md) | - [Atomic Test #3 - Extract all accounts in use as SPN using setspn](#atomic-test-3---extract-all-accounts-in-use-as-spn-using-setspn) | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1558.003.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1558.003/T1558.003.md) | ## Atomic Test #3 - Extract all accounts in use as SPN using setspn | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1558.003.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1558.003/T1558.003.md) | The following test will utilize setspn to extract the Service Principal Names. This behavior is typically used during a kerberos or silver ticket attack.  | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1558.003.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1558.003/T1558.003.md) | setspn -T #{domain_name} -Q */* | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1558.003.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1558.003/T1558.003.md) | setspn.exe -T #{domain_name} -Q */* \| Select-String '^CN' -Context 0,1 \| % { New-Object System.IdentityModel.Tokens.KerberosRequestorSecurityToken -ArgumentList $_.Context.PostContext[0].Trim() } | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)



MIT License. Copyright (c) 2020-2021 Strontic.


