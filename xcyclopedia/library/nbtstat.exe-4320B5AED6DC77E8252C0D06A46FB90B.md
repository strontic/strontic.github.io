
# nbtstat.exe 

* File Path: `C:\Windows\system32\nbtstat.exe`
* Description: TCP/IP NetBios Information
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `4320B5AED6DC77E8252C0D06A46FB90B`
SHA1 | `4619D719C8866DAD0AC93A9B524DD8F6262A7A53`
SHA256 | `41C05B8342ADD13AEF5F2CF291C18CF4AFF0DB4D62539C4D48F35D1AB1DB0570`
SHA384 | `515245BD68B753A2A19C07E55E0CEB7BB5BB3CCA2C7BF1AFEF047727D0DAF0ECEC2FF5D90FDC4CBD3DCBEE5AE359DA1E`
SHA512 | `5A921B0B05135E68463F3BD823F9768B94649AD4C5923A645D5A5594961D9204AA69D4A49726134CC5DFBD0B00D3B59096B1AC7DF849A1B340E81F71916AE6BA`
SSDEEP | `384:eLvvoNBKZfeaWCmfYjHCXgd2f18LXSdj28qJfsCWWrW:e7v7feaWCmfgYfmLoj3S`

## Runtime Data

### Usage (stdout):
```Batchfile

```

### Usage (stderr):
```Batchfile

Displays protocol statistics and current TCP/IP connections using NBT
(NetBIOS over TCP/IP).

NBTSTAT [ [-a RemoteName] [-A IP address] [-c] [-n]
        [-r] [-R] [-RR] [-s] [-S] [interval] ]

  -a   (adapter status) Lists the remote machine's name table given its name
  -A   (Adapter status) Lists the remote machine's name table given its
                        IP address.
  -c   (cache)          Lists NBT's cache of remote [machine] names and their IP addresses
  -n   (names)          Lists local NetBIOS names.
  -r   (resolved)       Lists names resolved by broadcast and via WINS
  -R   (Reload)         Purges and reloads the remote cache name table
  -S   (Sessions)       Lists sessions table with the destination IP addresses
  -s   (sessions)       Lists sessions table converting destination IP
                        addresses to computer NETBIOS names.
  -RR  (ReleaseRefresh) Sends Name Release packets to WINS and then, starts Refresh

  RemoteName   Remote host machine name.
  IP address   Dotted decimal representation of the IP address.
  interval     Redisplays selected statistics, pausing interval seconds
               between each display. Press Ctrl+C to stop redisplaying
               statistics.


```

### Child Processes:


## Signature

* Status: Signature verified.
* Serial: `33000000BCE120FDD27CC8EE930000000000BC`
* Thumbprint: `E85459B23C232DB3CB94C7A56D47678F58E8E51E`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: nbtinfo.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.14393.0 (rs1_release.160715-1616)
* Product Version: 10.0.14393.0
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.


## Additional Info

*Source: [MicrosoftDocs](https://github.com/MicrosoftDocs/windowsserverdocs) by [Microsoft](https://opensource.microsoft.com/codeofconduct/), available under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) license. Some links modified.*

---

# nbtstat

> Applies to: Windows Server (Semi-Annual Channel), Windows Server 2019, Windows Server 2016, Windows Server 2012 R2, Windows Server 2012

Displays NetBIOS over TCP/IP (NetBT) protocol statistics, NetBIOS name tables for both the local computer and remote computers, and the NetBIOS name cache. This command also allows a refresh of the NetBIOS name cache and the names registered with Windows Internet Name Service (WINS). Used without parameters, this command displays Help information.

This command is available only if the Internet Protocol (TCP/IP) protocol is installed as a component in the properties of a network adapter in Network Connections.

## Syntax

```
nbtstat [/a <remotename>] [/A <IPaddress>] [/c] [/n] [/r] [/R] [/RR] [/s] [/S] [<interval>]
```

#### Parameters

| Parameter | Description |
| --------- | ----------- |
| /a `<remotename>` | Displays the NetBIOS name table of a remote computer, where *remotename* is the NetBIOS computer name of the remote computer. The NetBIOS name table is the list of NetBIOS names that corresponds to NetBIOS applications running on that computer. |
| /A `<IPaddress>` | Displays the NetBIOS name table of a remote computer, specified by the IP address (in dotted decimal notation) of the remote computer. |
| /c | Displays the contents of the NetBIOS name cache, the table of NetBIOS names and their resolved IP addresses. |
| /n | Displays the NetBIOS name table of the local computer. The status of **registered** indicates that the name is registered either by broadcast or with a WINS server. |
| /r | Displays NetBIOS name resolution statistics. |
| /R | Purges the contents of the NetBIOS name cache and then reloads the pre-tagged entries from the **Lmhosts** file. |
| /RR | Releases and then refreshes NetBIOS names for the local computer that is registered with WINS servers. |
| /s | Displays NetBIOS client and server sessions, attempting to convert the destination IP address to a name. |
| /S | Displays NetBIOS client and server sessions, listing the remote computers by destination IP address only. |
| `<interval>` | Displays selected statistics, pausing the number of seconds specified in *interval* between each display. Press CTRL+C to stop displaying statistics. If this parameter is omitted, **nbtstat** prints the current configuration information only once. |
| /? | Displays help at the command prompt. |

#### Remarks

- The **nbtstat** command-line parameters are case-sensitive.

- The column headings generated by the **nbtstat** command, include:

    | Heading | Description |
    | ------- | ----------- |
    | Input | The number of bytes received. |
    | Output | The number of bytes sent. |
    | In/Out | Whether the connection is from the computer (outbound) or from another computer to the local computer (inbound). |
    | Life | The remaining time that a name table cache entry will live before it is purged. |
    | Local Name | The local NetBIOS name associated with the connection. |
    | Remote Host | The name or IP address associated with the remote computer. |
    | `<03>` | The last byte of a NetBIOS name converted to hexadecimal. Each NetBIOS name is 16 characters long. This last byte often has special significance because the same name might be present several times on a computer, differing only in the last byte. For example, `<20>` is a space in ASCII text. |
    | type | The type of name. A name can either be a unique name or a group name. |
    | Status | Whether the NetBIOS service on the remote computer is running (registered) or a duplicate computer name has registered the same service (Conflict). |
    | State | The state of NetBIOS connections. |

- The possible NetBIOS connection states, include:

    | State | Description |
    | ------- | ----------- |
    | Connected | A session has been established. |
    | listening | This endpoint is available for an inbound connection. |
    | Idle | This endpoint has been opened but cannot receive connections. |
    | Connecting | A session is in the connecting phase and the name-to-IP address mapping of the destination is being resolved. |
    | Accepting | An inbound session is currently being accepted and will be connected shortly. |
    | Reconnecting | A session is trying to reconnect (it failed to connect on the first attempt). |
    | Outbound | A session is in the connecting phase and the TCP connection is currently being created. |
    | Inbound | An inbound session is in the connecting phase. |
    | Disconnecting | A session is in the process of disconnecting. |
    | Disconnected | The local computer has issued a disconnect and it is waiting for confirmation from the remote system. |

### Examples

To display the NetBIOS name table of the remote computer with the NetBIOS computer name of *CORP07*, type:

```
nbtstat /a CORP07
```

To display the NetBIOS name table of the remote computer assigned the IP address of *10.0.0.99*, type:

```
nbtstat /A 10.0.0.99
```

To display the NetBIOS name table of the local computer, type:

```
nbtstat /n
```

To display the contents of the local computer NetBIOS name cache, type:

```
nbtstat /c
```

To purge the NetBIOS name cache and reload the pre-tagged entries in the local *Lmhosts* file, type:

```
nbtstat /R
```

To release the NetBIOS names registered with the WINS server and re-register them, type:

```
nbtstat /RR
```

To display NetBIOS session statistics by IP address every five seconds, type:

```
nbtstat /S 5
```

## Additional References

- [Command-Line Syntax Key](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/command-line-syntax-key.md)

---


MIT License. Copyright (c) 2020 Strontic.


