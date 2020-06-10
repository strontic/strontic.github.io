
# PING.EXE 
* File Path: `C:\WINDOWS\SysWOW64\PING.EXE`
* Description: TCP/IP Ping Command
* Comments: 

## Hashes
Type | Hash
-- | --
MD5 | `36A1F0BBF757F52C9F051C91D11DE6AA`
SHA1 | `1BA5FE277C64F780BB1307DDF73860BAE015874D`
SHA256 | `09E7534F7703B4E067455F0D83A77EFA28A04C368381C5A0456282A57E801B04`
SHA384 | `98EA48255579136BF4E34FE002995A815B310D0E8281D577C4A3299E3DDF5EFA3259B18EB657C0351B06636F3DCED961`
SHA415 | `135B9038B9017DA387850F24A0E960763F8115E9A5DDD05422BB89129FC6E296173FA18466F89A65EEA5DB621953E9CCC44ADDDE8C8BCB0F8D5E6833B5CDF093`
SSDEEP | `384:ICqLnT9yke5khypn1X5ObPcPQooZJLZbKWAlWz:IlO5khyN1a1oYJLZQE`

## Runtime Data
### Usage (stdout):
```Batchfile
Bad option -help.

Usage: ping [-t] [-a] [-n count] [-l size] [-f] [-i TTL] [-v TOS]
            [-r count] [-s count] [[-j host-list] | [-k host-list]]
            [-w timeout] [-R] [-S srcaddr] [-c compartment] [-p]
            [-4] [-6] target_name

Options:
    -t             Ping the specified host until stopped.
                   To see statistics and continue - type Control-Break;
                   To stop - type Control-C.
    -a             Resolve addresses to hostnames.
    -n count       Number of echo requests to send.
    -l size        Send buffer size.
    -f             Set Don't Fragment flag in packet (IPv4-only).
    -i TTL         Time To Live.
    -v TOS         Type Of Service (IPv4-only. This setting has been deprecated
                   and has no effect on the type of service field in the IP
                   Header).
    -r count       Record route for count hops (IPv4-only).
    -s count       Timestamp for count hops (IPv4-only).
    -j host-list   Loose source route along host-list (IPv4-only).
    -k host-list   Strict source route along host-list (IPv4-only).
    -w timeout     Timeout in milliseconds to wait for each reply.
    -R             Use routing header to test reverse route also (IPv6-only).
                   Per RFC 5095 the use of this routing header has been
                   deprecated. Some systems may drop echo requests if
                   this header is used.
    -S srcaddr     Source address to use.
    -c compartment Routing compartment identifier.
    -p             Ping a Hyper-V Network Virtualization provider address.
    -4             Force using IPv4.
    -6             Force using IPv6.


```

### Usage (stderr):
```Batchfile

```

### Child Processes:
conhost.exe

## Signature

* Status: Signature verified.
* Serial: 330000023241FB59996DCC4DFF000000000232
* Thumbprint: FF82BC38E1DA5E596DF374C53E3617F7EDA36B06
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: ping.exe
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.18362.1 (WinBuild.160101.0800)
* Product Version: 10.0.18362.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.


