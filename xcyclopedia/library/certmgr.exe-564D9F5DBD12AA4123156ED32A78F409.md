---
title: certmgr.exe | ECM Certificate Manager
excerpt: What is certmgr.exe?
---

# certmgr.exe 

* File Path: `C:\Program Files (x86)\Windows Kits\10\bin\10.0.19041.0\x64\certmgr.exe`
* Description: ECM Certificate Manager

## Hashes

Type | Hash
-- | --
MD5 | `564D9F5DBD12AA4123156ED32A78F409`
SHA1 | `944971D62DB020E0D0FD180348F973F49A8623F0`
SHA256 | `4CE851375F7A0CD135A3148EFEA34CFDB8A9E584E9D179653A142F3640701EDD`
SHA384 | `4791F33BBD92FECD5306AE124041C8BB4ECB2B8E58AF8E75800F112DB923874EDC077A7C66DA14E3AD49C1C765E2DACA`
SHA512 | `2FCD31877141C4AEC436DE46CF24B9C4EADB8272260981A077152B1F81E3C03E4072D01DE3B0A51D3EC5910391C0DF93FEE8F6AA8C7DCD6F5AB53891BB397F50`
SSDEEP | `1536:VrgQs8OivXyUtiB8JFtY/OT5oNuRGx8UBYw+WXsA9i9vY4u2:3FfvXyUto0qeyHKUBt+WXsNI2`
IMP | `288C77221EE9A27F869B542320D273EF`
PESHA1 | `B77D7F16DFD77FBDAB303A3EC7E491E9509D8BC0`
PE256 | `D461B1DE52943920018DBACB46209ADE2F651F1ED5D0D89F568F1C5CF7E7D3AC`

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
C:\Program Files (x86)\Windows Kits\10\bin\10.0.19041.0\x64\certmgr.exe |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\SYSTEM32\ntdll.dll |


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
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: Unknown

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Program Files (x86)\Windows Kits\10\bin\10.0.19041.0\arm64\certmgr.exe](certmgr.exe-B18C3F2FD9A7E9C7FC8C91BA0BE5FD89.md) | 46
[C:\Program Files (x86)\Windows Kits\10\bin\10.0.19041.0\x86\certmgr.exe](certmgr.exe-AFC75CA9510A5A5221222EDC66342935.md) | 44




MIT License. Copyright (c) 2020-2021 Strontic.


