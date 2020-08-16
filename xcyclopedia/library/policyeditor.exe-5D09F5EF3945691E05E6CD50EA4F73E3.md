---
title: policyeditor.exe | 
---

# policyeditor.exe 

* File Path: `C:\Program Files\AdoptOpenJDK\jdk-8.0.265.01-hotspot\bin\policyeditor.exe`

## Hashes

Type | Hash
-- | --
MD5 | `5D09F5EF3945691E05E6CD50EA4F73E3`
SHA1 | `B80288AC820BC34DCA0771CB2E04FEF4F7239D4E`
SHA256 | `BDD85F7FA9A0170B6C31AEC83369B4765587812E13391BE5222BDF514D8BB158`
SHA384 | `9F13F7800E09BA98C6277046BEEED0A6960F4A4CDA03138FC7D59C5385E8AC97A1056ECD80204AEF75B56732880F796C`
SHA512 | `1F8A59692E560F2A6BC05FC638A31BAC6D549CD2EEFF41E3A5F7EB7233DE78687E2A40209F38D429BBDB17E3647F5BE1296A603CEB7722725823E0275E50CFC4`
SSDEEP | `6144:otB159jXJC0wYv+9Aeoym9TuKVEUVKC8i4KpO4JQz:otr59jXJC0wYvWA1lR2IYifpyz`

## Runtime Data

### Usage (stdout):
```Batchfile
selected jre: C:\Program Files\Amazon Corretto\jdk11.0.8_10

SYNOPSIS
    policyeditor
    policyeditor [-file] policy_file

OPTIONS
    -codebase url                         - Specifies an applet codebase URL. This can be used with the other selector options to select a policy entry upon opening the editor; if no such identifier exists then it will be created and then selected.(Exactly one argument expected)
    -defaultfile                          - Specifies that the default user-level policy file should be opened. This is the file which is normally used by IcedTea-Web to make decisions about custom policies and permissions for applets at runtime, unless configured otherwise.(No argument expected)
    -file policy_file                     - Specifies a policy file path to open. If exactly one argument is given, and it is not this flag, it is interpreted as a file path to open, as if this flag was given first. This flag exists mostly for compatibility with Policy Tool.(Exactly one argument expected)
    -help                                 - Prints out information about supported command and basic usage.(No argument expected)
    -principals class_name principal_name - Specifies class name/principal name pairs (space-separated) for the policy entry identifier. This can be used with the other selector options to select a policy entry upon opening the editor; if no such identifier exists then it will be created and then selected.(Expected even number of arguments with param=value as valid argument)
    -signedby certificate_alias           - Specifies a certificate alias for a certificate stored in the keystore. This can be used with the other selector options to select a policy entry upon opening the editor; if no such identifier exists then it will be created and then selected.(Exactly one argument expected)
    -verbose                              - Enable verbose output.(No argument expected)


```

### Usage (stderr):
```Batchfile
WARNING: package javax.jnlp not in java.desktop
WARNING: package sun.awt.X11 not in java.desktop

```

### Child Processes:
java.exe

## Signature

* Status: Signature verified.
* Serial: `0F8CE162B26B70AE59D17A0B2A93AB3A`
* Thumbprint: `0180ED75D6615415E4D6C6C217613B4134F5745E`
* Issuer: CN=DigiCert SHA2 Assured ID Code Signing CA, OU=www.digicert.com, O=DigiCert Inc, C=US
* Subject: CN=London Jamocha Community CIC, O=London Jamocha Community CIC, L=London, C=GB

## File Metadata

* Original Filename: 
* Product Name: 
* Company Name: 
* File Version: 
* Product Version: 
* Language: 
* Legal Copyright: 

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Program Files\AdoptOpenJDK\jre-8.0.265.01-hotspot\bin\policyeditor.exe](policyeditor.exe-5D09F5EF3945691E05E6CD50EA4F73E3.md) | 100




MIT License. Copyright (c) 2020 Strontic.


