---
title: tcmsetup.exe | Microsoft Windows(TM) Telephony Administration Setup
excerpt: What is tcmsetup.exe?
---

# tcmsetup.exe 

* File Path: `C:\Windows\system32\tcmsetup.exe`
* Description: Microsoft Windows(TM) Telephony Administration Setup

## Screenshot

![tcmsetup.exe](screenshots/tcmsetup.exe-2A3CCDB782638FD831250BC528F3CB5E-1.png)

## Hashes

Type | Hash
-- | --
MD5 | `58F3B915B9AE7D63431772C2616B0945`
SHA1 | `6346E837DA3B0F551BECB7CAC6D160E3063696E9`
SHA256 | `E243501BA2EF7A6F04F51410BB916FAFFE0EC23450A4D030CE6BFE747E544B39`
SHA384 | `AEBC6FB1B84DD3E429A464135FF2955D78C401C86C22B2BB7ADC80C8CC0E914CDFE08AFC93D0FCED5846B2D8010649E3`
SHA512 | `7B09192AF460C502D1A94989A0D06191C8C7A058CE3A4541E3F45960A1E12529D0CDAFF9DA3D5BACFDCEED57AEB6DC9A159C6C0A95675C438F99BF7E418C6DC5`
SSDEEP | `384:A+W7Hrtkdpm8DwTWeErIiBAEdBTC2WGroW:Af7xapm8Dw6n3/CA`
IMP | `AE7E4F06CC6D11D0E730DEFD22D14777`
PESHA1 | `2C527A464E181F92E9917DF07B9519447E6443B3`
PE256 | `16CA9ABCCADD6EBDE93902EBCD3D9DAE96BB7A896EE91BA6DBD4A18AE8D5C061`

## Runtime Data

### Window Title:
Telephony Client Setup Help

### Open Handles:

Path | Type
-- | --
(R-D)   C:\Windows\Fonts\StaticCache.dat | File
(R-D)   C:\Windows\System32\en-US\tcmsetup.exe.mui | File
(RW-)   C:\Users\user | File
(RW-)   C:\Windows\WinSxS\amd64_microsoft.windows.common-controls_6595b64144ccf1df_6.0.19041.488_none_ca04af081b815d21 | File
\BaseNamedObjects\C:\*ProgramData\*Microsoft\*Windows\*Caches\*{6AF0698E-D558-4F6E-9B3C-3716689AF493}.2.ver0x0000000000000002.db | Section
\BaseNamedObjects\C:\*ProgramData\*Microsoft\*Windows\*Caches\*{DDF571F2-BE98-426D-8288-1A9A39C3FDA2}.2.ver0x0000000000000002.db | Section
\BaseNamedObjects\C:\*ProgramData\*Microsoft\*Windows\*Caches\*cversions.2 | Section
\BaseNamedObjects\NLS_CodePage_1252_3_2_0_0 | Section
\BaseNamedObjects\NLS_CodePage_437_3_2_0_0 | Section
\Sessions\1\Windows\Theme1175649999 | Section
\Windows\Theme601709542 | Section


### Loaded Modules:

Path |
-- |
C:\Windows\System32\ADVAPI32.dll |
C:\Windows\System32\GDI32.dll |
C:\Windows\System32\gdi32full.dll |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\System32\msvcp_win.dll |
C:\Windows\System32\msvcrt.dll |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\RPCRT4.dll |
C:\Windows\System32\sechost.dll |
C:\Windows\system32\tcmsetup.exe |
C:\Windows\System32\ucrtbase.dll |
C:\Windows\System32\USER32.dll |
C:\Windows\System32\win32u.dll |


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: TCMSETUP.EXE.MUI
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/74
* VirusTotal Link: https://www.virustotal.com/gui/file/e243501ba2ef7a6f04f51410bb916faffe0ec23450a4d030ce6bfe747e544b39/detection



## Additional Info*

**The information below is copied from [MicrosoftDocs](https://github.com/MicrosoftDocs/windowsserverdocs), which is maintained by [Microsoft](https://opensource.microsoft.com/codeofconduct/). Available under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) license.*

---

## tcmsetup

Sets up or disables the TAPI client. For TAPI to function correctly, you must run this command to specify the remote servers that will be used by TAPI clients.

> [!IMPORTANT]
> To use this command, you must be a member of the **Administrators** group on the local computer, or you must have been delegated the appropriate authority. If the computer is joined to a domain, members of the **Domain Admins** group might be able to perform this procedure. As a security best practice, consider using **Run as** to perform this procedure.

### Syntax

```
tcmsetup [/q] [/x] /c <server1> [<server2> â€¦]
tcmsetup  [/q] /c /d
```

#### Parameters

| Parameter | Description |
|--|--|
| /q | Prevents the display of message boxes. |
| /x | Specifies that connection-oriented callbacks will be used for heavy traffic networks where packet loss is high. When this parameter is omitted, connectionless callbacks will be used. |
| /c | Required. Specifies client setup. |
| `<server1>` | Required. Specifies the name of the remote server that has the TAPI service providers that the client will use. The client will use the service providers' lines and phones. The client must be in the same domain as the server or in a domain that has a two-way trust relationship with the domain that contains the server. |
| `<server2>â€¦` | Specifies any additional server or servers that will be available to this client. If you specify a list of servers is, use a space to separate the server names. |
| /d | Clears the list of remote servers. Disables the TAPI client by preventing it from using the TAPI service providers that are on the remote servers. |
| /? | Displays help at the command prompt. |

##### Remarks

- Before a client user can use a phone or line on a TAPI server, the telephony server administrator must assign the user to the phone or line.

- The list of telephony servers that is created by this command replaces any existing list of telephony servers available to the client. You can't use this command to add to the existing list.

### Additional References

- [Command-Line Syntax Key](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/command-line-syntax-key.md)

- [Command shell overview](/previous-versions/windows/it-pro/windows-server-2003/cc737438(v=ws.10))

- [Specify telephony servers on a client computer](/previous-versions/windows/it-pro/windows-server-2003/cc759226(v=ws.10))

- [Assign a telephony user to a line or phone](/previous-versions/windows/it-pro/windows-server-2003/cc736875(v=ws.10))

---



MIT License. Copyright (c) 2020 Strontic.


