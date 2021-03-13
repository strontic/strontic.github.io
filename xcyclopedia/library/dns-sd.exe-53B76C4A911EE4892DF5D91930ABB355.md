---
title: dns-sd.exe | Bonjour Console Utility
excerpt: What is dns-sd.exe?
---

# dns-sd.exe 

* File Path: `C:\Windows\SysWOW64\dns-sd.exe`
* Description: Bonjour Console Utility

## Hashes

Type | Hash
-- | --
MD5 | `53B76C4A911EE4892DF5D91930ABB355`
SHA1 | `46AEF82B84F29BB54585A487033F724B1AB09BDE`
SHA256 | `04151F4DB372718A1A0B5B611F833AE94B2E74D6F46F047F6708897C6F284541`
SHA384 | `A44C445EF00F2E9CD78E901B338E7F9ACE8FD8D01BC8A50F90634FD96EB2F19118497F4220C5B459CC43EB1324AFC34B`
SHA512 | `11A62D827219A8AFEE82822C7986C6BDEBC35A738ADCE1A47ECCDF195173E82F7788471FD510D6955F02F426642807A2D3992DDA57044D95E7E15AD9E7D33842`
SSDEEP | `1536:2UpInlAVwr1BTvm2hm2qW3gY1hP7a0BDkXOgmSaQGRtIk:0z+2hmQQk7RkOgmSaQGnl`

## Runtime Data

### Usage (stderr):
```cmhg
dns-sd.exe -E                  (Enumerate recommended registration domains)
dns-sd.exe -F                      (Enumerate recommended browsing domains)
dns-sd.exe -B        <Type> <Domain>        (Browse for services instances)
dns-sd.exe -L <Name> <Type> <Domain>           (Look up a service instance)
dns-sd.exe -R <Name> <Type> <Domain> <Port> [<TXT>...] (Register a service)
dns-sd.exe -P <Name> <Type> <Domain> <Port> <Host> <IP> [<TXT>...]  (Proxy)
dns-sd.exe -Z        <Type> <Domain>   (Output results in Zone File format)
dns-sd.exe -Q <FQDN> <rrtype> <rrclass> (Generic query for any record type)
dns-sd.exe -C <FQDN> <rrtype> <rrclass>   (Query; reconfirming each result)
dns-sd.exe -X udp/tcp/udptcp <IntPort> <ExtPort> <TTL>   (NAT Port Mapping)
dns-sd.exe -G v4/v6/v4v6 <Hostname>  (Get address information for hostname)
dns-sd.exe -V    (Get version of currently running daemon / system service)
dns-sd.exe -A                      (Test Adding/Updating/Deleting a record)
dns-sd.exe -U                                  (Test updating a TXT record)
dns-sd.exe -N                             (Test adding a large NULL record)
dns-sd.exe -T                            (Test creating a large TXT record)
dns-sd.exe -M      (Test creating a registration with multiple TXT records)
dns-sd.exe -I   (Test registering and then immediately updating TXT record)
dns-sd.exe -S                 (Test multiple operations on a shared socket)

```

### Loaded Modules:

Path |
-- |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\wow64.dll |
C:\Windows\System32\wow64win.dll |
C:\Windows\SysWOW64\dns-sd.exe |


## Signature

* Status: Signature verified.
* Serial: `2B20EB3380792AB011F662C064FDB473`
* Thumbprint: `173A28539CA6DAB5AC8C3B995ABAA692F95C5FC4`
* Issuer: CN=VeriSign Class 3 Code Signing 2010 CA, OU=Terms of use at https://www.verisign.com/rpa (c)10, OU=VeriSign Trust Network, O="VeriSign, Inc.", C=US
* Subject: CN=Apple Inc., OU=Digital ID Class 3 - Microsoft Software Validation v2, O=Apple Inc., L=Cupertino, S=California, C=US

## File Metadata

* Original Filename: dns-sd.exe
* Product Name: Bonjour
* Company Name: Apple Inc.
* File Version: 3,1,0,1
* Product Version: 3,1,0,1
* Language: English (United States)
* Legal Copyright: Copyright (c) 2003-2015 Apple Inc.






MIT License. Copyright (c) 2020-2021 Strontic.


