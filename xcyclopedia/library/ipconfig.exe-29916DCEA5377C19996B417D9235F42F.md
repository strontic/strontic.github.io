
# ipconfig.exe 
* File Path: `C:\Windows\system32\ipconfig.exe`
* Description: IP Configuration Utility
* Comments: 

## Hashes
Type | Hash
-- | --
MD5 | `29916DCEA5377C19996B417D9235F42F`
SHA1 | `A95BEAA8B81FD799DB6051A79D959908FFBDB22F`
SHA256 | `5EE3FD7CA1AC876D0DE539D469BFC333594FCA3DF9F377CC96C756D9648697F1`
SHA384 | `D5EDCDE639AFE00BE297ACFA1B96BDB292C757E9139F73647C092A01BD3C5C6410C04A0F6CCA8A0A5EC7AF08712D37A7`
SHA415 | `805C3BF8252BD90795E3D9C481686041A343BD5F805A8E16127529A3DF860AE45322C4DDD1CDD8F35E70E0FA7D1D98AF28D7B40F1F9FA711ED5B5CD149FC67B0`
SSDEEP | `768:e+7E/DIclS42UY4KN7afkCUeyBJD1eav8UyrdbK:nk1lEH+lUeyBJDhExrdW`

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
* Serial: 33000000BCE120FDD27CC8EE930000000000BC
* Thumbprint: E85459B23C232DB3CB94C7A56D47678F58E8E51E
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


