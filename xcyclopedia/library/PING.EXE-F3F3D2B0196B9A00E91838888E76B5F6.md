
# PING.EXE 

* File Path: `C:\WINDOWS\system32\PING.EXE`
* Description: TCP/IP Ping Command
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `F3F3D2B0196B9A00E91838888E76B5F6`
SHA1 | `565505D129A019780E351E615A29722AEF479380`
SHA256 | `E9EF80A7849F1CF02CB5FB8396FF9E270CB9006F30294A52C6490A72B373BE00`
SHA384 | `484AB07F4F7B72D8F5B53E48E044073B6580D053DCCE414A6DF78E0038B2463E57265529DBE01F52039734B0A22F7ACA`
SHA415 | `0125A85568303D6D25F77F944E5C66677AAA7EF9BF780375F9CA0177286F098C1AB1EDECDB58054BAF68B1DFC98CC7ED0DCA18A5948FB946D47E6F52CCA014D8`
SSDEEP | `384:4L97irkr1hp22PeQw78T5HfjQ1H6PE7Apsu0pFEfqmq16LQhWvWAlW:4LFfASeQw78TpY9uO0q116LQm`

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

* Original Filename: ping.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.18362.1 (WinBuild.160101.0800)
* Product Version: 10.0.18362.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.

MIT License. Copyright (c) 2020 Strontic.


