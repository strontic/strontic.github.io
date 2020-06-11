
# PING.EXE 

* File Path: `C:\Windows\SysWOW64\PING.EXE`
* Description: TCP/IP Ping Command
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `8CA6D537FD710AC4A2E5668877345C12`
SHA1 | `9B170284524AEF2C12F712A6169948F5748CAC61`
SHA256 | `BDC34D4260925E54B84395B8167CA5D6F9C4AA2E047221C14F7736DDDEB13906`
SHA384 | `0E8877DE4563BFA8E2802D675F7373975919734D38DE0764F13330462580FDADB823A8771C8E5798183AD04C76DF0AE9`
SHA415 | `92E94FF3A18B115D509F70A1581AAD35890B53EA340E53670174F68CCC5DA5516BCD3F23FD4940D9FDA0581A4B14D2CD3B6ACCE744911AC078BF4ECCE1526B95`
SSDEEP | `384:SxaLJouSQZtCJcKChCK8g6NSdXggoC5sxQ7pXpOWalW:SxaSlKkChCNwWLelXo`

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
* Serial: 33000000BCE120FDD27CC8EE930000000000BC
* Thumbprint: E85459B23C232DB3CB94C7A56D47678F58E8E51E
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: ping.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.14393.0 (rs1_release.160715-1616)
* Product Version: 10.0.14393.0
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.

MIT License. Copyright (c) 2020 Strontic.


