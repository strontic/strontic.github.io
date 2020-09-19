---
title: ktab.exe | OpenJDK Platform binary
---

# ktab.exe 

* File Path: `C:\program files (x86)\Amazon Corretto\jdk1.8.0_265\jre\bin\ktab.exe`
* Description: OpenJDK Platform binary

## Hashes

Type | Hash
-- | --
MD5 | `9538260E340CF8ECFA890862796E0C5D`
SHA1 | `D92F584ED0FF9B7C011D8A7EC40D5089CCA92045`
SHA256 | `ADAE3035CB54D9413E7EB1E777A6DD4A406848AD86D8BCCDFC7166EE94D1082B`
SHA384 | `EB71215D298A0651AFA6BC90BC2BFE21AE05A8A8C47EFEE396E9DBF17037A89829304EB25E4F56D93EA40F8B07B39367`
SHA512 | `BB10A9B35466C02BA65CF7E712BCF8BE73E1A212FB244BDBF408EACB780696888D5247A74C377BF63279061D66A8FF0F59F74D60C58B539D5DB7EEA7431366F5`
SSDEEP | `384:Gpsx5hnCq+mSHhV8laeeo4SzHK6jSEdDgf2hd:GpshnTS/8lHeo9KgdUf2hd`

## Runtime Data

### Usage (stdout):
```cmhg
Error: Useless extra argument help.

Usage: ktab <commands> <options>

Available commands:

-l [-e] [-t]
    list the keytab name and entries. -e with etype, -t with timestamp.
-a <principal name> [<password>] [-n <kvno>] [-append]
    add new key entries to the keytab for the given principal name with
    optional <password>. If a <kvno> is specified, new keys' Key Version
    Numbers equal to the value, otherwise, automatically incrementing
    the Key Version Numbers. If -append is specified, new keys are
    appended to the keytab, otherwise, old keys for the
    same principal are removed.
-d <principal name> [-f] [-e <etype>] [<kvno> | all | old]
    delete key entries from the keytab for the specified principal. If
    <kvno> is specified, delete keys whose Key Version Numbers match
    kvno. If "all" is specified, delete all keys. If "old" is specified,
    delete all keys except those with the highest kvno. Default action
    is "all". If <etype> is specified, only keys of this encryption type
    are deleted. <etype> should be specified as the numberic value etype
    defined in RFC 3961, section 8. A prompt to confirm the deletion is
    displayed unless -f is specified.

Common option(s):

-k <keytab name>
    specify keytab name and path with prefix FILE:

```

### Loaded Modules:

Path |
-- |
C:\program files (x86)\Amazon Corretto\jdk1.8.0_265\jre\bin\ktab.exe |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\wow64.dll |
C:\Windows\System32\wow64win.dll |


## Signature

* Status: Signature verified.
* Serial: `2F83C35B5136353D68CE9EB669FD1B0B`
* Thumbprint: `4BAD227329ADEF18F215B6475FB7948E1629B505`
* Issuer: CN=Symantec Class 3 SHA256 Code Signing CA, OU=Symantec Trust Network, O=Symantec Corporation, C=US
* Subject: CN=Amazon.com Services LLC, OU=Software Services, O=Amazon.com Services LLC, L=Seattle, S=Washington, C=US

## File Metadata

* Original Filename: ktab.exe
* Product Name: OpenJDK Platform 8
* Company Name: Amazon.com Inc.
* File Version: 8.0.2650.1
* Product Version: 8.0.2650.1
* Language: Language Neutral
* Legal Copyright: Copyright  2020

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\program files (x86)\Amazon Corretto\jdk1.8.0_265\bin\jarsigner.exe](jarsigner.exe-25F594CAD13F3B833E2FD7A5B6DA32BC.md) | 68
[C:\program files (x86)\Amazon Corretto\jdk1.8.0_265\bin\ktab.exe](ktab.exe-6363AC88C034BD9BBB51F5B5B3A21B22.md) | 90
[C:\program files (x86)\Amazon Corretto\jre8\bin\ktab.exe](ktab.exe-AB2485516E63BA82335DA60828829563.md) | 86




MIT License. Copyright (c) 2020 Strontic.


