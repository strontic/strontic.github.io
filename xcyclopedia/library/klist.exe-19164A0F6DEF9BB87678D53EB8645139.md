---
title: klist.exe | Tool for managing the Kerberos ticket cache
excerpt: What is klist.exe?
---

# klist.exe 

* File Path: `C:\Windows\system32\klist.exe`
* Description: Tool for managing the Kerberos ticket cache

## Hashes

Type | Hash
-- | --
MD5 | `19164A0F6DEF9BB87678D53EB8645139`
SHA1 | `41D5CAEECA4018A8C25EF7540300D38889BB9DA8`
SHA256 | `4F9808998461B5E994A81FC8525D495697FD6F5957C3BAA1503D6A2DAAB59692`
SHA384 | `73E43D307BEFA8C860E041EA818FECF9DABC6BBB73A7DA7BA16F4ACBBBF088951FEFF0918A5A6F70F20154F385BEAEB7`
SHA512 | `E91C2BEB1452FF044901F6F0D997B34250E64B061EBC7EF141061F96253B2544F5D6C35F9E507CBC21BA5465E68CB8EF44DE679FF0E866C9FF443788F8B6CC9E`
SSDEEP | `1536:w7KzPhAH0nsb7K3SwS4BvIkv5fdIJKIQvYV4evTuxvSq7KBFBsOn4t:w7iCh6i/rS5aVEUTLBFOf`
IMP | `D235A5641DE014C6EFBCA43F72899449`
PESHA1 | `FF84BCD1C296331C8C6ECDA4FD12CF74F68149F6`
PE256 | `0E22BAC22910CEC5BFBE61AF494821A42773590E2D1AEEB49AB2F59675C2F567`

## Runtime Data

### Usage (stdout):
```cmhg

Usage: klist.exe [command]

Command list:
  [tickets] [-lh <LogonId.HighPart>] [-li <LogonId.LowPart>]
  tgt [-lh <LogonId.HighPart>] [-li <LogonId.LowPart>]
  purge [-lh <LogonId.HighPart>] [-li <LogonId.LowPart>]
  sessions [-lh <LogonId.HighPart>] [-li <LogonId.LowPart>]
  kcd_cache [-lh <LogonId.HighPart>] [-li <LogonId.LowPart>]
  get <SPN> [-lh <LogonId.HighPart>] [-li <LogonId.LowPart>]
            [-kdcoptions <options>] [-cacheoptions <options>]
  add_bind <DOMAIN> <DC>
  query_bind
  purge_bind
  cloud_debug

```

### Loaded Modules:

Path |
-- |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\system32\klist.exe |
C:\Windows\SYSTEM32\ntdll.dll |


## Signature

* Status: Signature verified.
* Serial: `33000002EC6579AD1E670890130000000002EC`
* Thumbprint: `F7C2F2C96A328C13CDA8CDB57B715BDEA2CBD1D9`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: klist.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/73
* VirusTotal Link: https://www.virustotal.com/gui/file/4f9808998461b5e994a81fc8525d495697fd6f5957c3baa1503d6a2daab59692/detection


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



MIT License. Copyright (c) 2020-2021 Strontic.


