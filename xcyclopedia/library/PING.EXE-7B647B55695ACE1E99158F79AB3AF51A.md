
# PING.EXE 
* File Path: `C:\Windows\system32\PING.EXE`
* Description: TCP/IP Ping Command
* Comments: 

## Hashes
Type | Hash
-- | --
MD5 | `7B647B55695ACE1E99158F79AB3AF51A`
SHA1 | `57CC695F7FFA71A5970DDAB9A8656DDEC78E795A`
SHA256 | `ED7FA5B3CCBDD31A9E83F7C59F78AB5E2C83C7FEEDCC5F8B95948D11EBD7FF34`
SHA384 | `181690CEFD9E89C091067B01793D47615F56B8C17286AFB05F22EDD658CA45F9956D7024C32F96901AC9D7D7B73ABADE`
SHA415 | `D514F4FE5EFD0136BFBC834E7EFFD4F8351558B8C41C13A16162F0CEAD111853A254B8511CB490C8CEECA2482A214D4FD5669E9F4576ED921890740F3E4932A0`
SSDEEP | `384:iFnrwG6oyRxaMMJVyR3juVSEwpQ2DGrGHggpv/JOys4WalW:iONcMMJVyRqU6riH9F/Jn`

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


