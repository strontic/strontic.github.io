---
title: jarsigner.exe | OpenJDK Platform binary
---

# jarsigner.exe 

* File Path: `C:\program files\Amazon Corretto\jdk11.0.8_10\bin\jarsigner.exe`
* Description: OpenJDK Platform binary

## Hashes

Type | Hash
-- | --
MD5 | `24C345BA5B4270DD2E52E114356E9E76`
SHA1 | `AA781C178BC4841621F03C16FA46CD11A5C9692F`
SHA256 | `1975D326B94AF809AC724AAC4A2776F14A32F4642C2CE92C77E46D6EFEC0BB6B`
SHA384 | `E5546DB6FC3B158A7B9D4AC1D3E4104841E9196B0F6C5DA3D010EDF3C7D246A51BF96E77999FCFF50E5C163D3F14690F`
SHA512 | `98128A264D550831FA76082F3FBEC0C3114ED6A27D1EEC238AEE5012F2751395B3B348C312DCEBED15F0420D429CC8ED4AAAC83520072EF38D8CCEE288C98BE1`
SSDEEP | `384:O8bdNt3Sy/kBbFN6w5AUbK6jSbAH7Dgf2hO4o:luBFMw5LKgsAH7Uf2hfo`

## Runtime Data

### Usage (stdout):
```cmhg
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
                            (This option has been deprecated.)

[-altsignerpath <pathlist>] location of an alternative signing mechanism
                            (This option has been deprecated.)

[-internalsf]               include the .SF file inside the signature block

[-sectionsonly]             don't compute hash of entire manifest

[-protected]                keystore has protected authentication path

[-providerName <name>]      provider name

[-addprovider <name>        add security provider by name (e.g. SunPKCS11)
  [-providerArg <arg>]] ... configure argument for -addprovider

[-providerClass <class>     add security provider by fully-qualified class name
  [-providerArg <arg>]] ... configure argument for -providerClass

[-strict]                   treat warnings as errors

[-conf <url>]               specify a pre-configured options file

[-? -h --help]              Print this help message


```

### Usage (stderr):
```cmhg
Please specify alias name

```

### Loaded Modules:

Path |
-- |
C:\program files\Amazon Corretto\jdk11.0.8_10\bin\jarsigner.exe |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\SYSTEM32\ntdll.dll |


## Signature

* Status: Signature verified.
* Serial: `2F83C35B5136353D68CE9EB669FD1B0B`
* Thumbprint: `4BAD227329ADEF18F215B6475FB7948E1629B505`
* Issuer: CN=Symantec Class 3 SHA256 Code Signing CA, OU=Symantec Trust Network, O=Symantec Corporation, C=US
* Subject: CN=Amazon.com Services LLC, OU=Software Services, O=Amazon.com Services LLC, L=Seattle, S=Washington, C=US

## File Metadata

* Original Filename: jarsigner.exe
* Product Name: OpenJDK Platform 11
* Company Name: Amazon.com Inc.
* File Version: 11.0.8
* Product Version: 11.0.8
* Language: Language Neutral
* Legal Copyright: Copyright  2020

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\program files\AdoptOpenJDK\jdk-11.0.8.10-hotspot\bin\jarsigner.exe](jarsigner.exe-3545DF7A746A46163EA98D79A3CFAA65.md) | 44
[C:\program files\AdoptOpenJDK\jdk-11.0.8.10-hotspot\bin\jdb.exe](jdb.exe-B66DF0DC0BDF18F4A14DFC6A58F23BAB.md) | 40
[C:\program files\AdoptOpenJDK\jdk-11.0.8.10-hotspot\bin\jdeprscan.exe](jdeprscan.exe-F63BEA1831254EB65EEA19012774C7B9.md) | 38
[C:\program files\AdoptOpenJDK\jdk-11.0.8.10-hotspot\bin\jhsdb.exe](jhsdb.exe-61D7659F3C8D10C62224634404D1A91F.md) | 43
[C:\program files\AdoptOpenJDK\jdk-11.0.8.10-hotspot\bin\jshell.exe](jshell.exe-7102DE0DBB816DFE04784CDDDF0EABC9.md) | 44
[C:\program files\AdoptOpenJDK\jdk-11.0.8.10-hotspot\bin\keytool.exe](keytool.exe-F859E5BDEA1498C82945E824021AB601.md) | 38
[C:\program files\AdoptOpenJDK\jdk-11.0.8.10-hotspot\bin\pack200.exe](pack200.exe-DC5AA7BCD19D6CE293F14AE57C3082EC.md) | 40
[C:\program files\AdoptOpenJDK\jdk-11.0.8.10-hotspot\bin\rmiregistry.exe](rmiregistry.exe-6240D6F87038D7B1F32E590D20B6EB45.md) | 36
[C:\program files\AdoptOpenJDK\jdk-11.0.8.10-hotspot\bin\serialver.exe](serialver.exe-8C875F970BA9AFB45B48DF121220D535.md) | 41
[C:\program files\AdoptOpenJDK\jre-11.0.8.10-hotspot\bin\keytool.exe](keytool.exe-0EA9E813BC45594BC7B505FD193D233D.md) | 38
[C:\program files\AdoptOpenJDK\jre-11.0.8.10-hotspot\bin\pack200.exe](pack200.exe-D8F4EAC78AB739846BD1D5BBD256DBC3.md) | 40
[C:\program files\AdoptOpenJDK\jre-11.0.8.10-hotspot\bin\rmiregistry.exe](rmiregistry.exe-37B63F925D45FD055BA4A604F7E5F891.md) | 40
[C:\program files\Amazon Corretto\jdk11.0.8_10\bin\jdb.exe](jdb.exe-1AA2A866868B910E3B6E03B684B0D92A.md) | 58
[C:\program files\Amazon Corretto\jdk11.0.8_10\bin\jdeprscan.exe](jdeprscan.exe-9C38E559ACCB2282CB5E5B92FA82C016.md) | 61
[C:\program files\Amazon Corretto\jdk11.0.8_10\bin\jhsdb.exe](jhsdb.exe-913B7D99340BB598826DB8B68C19D939.md) | 60
[C:\program files\Amazon Corretto\jdk11.0.8_10\bin\jshell.exe](jshell.exe-2DBEA6AB20129B0362A8485BD5218AB4.md) | 57
[C:\program files\Amazon Corretto\jdk11.0.8_10\bin\keytool.exe](keytool.exe-6045C32AB7C9FE9F5292B494A1B2E232.md) | 61
[C:\program files\Amazon Corretto\jdk11.0.8_10\bin\pack200.exe](pack200.exe-7707DC7CCEBDF3F3EA696534A43B93F2.md) | 60
[C:\program files\Amazon Corretto\jdk11.0.8_10\bin\rmiregistry.exe](rmiregistry.exe-671083EBFFF617DF6BF54C7B3B98E748.md) | 61
[C:\program files\Amazon Corretto\jdk11.0.8_10\bin\serialver.exe](serialver.exe-3CCFF738D117AD8BC9F6817D3D323F41.md) | 66




MIT License. Copyright (c) 2020 Strontic.


