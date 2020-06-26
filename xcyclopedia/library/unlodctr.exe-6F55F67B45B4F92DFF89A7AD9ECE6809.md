---
title: unlodctr.exe | Unload PerfMon Counters
---

# unlodctr.exe 

* File Path: `C:\Windows\SysWOW64\unlodctr.exe`
* Description: Unload PerfMon Counters
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `6F55F67B45B4F92DFF89A7AD9ECE6809`
SHA1 | `94539146479327EBCBABB3FA646351BB74E4CD5B`
SHA256 | `2F5FB0EA5AC2181B55C0530C28FABE5955049B80006DED555900023D902A07ED`
SHA384 | `2B26CF3F47447E2E3D2A9268786C31EBEA29D6B94D97DC4FAF0FFDF9ACF88BD74282F114F7CC5BF5F294FCF3B8BE1CD7`
SHA512 | `4A81D069510D1B89C3613BFD8C13AEB5E78AD7AC2AA17A5756ECECA34D8C0A5AFFF219CD582F0AC33205873CD1112D778C32960659F273C48FED110AAB143812`
SSDEEP | `768:zzpb5lM8K8dUE9aDkH7snKweGrQX8lIFfZB3F5xfbYS3z:TlM8KG8kbeFQ0IZb1bYS3z`

## Runtime Data

### Usage (stdout):
```Batchfile


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

### Usage (stderr):
```Batchfile

```

### Child Processes:


## Signature

* Status: Signature verified.
* Serial: `33000000BCE120FDD27CC8EE930000000000BC`
* Thumbprint: `E85459B23C232DB3CB94C7A56D47678F58E8E51E`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: UNLODCTR.EXE.MUI
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.14393.0 (rs1_release.160715-1616)
* Product Version: 10.0.14393.0
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.





MIT License. Copyright (c) 2020 Strontic.


