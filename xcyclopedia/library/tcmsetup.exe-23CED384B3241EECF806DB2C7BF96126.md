---
title: tcmsetup.exe | Microsoft Windows(TM) Telephony Administration Setup
---

# tcmsetup.exe 

* File Path: `C:\WINDOWS\SysWOW64\tcmsetup.exe`
* Description: Microsoft Windows(TM) Telephony Administration Setup

## Screenshot

![tcmsetup.exe](screenshots/tcmsetup.exe-2A3CCDB782638FD831250BC528F3CB5E-1.png)

## Hashes

Type | Hash
-- | --
MD5 | `23CED384B3241EECF806DB2C7BF96126`
SHA1 | `C42A72880AC5CF93CC129B066D47A4DCAB8828EF`
SHA256 | `B0EA88481D83F5E3123FF00FB624F014E0656E62D0B237A81DB6E44077F2A22E`
SHA384 | `8AB2C58C8059D6F507E8369F6BA5AF554DA5FA3683EF6BD3D348105D3CB15073C2DAA5D07790EA91AFF9BF552DFDC690`
SHA512 | `A660742F3233DF88F9AE6C37021FBE17E2A0CC673381929C910727E8EAA228DE83922D395738371DE26A59E5CC1E2A599F7371982F2AA4484BD0244C34A62FAE`
SSDEEP | `192:WqMu21Wg6MyBF8TPJ9vXsDFWRLsCoad6V6WvQWGGoW:7MpYg26vX+WRQD8WvQWGGoW`

## Signature

* Status: Signature verified.
* Serial: `330000023241FB59996DCC4DFF000000000232`
* Thumbprint: `FF82BC38E1DA5E596DF374C53E3617F7EDA36B06`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: TCMSETUP.EXE.MUI
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.18362.1 (WinBuild.160101.0800)
* Product Version: 10.0.18362.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Windows\SysWOW64\tcmsetup.exe](tcmsetup.exe-8EC5D3BE26A23B88DF4DE0CC17931777.md) | 44


## Additional Info*

**The information below is copied from [MicrosoftDocs](https://github.com/MicrosoftDocs/windowsserverdocs), which is maintained by [Microsoft](https://opensource.microsoft.com/codeofconduct/). Available under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) license.*

---

## tcmsetup



Sets up or disables the TAPI client.

### Syntax

```
tcmsetup [/q] [/x] /c <Server1> [<Server2> â€¦]
tcmsetup  [/q] /c /d
```

##### Parameters

|Parameter|Description|
|---------|-----------|
|/q|Prevents the display of message boxes.|
|/x|Specifies that connection-oriented callbacks will be used for heavy traffic networks where packet loss is high. When this parameter is omitted, connectionless callbacks will be used.|
|/c|Required. Specifies client setup.|
|\<Server1>|Required. Specifies the name of the remote server that has the TAPI service providers that the client will use. The client will use the service providers' lines and phones. The client must be in the same domain as the server or in a domain that has a two-way trust relationship with the domain that contains the server.|
|\<Server2>â€¦|Specifies any additional server or servers that will be available to this client. If you specify a list of servers is, use a space to separate the server names.|
|/d|Clears the list of remote servers. Disables the TAPI client by preventing it from using the TAPI service providers that are on the remote servers.|
|/?|Displays help at the command prompt.|

### Remarks

-   To perform this procedure, you must be a member of the Administrators group on the local computer, or you must have been delegated the appropriate authority. If the computer is joined to a domain, members of the Domain Admins group might be able to perform this procedure. As a security best practice, consider using **Run as** to perform this procedure.
-   In order for TAPI to function correctly, you must run **tcmsetup** to specify the remote servers that will be used by TAPI clients.
-   Before a client user can use a phone or line on a TAPI server, the telephony server administrator must assign the user to the phone or line.
-   The list of telephony servers that is created by this command replaces any existing list of telephony servers available to the client. You cannot use this command to add to the existing list.

### Additional References

- [Command-Line Syntax Key](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/command-line-syntax-key.md)

[Command shell overview](/previous-versions/windows/it-pro/windows-server-2003/cc737438(v=ws.10))

[Specify telephony servers on a client computer](/previous-versions/windows/it-pro/windows-server-2003/cc759226(v=ws.10))

[Assign a telephony user to a line or phone](/previous-versions/windows/it-pro/windows-server-2003/cc736875(v=ws.10))

---



MIT License. Copyright (c) 2020 Strontic.


