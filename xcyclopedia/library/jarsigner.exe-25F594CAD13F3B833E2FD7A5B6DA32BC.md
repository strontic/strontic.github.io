---
title: jarsigner.exe | OpenJDK Platform binary
---

# jarsigner.exe 

* File Path: `C:\Program Files (x86)\Amazon Corretto\jdk1.8.0_265\bin\jarsigner.exe`
* Description: OpenJDK Platform binary

## Hashes

Type | Hash
-- | --
MD5 | `25F594CAD13F3B833E2FD7A5B6DA32BC`
SHA1 | `6AFE68E32796AAB584681E77A731A6B720B2188B`
SHA256 | `5731909239FE5C8282E7C74E3A27F4694D9F394A02002CD2789A230A2E2FC7DE`
SHA384 | `5FCB35E4735EA240D942CF67EAC29CFD5E9E61CABD91794BDB403D9562B6BEDBF7B6F781E45B76A8B1D19CB0BCA823D5`
SHA512 | `995458E9B022D44326D4C2A226C7EDBA57769F1059C11C64CCA5A3F1C82DB409388DE83C8B31ADD5E6F78FBF9FDB4DEA5A023404921F5497D12BA7E4E292D26C`
SSDEEP | `384:GpsM57nf9qbTBmSHhV8lHGeed4SzvGK6jSy0S2EDgf2h3u9:GpsUnfmUS/8VredJGKgpeEUf2h+9`

## Runtime Data

### Usage (stdout):
```Batchfile
Usage: jarsigner [options] jar-file alias
       jarsigner -verify [options] jar-file [alias...]

[-keystore <url>]           keystore location

[-storepass <password>]     password for keystore integrity

[-storetype <type>]         keystore type

[-keypass <password>]       password for private key (if different)

[-certchain <file>]         name of alternative certchain file

[-sigfile <file>]           name of .SF/.DSA file

[-signedjar <file>]         name of signed JAR file

[-digestalg <algorithm>]    name of digest algorithm

[-sigalg <algorithm>]       name of signature algorithm

[-verify]                   verify a signed JAR file

[-verbose[:suboptions]]     verbose output when signing/verifying.
                            suboptions can be all, grouped or summary

[-certs]                    display certificates when verbose and verifying

[-tsa <url>]                location of the Timestamping Authority

[-tsacert <alias>]          public key certificate for Timestamping Authority

[-tsapolicyid <oid>]        TSAPolicyID for Timestamping Authority

[-tsadigestalg <algorithm>] algorithm of digest data in timestamping request

[-altsigner <class>]        class name of an alternative signing mechanism

[-altsignerpath <pathlist>] location of an alternative signing mechanism

[-internalsf]               include the .SF file inside the signature block

[-sectionsonly]             don't compute hash of entire manifest

[-protected]                keystore has protected authentication path

[-providerName <name>]      provider name

[-providerClass <class>     name of cryptographic service provider's
  [-providerArg <arg>]] ... master class file and constructor argument

[-strict]                   treat warnings as errors


```

### Usage (stderr):
```Batchfile
Please specify alias name

```

## Signature

* Status: Signature verified.
* Serial: `2F83C35B5136353D68CE9EB669FD1B0B`
* Thumbprint: `4BAD227329ADEF18F215B6475FB7948E1629B505`
* Issuer: CN=Symantec Class 3 SHA256 Code Signing CA, OU=Symantec Trust Network, O=Symantec Corporation, C=US
* Subject: CN=Amazon.com Services LLC, OU=Software Services, O=Amazon.com Services LLC, L=Seattle, S=Washington, C=US

## File Metadata

* Original Filename: jarsigner.exe
* Product Name: OpenJDK Platform 8
* Company Name: Amazon.com Inc.
* File Version: 8.0.2650.1
* Product Version: 8.0.2650.1
* Language: Language Neutral
* Legal Copyright: Copyright  2020

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Program Files (x86)\Amazon Corretto\jdk1.8.0_265\bin\idlj.exe](idlj.exe-3C984B60B64012CE20E398C6A5CC8683.md) | 68
[C:\Program Files (x86)\Amazon Corretto\jdk1.8.0_265\bin\jdb.exe](jdb.exe-A84E4AB77C8F90E25B6D0C916B0D25E1.md) | 58
[C:\Program Files (x86)\Amazon Corretto\jdk1.8.0_265\bin\jps.exe](jps.exe-5AFACE3595288F9EF62F39721DEEC88C.md) | 65
[C:\Program Files (x86)\Amazon Corretto\jdk1.8.0_265\bin\ktab.exe](ktab.exe-6363AC88C034BD9BBB51F5B5B3A21B22.md) | 65
[C:\Program Files (x86)\Amazon Corretto\jdk1.8.0_265\bin\policytool.exe](policytool.exe-3A729B1278E40B9496C51829C2BF1A26.md) | 66
[C:\Program Files (x86)\Amazon Corretto\jdk1.8.0_265\bin\schemagen.exe](schemagen.exe-7E205BB6E38608FDF1EABE3C43EEE44A.md) | 69
[C:\Program Files (x86)\Amazon Corretto\jdk1.8.0_265\bin\servertool.exe](servertool.exe-482229C18D9D28C423A4B93F3A3B99C1.md) | 65
[C:\Program Files (x86)\Amazon Corretto\jdk1.8.0_265\jre\bin\ktab.exe](ktab.exe-9538260E340CF8ECFA890862796E0C5D.md) | 68
[C:\Program Files (x86)\Amazon Corretto\jdk1.8.0_265\jre\bin\policytool.exe](policytool.exe-E86C3045243C39EA196EB547BBE3C845.md) | 69
[C:\Program Files (x86)\Amazon Corretto\jdk1.8.0_265\jre\bin\servertool.exe](servertool.exe-5984FFFB2E2536E6E52FD59827AA6B7B.md) | 63
[C:\Program Files (x86)\Amazon Corretto\jre8\bin\ktab.exe](ktab.exe-AB2485516E63BA82335DA60828829563.md) | 65
[C:\Program Files (x86)\Amazon Corretto\jre8\bin\policytool.exe](policytool.exe-B3361507B9EC24799355B8C5B97505B8.md) | 69
[C:\Program Files (x86)\Amazon Corretto\jre8\bin\servertool.exe](servertool.exe-2DD6258EB5EA1F577129BAC139081CD3.md) | 65




MIT License. Copyright (c) 2020 Strontic.


