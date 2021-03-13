---
title: klist.exe | OpenJDK Platform binary
excerpt: What is klist.exe?
---

# klist.exe 

* File Path: `C:\program files (x86)\Amazon Corretto\jdk1.8.0_265\bin\klist.exe`
* Description: OpenJDK Platform binary

## Hashes

Type | Hash
-- | --
MD5 | `6A970FBA630D67B0F087637DB56EC0C2`
SHA1 | `5C2589ADA01DDA7659D392B4F26C76A00A2204AB`
SHA256 | `0E34904ADC201CD1AC3B9FFCA29B53D33A16F9C3B8088A5E0EFA41ECA8413D33`
SHA384 | `1884B6E1B899E8A18A2A65B33B0F59328855090F6C55AFAAB3287F0083AC75C6F984C51B28BF5B79E4C8FCCD72D3F176`
SHA512 | `A9D0D799E880421C60C71082158B0737C43C17523D778AEBB9D581A795168DEC3EBDAFAFB92DA61B8574619127C5BC99A6A35FAA278407D70A84FFED2DBFC7CA`
SSDEEP | `384:GpsN5hn+qdmSHhV8hwee74SzQK6jSfz9XDgf2hc5:Gps9nYS/8hFe7OKgwz9Uf2he`

## Runtime Data

### Usage (stdout):
```cmhg

Usage: klist [[-c] [-f] [-e] [-a [-n]]] [-k [-t] [-K]] [name]
   name	 name of credentials cache or  keytab with the prefix. File-based cache or keytab's prefix is FILE:.
   -c specifies that credential cache is to be listed
   -k specifies that key tab is to be listed
   options for credentials caches:
	-f 	 shows credentials flags
	-e 	 shows the encryption type
	-a 	 shows addresses
	  -n 	   do not reverse-resolve addresses
   options for keytabs:
	-t 	 shows keytab entry timestamps
	-K 	 shows keytab entry key value
	-e 	 shows keytab entry key type

Usage: java sun.security.krb5.tools.Klist -help for help.

```

### Loaded Modules:

Path |
-- |
C:\program files (x86)\Amazon Corretto\jdk1.8.0_265\bin\klist.exe |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\wow64.dll |
C:\Windows\System32\wow64cpu.dll |
C:\Windows\System32\wow64win.dll |


## Signature

* Status: Signature verified.
* Serial: `2F83C35B5136353D68CE9EB669FD1B0B`
* Thumbprint: `4BAD227329ADEF18F215B6475FB7948E1629B505`
* Issuer: CN=Symantec Class 3 SHA256 Code Signing CA, OU=Symantec Trust Network, O=Symantec Corporation, C=US
* Subject: CN=Amazon.com Services LLC, OU=Software Services, O=Amazon.com Services LLC, L=Seattle, S=Washington, C=US

## File Metadata

* Original Filename: klist.exe
* Product Name: OpenJDK Platform 8
* Company Name: Amazon.com Inc.
* File Version: 8.0.2650.1
* Product Version: 8.0.2650.1
* Language: Language Neutral
* Legal Copyright: Copyright  2020


## File Similarity (ssdeep match)

File | Score
-- | --
[C:\program files (x86)\Amazon Corretto\jdk1.8.0_265\bin\tnameserv.exe](tnameserv.exe-3274B8934FBFB5CB07060033719BAB5E.md) | 60
[C:\program files (x86)\Amazon Corretto\jdk1.8.0_265\jre\bin\klist.exe](klist.exe-DF405170A9755BF4C0A2817D16E67147.md) | 85
[C:\program files (x86)\Amazon Corretto\jdk1.8.0_265\jre\bin\tnameserv.exe](tnameserv.exe-7874489E19C78924C05D3BF61EA807EC.md) | 60
[C:\program files (x86)\Amazon Corretto\jre8\bin\klist.exe](klist.exe-6EC7CA20366247C1BBAA9E68103B9520.md) | 82
[C:\program files (x86)\Amazon Corretto\jre8\bin\rmid.exe](rmid.exe-D8EC5ABE57565E6260EA2D62D74EF506.md) | 71
[C:\program files (x86)\Amazon Corretto\jre8\bin\tnameserv.exe](tnameserv.exe-55DC2860B7D0F30D785998CC1ABA5B4E.md) | 60

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


