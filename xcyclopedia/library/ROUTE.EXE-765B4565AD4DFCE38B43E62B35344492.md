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
MD5 | `765B4565AD4DFCE38B43E62B35344492`
SHA1 | `4E867649592AA1DF6ABCC93760DD332AA8D87B0C`
SHA256 | `CCDCC49B612BD8C3C5075BF760B2E49DDA20A23A16E156EC3955DD349BCB5805`
SHA384 | `7D7F1203FA90C08AAC0C6BA0D44D94D66EE86E8379252C7D102D96676EB1A9E5E96B287F1661A2CC5C0ED712FC1DDF36`
SHA512 | `0825A20C975C62E455D126EF9BFB97164F9ED641C5EB0CCAD4D5BC014A51FF002AD2C15D03420AD2ED9261EB641974397068452350B064E99F42B7D706B52054`
SSDEEP | `384:oJCBVc4YeJwV2f/1Cv3wkzb7lQl8HlEeFqBKyWj0WC3:oJQbJZ34IkzIKlnFqBKXo3`
IMP | `BB55D8CE15016A967F7AAA263ECB6116`
PESHA1 | `56BD8748C2CC29E217C951E5F1873E6BBACAAF1D`
PE256 | `5A37BAA8A7958937A6AB88DE67F5D0C7B457667A6764E80A7FB4B324961FCC29`

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
* File Version: 10.0.17763.1 (WinBuild.160101.0800)
* Product Version: 10.0.17763.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/68
* VirusTotal Link: https://www.virustotal.com/gui/file/ccdcc49b612bd8c3c5075bf760b2e49dda20a23a16e156ec3955dd349bcb5805/detection/





MIT License. Copyright (c) 2020-2021 Strontic.


