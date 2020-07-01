---
title: qappsrv.exe | Query Remote Desktop Session Host Server Utility
---

# qappsrv.exe 

* File Path: `C:\windows\system32\qappsrv.exe`
* Description: Query Remote Desktop Session Host Server Utility
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `50A8F36BFB30F05701AD643173DADB89`
SHA1 | `E6C4431F5727F1CB3D899E0B4FC132F91808BA3D`
SHA256 | `CB7F28D3121604628402DB28B7627DE8D64A1B7116B883C83AE496D6F6D0B667`
SHA384 | `FA180BEA1554DEBF129ED3E6EEDF90B3EA6B0C996EC0DA8DFC15678E25B9683F53951CE1AA993DDFB7AB2CE641D320B3`
SHA512 | `5DE9CE7C15530FAE1FCB49C07B7D1C4AA03842024B00B1B496F712BE06B4A6527A0AF4B3BEF33D18E665D3A6EF7999D4CDAB0A9A34879C68723223ABA318238D`
SSDEEP | `384:F/U7HX5bP44grDMkiUHdE5z5XWjK8mKk5VGqqKEcgEgPJ5HPwe9Kp/14ED0lWLad:dGp8rDMOHKMjK8NO5NDOq94EQe`

## Runtime Data

### Usage (stdout):
```Batchfile
Displays the available Remote Desktop Session Host servers on the network.

QUERY TERMSERVER [servername] [/DOMAIN:domain] [/ADDRESS] [/CONTINUE]

  servername      Identifies a Remote Desktop Session Host server.
  /DOMAIN:domain  Displays information for the specified domain (defaults 
                  to the current domain).
  /ADDRESS        Displays network and node addresses.
  /CONTINUE       Does not pause after each screen of information.


```

### Usage (stderr):
```Batchfile
Invalid parameter(s)
Displays the available Remote Desktop Session Host servers on the network.

QUERY TERMSERVER [servername] [/DOMAIN:domain] [/ADDRESS] [/CONTINUE]

  servername      Identifies a Remote Desktop Session Host server.
  /DOMAIN:domain  Displays information for the specified domain (defaults 
                  to the current domain).
  /ADDRESS        Displays network and node addresses.
  /CONTINUE       Does not pause after each screen of information.


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

* Original Filename: qappsrv.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.17763.1 (WinBuild.160101.0800)
* Product Version: 10.0.17763.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\WINDOWS\system32\qappsrv.exe](qappsrv.exe-A1B5A921BAE0F96AE14900DFD5EEDC8A.md) | 75


## Additional Info*

**The information below is copied from [MicrosoftDocs](https://github.com/MicrosoftDocs/windowsserverdocs), which is maintained by [Microsoft](https://opensource.microsoft.com/codeofconduct/). Available under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) license.*

---

## qappsrv

> Applies to: Windows Server (Semi-Annual Channel), Windows Server 2019, Windows Server 2016, Windows Server 2012 R2, Windows Server 2012

Displays a list of all Remote Desktop Session Host servers on the network. To find out what's new in the latest version, see [What's New in Remote Desktop Services in Windows Server](https://docs.microsoft.com/previous-versions/windows/it-pro/windows-server-2012-R2-and-2012/dn283323(v=ws.11)).

> [!NOTE]
> This command is the same as the [query termserver command](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/query-termserver.md).

### Additional References

- [Command-Line Syntax Key](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/command-line-syntax-key.md)

- [query termserver command](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/query-termserver.md)

- [Remote Desktop Services (Terminal Services) Command Reference](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/remote-desktop-services-terminal-services-command-reference.md)

---



MIT License. Copyright (c) 2020 Strontic.


