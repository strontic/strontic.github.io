﻿---
title: ksetup.exe | Kerberos Setup tool
excerpt: What is ksetup.exe?
---

# ksetup.exe 

* File Path: `C:\WINDOWS\system32\ksetup.exe`
* Description: Kerberos Setup tool

## Hashes

Type | Hash
-- | --
MD5 | `07C2E5DAB5DD7323B5D9E72A4B83628D`
SHA1 | `98EE1A6788707D7B0F5C66C40C010617A7E5CE76`
SHA256 | `70E439F5F43B02D24D94C32FF837D35E29B12C5EED913D29C2F7E3E07A5FECA4`
SHA384 | `6BE6962EE9BF44ADCC76D91EB084C508AE875BB7614A3A02D1E03D9C79A178F1CD16104F44C3BCFAB17F9EB2AA96F70D`
SHA512 | `0F1430DF6B4793420E28B10274355B6C2917F006841EC2116F6E7E4D7CC95CD1A5B6CA31D62A1FE18C122D082112179E838B8C088030074E57CDDA35FE7C73A8`
SSDEEP | `1536:Zf5wssqKDpvbZ88144TV/34AlPJSDZDsUVNk:Vi2814cN3QNk`
IMP | `5527A2A68B8C18DB5E49E2664C4A8B67`
PESHA1 | `4A32D5E9899F1F6E9206FC746ACA737844FF23D3`
PE256 | `319854A337B5AF306620C212381D1E6298AFCA214B0672DAAE0A0971E54065EA`

## Runtime Data

### Usage (stdout):
```cmhg

USAGE:
/SetRealm <DnsDomainName>
	Makes this computer a member of an RFC1510 Kerberos Realm
/MapUser <Principal> [Account]
	Maps a Kerberos Principal ('*' = any principal)
	to an account ('*' = an account by same name);
	If account name is omitted, mapping is deleted 
	for the specified principal
/AddKdc <RealmName> [KdcName]
	Defines a KDC entry for the given realm.
	If KdcName omitted, DNS may be used to locate KDCs.
/DelKdc <RealmName> [KdcName]
	deletes a KDC entry for the realm.
	If KdcName omitted, the realm entry itself is deleted.
/AddKpasswd <Realmname> <KpasswdName>
	Add Kpasswd server address for a realm
/DelKpasswd <Realmname> <KpasswdName>
	Delete Kpasswd server address for a realm
/Server <Servername>
	specify name of a Windows machine to target the changes.
/SetComputerPassword <Password>
	Sets the password for the computer's domain account
	(or host principal)
/RemoveRealm <RealmName>
	delete all information for this realm from the registry.
/Domain [DomainName]
	use this domain (if DomainName is unspecified, detect it)
/ChangePassword <OldPasswd> <NewPasswd>
	Use Kpasswd to change the logged-on user's password.
	Use '*' to be prompted for passwords.
/ListRealmFlags (no args)
	Lists the available Realm flags that ksetup knows
/SetRealmFlags <realm> <flag> [flag] [flag] [...]
	Sets RealmFlags for a specific realm
/AddRealmFlags <realm> <flag> [flag] [flag] [...]
	Adds additional RealmFlags to a realm
/DelRealmFlags <realm> <flag> [flag] [flag] [...]
	Deletes RealmFlags from a realm.
/DumpState (no args)
	Analyze the kerberos configuration on the given machine.
/AddHostToRealmMap <host> <realm>
	Adds a mapping for <host> to <realm> to the registry.
/DelHostToRealmMap <host> <realm>
	Deletes existing mapping for <host> to <realm> from the registry.
/SetEncTypeAttr <domainname> <enctypes>
	Sets the encryption types trust attribute for <domain> to <enctypes> (multiple types should be separated by spaces).
	Supported encryption types are:
	  DES-CBC-CRC, DES-CBC-MD5, RC4-HMAC-MD5, 
	  AES128-CTS-HMAC-SHA1-96, AES256-CTS-HMAC-SHA1-96
/GetEncTypeAttr <domainname>
	Gets the encryption types trust attribute for <domain>.
/AddEncTypeAttr <domainname> <enctypes>
	Adds <enctypes> to the encryption types trust attribute for <domain> (multiple types should be separated by spaces).
/DelEncTypeAttr <domainname>
	Deletes the encryption types trust attribute for <domain>.

```

### Loaded Modules:

Path |
-- |
C:\WINDOWS\System32\KERNEL32.DLL |
C:\WINDOWS\System32\KERNELBASE.dll |
C:\WINDOWS\system32\ksetup.exe |
C:\WINDOWS\SYSTEM32\ntdll.dll |


## Signature

* Status: Signature verified.
* Serial: `33000002ED2C45E4C145CF48440000000002ED`
* Thumbprint: `312860D2047EB81F8F58C29FF19ECDB4C634CF6A`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: ksetup.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.22000.1 (WinBuild.160101.0800)
* Product Version: 10.0.22000.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/73
* VirusTotal Link: https://www.virustotal.com/gui/file/70e439f5f43b02d24d94c32ff837d35e29b12c5eed913d29c2f7e3e07a5feca4/detection



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


