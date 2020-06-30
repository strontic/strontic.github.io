---
title: iisreset.exe | IIS control command line utility
---

# iisreset.exe 

* File Path: `C:\Windows\SysWOW64\iisreset.exe`
* Description: IIS control command line utility
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `9EE229F266E60A4EA221A6AB26A87CDB`
SHA1 | `685EE14EBBA35CED188158F55D8D7C322FE398E2`
SHA256 | `59E7F581688D62D8A52AAF985C5F918D6307FFA9E789FEE559C99EAA6ECA4FDA`
SHA384 | `D80D58529CEFDCEA34A752278A626E292E43FDB5B6E99839641364BE35321F7B38AB84684ED8C791273E90FC72BB3DB6`
SHA512 | `4CAD1B85E512CBDD2FDD4958E86F42838DB6F3D9AAEC088AA408D4A3C936A44004DAF0F9DAACACC2FE19932A7470C2E22C85E48A05408CCB9A74174B3FE79D62`
SSDEEP | `192:4WtwnElnIgm2iQ3O6MZ2PlXA/tLMntInMQoOoLwtJd3mfXqmzckrWgOf:vS2iQ+6Mua/YISAJd3NmzvrWgC`

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
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
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


