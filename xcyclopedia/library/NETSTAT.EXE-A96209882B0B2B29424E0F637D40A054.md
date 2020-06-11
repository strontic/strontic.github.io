
# NETSTAT.EXE 

* File Path: `C:\Windows\system32\NETSTAT.EXE`
* Description: TCP/IP Netstat Command
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `A96209882B0B2B29424E0F637D40A054`
SHA1 | `DDF26C79F8F35E6B24514691903C1E76B5284C6F`
SHA256 | `9F070E1F4AA9AE0A5EA084FEBBD5983293E5748D0A5CC5D46098CB9271D2D508`
SHA384 | `B39DB56EF87790684F0ABC87B8452CF618CBAC8AC59E63E694200ACECF021C1BDB0E641960205045D165A722345851FD`
SHA415 | `F12A33D18E737A27509E5C2074F5ABAC745D4F10C331DBB021B399AB7B0D57BC0669451B4A547D37775DEFEC8AFEE13D17AD4DE8B8639944ADCAF7843B5E23D3`
SSDEEP | `768:yyy7240Mf3csNXGEPJfHepZsRupU6OlSfp9TW79T1Obn:a0YJ9PZHepuZ6kSfp9T69TYbn`

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


