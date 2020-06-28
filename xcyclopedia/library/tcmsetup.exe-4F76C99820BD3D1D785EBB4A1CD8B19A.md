---
title: tcmsetup.exe | Microsoft Windows(TM) Telephony Administration Setup
---

# tcmsetup.exe 

* File Path: `C:\Windows\SysWOW64\tcmsetup.exe`
* Description: Microsoft Windows(TM) Telephony Administration Setup
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `4F76C99820BD3D1D785EBB4A1CD8B19A`
SHA1 | `5AD4603F0AFF29B06E905BD8F665FA3DAC57ABF3`
SHA256 | `D8827FD646B673E259C97417A17ABF6F1015B07384801933782337036F18FB25`
SHA384 | `4FA30D57353B76901205826C29D31BCBE0AE5FFAAC7E4BEEE391A06B68436ED4925D4C792B9ED3562CB8CE13C2CDBF7E`
SHA512 | `99676C22A7DA23B91C4FDF9CEFE65B7EF07BA8AFCE05A9898090599722D39A6CE29B48C03412837D51CFDB4EECB49C0DF0299F12E782456A7FF7A0B3BF77B323`
SSDEEP | `192:SI2aAWyEpgCU/MvlZ/HsDlWTsLloadczmvYWGroWfz:SfdJ8/HeWwLWkvYWGroW`

## Runtime Data

### Usage (stdout):
```Batchfile

```

### Usage (stderr):
```Batchfile

```

### Child Processes:


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

[Command shell overview](https://technet.microsoft.com/library/cc737438(v=ws.10).aspx)

[Specify telephony servers on a client computer](https://technet.microsoft.com/library/cc759226(v=ws.10).aspx)

[Assign a telephony user to a line or phone](https://technet.microsoft.com/library/cc736875(v=ws.10).aspx)


---



MIT License. Copyright (c) 2020 Strontic.


