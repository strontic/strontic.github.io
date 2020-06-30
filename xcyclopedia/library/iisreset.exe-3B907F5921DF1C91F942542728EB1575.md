---
title: iisreset.exe | IIS control command line utility
---

# iisreset.exe 

* File Path: `C:\Windows\system32\iisreset.exe`
* Description: IIS control command line utility
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `3B907F5921DF1C91F942542728EB1575`
SHA1 | `D5F5873EE621DDCF25FD8F19BF5C8A38E8026B90`
SHA256 | `6DA6EA7C5D6410D9BC1912D6AA7AC4F094891CCDC2A9A1D29E071E50DB72AC06`
SHA384 | `1020AD3362A530FDEDD9C127DA21BCA22F200D7C958D953F3AAAE407FAB318E9413E3870049FD33CD693B5A0DFB34A72`
SHA512 | `DBB95F3ABB43286DF518B5D64591D2C7E4060FEEE42131427701F6922D58D69D77A35B3A3C32CFB2F8EED23177DC2CCCE5D37046CE608F325CC45C0E0CC1E4DA`
SSDEEP | `384:rIHvC5RBOGxzvnT7h7bYzIDq+mnULd3+mz3DWg:rpRNzvnTJDzLdOmz3P`

## Runtime Data

### Usage (stdout):
```Batchfile

IISRESET.EXE (c) Microsoft Corp. 1998-2005

Usage:
iisreset [computername]

    /RESTART            Stop and then restart all Internet services.
    /START              Start all Internet services.
    /STOP               Stop all Internet services.
    /REBOOT             Reboot the computer.
    /REBOOTONERROR      Reboot the computer if an error occurs when starting,
                        stopping, or restarting Internet services.
    /NOFORCE            Do not forcefully terminate Internet services if
                        attempting to stop them gracefully fails.
    /TIMEOUT:val        Specify the timeout value ( in seconds ) to wait for 
                        a successful stop of Internet services. On expiration
                        of this timeout the computer can be rebooted if 
                        the /REBOOTONERROR parameter is specified.
                        The default value is 20s for restart, 60s for stop,
                        and 0s for reboot.
    /STATUS             Display the status of all Internet services.
    /ENABLE             Enable restarting of Internet Services 
                        on the local system.
    /DISABLE            Disable restarting of Internet Services 
                        on the local system.

```

### Usage (stderr):
```Batchfile

```

### Child Processes:
conhost.exe

## Signature

* Status: Signature verified.
* Serial: `33000001C422B2F79B793DACB20000000001C4`
* Thumbprint: `AE9C1AE54763822EEC42474983D8B635116C8452`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: iisreset.exe
* Product Name: Internet Information Services
* Company Name: Microsoft Corporation
* File Version: 10.0.17763.1 (WinBuild.160101.0800)
* Product Version: 10.0.17763.1
* Language: Language Neutral
* Legal Copyright:  Microsoft Corporation. All rights reserved.





MIT License. Copyright (c) 2020 Strontic.


