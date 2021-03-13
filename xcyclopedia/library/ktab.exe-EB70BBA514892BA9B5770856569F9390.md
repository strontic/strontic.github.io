---
title: ktab.exe | OpenJDK Platform binary
excerpt: What is ktab.exe?
---

# ktab.exe 

* File Path: `C:\Program Files\Amazon Corretto\jdk1.8.0_265\bin\ktab.exe`
* Description: OpenJDK Platform binary

## Hashes

Type | Hash
-- | --
MD5 | `EB70BBA514892BA9B5770856569F9390`
SHA1 | `17F02C8609202467A3D135760A47C3A052609506`
SHA256 | `331E6F39749DDD5444D3EAC66DEA2263878BFF98A2D4C41B65914E27F7D442FB`
SHA384 | `98D4C511882FDD0C71478CB7943280567F3842884245DEA800ED1C1398FF1C4BA69CA4F7A2B1167DC1915618A4953EC7`
SHA512 | `BCCA0654661AD5D12BAADE30C9334A0632720EE2FE81E14B4EF57D3664F56825E161D6151D471E6FA9BB6F6AB176BE257CC23F7BCEA57F899F0BF9607D1B8285`
SSDEEP | `384:NPaEK6KNdl6QeENaK6jS3HdYODgf2hjM+:RaZ/wlEgKgFOUf2hI+`
IMP | `2C43CDA2243B5AF72E180E8D1F09446D`
PESHA1 | `58500807E96D52406388B83D6BE7CAB0F533D591`
PE256 | `E5F25468BE471199161F6B21509C5659D0C7289F292FB5791AB586C62BDDF7A8`

## Runtime Data

### Usage (stdout):
```cmhg
Error: Useless extra argument C:\temp\strontic-xcyclopedia\notepad.exe.

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
C:\Program Files\Amazon Corretto\jdk1.8.0_265\bin\ktab.exe |
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

* Original Filename: ktab.exe
* Product Name: OpenJDK Platform 8
* Company Name: Amazon.com Inc.
* File Version: 8.0.2650.1
* Product Version: 8.0.2650.1
* Language: Language Neutral
* Legal Copyright: Copyright  2020
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/70
* VirusTotal Link: https://www.virustotal.com/gui/file/331e6f39749ddd5444d3eac66dea2263878bff98a2d4c41b65914e27f7d442fb/detection/

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Program Files\Amazon Corretto\jdk1.8.0_265\jre\bin\ktab.exe](ktab.exe-4E10E111BC97C675CFE3BF5A40E0D29F.md) | 80
[C:\Program Files\Amazon Corretto\jre8\bin\ktab.exe](ktab.exe-7273553C79E43A7A0FC111E39B2D7462.md) | 80




MIT License. Copyright (c) 2020-2021 Strontic.


