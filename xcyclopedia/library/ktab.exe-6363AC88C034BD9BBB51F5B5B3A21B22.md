---
title: ktab.exe | OpenJDK Platform binary
---

# ktab.exe 

* File Path: `C:\program files (x86)\Amazon Corretto\jdk1.8.0_265\bin\ktab.exe`
* Description: OpenJDK Platform binary

## Hashes

Type | Hash
-- | --
MD5 | `6363AC88C034BD9BBB51F5B5B3A21B22`
SHA1 | `4E1F927E00C65D318212D61E973CDC76C61BD962`
SHA256 | `D3A2C97CBE07A77676B149072007E43B62FA69B1D55AD7E5202EACF32EE99182`
SHA384 | `73F8BFDAE60AC787509A73928D91A8A291CEC9D96C774A454E348D023FBC28564F9F09F86F517A92BA4A5FCA65B39BF8`
SHA512 | `F9FD440AB683B5093AFB87FC3EB042DA40239E16E8E339086A7B866FBE6CA8B00B27B399EA1F31E914622574C56A3DDA593559F3FF2DDBE1CADEDCDD48048E4D`
SSDEEP | `384:Gpst5hnCq+mSHhV8laeeo4SzHK6jSXznDgf2hO:GpsdnTS/8lHeo9KgmDUf2hO`

## Runtime Data

### Usage (stdout):
```Batchfile
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
C:\program files (x86)\Amazon Corretto\jdk1.8.0_265\bin\ktab.exe |
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
[C:\program files (x86)\Amazon Corretto\jdk1.8.0_265\bin\jfr.exe](jfr.exe-B941B77B992BC329570061F0856916EA.md) | 68
[C:\program files (x86)\Amazon Corretto\jdk1.8.0_265\jre\bin\ktab.exe](ktab.exe-9538260E340CF8ECFA890862796E0C5D.md) | 90
[C:\program files (x86)\Amazon Corretto\jre8\bin\ktab.exe](ktab.exe-AB2485516E63BA82335DA60828829563.md) | 88




MIT License. Copyright (c) 2020 Strontic.


