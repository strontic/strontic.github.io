
# NETSTAT.EXE 
* File Path: `C:\WINDOWS\system32\NETSTAT.EXE`
* Description: TCP/IP Netstat Command
* Comments: 

## Hashes
Type | Hash
-- | --
MD5 | `2445DECE99DEEDBD701DC6DFE10E648E`
SHA1 | `BFFF6FBFD1021A0AE4A6123414FCB021E2C62EDE`
SHA256 | `5A780D6630639FFB7FD3D295C182EAA2A7CAD2C70248C5BA8F334BB3803353CA`
SHA384 | `6D7F8D9B806A4706949C11B08B0E71FC467272FB0BA73E38B4367F9D715A25B21353CC5BE7DDEDCAF4DB3768343B7418`
SHA415 | `5815BEA5548B47515CE4DF76B1CD9618F71A8307AAFC7E79FB66398BBD60DDABDA43A7EEE74D1AC30EB9F0F3342B478250886E02F094259964B6B0415F5AA623`
SSDEEP | `768:KCypZ5fjx6DnzLknmAWAhRZpU6OqPN5ZDQgdiyxuC:RnemAWAhy63l5Z0wiyxuC`

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
* Serial: 330000023241FB59996DCC4DFF000000000232
* Thumbprint: FF82BC38E1DA5E596DF374C53E3617F7EDA36B06
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: netstat.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.18362.1 (WinBuild.160101.0800)
* Product Version: 10.0.18362.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.


