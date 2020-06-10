
# nbtstat.exe 
* File Path: `C:\Windows\system32\nbtstat.exe`
* Description: TCP/IP NetBios Information
* Comments: 

## Hashes
Type | Hash
-- | --
MD5 | `4320B5AED6DC77E8252C0D06A46FB90B`
SHA1 | `4619D719C8866DAD0AC93A9B524DD8F6262A7A53`
SHA256 | `41C05B8342ADD13AEF5F2CF291C18CF4AFF0DB4D62539C4D48F35D1AB1DB0570`
SHA384 | `515245BD68B753A2A19C07E55E0CEB7BB5BB3CCA2C7BF1AFEF047727D0DAF0ECEC2FF5D90FDC4CBD3DCBEE5AE359DA1E`
SHA415 | `5A921B0B05135E68463F3BD823F9768B94649AD4C5923A645D5A5594961D9204AA69D4A49726134CC5DFBD0B00D3B59096B1AC7DF849A1B340E81F71916AE6BA`
SSDEEP | `384:eLvvoNBKZfeaWCmfYjHCXgd2f18LXSdj28qJfsCWWrW:e7v7feaWCmfgYfmLoj3S`

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
* Serial: 33000000BCE120FDD27CC8EE930000000000BC
* Thumbprint: E85459B23C232DB3CB94C7A56D47678F58E8E51E
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: nbtinfo.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.14393.0 (rs1_release.160715-1616)
* Product Version: 10.0.14393.0
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.


