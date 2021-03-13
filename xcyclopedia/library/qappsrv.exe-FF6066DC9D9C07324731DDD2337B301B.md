---
title: qappsrv.exe | Query Remote Desktop Session Host Server Utility
excerpt: What is qappsrv.exe?
---

# qappsrv.exe 

* File Path: `C:\Windows\SysWOW64\qappsrv.exe`
* Description: Query Remote Desktop Session Host Server Utility

## Hashes

Type | Hash
-- | --
MD5 | `FF6066DC9D9C07324731DDD2337B301B`
SHA1 | `90D24B175704A5060AF44BC8B5CF0C49F0F402A3`
SHA256 | `A17E6E3EF7DCFED272A02E962C009A4EB2394B853C7584A55163DDD72B21C743`
SHA384 | `7FC5058E8A8E069346D6A8A8D8608FAD545BE1FB26180302F9FD2E826F5351DD8B0F4AC876FCFECB8BB164B0EDACABE4`
SHA512 | `3519B93492CAFF889F782D787FAE1D121856B7AC8CBA9A6CF9BA1F7CB297780ED191E313CE77D5E0BA88FC35F4C0D7F0E8922479A932C9404797DB12C1CFCFF0`
SSDEEP | `384:UyFo0xErt7IRU9CPWb/AeaEXusR3D5N9B9WxlWPaWlW:UyFBSICL/us9Axic`

## Runtime Data

### Usage (stdout):
```cmhg
Displays the available Remote Desktop Session Host servers on the network.

QUERY TERMSERVER [servername] [/DOMAIN:domain] [/ADDRESS] [/CONTINUE]

  servername      Identifies a Remote Desktop Session Host server.
  /DOMAIN:domain  Displays information for the specified domain (defaults 
                  to the current domain).
  /ADDRESS        Displays network and node addresses.
  /CONTINUE       Does not pause after each screen of information.


```

### Usage (stderr):
```cmhg
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
* Serial: `33000000BCE120FDD27CC8EE930000000000BC`
* Thumbprint: `E85459B23C232DB3CB94C7A56D47678F58E8E51E`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: qappsrv.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.14393.0 (rs1_release.160715-1616)
* Product Version: 10.0.14393.0
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.




## Additional Info*

**The information below is copied from [MicrosoftDocs](https://github.com/MicrosoftDocs/windowsserverdocs), which is maintained by [Microsoft](https://opensource.microsoft.com/codeofconduct/). Available under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) license.*

---

## qappsrv

> Applies to: Windows Server (Semi-Annual Channel), Windows Server 2019, Windows Server 2016, Windows Server 2012 R2, Windows Server 2012

Displays a list of all Remote Desktop Session Host servers on the network. To find out what's new in the latest version, see [What's New in Remote Desktop Services in Windows Server](/previous-versions/windows/it-pro/windows-server-2012-r2-and-2012/dn283323(v=ws.11)).

> [!NOTE]
> This command is the same as the [query termserver command](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/query-termserver.md).

### Additional References

- [Command-Line Syntax Key](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/command-line-syntax-key.md)

- [query termserver command](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/query-termserver.md)

- [Remote Desktop Services (Terminal Services) Command Reference](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/remote-desktop-services-terminal-services-command-reference.md)

---



MIT License. Copyright (c) 2020-2021 Strontic.


