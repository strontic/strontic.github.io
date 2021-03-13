---
title: tcmsetup.exe | Microsoft Windows(TM) Telephony Administration Setup
excerpt: What is tcmsetup.exe?
---

# tcmsetup.exe 

* File Path: `C:\Windows\SysWOW64\tcmsetup.exe`
* Description: Microsoft Windows(TM) Telephony Administration Setup

## Screenshot

![tcmsetup.exe](screenshots/tcmsetup.exe-2A3CCDB782638FD831250BC528F3CB5E-1.png)

## Hashes

Type | Hash
-- | --
MD5 | `F03C345FE3B1666D85A1CB2C715491F8`
SHA1 | `AED3CAB95CF6722FF146915905D8DF93FE945B50`
SHA256 | `1445308B23F4B6C5172985E954D9DF024C817EA7E8F2F3D9A59B8D311FE843DC`
SHA384 | `194C8F196CD9C0E488F3315900BDE67DC44D8E147AAA666860ADB714994AA6C49752C1923B30B8ECC14634A693419A05`
SHA512 | `8B1E09D2A4F637576FAF9DCB89CE62F2CCE85A14EDE8DF6A71660FEF80CAABE2A419DAF4FB96034D833A4862676F0219DF9785C4A9728CA9C51055DF41895BA6`
SSDEEP | `192:s2FcUxt1Gfc5+zh87KXvwrxDQDcTfbaoadRf+voWGEoW7+Nu:TzDaDXvwN/z7jvoWGEoWSI`

## Signature

* Status: Signature verified.
* Serial: `33000000BCE120FDD27CC8EE930000000000BC`
* Thumbprint: `E85459B23C232DB3CB94C7A56D47678F58E8E51E`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: TCMSETUP.EXE.MUI
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.14393.0 (rs1_release.160715-1616)
* Product Version: 10.0.14393.0
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.




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



MIT License. Copyright (c) 2020-2021 Strontic.


