
# iisreset.exe 
* File Path: `C:\Windows\system32\iisreset.exe`
* Description: IIS control command line utility
* Comments: 

## Hashes
Type | Hash
-- | --
MD5 | `D09D9DAD407B4A61CCB96EA5974AEFEB`
SHA1 | `63A0ADA875FE271DC6AC746CB61B55C1F917A5C5`
SHA256 | `EDA5883BD414852613CA4C25B4CAB15197DA73C3DAC182F7876A27BAC9DCDE23`
SHA384 | `6240FA5A79EF5B9CA1DE30A0C9339FBF07FC69C28DE13D3296178F71515571636968C4F17251881AC798BEC46B503CF4`
SHA415 | `8DE4CC8CC09FA56C65D713176A2B2C9BA1AC9277167AD83F5FFD7AF1A8569A6FE300F6EF837B322FE685D5998C1687AC5755F564968459B60115406B0834A2A4`
SSDEEP | `384:1rfAz/f54lG6A0O3yc7tGlps62gy8HDExabCviEgQBIbW0:ZG41A0O3bEl9H/WvijQBIz`

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
* Serial: 33000001733031072665B8B9B3000000000173
* Thumbprint: 14590DC5C3AAF238FCFD7785B4B93F4071402C34
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


