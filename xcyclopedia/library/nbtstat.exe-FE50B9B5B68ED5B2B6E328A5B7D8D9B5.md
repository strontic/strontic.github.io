
# nbtstat.exe 

* File Path: `C:\WINDOWS\system32\nbtstat.exe`
* Description: TCP/IP NetBios Information
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `FE50B9B5B68ED5B2B6E328A5B7D8D9B5`
SHA1 | `5AA269F216EC8B4DB21B534347565F0AFBAD2CA0`
SHA256 | `40ABBD7EBDB3CD6FA60E9AF4A584E99D7295DD10D97FECCFEAF5183F5A943C54`
SHA384 | `8376751B6C39755AB318CDCE7A11FECDAD318FDDEFA6192BDE7C3172B3CE38F724379CA7875E298C66C167B6D29183C0`
SHA415 | `F842778706CC220EAC7794264D89E6A39C171B18B5FC7B8417124AEE2C2F8946B89762FF21C09A61BB12CA319AF99310BB05B1CB4DAFC3AB423F5A9FA4E07632`
SSDEEP | `384:KCZSVzL69ZiDYYv2L9Q9RlS9ptktI7J8WUrW:K2SFOPiMYUyPT9`

## Runtime Data

### Usage (stdout):
```Batchfile

```

### Usage (stderr):
```Batchfile

Displays protocol statistics and current TCP/IP connections using NBT
(NetBIOS over TCP/IP).

NBTSTAT [ [-a RemoteName] [-A IP address] [-c] [-n]
        [-r] [-R] [-RR] [-s] [-S] [interval] ]

  -a   (adapter status) Lists the remote machine's name table given its name
  -A   (Adapter status) Lists the remote machine's name table given its
                        IP address.
  -c   (cache)          Lists NBT's cache of remote [machine] names and their IP addresses
  -n   (names)          Lists local NetBIOS names.
  -r   (resolved)       Lists names resolved by broadcast and via WINS
  -R   (Reload)         Purges and reloads the remote cache name table
  -S   (Sessions)       Lists sessions table with the destination IP addresses
  -s   (sessions)       Lists sessions table converting destination IP
                        addresses to computer NETBIOS names.
  -RR  (ReleaseRefresh) Sends Name Release packets to WINS and then, starts Refresh

  RemoteName   Remote host machine name.
  IP address   Dotted decimal representation of the IP address.
  interval     Redisplays selected statistics, pausing interval seconds
               between each display. Press Ctrl+C to stop redisplaying
               statistics.


```

### Child Processes:


## Signature

* Status: Signature verified.
* Serial: 330000023241FB59996DCC4DFF000000000232
* Thumbprint: FF82BC38E1DA5E596DF374C53E3617F7EDA36B06
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: nbtinfo.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.18362.1 (WinBuild.160101.0800)
* Product Version: 10.0.18362.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.

MIT License. Copyright (c) 2020 Strontic.


