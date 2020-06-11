
# ARP.EXE 

* File Path: `C:\WINDOWS\SysWOW64\ARP.EXE`
* Description: TCP/IP Arp Command
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `1E04A5BD586C72BDC4890FF468DB350D`
SHA1 | `93AEE2545EBD6FB76BF04595CD27BA73CF652144`
SHA256 | `0EDDB0E2A49B30E99F5F435BDFF0928263350729020DF02892CEAFBA368255BB`
SHA384 | `5E4EDE38DAF9E4944057CF203E724E790FD96CD0920A92EDE05B3FF5DC6D6388396852C50D9B32EB867EE2DC8A45CA39`
SHA415 | `5CD3E606A5EE3EB183BCA94657194446B47FBC9457BE52E9DC892DEFDE1A65B7089BAA5F1F121B9D74AB8F84B81287DAE6179B5FC9798CBC5F59E510A191C23C`
SSDEEP | `384:ks0uDm3V7A3TmJsMonFaRQo2A4N66GijP25gWScmWE:kvuDmODmuzFaWo21Yij+5l8`

## Runtime Data

### Usage (stdout):
```Batchfile

Displays and modifies the IP-to-Physical address translation tables used by
address resolution protocol (ARP).

ARP -s inet_addr eth_addr [if_addr]
ARP -d inet_addr [if_addr]
ARP -a [inet_addr] [-N if_addr] [-v]

  -a            Displays current ARP entries by interrogating the current
                protocol data.  If inet_addr is specified, the IP and Physical
                addresses for only the specified computer are displayed.  If
                more than one network interface uses ARP, entries for each ARP
                table are displayed.
  -g            Same as -a.
  -v            Displays current ARP entries in verbose mode.  All invalid 
                entries and entries on the loop-back interface will be shown.
  inet_addr     Specifies an internet address.
  -N if_addr    Displays the ARP entries for the network interface specified
                by if_addr.
  -d            Deletes the host specified by inet_addr. inet_addr may be 
                wildcarded with * to delete all hosts.
  -s            Adds the host and associates the Internet address inet_addr
                with the Physical address eth_addr.  The Physical address is
                given as 6 hexadecimal bytes separated by hyphens. The entry
                is permanent.
  eth_addr      Specifies a physical address.
  if_addr       If present, this specifies the Internet address of the
                interface whose address translation table should be modified.
                If not present, the first applicable interface will be used.
Example:
  > arp -s 157.55.85.212   00-aa-00-62-c6-09  .... Adds a static entry.
  > arp -a                                    .... Displays the arp table.

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

* Original Filename: arp.exe
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.18362.1 (WinBuild.160101.0800)
* Product Version: 10.0.18362.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.

MIT License. Copyright (c) 2020 Strontic.


