
# NETSTAT.EXE 

* File Path: `C:\Windows\SysWOW64\NETSTAT.EXE`
* Description: TCP/IP Netstat Command
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `FFE367661AFCD0ED0EB8E305A436797A`
SHA1 | `79A5027CD9BA4C5BD29D5A5C5EE28C616E2F0FEA`
SHA256 | `1F07B7C0C17324AEEAD6E7105A9668976D8731414448F56AACEE49BAA01351F6`
SHA384 | `72313F7DBCE927CB9AC5FE67EFD79C6A223CBD507A5382A21A6DBFDA886B153FF90C72B5438129E9ABEF6BEFA4C3C557`
SHA415 | `C43B790C82A27F82F63963F2BB9CD5F0F985CDF034AB4CC5CAEBE1CE5BA13DE235A658D0EE4B5AA3F4C5BC1EA25163E434E4C0E8FD88B8F12C991FE089E9C525`
SSDEEP | `384:XH/8LvAy7E9FKkUpzMiMJ2D33ns3FIC/UomimtUcuVO55O6ozvAXFuy4ahYvE3G2:XHrRWkUa53Fky1u/oLsu1vEubS6`

## Runtime Data

### Usage (stdout):
```Batchfile

```

### Usage (stderr):
```Batchfile

Displays protocol statistics and current TCP/IP network connections.

NETSTAT [-a] [-b] [-e] [-f] [-n] [-o] [-p proto] [-r] [-s] [-x] [-t] [interval]

  -a            Displays all connections and listening ports.
  -b            Displays the executable involved in creating each connection or
                listening port. In some cases well-known executables host
                multiple independent components, and in these cases the
                sequence of components involved in creating the connection
                or listening port is displayed. In this case the executable
                name is in [] at the bottom, on top is the component it called,
                and so forth until TCP/IP was reached. Note that this option
                can be time-consuming and will fail unless you have sufficient
                permissions.
  -e            Displays Ethernet statistics. This may be combined with the -s
                option.
  -f            Displays Fully Qualified Domain Names (FQDN) for foreign
                addresses.
  -n            Displays addresses and port numbers in numerical form.
  -o            Displays the owning process ID associated with each connection.
  -p proto      Shows connections for the protocol specified by proto; proto
                may be any of: TCP, UDP, TCPv6, or UDPv6.  If used with the -s
                option to display per-protocol statistics, proto may be any of:
                IP, IPv6, ICMP, ICMPv6, TCP, TCPv6, UDP, or UDPv6.
  -q            Displays all connections, listening ports, and bound
                nonlistening TCP ports. Bound nonlistening ports may or may not
                be associated with an active connection.
  -r            Displays the routing table.
  -s            Displays per-protocol statistics.  By default, statistics are
                shown for IP, IPv6, ICMP, ICMPv6, TCP, TCPv6, UDP, and UDPv6;
                the -p option may be used to specify a subset of the default.
  -t            Displays the current connection offload state.
  -x            Displays NetworkDirect connections, listeners, and shared
                endpoints.
  -y            Displays the TCP connection template for all connections.
                Cannot be combined with the other options.
  interval      Redisplays selected statistics, pausing interval seconds
                between each display.  Press CTRL+C to stop redisplaying
                statistics.  If omitted, netstat will print the current
                configuration information once.


```

### Child Processes:


## Signature

* Status: Signature verified.
* Serial: 33000001733031072665B8B9B3000000000173
* Thumbprint: 14590DC5C3AAF238FCFD7785B4B93F4071402C34
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: netstat.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.14393.0 (rs1_release.160715-1616)
* Product Version: 10.0.14393.0
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.

MIT License. Copyright (c) 2020 Strontic.


