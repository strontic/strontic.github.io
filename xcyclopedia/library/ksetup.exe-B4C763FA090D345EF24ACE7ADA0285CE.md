---
title: ksetup.exe | Kerberos Setup tool
excerpt: What is ksetup.exe?
---

# ksetup.exe 

* File Path: `C:\windows\system32\ksetup.exe`
* Description: Kerberos Setup tool

## Hashes

Type | Hash
-- | --
MD5 | `B4C763FA090D345EF24ACE7ADA0285CE`
SHA1 | `209B203B41AF29A84B4C0C1F84872B434F94E74A`
SHA256 | `80A7E82326DC311CFD9DEE9CC2BBA4E744F4E5A99BA2E298AB7DD966170F1831`
SHA384 | `016DF03470349EDB65D0F6ECCA8D2D4AE698A8CF386762794F7BB19A0937BA91E60B621A4498A17450553C10B1D6A657`
SHA512 | `6D6B096969E516F62C3908CB7B87762632CFBBA25FA69FEAF3C7B39F5031CCA6DAB18DC3A377FDABADAEF0959F800CCFCD8003C1DF431C8312F7838A2BF7C683`
SSDEEP | `768:ewYDtXYI/h8vZQvrM/uwCVl46noXpdReL5No3a5BOpEe2JlKJy:KPeOSXfRZa5BOWe2qJ`

## Signature

* Status: The file C:\windows\system32\ksetup.exe is not digitally signed. You cannot run this script on the current system. For more information about running scripts and setting execution policy, see about_Execution_Policies at http://go.microsoft.com/fwlink/?LinkID=135170
* Serial: ``
* Thumbprint: ``
* Issuer: 
* Subject: 

## File Metadata

* Original Filename: ksetup.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 6.3.9600.16384 (winblue_rtm.130821-1623)
* Product Version: 6.3.9600.16384
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.




## Additional Info*

**The information below is copied from [MicrosoftDocs](https://github.com/MicrosoftDocs/windowsserverdocs), which is maintained by [Microsoft](https://opensource.microsoft.com/codeofconduct/). Available under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) license.*

---

## ksetup

Performs tasks related to setting up and maintaining Kerberos protocol and the Key Distribution Center (KDC) to support Kerberos realms. Specifically, this command is used to:

- Change the computer settings for locating Kerberos realms. In non-Microsoft, Kerberosâ€“based implementations, this information is usually kept in the Krb5.conf file. In Windows Server operating systems, it's kept in the registry. You can use this tool to modify these settings. These settings are used by workstations to locate Kerberos realms and by domain controllers to locate Kerberos realms for cross-realm trust relationships.

- Initialize registry keys that the Kerberos Security Support Provider (SSP) uses to locate a KDC for the Kerberos realm, if the computer is isn't a member of a Windows domain. After configuration, the user of a client computer running the Windows operating system can log on to accounts in the Kerberos realm.

- Search the registry for the domain name of the user's realm and then resolves the name to an IP address by querying a DNS server. The Kerberos protocol can use DNS to locate KDCs by using only the realm name, but it must be specially configured to do so.

### Syntax

```
ksetup
[/setrealm <DNSdomainname>]
[/mapuser <principal> <account>]
[/addkdc <realmname> <KDCname>]
[/delkdc <realmname> <KDCname>]
[/addkpasswd <realmname> <KDCPasswordName>]
[/delkpasswd <realmname> <KDCPasswordName>]
[/server <servername>]
[/setcomputerpassword <password>]
[/removerealm <realmname>]
[/domain <domainname>]
[/changepassword <oldpassword> <newpassword>]
[/listrealmflags]
[/setrealmflags <realmname> [sendaddress] [tcpsupported] [delegate] [ncsupported] [rc4]]
[/addrealmflags <realmname> [sendaddress] [tcpsupported] [delegate] [ncsupported] [rc4]]
[/delrealmflags [sendaddress] [tcpsupported] [delegate] [ncsupported] [rc4]]
[/dumpstate]
[/addhosttorealmmap] <hostname> <realmname>]
[/delhosttorealmmap] <hostname> <realmname>]
[/setenctypeattr] <domainname> {DES-CBC-CRC | DES-CBC-MD5 | RC4-HMAC-MD5 | AES128-CTS-HMAC-SHA1-96 | AES256-CTS-HMAC-SHA1-96}
[/getenctypeattr] <domainname>
[/addenctypeattr] <domainname> {DES-CBC-CRC | DES-CBC-MD5 | RC4-HMAC-MD5 | AES128-CTS-HMAC-SHA1-96 | AES256-CTS-HMAC-SHA1-96}
[/delenctypeattr] <domainname>
```

#### Parameters

| Parameter | Description |
| --------- | ----------- |
| [ksetup setrealm](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/ksetup-setrealm.md) | Makes this computer a member of a Kerberos realm. |
| [ksetup addkdc](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/ksetup-addkdc.md) | Defines a KDC entry for the given realm. |
| [ksetup delkdc](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/ksetup-delkdc.md) | Deletes a KDC entry for the realm. |
| [ksetup addkpasswd](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/ksetup-addkpasswd.md) | Adds a kpasswd server address for a realm. |
| [ksetup delkpasswd](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/ksetup-delkpasswd.md) | Deletes a kpasswd server address for a realm. |
| [ksetup server](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/ksetup-server.md) | Allows you to specify the name of a Windows computer on which to apply the changes. |
| [ksetup setcomputerpassword](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/ksetup-setcomputerpassword.md) | Sets the password for the computer's domain account (or host principal). |
| [ksetup removerealm](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/ksetup-removerealm.md) | Deletes all information for the specified realm from the registry. |
| [ksetup domain](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/ksetup-domain.md) | Allows you to specify a domain (if the `<domainname>` hasn't already been set by the **/domain** parameter). |
| [ksetup changepassword](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/ksetup-changepassword.md) | Allows you to use the kpasswd to change the logged on user's password. |
| [ksetup listrealmflags](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/ksetup-listrealmflags.md) | Lists the available realm flags that **ksetup** can detect. |
| [ksetup setrealmflags](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/ksetup-setrealmflags.md) | Sets realm flags for a specific realm. |
| [ksetup addrealmflags](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/ksetup-addrealmflags.md) | Adds additional realm flags to a realm. |
| [ksetup delrealmflags](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/ksetup-delrealmflags.md) | Deletes realm flags from a realm. |
| [ksetup dumpstate](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/ksetup-dumpstate.md) | Analyzes the Kerberos configuration on the given computer. Adds a host to realm mapping to the registry. |
| [ksetup addhosttorealmmap](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/ksetup-addhosttorealmmap.md) | Adds a registry value to map the host to the Kerberos realm. |
| [ksetup delhosttorealmmap](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/ksetup-delhosttorealmmap.md) | Deletes the registry value that mapped the host computer to the Kerberos realm. |
| [ksetup setenctypeattr](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/ksetup-setenctypeattr.md) | Sets one or more encryption types trust attributes for the domain. |
| [ksetup getenctypeattr](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/ksetup-getenctypeattr.md) | Gets the encryption types trust attribute for the domain. |
| [ksetup addenctypeattr](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/ksetup-addenctypeattr.md) | Adds encryption types to the encryption types trust attribute for the domain. |
| [ksetup delenctypeattr](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/ksetup-delenctypeattr.md) | Deletes the encryption types trust attribute for the domain. |
| /? | Displays Help at the command prompt. |

### Additional References

- [Command-Line Syntax Key](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/command-line-syntax-key.md)

---



MIT License. Copyright (c) 2020-2021 Strontic.


