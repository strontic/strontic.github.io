---
title: qappsrv.exe | Query Remote Desktop Session Host Server Utility
excerpt: What is qappsrv.exe?
---

# qappsrv.exe 

* File Path: `C:\Windows\system32\qappsrv.exe`
* Description: Query Remote Desktop Session Host Server Utility

## Hashes

Type | Hash
-- | --
MD5 | `50A8F36BFB30F05701AD643173DADB89`
SHA1 | `E6C4431F5727F1CB3D899E0B4FC132F91808BA3D`
SHA256 | `CB7F28D3121604628402DB28B7627DE8D64A1B7116B883C83AE496D6F6D0B667`
SHA384 | `FA180BEA1554DEBF129ED3E6EEDF90B3EA6B0C996EC0DA8DFC15678E25B9683F53951CE1AA993DDFB7AB2CE641D320B3`
SHA512 | `5DE9CE7C15530FAE1FCB49C07B7D1C4AA03842024B00B1B496F712BE06B4A6527A0AF4B3BEF33D18E665D3A6EF7999D4CDAB0A9A34879C68723223ABA318238D`
SSDEEP | `384:F/U7HX5bP44grDMkiUHdE5z5XWjK8mKk5VGqqKEcgEgPJ5HPwe9Kp/14ED0lWLad:dGp8rDMOHKMjK8NO5NDOq94EQe`
IMP | `C715564F456F9C30B145ACEC03F1E5C4`
PESHA1 | `EB00938B5942323335D53D58A4D8C1C52A7383E3`
PE256 | `E4B65071CDAC0AC2EE4E9ADDE59118483182D8A1AED0510E0F481BF6EEE9EDA3`

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
\BaseNamedObjects\C:\*ProgramData\*Microsoft\*Windows\*Caches\*{6AF0698E-D558-4F6E-9B3C-3716689AF493}.2.ver0x0000000000000004.db | Section
\BaseNamedObjects\C:\*ProgramData\*Microsoft\*Windows\*Caches\*{DDF571F2-BE98-426D-8288-1A9A39C3FDA2}.2.ver0x0000000000000004.db | Section
\BaseNamedObjects\C:\*ProgramData\*Microsoft\*Windows\*Caches\*cversions.2.ro | Section
\BaseNamedObjects\NLS_CodePage_1252_3_2_0_0 | Section
\BaseNamedObjects\NLS_CodePage_437_3_2_0_0 | Section


### Loaded Modules:

Path |
-- |
C:\Windows\System32\GDI32.dll |
C:\Windows\System32\gdi32full.dll |
C:\Windows\System32\IMM32.DLL |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\System32\msvcp_win.dll |
C:\Windows\System32\msvcrt.dll |
C:\Windows\system32\NETAPI32.dll |
C:\Windows\system32\NETUTILS.DLL |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\system32\qappsrv.exe |
C:\Windows\System32\RPCRT4.dll |
C:\Windows\system32\SRVCLI.DLL |
C:\Windows\System32\ucrtbase.dll |
C:\Windows\System32\USER32.dll |
C:\Windows\System32\win32u.dll |


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
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/69
* VirusTotal Link: https://www.virustotal.com/gui/file/cb7f28d3121604628402db28b7627de8d64a1b7116b883c83ae496d6f6d0b667/detection/

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\WINDOWS\system32\qappsrv.exe](qappsrv.exe-A1B5A921BAE0F96AE14900DFD5EEDC8A.md) | 75


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


