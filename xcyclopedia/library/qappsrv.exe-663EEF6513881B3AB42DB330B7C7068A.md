---
title: qappsrv.exe | Query Remote Desktop Session Host Server Utility
---

# qappsrv.exe 

* File Path: `C:\Windows\system32\qappsrv.exe`
* Description: Query Remote Desktop Session Host Server Utility
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `663EEF6513881B3AB42DB330B7C7068A`
SHA1 | `2D98697ADD27C7F0233E4B4DEC38C98F74BB99FD`
SHA256 | `7854BECE46ECA8917904D60666A856DE11CA4896C6452D5AF1A1B20F1626C971`
SHA384 | `F82DB34F12D90A88E8251DF4B71FD82E1797C328D67F02D79F398CF560788344741395AE19A73A50FA317FD8F276FB58`
SHA512 | `E724B8956E423B63DEC7A3487CA788A9E16E67E4413932E86909F920710E240E324398E00042FA32B9B16AEA2DF4A7EBB347CA14ECF7A068C3C6691CBA3823FF`
SSDEEP | `384:DQTcgWLsYGvRO+UxtRT5dseZ87BvFtSZa6KuRX390pkINWgaWF:DQoMYGvRO+UtYeZ8Nr6ckIx`

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
* Serial: `330000023241FB59996DCC4DFF000000000232`
* Thumbprint: `FF82BC38E1DA5E596DF374C53E3617F7EDA36B06`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: qappsrv.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.



## Additional Info*

**The information below is copied from [MicrosoftDocs](https://github.com/MicrosoftDocs/windowsserverdocs), which is maintained by [Microsoft](https://opensource.microsoft.com/codeofconduct/). Available under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) license.*

---
## qappsrv

> Applies to: Windows Server (Semi-Annual Channel), Windows Server 2019, Windows Server 2016, Windows Server 2012 R2, Windows Server 2012

Displays a list of all Remote Desktop Session Host (RD Session Host) servers on the network.

> [!NOTE]
> In Windows Server 2008 R2, Terminal Services was renamed Remote Desktop Services. To find out what's new in the latest version, see [What s New in Remote Desktop Services in Windows Server 2012](https://technet.microsoft.com/library/hh831527) in the Windows Server TechNet Library.

### Remarks
This command is the same as the **query termserver** command.

### Additional References
[query termserver](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/query-termserver.md)
- [Command-Line Syntax Key](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/command-line-syntax-key.md)
[Remote Desktop Services (Terminal Services) Command Reference](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/remote-desktop-services-terminal-services-command-reference.md)

---



MIT License. Copyright (c) 2020 Strontic.


