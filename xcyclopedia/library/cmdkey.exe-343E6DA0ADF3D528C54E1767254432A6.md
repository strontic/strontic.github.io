
# cmdkey.exe 

* File Path: `C:\Windows\system32\cmdkey.exe`
* Description: Credential Manager Command Line Utility
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `343E6DA0ADF3D528C54E1767254432A6`
SHA1 | `AD489907F7EE31329CC09E70E21FF70B8EF43DB1`
SHA256 | `89B6A8CB5CF989E3D999482CECF779BA295871A9C80C8CA151694942D5881114`
SHA384 | `861113EC543A92759B4A659F0027A6E1C2C0B91A35E7721C14A2793B4B0654A3A93A90187DD7335C8178F219BE1B947F`
SHA512 | `7BEA84928ED745BFDF9F22E11E2032168AF402B4BF76F35AB05CE2EE54CF1755385AAB74F2551CF74347FD212513DF15F7A08C9C4C9C3A2EA7211ACCA263D705`
SSDEEP | `384:uEpXrrS58wQb5Hm/D9LtkwkNdsHCybbm/rD1/D/8F62WQwW:7rSHQlH+YICmm/rD1b8Q4`

## Runtime Data

### Usage (stdout):
```Batchfile

Creates, displays, and deletes stored user names and passwords.

The syntax of this command is:

CMDKEY [{/add | /generic}:targetname {/smartcard | /user:username {/pass{:password}}} | /delete{:targetname | /ras} | /list{:targetname}]

Examples:

  To list available credentials:
     cmdkey /list
     cmdkey /list:targetname

  To create domain credentials:
     cmdkey /add:targetname /user:username /pass:password
     cmdkey /add:targetname /user:username /pass
     cmdkey /add:targetname /user:username
     cmdkey /add:targetname /smartcard
     
  To create generic credentials:
     The /add switch may be replaced by /generic to create generic credentials

  To delete existing credentials:
     cmdkey /delete:targetname

  To delete RAS credentials:
     cmdkey /delete /ras
     

```

### Usage (stderr):
```Batchfile

```

### Child Processes:


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: cmdkey.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.14393.0 (rs1_release.160715-1616)
* Product Version: 10.0.14393.0
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.




## Additional Info*

**The information below is copied from [MicrosoftDocs](https://github.com/MicrosoftDocs/windowsserverdocs), which is maintained by [Microsoft](https://opensource.microsoft.com/codeofconduct/). Available under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) license.*

---
# cmdkey

> Applies to: Windows Server (Semi-Annual Channel), Windows Server 2019, Windows Server 2016, Windows Server 2012 R2, Windows Server 2012

Creates, lists, and deletes stored user names and passwords or credentials.

## Syntax

```
cmdkey [{/add:<targetname>|/generic:<targetname>}] {/smartcard | /user:<username> [/pass:<password>]} [/delete{:<targetname> | /ras}] /list:<targetname>
```

### Parameters

| Parameters | Description |
| ---------- | ----------- |
| /add:`<targetname>` | Adds a user name and password to the list.<p>Requires the parameter of `<targetname>` which identifies the computer or domain name that this entry will be associated with. |
| /generic:`<targetname>` | Adds generic credentials to the list.<p>Requires the parameter of `<targetname>` which identifies the computer or domain name that this entry will be associated with. |
| /smartcard | Retrieves the credential from a smart card. If more than one smart card is found on the system when this option is used, **cmdkey** displays information about all available smart cards, and then prompts the user to specify which one to use. |
| /user:`<username>` | Specifies the user or account name to store with this entry. If `<username>` isn't supplied, it will be requested. |
|/pass:`<password>` | Specifies the password to store with this entry. If `<password>` isn't supplied, it will be requested. Passwords are not displayed after they're stored. |
| /delete{:`<targetname>` | /ras} | Deletes a user name and password from the list. If `<targetname>` is specified, that entry is deleted. If `/ras` is specified, the stored remote access entry is deleted. |
| /list:`<targetname>` | Displays the list of stored user names and credentials. If `<targetname>` isn't specified, all stored user names and credentials are listed. |
| /? | Displays help at the command prompt. |

## Examples

To display a list of all user names and credentials that are stored, type:

```
cmdkey /list
```

To add a user name and password for user *Mikedan* to access computer *Server01* with the password *Kleo*, type:

```
cmdkey /add:server01 /user:mikedan /pass:Kleo
```

To add a user name and password for user *Mikedan* to access computer *Server01* and prompt for the password whenever Server01 is accessed, type:

```
cmdkey /add:server01 /user:mikedan
```

To delete a credential stored by remote access, type:

```
cmdkey /delete /ras
```

To delete a credential stored for *Server01*, type:

```
cmdkey /delete:server01
```

## Additional References

- [Command-Line Syntax Key](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/command-line-syntax-key.md)

---


MIT License. Copyright (c) 2020 Strontic.


