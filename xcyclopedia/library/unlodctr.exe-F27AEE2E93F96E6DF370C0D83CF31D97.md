---
title: unlodctr.exe | Unload PerfMon Counters
excerpt: What is unlodctr.exe?
---

# unlodctr.exe 

* File Path: `C:\Windows\SysWOW64\unlodctr.exe`
* Description: Unload PerfMon Counters

## Hashes

Type | Hash
-- | --
MD5 | `F27AEE2E93F96E6DF370C0D83CF31D97`
SHA1 | `0973E0BCB0CE3D7390953A21C5530AFD400C18AD`
SHA256 | `47CF991CA0F91ADCD98AF1BADE9E2BCE82600D842237404BD6A5313A539B2E13`
SHA384 | `D544A44EE41BBD2FEE5A75190AED821284F5DFBDE383E4AA61A02BE346EA3AA07DD5985582BA3F89276AF7A9B2FFDAFE`
SHA512 | `8BCBD26F616D54441650DF2A83DBD20714F6674B83BB04B891C45C6F18600ABCB07371A852EAE8779FFB0AD22D376158337658F7E0F0033FD6F3507BA8C04111`
SSDEEP | `768:uZlM8QUUYOByqUZvtUPWVj9RjGd+QfHP:8lM81UrovtUPa9VG0QfHP`

## Runtime Data

### Usage (stdout):
```cmhg


UNLODCTR
    Removes counter names and explain text for the specified extensible counter.

Usage:

    UNLODCTR <driver>
        driver is the name of the device driver which is to have its
            counter name definitions and explain text removed from the system's
            registry.

    UNLODCTR /m:<manifest>
        manifest is the name of the manifest file that contains performance
            counter definitions. These counters will be removed from local system.

    UNLODCTR /g:{ProviderGuid}
        ProviderGuid identifies the performance counter provider being unloaded.

    UNLODCTR /p:<ProviderName>
        ProviderName identifies the performance counter provider being unloaded.

Note: any arguments with spaces in the names must be enclosed within
Double Quotation marks.

```

### Loaded Modules:

Path |
-- |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\wow64.dll |
C:\Windows\SysWOW64\unlodctr.exe |


## Signature

* Status: Signature verified.
* Serial: `33000001C422B2F79B793DACB20000000001C4`
* Thumbprint: `AE9C1AE54763822EEC42474983D8B635116C8452`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: UNLODCTR.EXE
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.17763.1 (WinBuild.160101.0800)
* Product Version: 10.0.17763.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.






MIT License. Copyright (c) 2020 Strontic.


