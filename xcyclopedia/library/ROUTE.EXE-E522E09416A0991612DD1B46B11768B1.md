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
MD5 | `E522E09416A0991612DD1B46B11768B1`
SHA1 | `9BEDE2EAF0B5770CFE8C05573E93FA69BB3C9A73`
SHA256 | `3EE231B69BCCACFBF961D2A8C624F4B4236EC54A239490B080D31D82B03F7C2D`
SHA384 | `434047FF2728C627A2BA4884FA990687C81783E43F4C87DC1B30EFC7FBBA1E5964725A0BBDF837CA52B1658B7D590D20`
SHA512 | `C3163A037EC491311AA2A56813B512654FC88718ECEF45A53A0C6EF6DC31D3B0ACB61A6F14721AD189F1AE27F0A46FAA1B052B8B82CFA75A064912CADAB73ADA`
SSDEEP | `384:l+IVcCyCip64J3HHXnM5eXuxEfhtzbzSqlqArF42xr90Tn5acke7FqO3qWj0W:0CF2hXnM5eXxJslAr7P0NYcFqO3/`
IMP | `95110DF86CE2E63EB457CE5860C12E57`
PESHA1 | `6FE7166E972C41D1C612E9B0F2C62FB2F0426668`
PE256 | `172B931B2311E3609DF256C804A0E058F37D0B222154E15B5AE3E94796D39AB1`

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

### Child Processes:
RdpSa.exe

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
* File Version: 10.0.17763.1 (WinBuild.160101.0800)
* Product Version: 10.0.17763.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/71
* VirusTotal Link: https://www.virustotal.com/gui/file/3ee231b69bccacfbf961d2a8c624f4b4236ec54a239490b080d31d82b03f7c2d/detection/





MIT License. Copyright (c) 2020-2021 Strontic.


