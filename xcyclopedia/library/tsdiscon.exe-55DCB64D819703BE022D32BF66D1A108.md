
# tsdiscon.exe 

* File Path: `C:\Windows\system32\tsdiscon.exe`
* Description: Session Disconnection Utility
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `55DCB64D819703BE022D32BF66D1A108`
SHA1 | `9E654AD675965B51DED819909AF6506A2E7BBFE8`
SHA256 | `F80EDBEB4CC05669EA5E9074261504BBABFCA2370AF868AE8C7B96E7645C3B41`
SHA384 | `9CABF98023EC1DDCBAFD900363E9FAA2890AFC8778D7112BCFD3D3372C3E4CF0DCDCFA796C8008226CDF746B546F48F3`
SHA415 | `F81BD057F3889B8012B1110512EF08F7A983D838FDA6F5DEB33E9C9358B8BB180AD7A33C9A008E19B8BCB898924A6DA773CBB71977FBE54DC7ABB3AAE55DD77A`
SSDEEP | `384:xGRs3qOHWuTfRDB825sttUGnREL55rSg0Nh7CJzjjp+vcu05yKcyGMrUEePWMmWW:xGRmHzw2ynnA9DYRCFjUjwyLEeQ`

## Runtime Data

### Usage (stdout):
```Batchfile
Disconnects a Remote Desktop Services session.

TSDISCON [sessionid | sessionname] [/SERVER:servername] [/V] [/VM]

  sessionid           The ID of the session.
  sessionname         The name of the session.
  /SERVER:servername  Specifies the Remote Desktop Session Host server (default is current).
  /V                  Displays information about the actions performed.
  /VM                 Disconnects session on server or within virtual machine. The unique ID of the session needs to be specified.


```

### Usage (stderr):
```Batchfile
Invalid parameter(s)
Disconnects a Remote Desktop Services session.

TSDISCON [sessionid | sessionname] [/SERVER:servername] [/V] [/VM]

  sessionid           The ID of the session.
  sessionname         The name of the session.
  /SERVER:servername  Specifies the Remote Desktop Session Host server (default is current).
  /V                  Displays information about the actions performed.
  /VM                 Disconnects session on server or within virtual machine. The unique ID of the session needs to be specified.


```

### Child Processes:


## Signature

* Status: Signature verified.
* Serial: 33000000BCE120FDD27CC8EE930000000000BC
* Thumbprint: E85459B23C232DB3CB94C7A56D47678F58E8E51E
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: tsdiscon.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.14393.0 (rs1_release.160715-1616)
* Product Version: 10.0.14393.0
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.

MIT License. Copyright (c) 2020 Strontic.


