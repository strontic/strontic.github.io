---
title: WCA.exe | wca.exe
excerpt: What is WCA.exe?
---

# WCA.exe 

* File Path: `C:\Program Files (x86)\Microsoft SDKs\Windows\v10.0A\bin\NETFX 4.8 Tools\WCA.exe`
* Description: wca.exe
* Comments: Flavor=Retail


## Hashes

Type | Hash
-- | --
MD5 | `0D49D0C3B0554836FEC4A71BBE4A0BA4`
SHA1 | `750BB9F953052CB768A0D5547A0DD4B3D150CF8C`
SHA256 | `3C8AA7ADE8FD2DC0EE12E92274449520CFA36317C365F7C4B7235B50CF766B40`
SHA384 | `F80F00C45C1AAA4E0E827F9EF92D76D759A8A833C9D7E2EC9EC14DEDC08C5DBF269F5D6A462D830C5AF7DE49C219012E`
SHA512 | `FCFF2F05BB5DA97996D538332FE6A1BE5DA6807F8697FDF39FA0E519DB0254963E4515C29153AF014B64FF5CFDE3EFDBD32A10DCFC019F5E2E412BF8D845048A`
SSDEEP | `1536:26Eq5DMvEun/BcW21f6QQ3sXHd5honeHZo8P+:26Eq5DMvEunph1Cd5rZ2`
IMP | `F34D5F2D4577ED6D9CEEC516C1F5A744`
PESHA1 | `CD3DA6D55B7F07A4B32A6DDB6E86C77301030477`
PE256 | `5ADEA1D3DCFEEDBD01B26B7273C47FF0F36A7A1F94F544EA3D87A111D108A9A9`

## Runtime Data

### Usage (stdout):
```cmhg
Microsoft (R) Workflow Communications Activity generator utility
[Microsoft(R) .NET Framework, Version 4.8.4084.0]
Copyright (C) Microsoft Corporation. All rights reserved.

wca.exe -
    Utility to generate activities from a valid workflow communication
    interface

wca.exe <assembly>.dll|.exe [/c] [/i] [/l:] [/o:]

                - OPTIONS -

/collapseArgs
    Collapse HandleExternalEventActivity EventArg properties into a single
    variable E.  Default is to create a public property on the
    HandleExternalEventActivity for each public property and public field in
    the EventArgs.  Short form is '/c'.

/includeSender
    Include the object Sender as a property of the HandleExternalEventActivity.
    Default is not to include the sender property.  Short form is '/i'.

/language:<language>
    The language to use for the generated code.  Choose from 'CS' or 'VB'.
    Default is 'CS'.  Short form is '/l:'.

/out:<directoryName>
    The output directory in which to create the files.  Default is the current
    directory.  Short form is '/o:'.

/namespace:<namespace>
    The namespace to which the activity classes will belong.  Default is the
    namespace of the corresponding interface.  Short form is '/n:'.

                - ARGUMENTS -

<assembly>.dll|.exe
    Name of an assembly containing interfaces to generate activities for.


```

### Loaded Modules:

Path |
-- |
C:\Program Files (x86)\Microsoft SDKs\Windows\v10.0A\bin\NETFX 4.8 Tools\WCA.exe |
C:\Windows\System32\KERNEL32.dll |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\SYSTEM32\MSCOREE.DLL |
C:\Windows\SYSTEM32\ntdll.dll |


## Signature

* Status: Signature verified.
* Serial: `33000001519E8D8F4071A30E41000000000151`
* Thumbprint: `62009AAABDAE749FD47D19150958329BF6FF4B34`
* Issuer: CN=Microsoft Code Signing PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Corporation, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: wca.exe
* Product Name: Microsoft .NET Framework
* Company Name: Microsoft Corporation
* File Version: 4.8.4084.0 built by: NET48REL1
* Product Version: 4.8.4084.0
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation.  All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/73
* VirusTotal Link: https://www.virustotal.com/gui/file/3c8aa7ade8fd2dc0ee12e92274449520cfa36317c365f7c4b7235b50cf766b40/detection





MIT License. Copyright (c) 2020 Strontic.


