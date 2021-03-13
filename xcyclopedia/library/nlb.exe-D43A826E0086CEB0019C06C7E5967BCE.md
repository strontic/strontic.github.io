---
title: nlb.exe | Network Load Balancing Control Utility
excerpt: What is nlb.exe?
---

# nlb.exe 

* File Path: `C:\Windows\system32\nlb.exe`
* Description: Network Load Balancing Control Utility

## Hashes

Type | Hash
-- | --
MD5 | `D43A826E0086CEB0019C06C7E5967BCE`
SHA1 | `E03875C9C2830DE9A4776863218B0F433AACDECC`
SHA256 | `AA9FAD3495C8929D5AEFC3861887F604BBB56F3B797570EF3B8933AFC341E866`
SHA384 | `B28275E4115182CD78795FDBE0D5C1B06F956C80520AB72A49736C754919F734F346824E796568BF7318D3D7C00D01BC`
SHA512 | `6FBCA9BAEDDED1B8614B51A6A9D601A4C0358C19778EFF1BBC4EBD6A226AB88E1F1BFFB10EC06A048C071A51EA8DF7F8F7A61FF2D6911BDC38688A04E911B6D3`
SSDEEP | `1536:/GRqS4Do2QRllMJDVcXG22Nvz42yOoSw9sLKKOTu:Zno7zMJCXRYz42yOo/9KKvTu`

## Runtime Data

### Usage (stdout):
```cmhg
NLB Cluster Control Utility V2.6
Usage: NLB <command> 
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

## Signature

* Status: Signature verified.
* Serial: `33000001C422B2F79B793DACB20000000001C4`
* Thumbprint: `AE9C1AE54763822EEC42474983D8B635116C8452`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: NLB.EXE.MUI
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.17763.1 (WinBuild.160101.0800)
* Product Version: 10.0.17763.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.


## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Windows\system32\wlbs.exe](wlbs.exe-B4E18FE3F877EAAB319DE6C58531569B.md) | 69




MIT License. Copyright (c) 2020-2021 Strontic.


