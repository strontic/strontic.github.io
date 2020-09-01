---
title: iisreset.exe | IIS control command line utility
---

# iisreset.exe 

* File Path: `C:\Windows\SysWOW64\iisreset.exe`
* Description: IIS control command line utility

## Hashes

Type | Hash
-- | --
MD5 | `ED814B283BD6CC138A44A121A1D7CE5B`
SHA1 | `2737D69827E58930878DAE861BC958714D143A99`
SHA256 | `9B5363AE9FDC399A71BEB6ED13505E351AA7C936B701A606134B5C3BF07FCB56`
SHA384 | `16FDBED51FD1C1FC3526A7BD7A64A0913DC5245FBD6C31D69986BD1F9B45CA46607D9E3D14FF1AE6CA6CD854C6682373`
SHA512 | `23F4520D275B4BFE5B59BDFED9538BBD36BCF4AC31C14F1BE71339FC190429DF21B8C481341ABD2D65527EFFC999D73EA94CA8E6E7F87A2B5186D1A2B1AD5B55`
SSDEEP | `192:QtFVFt4Bbe2a5P/j1JI3wHdNVtXB2TPpMQoY03UtdiEgc1XqQB1kzW0ItY:KH2a5P/xA2bXe+AdiEuQBCzW0I`

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

### Child Processes:
conhost.exe

### Loaded Modules:

Path |
-- |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\SysWOW64\iisreset.exe |


## Signature

* Status: Signature verified.
* Serial: `33000001733031072665B8B9B3000000000173`
* Thumbprint: `14590DC5C3AAF238FCFD7785B4B93F4071402C34`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: iisreset.exe.mui
* Product Name: Internet Information Services
* Company Name: Microsoft Corporation
* File Version: 10.0.14393.0 (rs1_release.160715-1616)
* Product Version: 10.0.14393.0
* Language: Language Neutral
* Legal Copyright:  Microsoft Corporation. All rights reserved.





MIT License. Copyright (c) 2020 Strontic.


