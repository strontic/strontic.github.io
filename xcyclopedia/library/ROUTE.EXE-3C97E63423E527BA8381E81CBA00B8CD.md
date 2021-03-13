---
title: ROUTE.EXE | TCP/IP Route Command
excerpt: What is ROUTE.EXE?
---

# ROUTE.EXE 

* File Path: `C:\Windows\system32\ROUTE.EXE`
* Description: TCP/IP Route Command

## Hashes

Type | Hash
-- | --
MD5 | `3C97E63423E527BA8381E81CBA00B8CD`
SHA1 | `DC9ECD7E9FF4A4675C977A418BF1BB562C34C890`
SHA256 | `B8A28AEB6345CA88B04FF3D9FADF30EACF26958C991BD8E4FB1DF12A68F60EAE`
SHA384 | `E51897911ED0AA70721420E322563436381118BE0373F5221A994CE281292A1DA23213977193B0FDBD3F29949B7744CC`
SHA512 | `E202D2202632A40423C339BE2EABD6430B3EA07A744FEF536C555A3C083A678E8E2E03B8CA95E19198CE744C33FBDFBC4DB050C6738C5837A8675BCDF203CFDD`
SSDEEP | `384:wlHC4G+lpeWcH385iN5BTP8vtAznh9M+OPH1zryxavKifGwkerFqZ9AZdyWI0W:2+ey385iB8FnHrdYkFqZ9IdM`
IMP | `95110DF86CE2E63EB457CE5860C12E57`
PESHA1 | `138E1FC81C9260B4240FE42FBBAEA75B98AB04F6`
PE256 | `D3E1C8B99695BAC527458C2A4800F973605D03B5FD1A7CD6D64A207E1E93D07D`

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
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\system32\ROUTE.EXE |


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: route.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/76
* VirusTotal Link: https://www.virustotal.com/gui/file/b8a28aeb6345ca88b04ff3d9fadf30eacf26958c991bd8e4fb1df12a68f60eae/detection





MIT License. Copyright (c) 2020-2021 Strontic.


