---
title: mofcomp.exe | The Managed Object Format (MOF) Compiler 
excerpt: What is mofcomp.exe?
---

# mofcomp.exe 

* File Path: `C:\Windows\system32\wbem\mofcomp.exe`
* Description: The Managed Object Format (MOF) Compiler 

## Hashes

Type | Hash
-- | --
MD5 | `5D4918AD2054B0BA69E760BEA2F551DB`
SHA1 | `55C41854AB4096CC0526A056768E0CAB59BAEA6B`
SHA256 | `EC049A032436A2BD31491AEE3BF054AAE9D63B24282186F208D93A4CF4C946C9`
SHA384 | `B1157E620713AAF715598C3D6C4403C2460B8DF1BB23C746FE2311371D509E673925CA53779ECF51D2D135CA140CB3B4`
SHA512 | `458D2C1B2BBB28300B627D80A6358E7B6B38E28143E6193E5DFF99D647A094EC562B303B850583EFDE59A842B679EDA71475FE7D46A1E97DEFF2C7D2BCDDE710`
SSDEEP | `384:h0Muz/PafIvOMvK+bsxGrsM1tBm66loHKc0x0NvoahE/djiW1oW:g2fIvOMv4xcBGkp0x0Nvoa6/5x`
IMP | `4BDF4258DBC932662B0ABC3DFBD4A0C3`
PESHA1 | `F178DB7E50A9359BFDFE9A6A32492371DCD7EA26`
PE256 | `0965FDC4AD2F543C4BC39C55415377BDB8BD422D5C50E6EB9B7D11DE342ABFE4`

## Runtime Data

### Usage (stdout):
```cmhg
Microsoft (R) MOF Compiler Version 10.0.17763.1
Copyright (c) Microsoft Corp. 1997-2006. All rights reserved.

usage: mofcomp [-check] [-N:<Path>]
               [-class:updateonly|-class:createonly]
               [-instance:updateonly|-instance:createonly]
               [-B:<filename>] [-P:<Password>] [-U:<UserName>]
               [-A:<Authority>] [-WMI] [-AUTORECOVER]
               [-MOF:<path>] [-MFL:<path>] [-AMENDMENT:<Locale>]
               [-ER:<ResourceName>] [-L:<ResourceLocale>] 
               <MOF filename>

   -check                    Syntax check only
   -N:<path>                 Load into this namespace by default
   -class:updateonly         Do not create new classes
   -class:safeupdate         Update unless conflicts exist
   -class:forceupdate        Update resolving conflicts if possible
   -class:createonly         Do not change existing classes
   -instance:updateonly      Do not create new instances
   -instance:createonly      Do not change existing instances
   -U:<UserName>             User Name
   -P:<Password>             Login password
   -A:<Authority>            Example: NTLMDOMAIN:Domain
   -B:<destination filename> Creates a binary MOF file, does not add to DB
   -WMI                      Do Windows Driver Model (WDM) checks, requires -B switch
   -AUTORECOVER              Adds MOF to list of files compiled during DB recovery
   -Amendment:<LOCALE>       splits MOF into language neutral and specific versions
                             where locale is of the form "MS_4??"
   -MOF:<path>               name of the language neutral output
   -MFL:<path>               name of the language specific output
   -ER:<ResourceName>        extracts binary mof from named resource
   -L:<ResourceLocale>       optional specific locale number when using -ER switch

   Example c:>mofcomp -N:root\default yourmof.mof

```

### Loaded Modules:

Path |
-- |
C:\Windows\System32\bcrypt.dll |
C:\Windows\System32\bcryptPrimitives.dll |
C:\Windows\System32\clbcatq.dll |
C:\Windows\System32\combase.dll |
C:\Windows\System32\kernel.appcore.dll |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\System32\msvcp_win.dll |
C:\Windows\System32\msvcrt.dll |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\OLEAUT32.dll |
C:\Windows\System32\RPCRT4.dll |
C:\Windows\System32\sechost.dll |
C:\Windows\System32\ucrtbase.dll |
C:\Windows\system32\wbem\mofcomp.exe |
C:\Windows\system32\wbem\mofd.dll |
C:\Windows\system32\wbem\wmiutils.dll |
C:\Windows\SYSTEM32\wbemcomn.dll |
C:\Windows\System32\WS2_32.dll |


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: mofcomp.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.17763.1 (WinBuild.160101.0800)
* Product Version: 10.0.17763.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/66
* VirusTotal Link: https://www.virustotal.com/gui/file/ec049a032436a2bd31491aee3bf054aae9d63b24282186f208d93a4cf4c946c9/detection/





MIT License. Copyright (c) 2020 Strontic.


