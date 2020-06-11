
# ksetup.exe 

* File Path: `C:\Windows\SysWOW64\ksetup.exe`
* Description: Kerberos Setup tool
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `DC949023143F0672926669523C18C5D3`
SHA1 | `36599B3871F7B785F3FF890EFB0680FDBCB9E76A`
SHA256 | `1DBE0A1A0FC8E8ABEDA38DF7C81538296033D8D857C83B8C22B95A109C3FFA8F`
SHA384 | `B49FD87A6694C32991DA685F594E3980CD448BC49DB1B9932B8691DD50E53DC5B440DF0745F69D16049946B61A613753`
SHA415 | `89204168C484B8199A67D2F833C1533974EC0574BFE572A638C255FC0246D56DD31DAB03F92F2CCE2911C4BFEF08CAF2BF7521FA3E1196BAED3D1CC7152396CA`
SSDEEP | `384:lpbmAwwWaM/kDonLvuAiaSR/dUbhdORa4RdTRXqcHw+R9pdri84Vey4W9ExWZuEb:gwWaMVnLv1AodOlRucQ+RP4VekE4tln`

## Runtime Data

### Usage (stdout):
```Batchfile

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

### Usage (stderr):
```Batchfile

```

### Child Processes:


## Signature

* Status: Signature verified.
* Serial: 33000000BCE120FDD27CC8EE930000000000BC
* Thumbprint: E85459B23C232DB3CB94C7A56D47678F58E8E51E
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: ksetup.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.14393.0 (rs1_release.160715-1616)
* Product Version: 10.0.14393.0
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.

MIT License. Copyright (c) 2020 Strontic.


