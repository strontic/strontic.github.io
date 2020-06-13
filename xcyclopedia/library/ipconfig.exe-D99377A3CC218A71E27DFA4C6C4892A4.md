
# ipconfig.exe 

* File Path: `C:\Windows\SysWOW64\ipconfig.exe`
* Description: IP Configuration Utility
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `D99377A3CC218A71E27DFA4C6C4892A4`
SHA1 | `7CFEC219D13AB5F4CF526FC159BBCB1656E11DD4`
SHA256 | `5F2FF9DFA80DCBAE0301500B50F5BB10DDA257BE9C061B3CFCC9BA3C1FBC8891`
SHA384 | `3CF84143A586F18DFCC568742A8236A6FA1FA4E3EB78EB7F289549D4F87A5DF2DC0542E3A2D23BEBDB37B01227F63989`
SHA512 | `5D98555E5E9DAB7895E1AE53FB0301672CFAE96EFEAB8DE50A4F5496FBBC69DAB20C233CE9568CA8CA316ABA62C9FE8B4C1D1B4D609D234A595D11E1834C3B46`
SSDEEP | `768://oPP271WqFL6RPh6sl1GRliZz0ZdQGde:H4P2ZPFePhRl1GGAZdQGd`

## Runtime Data

### Usage (stdout):
```Batchfile

Error: unrecognized or incomplete command line.

USAGE:
    ipconfig [/allcompartments] [/? | /all | 
                                 /renew [adapter] | /release [adapter] |
                                 /renew6 [adapter] | /release6 [adapter] |
                                 /flushdns | /displaydns | /registerdns |
                                 /showclassid adapter |
                                 /setclassid adapter [classid] |
                                 /showclassid6 adapter |
                                 /setclassid6 adapter [classid] ]

where
    adapter             Connection name 
                       (wildcard characters * and ? allowed, see examples)

    Options:
       /?               Display this help message
       /all             Display full configuration information.
       /release         Release the IPv4 address for the specified adapter.
       /release6        Release the IPv6 address for the specified adapter.
       /renew           Renew the IPv4 address for the specified adapter.
       /renew6          Renew the IPv6 address for the specified adapter.
       /flushdns        Purges the DNS Resolver cache.
       /registerdns     Refreshes all DHCP leases and re-registers DNS names
       /displaydns      Display the contents of the DNS Resolver Cache.
       /showclassid     Displays all the dhcp class IDs allowed for adapter.
       /setclassid      Modifies the dhcp class id.  
       /showclassid6    Displays all the IPv6 DHCP class IDs allowed for adapter.
       /setclassid6     Modifies the IPv6 DHCP class id.


The default is to display only the IP address, subnet mask and
default gateway for each adapter bound to TCP/IP.

For Release and Renew, if no adapter name is specified, then the IP address
leases for all adapters bound to TCP/IP will be released or renewed.

For Setclassid and Setclassid6, if no ClassId is specified, then the ClassId is removed.

Examples:
    > ipconfig                       ... Show information
    > ipconfig /all                  ... Show detailed information
    > ipconfig /renew                ... renew all adapters
    > ipconfig /renew EL*            ... renew any connection that has its 
                                         name starting with EL
    > ipconfig /release *Con*        ... release all matching connections,
                                         eg. "Wired Ethernet Connection 1" or
                                             "Wired Ethernet Connection 2"
    > ipconfig /allcompartments      ... Show information about all 
                                         compartments
    > ipconfig /allcompartments /all ... Show detailed information about all
                                         compartments

```

### Usage (stderr):
```Batchfile

```

### Child Processes:


## Signature

* Status: Signature verified.
* Serial: `33000000BCE120FDD27CC8EE930000000000BC`
* Thumbprint: `E85459B23C232DB3CB94C7A56D47678F58E8E51E`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: ipconfig.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.14393.0 (rs1_release.160715-1616)
* Product Version: 10.0.14393.0
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.


## Additional Info

*Source: [MicrosoftDocs](https://github.com/MicrosoftDocs/windowsserverdocs) by [Microsoft](https://opensource.microsoft.com/codeofconduct/), available under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) license. Some links modified.*

---

# ipconfig

Displays all current TCP/IP network configuration values and refreshes Dynamic Host Configuration Protocol (DHCP) and Domain Name System (DNS) settings. Used without parameters, **ipconfig** displays Internet Protocol version 4 (IPv4) and IPv6 addresses, subnet mask, and default gateway for all adapters.

## Syntax

```
ipconfig [/allcompartments] [/all] [/renew [<adapter>]] [/release [<adapter>]] [/renew6[<adapter>]] [/release6 [<adapter>]] [/flushdns] [/displaydns] [/registerdns] [/showclassid <adapter>] [/setclassid <adapter> [<classID>]]
```

### Parameters

| Parameter | Description |
| --------- | ----------- |
| /all | Displays the full TCP/IP configuration for all adapters. Adapters can represent physical interfaces, such as installed network adapters, or logical interfaces, such as dial-up connections. |
| /displaydns | Displays the contents of the DNS client resolver cache, which includes both entries preloaded from the local Hosts file and any recently obtained resource records for name queries resolved by the computer. The DNS Client service uses this information to resolve frequently queried names quickly, before querying its configured DNS servers. |
| /flushdns | Flushes and resets the contents of the DNS client resolver cache. During DNS troubleshooting, you can use this procedure to discard negative cache entries from the cache, as well as any other entries that have been added dynamically. |
| /registerdns | Initiates manual dynamic registration for the DNS names and IP addresses that are configured at a computer. You can use this parameter to troubleshoot a failed DNS name registration or resolve a dynamic update problem between a client and the DNS server without rebooting the client computer. The DNS settings in the advanced properties of the TCP/IP protocol determine which names are registered in DNS. |
| /release `[<adapter>]` | Sends a DHCPRELEASE message to the DHCP server to release the current DHCP configuration and discard the IP address configuration for either all adapters (if an adapter is not specified) or for a specific adapter if the *adapter* parameter is included. This parameter disables TCP/IP for adapters configured to obtain an IP address automatically. To specify an adapter name, type the adapter name that appears when you use **ipconfig** without parameters. |
| /release6`[<adapter>]` | Sends a DHCPRELEASE message to the DHCPv6 server to release the current DHCP configuration and discard the IPv6 address configuration for either all adapters (if an adapter is not specified) or for a specific adapter if the *adapter* parameter is included. This parameter disables TCP/IP for adapters configured to obtain an IP address automatically. To specify an adapter name, type the adapter name that appears when you use **ipconfig** without parameters. |
| /renew `[<adapter>]` | Renews DHCP configuration for all adapters (if an adapter is not specified) or for a specific adapter if the *adapter* parameter is included. This parameter is available only on computers with adapters that are configured to obtain an IP address automatically. To specify an adapter name, type the adapter name that appears when you use **ipconfig** without parameters. |
| /renew6 `[<adapter>]` | Renews DHCPv6 configuration for all adapters (if an adapter is not specified) or for a specific adapter if the *adapter* parameter is included. This parameter is available only on computers with adapters that are configured to obtain an IPv6 address automatically. To specify an adapter name, type the adapter name that appears when you use **ipconfig** without parameters. |
| /setclassid `<adapter>[<classID>]` | Configures the DHCP class ID for a specified adapter. To set the DHCP class ID for all adapters, use the asterisk (**&#42;**) wildcard character in place of *adapter*. This parameter is available only on computers with adapters that are configured to obtain an IP address automatically. If a DHCP class ID is not specified, the current class ID is removed. |
| /showclassid `<adapter>` | Displays the DHCP class ID for a specified adapter. To see the DHCP class ID for all adapters, use the asterisk (**&#42;**) wildcard character in place of *adapter*. This parameter is available only on computers with adapters that are configured to obtain an IP address automatically. |
| /? | Displays Help at the command prompt. |

#### Remarks

- This command is most useful on computers that are configured to obtain an IP address automatically. This enables users to determine which TCP/IP configuration values have been configured by DHCP, Automatic Private IP Addressing (APIPA), or an alternate configuration.

- If the name you supply for *adapter* contains any spaces, use quotation marks around the adapter name (for example, "adapter name").

- For adapter names, **ipconfig** supports the use of the asterisk (*) wildcard character to specify either adapters with names that begin with a specified string or adapters with names that contain a specified string. For example, `Local*` matches all adapters that start with the string Local and `*Con*` matches all adapters that contain the string Con.

### Examples

To display the basic TCP/IP configuration for all adapters, type:

```
ipconfig
```

To display the full TCP/IP configuration for all adapters, type:

```
ipconfig /all
```

To renew a DHCP-assigned IP address configuration for only the Local Area Connection adapter, type:

```
ipconfig /renew Local Area Connection
```

To flush the DNS resolver cache when troubleshooting DNS name resolution problems, type:

```
ipconfig /flushdns
```

To display the DHCP class ID for all adapters with names that start with Local, type:

```
ipconfig /showclassid Local*
```

To set the DHCP class ID for the Local Area Connection adapter to TEST, type:

```
ipconfig /setclassid Local Area Connection TEST
```

## Additional References

- [Command-Line Syntax Key](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/command-line-syntax-key.md)

---


MIT License. Copyright (c) 2020 Strontic.


