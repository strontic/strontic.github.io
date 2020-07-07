---
title: tcmsetup.exe | Microsoft Windows(TM) Telephony Administration Setup
---

# tcmsetup.exe 

* File Path: `C:\Windows\system32\tcmsetup.exe`
* Description: Microsoft Windows(TM) Telephony Administration Setup
* Comments: 

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
* Serial: `330000023241FB59996DCC4DFF000000000232`
* Thumbprint: `FF82BC38E1DA5E596DF374C53E3617F7EDA36B06`
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


