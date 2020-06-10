
# ipconfig.exe 
* File Path: `C:\WINDOWS\system32\ipconfig.exe`
* Description: IP Configuration Utility
* Comments: 

## Hashes
Type | Hash
-- | --
MD5 | `741462AB431A22233C787BAAB9B653C7`
SHA1 | `AEDB279E378BED6C2DB3C9DC9E12BA635E0B391C`
SHA256 | `A4370C0CF81686C0B696FA6261C9D3E0D810AE704AB8301839DFFD5D5112F476`
SHA384 | `87BF929855780EF927F0A0F4460B6135C06F111603C28D83E37FD075025A9BD43A997BDA808641E117274432AD2CF1B8`
SHA415 | `74642DB3D3A63212332D348CC06AB4F9C1478DE48559C44B17EAAECAC8DEA5B37E406E2C91BF92B6A2A4C8596D25ED6F7417860A0EA59FF26BAC1985E6BA5074`
SSDEEP | `768:4tC/CWA2ccnjnsOwu431kBmBgt+nYVb9nK:4c/ClhcPwuqk4B++YF9nK`

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

* Original Filename: ipconfig.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.18362.1 (WinBuild.160101.0800)
* Product Version: 10.0.18362.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.


