---
title: wlbs.exe | Network Load Balancing Control Utility
---

# wlbs.exe 

* File Path: `C:\Windows\system32\wlbs.exe`
* Description: Network Load Balancing Control Utility
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `B4E18FE3F877EAAB319DE6C58531569B`
SHA1 | `A043C32BFDE692EC582235E71598C6F4352D2E9A`
SHA256 | `963DA7580E555D7CC3961530D436F7DAA80A0730E3BAE7D94CDCD0D6265A6E2A`
SHA384 | `F8FF32A5D17C24084B339CFA26FCD8BD150847A38AE076C4522D7CFDCEC847B5788EED748C48613FF93E9D33FE5621AC`
SHA512 | `B603F814276AB6F65AC46FEC57CA56F2968B760E1B3DE1CBAC44306824945EB530F6356A010F34908E609D440AEACF6F4BB2AF7B19A15DD3380C66DCBA5FFBE8`
SSDEEP | `1536:NGRqS4Do2QRllMJDVcfG2O9H7Imq7oSw9s9fOT4:Pno7zMJCfRY7Imq7o/9MWT4`

## Runtime Data

### Usage (stdout):
```Batchfile
WLBS Cluster Control Utility V2.6
Usage: WLBS <command> 
<command>
  help                                  - Displays this help
  ip2mac    <cluster>                   - Displays the MAC address for the
                                          specified cluster
  reload    [<cluster> | ALL]           - Reloads the driver's parameters from
                                          the registry for the specified
                                          cluster (local only). Same as ALL if
                                          parameter is not specified.
  display   [<cluster> | ALL]           - Displays configuration parameters,
                                          current status, and last several
                                          event log messages for the specified
                                          cluster (local only). Same as ALL if
                                          parameter is not specified.
  query     [<cluster_spec>]            - Displays the current cluster state
                                          for the current members of the
                                          specified cluster.
  suspend   [<cluster_spec>]            - Suspends cluster operations (start,
                                          stop, etc.) for the specified cluster
                                          until the resume command is issued.
  resume    [<cluster_spec>]            - Resume cluster operations after a
                                          previous suspend command for the
                                          specified cluster.
  start     [<cluster_spec>]            - Start cluster operations for the
                                          specified cluster.
  stop      [<cluster_spec>]            - Stop cluster operations on the
                                          specified cluster.
  drainstop [<cluster_spec>]            - Disable all new traffic handling on
                                          the specified cluster and stops
                                          cluster operations.
  enable    <port_spec>                 - Enable traffic handling on the
            [<cluster_spec>]              specified cluster for the rule whose
                                          port range contains the specified
                                          port
  disable   <port_spec>                 - Disable ALL traffic handling on the
            [<cluster_spec>]              specified cluster for the rule whose
                                          port range contains the specified
                                          port
  drain     <port_spec>                 - Disable NEW traffic handling on the
            [<cluster_spec>]              specified cluster for the rule whose
                                          port range contains the specified
                                          port.
  queryport [<vip>: | ALL:]<port>       - Retrieve the current state of the
            [<cluster_spec>]              port rule. If no virtual IP
                                          address is specified, "ALL" is
                                          assumed. If the rule is handling
                                          traffic, packet handling statistics
                                          are also returned.
  params [<cluster> | ALL]              - Retrieve the current parameters from
                                          the NLB driver for the specified
                                          cluster on the local host.
<port_spec>
  [<vip>: | ALL:](<port> | ALL)         - Specific load balanced IP address or
                                          use "ALL" to apply to all load
                                          balanced IP addresses.
                                          Specific <port> to identify the port
                                          rule or "ALL". Valid port range:
                                          0-65535.
<cluster_spec>
  <cluster>[:<host>] [GLOBAL]           - Specific <cluster> on the local 
                                          machine, or on the remote <host>.
                                          If GLOBAL is specified, then applies
                                          to all members of the cluster.  If
                                          <cluster_spec> is not specified, then
                                          applies to all cluster instances on
                                          the local host.

<cluster>                               - Cluster name or cluster primary IP
                                          address (if address family is IPv6,
                                          IP address should be enclosed in 
                                          square brackets, as in [<cluster>]
<host>                                  - Remote host within the cluster: 
                                          dedicated name | IP address (if
                                          address family is IPv6, IP address
                                          should be enclosed in square 
                                          brackets, as in [<host>])
<vip>                                   - Virtual IP address in the port rule
                                          (if address family is IPv6, IP 
                                          address should be enclosed in square 
                                          brackets as in [<vip>])
<port>                                  - TCP/UDP port number

For detailed information, see the online help for NLB.

```

### Usage (stderr):
```Batchfile

```

### Child Processes:


## Signature

* Status: Signature verified.
* Serial: `33000001C422B2F79B793DACB20000000001C4`
* Thumbprint: `AE9C1AE54763822EEC42474983D8B635116C8452`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: WLBS.EXE.MUI
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.17763.1 (WinBuild.160101.0800)
* Product Version: 10.0.17763.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Windows\system32\nlb.exe](nlb.exe-D43A826E0086CEB0019C06C7E5967BCE.md) | 69




MIT License. Copyright (c) 2020 Strontic.


