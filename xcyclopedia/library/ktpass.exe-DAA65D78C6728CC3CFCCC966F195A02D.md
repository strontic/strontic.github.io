﻿---
title: ktpass.exe | Kerberos keytab tool
excerpt: What is ktpass.exe?
---

# ktpass.exe 

* File Path: `C:\Windows\SysWOW64\ktpass.exe`
* Description: Kerberos keytab tool

## Hashes

Type | Hash
-- | --
MD5 | `DAA65D78C6728CC3CFCCC966F195A02D`
SHA1 | `534EF57DF649229E1633F0B91AC7F97E79A425D8`
SHA256 | `48B30EAFC82DC388DFE5BBD55C26C863FC3EC53ABEF16B2B8BB42BC7AD471885`
SHA384 | `5D93B853E7586D72831859D96CBE69F8A5FC617BB592AE3DA1F2186782C50B261A12DFAABCA50CDA1B688E346EABA29C`
SHA512 | `FC1AD93270F72E36FD06E6811E8335AD06EB4ED85C0BCA64232540A9DF3409C61B514936843C6D06513A176F6E1759D601DCA17747BF3644D7A732F2E38BD7D9`
SSDEEP | `1536:gRYcEn5C+md8bsCBjaQCQ1zITn9Gu/DD4:zvCHi1f0T9Gu/`
IMP | `6B4DAF16B8CA0A105FADE9AD3A440777`
PESHA1 | `F4F064B1528D3CAA4381F41E219CB36618C727A8`
PE256 | `04E5700505CD7F20F481B59D383535C4A889D024C9CFACF545BBFA4209ABDFD5`

## Runtime Data

### Usage (stderr):
```cmhg
unknown option '--help'.
Command line options:

---------------------most useful args
[- /]          out : Keytab to produce
[- /]        princ : Principal name (user@REALM)
[- /]         pass : password to use
                     use '*' to prompt for password.
[- +]      rndPass : ... or use +rndPass to generate a random password
[- /]      minPass : minimum length for random password (def:15)
[- /]      maxPass : maximum length for random password (def:256)
---------------------less useful stuff
[- /]      mapuser : map princ (above) to this user account (default: don't)
[- /]        mapOp : how to set the mapping attribute (default: add it)
[- /]        mapOp :  is one of: 
[- /]        mapOp :        add : add value (default) 
[- /]        mapOp :        set : set value 
[- +]      DesOnly : Set account for des-only encryption (default:don't)
[- /]           in : Keytab to read/digest
---------------------options for key generation
[- /]       crypto : Cryptosystem to use
[- /]       crypto :  is one of: 
[- /]       crypto : DES-CBC-CRC : for compatibility 
[- /]       crypto : DES-CBC-MD5 : for compatibility 
[- /]       crypto : RC4-HMAC-NT : default 128-bit encryption 
[- /]       crypto : AES256-SHA1 : AES256-CTS-HMAC-SHA1-96 
[- /]       crypto : AES128-SHA1 : AES128-CTS-HMAC-SHA1-96 
[- /]       crypto :        All : All supported types 
[- /]    IterCount : Iteration Count used for AES encryption
                     Default: ignored for non-AES, 4096 for AES
[- /]        ptype : principal type in question
[- /]        ptype :  is one of: 
[- /]        ptype : KRB5_NT_PRINCIPAL : The general ptype-- recommended 
[- /]        ptype : KRB5_NT_SRV_INST : user service instance 
[- /]        ptype : KRB5_NT_SRV_HST : host service instance 
[- /]        ptype : KRB5_NT_SRV_XHST :   
[- /]         kvno : Override Key Version Number
                     Default: query DC for kvno. Use /kvno 1 for Win2K compat.
[- +]       Answer : +Answer answers YES to prompts. -Answer answers NO.
[- /]       Target : Which DC to use. Default:detect
[- /]      RawSalt : raw salt to use when generating key (not needed)
[- +]     DumpSalt : show us the MIT salt being used to generate the key
[- +]       SetUpn : Set the UPN in addition to the SPN. Default DO.
[- +]      SetPass : Set the user's password if supplied.

```

### Loaded Modules:

Path |
-- |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\wow64.dll |
C:\Windows\System32\wow64cpu.dll |
C:\Windows\System32\wow64win.dll |
C:\Windows\SysWOW64\ktpass.exe |


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: ktpass.exe
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.17763.652 (WinBuild.160101.0800)
* Product Version: 10.0.17763.652
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/73
* VirusTotal Link: https://www.virustotal.com/gui/file/48b30eafc82dc388dfe5bbd55c26c863fc3ec53abef16b2b8bb42bc7ad471885/detection/



## Additional Info*

**The information below is copied from [MicrosoftDocs](https://github.com/MicrosoftDocs/windowsserverdocs), which is maintained by [Microsoft](https://opensource.microsoft.com/codeofconduct/). Available under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) license.*

---

## ktpass

>Applies to: Windows Server 2022, Windows Server 2019, Windows Server 2016, Windows Server 2012 R2, Windows Server 2012

Configures the server principal name for the host or service in Active Directory Domain Services (AD DS) and generates a .keytab file that contains the shared secret key of the service. The .keytab file is based on the Massachusetts Institute of Technology (MIT) implementation of the Kerberos authentication protocol. The ktpass command-line tool allows non-Windows services that support Kerberos authentication to use the interoperability features provided by the Kerberos Key Distribution Center (KDC) service.

### Syntax

```
ktpass
[/out <filename>]
[/princ <principalname>]
[/mapuser <useraccount>]
[/mapop {add|set}] [{-|+}desonly] [/in <filename>]
[/pass {password|*|{-|+}rndpass}]
[/minpass]
[/maxpass]
[/crypto {DES-CBC-CRC|DES-CBC-MD5|RC4-HMAC-NT|AES256-SHA1|AES128-SHA1|All}]
[/itercount]
[/ptype {KRB5_NT_PRINCIPAL|KRB5_NT_SRV_INST|KRB5_NT_SRV_HST}]
[/kvno <keyversionnum>]
[/answer {-|+}]
[/target]
[/rawsalt] [{-|+}dumpsalt] [{-|+}setupn] [{-|+}setpass <password>]  [/?|/h|/help]
```

#### Parameters

| Parameter | Description |
| --------- | ------------|
| /out `<filename>` | Specifies the name of the Kerberos version 5 .keytab file to generate. **Note:** This is the .keytab file you transfer to a computer that isn't running the Windows operating system, and then replace or merge with your existing .keytab file, */Etc/Krb5.keytab*. |
| /princ `<principalname>` | Specifies the principal name in the form host/computer.contoso.com@CONTOSO.COM. **Warning:** This parameter is case-sensitive. |
| /mapuser `<useraccount>` | Maps the name of the Kerberos principal, which is specified by the **princ** parameter, to the specified domain account. |
| /mapop `{add|set}` | Specifies how the mapping attribute is set.<ul><li>**Add** - Adds the value of the specified local user name. This is the default.</li><li>**Set** - Sets the value for Data Encryption Standard (DES)-only encryption for the specified local user name.</li></ul> |
| `{-|+}`desonly | DES-only encryption is set by default.<ul><li>**+** Sets an account for DES-only encryption.</li><li>**-** Releases restriction on an account for DES-only encryption. **Important:** Windows doesn't support DES by default.</li></ul> |
| /in `<filename>` | Specifies the .keytab file to read from a host computer that is not running the Windows operating system. |
| /pass `{password|*|{-|+}rndpass}` | Specifies a password for the principal user name that is specified by the **princ** parameter. Use `*` to prompt for a password. |
| /minpass | Sets the minimum length of the random password to 15 characters. |
| /maxpass | Sets the maximum length of the random password to 256 characters. |
| /crypto `{DES-CBC-CRC|DES-CBC-MD5|RC4-HMAC-NT|AES256-SHA1|AES128-SHA1|All}` | Specifies the keys that are generated in the keytab file:<ul><li>**DES-CBC-CRC** - Used for compatibility.</li><li>**DES-CBC-MD5** - Adheres more closely to the MIT implementation and is used for compatibility.</li><li>**RC4-HMAC-NT** - Employs 128-bit encryption.</li><li>**AES256-SHA1** - Employs AES256-CTS-HMAC-SHA1-96 encryption.</li><li>   **AES128-SHA1** - Employs AES128-CTS-HMAC-SHA1-96 encryption.</li><li>**All** - States that all supported cryptographic types can be used.</li></ul><p>**Note:** Because the default settings are based on older MIT versions, you should always use the `/crypto` parameter. |
| /itercount | Specifies the iteration count that is used for AES encryption. The default ignores **itercount** for non-AES encryption and sets AES encryption to 4,096. |
| /ptype `{KRB5_NT_PRINCIPAL|KRB5_NT_SRV_INST|KRB5_NT_SRV_HST}` | Specifies the principal type.<ul><li>**KRB5_NT_PRINCIPAL** - The general principal type (recommended).</li><li>**KRB5_NT_SRV_INST** - The user service instance</li><li>  **KRB5_NT_SRV_HST** - The host service instance</li></ul> |
| /kvno `<keyversionnum>` | Specifies the key version number. The default value is 1. |
| /answer `{-|+}` | Sets the background answer mode:<ul><li>**-** Answers reset password prompts automatically with **NO**.</li><li>**+** Answers reset password prompts automatically with **YES**.</li></ul> |
| /target | Sets which domain controller to use. The default is for the domain controller to be detected, based on the principal name. If the domain controller name doesn't resolve, a dialog box will prompt for a valid domain controller. |
| /rawsalt | forces ktpass to use the rawsalt algorithm when generating the key. This parameter is optional. |
| `{-|+}dumpsalt` | The output of this parameter shows the MIT salt algorithm that is being used to generate the key. |
| `{-|+}setupn` | Sets the user principal name (UPN) in addition to the service principal name (SPN). The default is to set both in the .keytab file. |
| `{-|+}setpass <password>` | Sets the user's password when supplied. If rndpass is used, a random password is generated instead. |
| /? | Displays Help for this command. |

##### Remarks

- Services running on systems that aren't running the Windows operating system can be configured with service instance accounts in AD DS. This allows any Kerberos client to authenticate to services that are not running the Windows operating system by using Windows KDCs.

- The **/princ** parameter isn't evaluated by ktpass and is used as provided. There's no check to see if the parameter matches the exact case of the **userPrincipalName** attribute value when generating the Keytab file. Case-sensitive Kerberos distributions using this Keytab file might have problems if there's no exact case match, and could even fail during pre-authentication. To check and retrieve the correct **userPrincipalName** attribute value from a LDifDE export file. For example:

    ```
    ldifde /f keytab_user.ldf /d CN=Keytab User,OU=UserAccounts,DC=contoso,DC=corp,DC=microsoft,DC=com /p base /l samaccountname,userprincipalname
    ````

#### Examples

To create a Kerberos .keytab file for a host computer that isn't running the Windows operating system, you must map the principal to the account and set the host principal password.

1. Use the active directory **User and computers** snap-in to create a user account for a service on a computer that is not running the Windows operating system. For example, create an account with the name *User1*.

2. Use the **ktpass** command to set up an identity mapping for the user account by typing:

    ```
    ktpass /princ host/User1.contoso.com@CONTOSO.COM /mapuser User1 /pass MyPas$w0rd /out machine.keytab /crypto all /ptype KRB5_NT_PRINCIPAL /mapop set
    ```

    > [!NOTE]
    > You cannot map multiple service instances to the same user account.

3. Merge the .keytab file with the */Etc/Krb5.keytab* file on a host computer that isn't running the Windows operating system.

### Additional References

- [Command-Line Syntax Key](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/command-line-syntax-key.md)

---



MIT License. Copyright (c) 2020-2021 Strontic.


