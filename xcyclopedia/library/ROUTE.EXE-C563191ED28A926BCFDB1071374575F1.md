---
title: ROUTE.EXE | TCP/IP Route Command
excerpt: What is ROUTE.EXE?
---

# ROUTE.EXE 

* File Path: `C:\Windows\SysWOW64\ROUTE.EXE`
* Description: TCP/IP Route Command

## Hashes

Type | Hash
-- | --
MD5 | `C563191ED28A926BCFDB1071374575F1`
SHA1 | `D835E16660647CF2EFF6D006E5E5AF22756AA30D`
SHA256 | `3EEB168F75126E2DC62746E5231399E9B0F71E8B910195931189DDFC5EDF88C6`
SHA384 | `78B672C878D620F3DCD1AD394A4E106481D39DF3DEAD8F40BDBFBF8E3A1212938030317DD409963685A59EC88DFBA70E`
SHA512 | `F4DB8AE1EA3757ADD3365AE8B54DF8996CC6598D913945B886980814F37EB6159C6F13271F2C4A9BB813F3371DE61FF9B504F21CC1BB0C97DED5041C68811C41`
SSDEEP | `384:8h2JsK2FQCOwb2eorV3wtCGLJfF8HlE+Fq2K6WI0W8E:8htGJvv6tCAKlfFq2KUb`
IMP | `BB55D8CE15016A967F7AAA263ECB6116`
PESHA1 | `0B5666DDCD7A47619D27D2F00A179295BA5823E9`
PE256 | `9E9EBE933604DC1AFE1742DB61963FDAA9001908EAFB31A8AAC15283AE05EB4F`

## Runtime Data

### Usage (stderr):
```cmhg

Manipulates network routing tables.

ROUTE [-f] [-p] [-4|-6] command [destination]
                  [MASK netmask]  [gateway] [METRIC metric]  [IF interface]

  -f           Clears the routing tables of all gateway entries.  If this is
               used in conjunction with one of the commands, the tables are
               cleared prior to running the command.
               
  -p           When used with the ADD command, makes a route persistent across
               boots of the system. By default, routes are not preserved
               when the system is restarted. Ignored for all other commands, 
               which always affect the appropriate persistent routes.
               
  -4	       Force using IPv4.

  -6           Force using IPv6. 
  
  command      One of these:
                 PRINT     Prints  a route
                 ADD       Adds    a route
                 DELETE    Deletes a route
                 CHANGE    Modifies an existing route	
  destination  Specifies the host.
  MASK         Specifies that the next parameter is the 'netmask' value.
  netmask      Specifies a subnet mask value for this route entry.
               If not specified, it defaults to 255.255.255.255.
  gateway      Specifies gateway.
  interface    the interface number for the specified route.
  METRIC       specifies the metric, ie. cost for the destination.

All symbolic names used for destination are looked up in the network database
file NETWORKS. The symbolic names for gateway are looked up in the host name
database file HOSTS.

If the command is PRINT or DELETE. Destination or gateway can be a wildcard,
(wildcard is specified as a star '*'), or the gateway argument may be omitted.

If Dest contains a * or ?, it is treated as a shell pattern, and only
matching destination routes are printed. The '*' matches any string,
and '?' matches any one char. Examples: 157.*.1, 157.*, 127.*, *224*.

Pattern match is only allowed in PRINT command.
Diagnostic Notes:
    Invalid MASK generates an error, that is when (DEST & MASK) != DEST.
    Example> route ADD 157.0.0.0 MASK 155.0.0.0 157.55.80.1 IF 1
             The route addition failed: The specified mask parameter is invalid. (Destination & Mask) != Destination.

Examples:

    > route PRINT
    > route PRINT -4
    > route PRINT -6
    > route PRINT 157*          .... Only prints those matching 157*
	
    > route ADD 157.0.0.0 MASK 255.0.0.0  157.55.80.1 METRIC 3 IF 2
             destination^      ^mask      ^gateway     metric^    ^
                                                         Interface^
      If IF is not given, it tries to find the best interface for a given 
      gateway.
    > route ADD 3ffe::/32 3ffe::1
    
    > route CHANGE 157.0.0.0 MASK 255.0.0.0 157.55.80.5 METRIC 2 IF 2
    
      CHANGE is used to modify gateway and/or metric only.
    
    > route DELETE 157.0.0.0
    > route DELETE 3ffe::/32

```

### Loaded Modules:

Path |
-- |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\wow64.dll |
C:\Windows\System32\wow64cpu.dll |
C:\Windows\System32\wow64win.dll |
C:\Windows\SysWOW64\ROUTE.EXE |


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: route.exe
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/76
* VirusTotal Link: https://www.virustotal.com/gui/file/3eeb168f75126e2dc62746e5231399e9b0f71e8b910195931189ddfc5edf88c6/detection





MIT License. Copyright (c) 2020-2021 Strontic.


