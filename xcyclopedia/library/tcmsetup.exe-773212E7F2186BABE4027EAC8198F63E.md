---
title: tcmsetup.exe | Microsoft Windows(TM) Telephony Administration Setup
---

# tcmsetup.exe 

* File Path: `C:\windows\SysWOW64\tcmsetup.exe`
* Description: Microsoft Windows(TM) Telephony Administration Setup
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `773212E7F2186BABE4027EAC8198F63E`
SHA1 | `9A47400C692AB5A423CEA4F6D0BCEE1C25D17E27`
SHA256 | `C1455B1E8C9F3D41B7D131B296215BA912A312907049CA36844D1CF472DA2857`
SHA384 | `9B95549E3D69697DC29B5B8EF6D21AAE8EF82FFF1D65E9966CC0C3C5650B2B4E69FE9881F5FD1771F5C0E78CC135FDA7`
SHA512 | `981DD8F111641171BD43A5027E958347743E6FF205ABCCF53FEDF1F8BCF69EA88E1326190CA3C4AD23FCA3EFEE0DAC0A9E214DF35676AC1B276874BA95229C03`
SSDEEP | `192:auSV5gIBIKfHqgDqp8X4g1EDTT+GWO+JdL3ohvYWGpoW3M:9SPl2UKJyXlgntFvYWGpoWc`

## Runtime Data

### Usage (stdout):
```Batchfile

```

### Usage (stderr):
```Batchfile

```

### Child Processes:


## Signature

* Status: The file C:\windows\SysWOW64\tcmsetup.exe is not digitally signed. You cannot run this script on the current system. For more information about running scripts and setting execution policy, see about_Execution_Policies at http://go.microsoft.com/fwlink/?LinkID=135170
* Serial: ``
* Thumbprint: ``
* Issuer: 
* Subject: 

## File Metadata

* Original Filename: TCMSETUP.EXE.MUI
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 6.3.9600.16384 (winblue_rtm.130821-1623)
* Product Version: 6.3.9600.16384
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


