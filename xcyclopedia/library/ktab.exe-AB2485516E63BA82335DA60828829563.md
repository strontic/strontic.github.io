---
title: ktab.exe | OpenJDK Platform binary
excerpt: What is ktab.exe?
---

# ktab.exe 

* File Path: `C:\program files (x86)\Amazon Corretto\jre8\bin\ktab.exe`
* Description: OpenJDK Platform binary

## Hashes

Type | Hash
-- | --
MD5 | `AB2485516E63BA82335DA60828829563`
SHA1 | `DE04858102D40C51F82A47715A3597ABAF212BDD`
SHA256 | `76F0CC72714D14EC5B765B4557546A3CCED5A8CF05AFC75398BAAAA4E67B7121`
SHA384 | `99BEAA6D348D403370EF94DB111A4DB74940445787A85B317D6C833A9B124BB254991B190D65A72BAD4B049A26756134`
SHA512 | `73B2F74F505DEFF4E416D300BFEE6F303B84EDAEB13AF3408414B0E362A38E67318457B9E0A7954A7E77046C8800DF22C24AC13C2409359FBFADCBB3CD02CFCB`
SSDEEP | `384:Gpsi5hnCq+mSHhV8laeeo4Sz8K6jSL8XDgf2hv:GpsEnTS/8lHeoeKgeMUf2hv`

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
C:\program files (x86)\Amazon Corretto\jre8\bin\ktab.exe |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\wow64.dll |
C:\Windows\System32\wow64cpu.dll |
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
[C:\program files (x86)\Amazon Corretto\jdk1.8.0_265\bin\jarsigner.exe](jarsigner.exe-25F594CAD13F3B833E2FD7A5B6DA32BC.md) | 65
[C:\program files (x86)\Amazon Corretto\jdk1.8.0_265\bin\jjs.exe](jjs.exe-50283CF0315C0D9CB58A0C666D5CEFF7.md) | 77
[C:\program files (x86)\Amazon Corretto\jdk1.8.0_265\bin\ktab.exe](ktab.exe-6363AC88C034BD9BBB51F5B5B3A21B22.md) | 88
[C:\program files (x86)\Amazon Corretto\jdk1.8.0_265\jre\bin\jjs.exe](jjs.exe-EF545E6EFCC0E8BA4089FE7DC1DFDE90.md) | 71
[C:\program files (x86)\Amazon Corretto\jdk1.8.0_265\jre\bin\ktab.exe](ktab.exe-9538260E340CF8ECFA890862796E0C5D.md) | 86
[C:\program files (x86)\Amazon Corretto\jre8\bin\jjs.exe](jjs.exe-F1EAC51F83F1299AD8072546BD948015.md) | 72




MIT License. Copyright (c) 2020-2021 Strontic.


