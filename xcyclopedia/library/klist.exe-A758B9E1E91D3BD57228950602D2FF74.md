---
title: klist.exe | Tool for managing the Kerberos ticket cache
excerpt: What is klist.exe?
---

# klist.exe 

* File Path: `C:\windows\system32\klist.exe`
* Description: Tool for managing the Kerberos ticket cache

## Hashes

Type | Hash
-- | --
MD5 | `A758B9E1E91D3BD57228950602D2FF74`
SHA1 | `8233D14848E3ECA0F3B1631B910F425EDE4E2548`
SHA256 | `3A73E088BE5A83D9C15D57B59309B193BB8848FC8BE5838F333D25D6B72FC858`
SHA384 | `B22CA109C789613C4DDD41CEF4E338577BA1527B998250B3F2D918CE4B7C7501F42279768D789591090C26DF440E6EC1`
SHA512 | `00AEF735F6DF6ACD82FEB838CB52AC94E38DDA24FED03CC83309CA5A3002BA10ECB59B710CA4930924F1A1D632E6A84CD42FC32F786EADB958F923B6B12BD1A5`
SSDEEP | `768:WNQ8Fci4q8a1YjKG3ZL4wdeviktNJeEr+sQ90RQkHw/qe/C/beQocawO/MFx:WaKKde3tNwsjRQk72DQvO/Mv`

## Signature

* Status: The file C:\windows\system32\klist.exe is not digitally signed. You cannot run this script on the current system. For more information about running scripts and setting execution policy, see about_Execution_Policies at http://go.microsoft.com/fwlink/?LinkID=135170
* Serial: ``
* Thumbprint: ``
* Issuer: 
* Subject: 

## File Metadata

* Original Filename: klist.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 6.3.9600.16384 (winblue_rtm.130821-1623)
* Product Version: 6.3.9600.16384
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.



## Possible Misuse

*The following table contains possible examples of `klist.exe` being misused. While `klist.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1558.001.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1558.001/T1558.001.md) | klist purge | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1558.001.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1558.001/T1558.001.md) | klist | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)

## Additional Info*

**The information below is copied from [MicrosoftDocs](https://github.com/MicrosoftDocs/windowsserverdocs), which is maintained by [Microsoft](https://opensource.microsoft.com/codeofconduct/). Available under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) license.*

---

## klist

Displays a list of currently cached Kerberos tickets.

> [!IMPORTANT]
> You must be at least a **Domain Admin**, or equivalent, to run all the parameters of this command.

### Syntax

```
klist [-lh <logonID.highpart>] [-li <logonID.lowpart>] tickets | tgt | purge | sessions | kcd_cache | get | add_bind | query_bind | purge_bind
```

#### Parameters

| Parameter | Description |
| --------- | ----------- |
| -lh | Denotes the high part of the user's locally unique identifier (LUID), expressed in hexadecimal. If neither **â€“lh** nor **â€“li** are present, the command defaults to the LUID of the user who is currently signed in. |
| -li | Denotes the low part of the user's locally unique identifier (LUID), expressed in hexadecimal. If neither **â€“lh** nor **â€“li** are present, the command defaults to the LUID of the user who is currently signed in. |
| tickets | Lists the currently cached ticket-granting-tickets (TGTs), and service tickets of the specified logon session. This is the default option. |
| tgt | Displays the initial Kerberos TGT. |
| purge | Allows you to delete all the tickets of the specified logon session. |
| sessions | Displays a list of logon sessions on this computer. |
| kcd_cache | Displays the Kerberos constrained delegation cache information. |
| get | Allows you to request a ticket to the target computer specified by the service principal name (SPN). |
| add_bind | Allows you to specify a preferred domain controller for Kerberos authentication. |
| query_bind | Displays a list of cached preferred domain controllers for each domain that Kerberos has contacted. |
| purge_bind | Removes the cached preferred domain controllers for the domains specified. |
| kdcoptions | Displays the Key Distribution Center (KDC) options specified in RFC 4120. |
| /? | Displays Help for this command. |

##### Remarks

- If no parameters are provided, **klist** retrieves all the tickets for the currently logged on user.

- The parameters display the following information:

  - **tickets** - Lists the currently cached tickets of services that you have authenticated to since logon. Displays the following attributes of all cached tickets:

    - **LogonID:** The LUID.

    - **Client:** The concatenation of the client name and the domain name of the client.

    - **Server:** The concatenation of the service name and the domain name of the service.

    - **KerbTicket Encryption Type:** The encryption type that is used to encrypt the Kerberos ticket.

    - **Ticket Flags:** The Kerberos ticket flags.

    - **Start Time:** The time from which the ticket is valid.

    - **End Time:** The time the ticket becomes no longer valid. When a ticket is past this time, it can no longer be used to authenticate to a service or be used for renewal.

    - **Renew Time:** The time that a new initial authentication is required.

    - **Session Key Type:** The encryption algorithm that is used for the session key.

  - **tgt** - Lists the initial Kerberos TGT and the following attributes of the currently cached ticket:

    - **LogonID:** Identified in hexadecimal.

    - **ServiceName:** krbtgt

    - **TargetName `<SPN>`:** krbtgt

    - **DomainName:** Name of the domain that issues the TGT.

    - **TargetDomainName:** Domain that the TGT is issued to.

    - **AltTargetDomainName:** Domain that the TGT is issued to.

    - **Ticket Flags:** Address and target actions and type.

    - **Session Key:** Key length and encryption algorithm.

    - **StartTime:** Local computer time that the ticket was requested.

    - **EndTime:** Time the ticket becomes no longer valid. When a ticket is past this time, it can no longer be used to authenticate to a service.

    - **RenewUntil:** Deadline for ticket renewal.

    - **TimeSkew:** Time difference with the Key Distribution Center (KDC).

    - **EncodedTicket:** Encoded ticket.

  - **purge** - Allows you to delete a specific ticket. Purging tickets destroys all tickets that you have cached, so use this attribute with caution. It might stop you from being able to authenticate to resources. If this happens, you'll have to log off and log on again.

    - **LogonID:** Identified in hexadecimal.

  - **sessions** - Allows you to list and display the information for all logon sessions on this computer.

    - **LogonID:** If specified, displays the logon session only by the given value. If not specified, displays all the logon sessions on this computer.

  - **kcd_cache** - Allows you to display the Kerberos constrained delegation cache information.

    - **LogonID:** If specified, displays the cache information for the logon session by the given value. If not specified, displays the cache information for the current user's logon session.

  - **get** - Allows you to request a ticket to the target that is specified by the SPN.

    - **LogonID:** If specified, requests a ticket by using the logon session by the given value. If not specified, requests a ticket by using the current user's logon session.

    - **kdcoptions:** Requests a ticket with the given KDC options

  - **add_bind** - Allows you to specify a preferred domain controller for Kerberos authentication.

  - **query_bind** - Allows you to display cached, preferred domain controllers for the domains.

  - **purge_bind** - Allows you to remove cached, preferred domain controllers for the domains.

  - **kdcoptions** - For the current list of options and their explanations, see [RFC 4120](http://www.ietf.org/rfc/rfc4120.txt).

#### Examples

To query the Kerberos ticket cache to determine if any tickets are missing, if the target server or account is in error, or if the encryption type is not supported due to an Event ID 27 error, type:

```
klist
```

```
klist â€“li 0x3e7
```

To learn about the specifics of each ticket-granting-ticket that is cached on the computer for a logon session, type:

```
klist tgt
```

To purge the Kerberos ticket cache, log off, and then log back on,  type:

```
klist purge
```

```
klist purge â€“li 0x3e7
```

To diagnose a logon session and to locate a logonID for a user or a service, type:

```
klist sessions
```

To diagnose Kerberos constrained delegation failure, and to find the last error that was encountered, type:

```
klist kcd_cache
```

To diagnose if a user or a service can get a ticket to a server, or to request a ticket for a specific SPN, type:

```
klist get host/%computername%
```

To diagnose replication issues across domain controllers, you typically need the client computer to target a specific domain controller. To target the client computer to the specific domain controller, type:

```
klist add_bind CONTOSO KDC.CONTOSO.COM
```

```
klist add_bind CONTOSO.COM KDC.CONTOSO.COM
```

To query which domain controllers were recently contacted by this computer, type:

```
klist query_bind
```

To rediscover domain controllers, or to flush the cache before creating new domain controller bindings with `klist add_bind`, type:

```
klist purge_bind
```

### Additional References

- [Command-Line Syntax Key](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/command-line-syntax-key.md)

---



MIT License. Copyright (c) 2020 Strontic.


