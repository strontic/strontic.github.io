
# ROUTE.EXE 

* File Path: `C:\Windows\SysWOW64\ROUTE.EXE`
* Description: TCP/IP Route Command
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `47F84BE121A0120DD6FF2CC2BDA65694`
SHA1 | `DE0E34B833F60E2E14F98B7BAA8D72A900E83A66`
SHA256 | `3BC0A2C1F62BDCC9D697685EF2ED70D083234995DFAEEBFB974FF1F1EB5D0C9A`
SHA384 | `51EF59D5CF6E124AFAE8482E26B1739A63BA36EF0A4FAA9C2DFD9A20F063A3EFA7180C4619DDE2707FDAB0D72DF8A68C`
SHA415 | `2944D1E66FB65B782A9DC6D77F277B68B6FE2AC1FD22CED28BF1DA9D1E9703EC7FE4A31A646357641F9EE229C3B2F77A8997A9169E742415768D525067011433`
SSDEEP | `384:QeFhDOFH6yH1feFvIhXh2pTOQ4qHl8ZpZCKWn0WQ7:Qx9Neyz2pygl8pZCL`

## Runtime Data

### Usage (stdout):
```Batchfile

```

### Usage (stderr):
```Batchfile

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


## Signature

* Status: Signature verified.
* Serial: 33000001733031072665B8B9B3000000000173
* Thumbprint: 14590DC5C3AAF238FCFD7785B4B93F4071402C34
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: route.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.14393.0 (rs1_release.160715-1616)
* Product Version: 10.0.14393.0
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.

MIT License. Copyright (c) 2020 Strontic.


