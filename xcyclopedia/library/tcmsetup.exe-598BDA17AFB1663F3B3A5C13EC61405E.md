---
title: tcmsetup.exe | Microsoft Windows(TM) Telephony Administration Setup
---

# tcmsetup.exe 

* File Path: `C:\windows\system32\tcmsetup.exe`
* Description: Microsoft Windows(TM) Telephony Administration Setup
* Comments: 

## Screenshot

![tcmsetup.exe](screenshots/tcmsetup.exe-2A3CCDB782638FD831250BC528F3CB5E-1.png)

## Hashes

Type | Hash
-- | --
MD5 | `598BDA17AFB1663F3B3A5C13EC61405E`
SHA1 | `70E3553AC283A0B121F420CA05E3AEEFDEF2A903`
SHA256 | `69420A6F5A963337087EB774BB3BC4E3AC18CE8A443792591CFCA6811E094584`
SHA384 | `4A9DFA70EC46B43A731F52CD91CE03D4034061510663284FFE5C6DAB782E53418484CC153E35DE70EAD8CA5675DB95C3`
SHA512 | `11F7383AE958410C8AF8200139DC977508CC48A944C913D28BD395D8F0921F04DCF213EA443B91510225CFDC3C9283F8106769BB8DBEAC3E386A3E56696151F9`
SSDEEP | `192:yebIMC8k7HAoEQggMaPTy4SOv0Urr+ppuzRQKS/SG77p7d2+TGWGpoW:FbTk+Qgncy4SO8Y++vG77tGWGpoW`

## Runtime Data

### Usage (stdout):
```Batchfile

```

### Usage (stderr):
```Batchfile

```

### Child Processes:


## Signature

* Status: The file C:\windows\system32\tcmsetup.exe is not digitally signed. You cannot run this script on the current system. For more information about running scripts and setting execution policy, see about_Execution_Policies at http://go.microsoft.com/fwlink/?LinkID=135170
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


