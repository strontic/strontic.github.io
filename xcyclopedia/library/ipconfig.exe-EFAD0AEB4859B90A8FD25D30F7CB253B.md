
# ipconfig.exe 

* File Path: `C:\WINDOWS\SysWOW64\ipconfig.exe`
* Description: IP Configuration Utility
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `EFAD0AEB4859B90A8FD25D30F7CB253B`
SHA1 | `8AD80C59EE4D9459C112446762320DA7AE2D24F0`
SHA256 | `1803F2B06149D09D568A0D83CAB8017925ADED03047791DC92D8254DE7B2262A`
SHA384 | `0211DE8F47B172248E69EA17B9F0CEE8169D9F8C53AC7B9A234441A10B1A55CF641C3B0A0B7DDFE13C5F396763490861`
SHA415 | `69FF654BE934BDB24B8CD9859843DD6DA2E82892220226C203AC969FB5605B7F847E4815854A8E3EE628300E0F265357280D6719D84535140261DC2C50647E9E`
SSDEEP | `384:kSTbXHl9D4Yi9ntDqFHj+4Dj/UVWsP4sqLl9vjxsvXgmfqB/uNpyDi4b90RWJGWz:kMTi9dqtNjsVWsPGlRqvjyDb9X`

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
* Serial: 330000023241FB59996DCC4DFF000000000232
* Thumbprint: FF82BC38E1DA5E596DF374C53E3617F7EDA36B06
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: ipconfig.exe
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.18362.1 (WinBuild.160101.0800)
* Product Version: 10.0.18362.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.

MIT License. Copyright (c) 2020 Strontic.


