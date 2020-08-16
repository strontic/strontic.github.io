---
title: jmap.exe | OpenJDK Platform binary
---

# jmap.exe 

* File Path: `C:\Program Files\Amazon Corretto\jdk11.0.8_10\bin\jmap.exe`
* Description: OpenJDK Platform binary

## Hashes

Type | Hash
-- | --
MD5 | `270A52F3872A5B75C42F5E7C7EE130D0`
SHA1 | `3A7C0CA6FFC1B831B5ABA61B40E0128E2E509D4B`
SHA256 | `02539D527DDEB27C47B22D7BF829EBD5DDD323688FD6925F423F14D71F0DBEFF`
SHA384 | `70501C50D37878D9F46E4EB60CD87922A3C337B5929641A15EF9857DFFE949DA05C8F80AFF754279EDFEFC536F690773`
SHA512 | `816206C8A18F658305C2C12AC43B18A99BD1435ABFC84ED3E6A1CB6EB4C659A276797B46D3001FD11D205BE9F7F9B49C45A46EE46333610E7C26AA7120FB78AF`
SSDEEP | `384:Fb9biPqNye5xFBbFMm5AdbK6jSp4kDgf2hI:HOPreXFMm56Kg5kUf2hI`

### Usage (stderr):
```Batchfile
Usage:
    jmap -clstats <pid>
        to connect to running process and print class loader statistics
    jmap -finalizerinfo <pid>
        to connect to running process and print information on objects awaiting finalization
    jmap -histo[:live] <pid>
        to connect to running process and print histogram of java object heap
        if the "live" suboption is specified, only count live objects
    jmap -dump:<dump-options> <pid>
        to connect to running process and dump java heap
    jmap -? -h --help
        to print this help message

    dump-options:
      live         dump only live objects; if not specified,
                   all objects in the heap are dumped.
      format=b     binary format
      file=<file>  dump heap to <file>

    Example: jmap -dump:live,format=b,file=heap.bin <pid>

```

## Signature

* Status: Signature verified.
* Serial: `2F83C35B5136353D68CE9EB669FD1B0B`
* Thumbprint: `4BAD227329ADEF18F215B6475FB7948E1629B505`
* Issuer: CN=Symantec Class 3 SHA256 Code Signing CA, OU=Symantec Trust Network, O=Symantec Corporation, C=US
* Subject: CN=Amazon.com Services LLC, OU=Software Services, O=Amazon.com Services LLC, L=Seattle, S=Washington, C=US

## File Metadata

* Original Filename: jmap.exe
* Product Name: OpenJDK Platform 11
* Company Name: Amazon.com Inc.
* File Version: 11.0.8
* Product Version: 11.0.8
* Language: Language Neutral
* Legal Copyright: Copyright  2020

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Program Files\AdoptOpenJDK\jdk-11.0.8.10-hotspot\bin\jmap.exe](jmap.exe-04C49823E33A3ABCF73C414C8329F37A.md) | 52




MIT License. Copyright (c) 2020 Strontic.


