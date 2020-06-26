---
title: dns-sd.exe | Bonjour Console Utility
---

# dns-sd.exe 

* File Path: `C:\Windows\system32\dns-sd.exe`
* Description: Bonjour Console Utility
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `B028C54FA794C275703BF3F3BABDC119`
SHA1 | `4F7DC4A2963A283DF429BB8C751598E415E34B00`
SHA256 | `6A27826B490457CCFECEBAF98A01325CC1CCECC81917B156AA1E566D141B520C`
SHA384 | `C50C625F60BBF04C8943BF4FF5D3E7D1FD125E376BAF14B4214338DFDB4736CA73C46EECF112FE7CB0CCAAAB5BB5DA5E`
SHA512 | `79CA9874EC2B18F70A81A46BC7580786108F329BAB287C0EE4DF30578831A90A40FDFACE604BE8D1AA8738A046F886A610C3FFADAAC48A5164FC7D6004F7CF6F`
SSDEEP | `1536:itKnTo4lhyfVgIqR/z6lFEaXYoeeTOhvU7Cupxrptx1uj9L+4gkF4QSZ:zmfVezaLKeTsvWCKbBWxF4BZ`

## Runtime Data

### Usage (stdout):
```Batchfile

```

### Usage (stderr):
```Batchfile
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

### Child Processes:


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





MIT License. Copyright (c) 2020 Strontic.


