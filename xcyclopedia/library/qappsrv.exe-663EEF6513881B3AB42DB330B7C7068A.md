﻿---
title: qappsrv.exe | Query Remote Desktop Session Host Server Utility
excerpt: What is qappsrv.exe?
---

# qappsrv.exe 

* File Path: `C:\Windows\system32\qappsrv.exe`
* Description: Query Remote Desktop Session Host Server Utility

## Hashes

Type | Hash
-- | --
MD5 | `663EEF6513881B3AB42DB330B7C7068A`
SHA1 | `2D98697ADD27C7F0233E4B4DEC38C98F74BB99FD`
SHA256 | `7854BECE46ECA8917904D60666A856DE11CA4896C6452D5AF1A1B20F1626C971`
SHA384 | `F82DB34F12D90A88E8251DF4B71FD82E1797C328D67F02D79F398CF560788344741395AE19A73A50FA317FD8F276FB58`
SHA512 | `E724B8956E423B63DEC7A3487CA788A9E16E67E4413932E86909F920710E240E324398E00042FA32B9B16AEA2DF4A7EBB347CA14ECF7A068C3C6691CBA3823FF`
SSDEEP | `384:DQTcgWLsYGvRO+UxtRT5dseZ87BvFtSZa6KuRX390pkINWgaWF:DQoMYGvRO+UtYeZ8Nr6ckIx`
IMP | `868BFA1AAB4C99A8643F150421706BD1`
PESHA1 | `017914B13A0075C38D0D0C88561A7AE18D27D834`
PE256 | `CE21F7D9C92B79D0FEE6BD70B832D6C13A91A04531BB19A27511F2855F979AA9`

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

### Open Handles:

Path | Type
-- | --
(R-D)   C:\Windows\System32\en-US\qappsrv.exe.mui | File
(RW-)   C:\Users\user | File
\BaseNamedObjects\C:\*ProgramData\*Microsoft\*Windows\*Caches\*{6AF0698E-D558-4F6E-9B3C-3716689AF493}.2.ver0x0000000000000002.db | Section
\BaseNamedObjects\C:\*ProgramData\*Microsoft\*Windows\*Caches\*{DDF571F2-BE98-426D-8288-1A9A39C3FDA2}.2.ver0x0000000000000002.db | Section
\BaseNamedObjects\C:\*ProgramData\*Microsoft\*Windows\*Caches\*cversions.2 | Section
\BaseNamedObjects\NLS_CodePage_1252_3_2_0_0 | Section
\BaseNamedObjects\NLS_CodePage_437_3_2_0_0 | Section


### Loaded Modules:

Path |
-- |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\system32\qappsrv.exe |


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
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/74
* VirusTotal Link: https://www.virustotal.com/gui/file/7854bece46eca8917904d60666a856de11ca4896c6452d5af1a1b20f1626c971/detection



## Additional Info*

**The information below is copied from [MicrosoftDocs](https://github.com/MicrosoftDocs/windowsserverdocs), which is maintained by [Microsoft](https://opensource.microsoft.com/codeofconduct/). Available under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) license.*

---

## qappsrv

>Applies to: Windows Server 2022, Windows Server 2019, Windows Server 2016, Windows Server 2012 R2, Windows Server 2012

Displays a list of all Remote Desktop Session Host servers on the network. To find out what's new in the latest version, see [What's New in Remote Desktop Services in Windows Server](/previous-versions/windows/it-pro/windows-server-2012-r2-and-2012/dn283323(v=ws.11)).

> [!NOTE]
> This command is the same as the [query termserver command](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/query-termserver.md).

### Additional References

- [Command-Line Syntax Key](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/command-line-syntax-key.md)

- [query termserver command](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/query-termserver.md)

- [Remote Desktop Services (Terminal Services) Command Reference](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/remote-desktop-services-terminal-services-command-reference.md)

---



MIT License. Copyright (c) 2020-2021 Strontic.


