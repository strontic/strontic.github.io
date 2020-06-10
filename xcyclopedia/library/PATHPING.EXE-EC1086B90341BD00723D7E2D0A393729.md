
# PATHPING.EXE 
* File Path: `C:\Windows\system32\PATHPING.EXE`
* Description: TCP/IP PathPing Command
* Comments: 

## Hashes
Type | Hash
-- | --
MD5 | `EC1086B90341BD00723D7E2D0A393729`
SHA1 | `FEF6B168F5C196C3AA3545460E469A24238A87B0`
SHA256 | `3B2271E94D1479D553477756DBB71B40BBBC1579AD0DAFD63E135699EE77F12E`
SHA384 | `F7DC556BBFA991CB8706CDCA76B76B945FB1C3E1F3DAA2948499A1321382A630C0FBFDAFC333C7B6FCA4ADABD9B2293C`
SHA415 | `8522DE0BCBE5FF97BE1060B40389B152D24F47EAA58B053B333F16D6CA0A2C7DC79599888EE46A6061EE59E0754924C3F53B880A45EB2A0149FE6FC49B7FF1E8`
SSDEEP | `384:cETzJAabkAHlNGtSyN8pYx9o5iqDILDh0Hg9j0jXKzN1y7WmAW:cERytSYusLD9j0jXINst`

## Runtime Data
### Usage (stdout):
```Batchfile

Usage: pathping [-g host-list] [-h maximum_hops] [-i address] [-n] 
                [-p period] [-q num_queries] [-w timeout] 
                [-4] [-6] target_name

Options:
    -g host-list     Loose source route along host-list.
    -h maximum_hops  Maximum number of hops to search for target.
    -i address       Use the specified source address. 
    -n               Do not resolve addresses to hostnames.
    -p period        Wait period milliseconds between pings.
    -q num_queries   Number of queries per hop.
    -w timeout       Wait timeout milliseconds for each reply.
    -4               Force using IPv4.
    -6               Force using IPv6.

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

* Original Filename: pathping.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.14393.0 (rs1_release.160715-1616)
* Product Version: 10.0.14393.0
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.


