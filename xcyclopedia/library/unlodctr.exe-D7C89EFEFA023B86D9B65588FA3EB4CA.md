
# unlodctr.exe 
* File Path: `C:\Windows\system32\unlodctr.exe`
* Description: Unload PerfMon Counters
* Comments: 

## Hashes
Type | Hash
-- | --
MD5 | `D7C89EFEFA023B86D9B65588FA3EB4CA`
SHA1 | `ED2FC85994E5E1767DA69C81680F6E97BE272199`
SHA256 | `B397CB97FDD6DACBEE6021D7E3A982A8419C2F61CC5803EA80B6169CE669D121`
SHA384 | `39EA2457AB29B934546BAED687864783226B9F559D96DE0668594FEFEE03CD7E1E66298844C54DB7C0BFD9C1F0CBD8CC`
SHA415 | `E8C92389855ED14955EEFFDAC54157C870C17C0D30336B947AD488DC0BFBFBC62A69983C9D95B8E5889E5D119E9747B7D2B15E75BFFCE97E0F239DAEC976BF35`
SSDEEP | `768:nuZpVyGynw6d5C1oBtWFebMiPN8uDHbplMc8+xFcYS7DTk:nubXW8uplMcb7cYS7DTk`

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
* Serial: 33000000BCE120FDD27CC8EE930000000000BC
* Thumbprint: E85459B23C232DB3CB94C7A56D47678F58E8E51E
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


