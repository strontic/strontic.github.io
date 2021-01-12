---
title: certmgr.exe | ECM Certificate Manager
excerpt: What is certmgr.exe?
---

# certmgr.exe 

* File Path: `C:\Program Files (x86)\Windows Kits\10\bin\10.0.19041.0\x86\certmgr.exe`
* Description: ECM Certificate Manager

## Hashes

Type | Hash
-- | --
MD5 | `AFC75CA9510A5A5221222EDC66342935`
SHA1 | `C7ED5066BCB574529F7E1F8D32CC55B223E3E509`
SHA256 | `AEB5C24499FAFAEACE3C8F93E6936730BC5AB17512E38E4F74164AF6868769D2`
SHA384 | `DACB9201DD4068C1C051519677DEC165B04CDB007EFFE252DC7635B22C76372832818CFF68D8F0FC7F9CFD663EE823B4`
SHA512 | `AAB3002CBB3E40820B1125D972F251C5EB7E6D12FB32CD1741D94BA78E72B925B18A8C5A71A3198BF76055B7ECA6034F2355B65F0C95BAAB1B740FC76FF0B5FD`
SSDEEP | `1536:0SVBbOaDDcxFXdf9qAhyMUBYw+WXsA9i9vYRf:0SnCdkAvUBt+WXsNYf`
IMP | `0FC82C88FCC1CB6AB4E7AB78D4291CF0`
PESHA1 | `30AD7D540D96F24446745E54305BE9F80D9F149C`
PE256 | `638621EA61E591535C213FF68C4D22E54784E7A968CDE78C30CBF02FF6E4FB40`

## Runtime Data

### Usage (stdout):
```cmhg
Usage: CertMgr [options][-s [-r <location>][SourceStoreName]
                        [-s [-r <location>][DestinationStoreName]
Options: 
 -add               Add certificates/CRLs/CTLs to a storeFile or a system store
 -del               Delete certificates/CRLs/CTLs from a storeFile or 
                    a system store
 -put               Put an encoded certificate/CRL/CTL from a storeFile or
                    a system store to a file.  The file will be saved in X.509
                    format. -7 can be used to save the file in PKCS #7 format
 -s                 Indicate the store is a system store 
 -r    <location>   The system store location 
                        <currentUser|localMachine> Default to 'currentUser' 
 -c                 Certificates in the store
 -crl               Certificates revocation lists(CRLs) in the store
 -ctl               Certificates trust lists(CTLs) in the store
 -v                 Verbose display of the certificates/CRLs/CTLs 
 -all               All certificates/CRLs/CTLs in the store
 -n    <name>       Common name of the certificate 
 -sha1 <thumbPrint> The sha1 hash of the certificate/CRLs/CTLs 
 -7                 Save the destination store in PKCS #7 format
 -e    <encode>     Certificate/CRL/CTL encoding type.  
                    Default to X509_ASN_ENCODING
 -f    <flag>       CertStore open flags.  Meaningful only if -y is set
 -y    <provider>   CertStore provider name

```

### Loaded Modules:

Path |
-- |
C:\Program Files (x86)\Windows Kits\10\bin\10.0.19041.0\x86\certmgr.exe |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\wow64.dll |
C:\Windows\System32\wow64cpu.dll |
C:\Windows\System32\wow64win.dll |


## Signature

* Status: Signature verified.
* Serial: `33000002CF6D2CC57CAA65A6D80000000002CF`
* Thumbprint: `1A221B3B4FEF088B17BA6704FD088DF192D9E0EF`
* Issuer: CN=Microsoft Code Signing PCA 2010, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Corporation, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: CERTMGR.EXE
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/73
* VirusTotal Link: https://www.virustotal.com/gui/file/aeb5c24499fafaeace3c8f93e6936730bc5ab17512e38e4f74164af6868769d2/detection

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Program Files (x86)\Windows Kits\10\bin\10.0.19041.0\arm64\certmgr.exe](certmgr.exe-B18C3F2FD9A7E9C7FC8C91BA0BE5FD89.md) | 49
[C:\Program Files (x86)\Windows Kits\10\bin\10.0.19041.0\x64\certmgr.exe](certmgr.exe-564D9F5DBD12AA4123156ED32A78F409.md) | 44




MIT License. Copyright (c) 2020 Strontic.


