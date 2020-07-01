---
title: dcgpofix.exe | Microsoft (C) Default Group Policy Object Restore Utility
---

# dcgpofix.exe 

* File Path: `C:\windows\system32\dcgpofix.exe`
* Description: Microsoft (C) Default Group Policy Object Restore Utility
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `D78F40FD6F3B360FFF2D8CBDC34CDF2D`
SHA1 | `6FA6F1DF79F7D0E2C7D3AED1C0E09071ED7E8C72`
SHA256 | `5942323F73597499D9FC6D5E24CE23EE357B24E432C81349103D4DB8E47F3D74`
SHA384 | `98E059E47DAFB34AF9842E6D29944223B7D5241084357FD5FFA87DC740114A17CB224EBD4F3B8231CF78990D50247E87`
SHA512 | `84F1F85CC7044B155952C98F72ECB48121B1DDFFB91DD9AA63F677826B6F5169531DA45C05CA384E38744C3AEFAF77837762AB36B86AC8CCDA8F2B795C2F59DE`
SSDEEP | `1536:J/UeGWgt0lsWW8Jj79ynP+Jj4LyXqRVIji0:SsbNJEP+Jj4LyXaqjP`

## Runtime Data

### Usage (stdout):
```Batchfile

Microsoft(R) Windows(R) Operating System Default Group Policy Restore Utility v5.1

Copyright (C) Microsoft Corporation. 1981-2003

Description: Recreates the Default Group Policy Objects (GPOs) for a domain

Syntax: DcGPOFix [/ignoreschema] [/Target: Domain | DC | BOTH]

/target: {Domain | DC | BOTH}
Optional.  Specifies the GPO to be restored: the Default Domain Policy GPO, the Default Domain Controllers Policy GPO, or both.

/ignoreschema:
Optional. Use this switch to enable this tool to ignore the schema version of  Active Directory. Otherwise, this tool will only work on the same AD schema version as the Windows version in which the tool was shipped.


```

### Usage (stderr):
```Batchfile

```

### Child Processes:


## Signature

* Status: Signature verified.
* Serial: `33000001C422B2F79B793DACB20000000001C4`
* Thumbprint: `AE9C1AE54763822EEC42474983D8B635116C8452`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: DefaultGPOFix
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.17763.1 (WinBuild.160101.0800)
* Product Version: 10.0.17763.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.



## Additional Info*

**The information below is copied from [MicrosoftDocs](https://github.com/MicrosoftDocs/windowsserverdocs), which is maintained by [Microsoft](https://opensource.microsoft.com/codeofconduct/). Available under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) license.*

---

## dcgpofix

Recreates the default Group Policy Objects (GPOs) for a domain. To get to the Group Policy Management Console (GPMC), you must install Group Policy Management as a feature through Server Manager.

>[!IMPORTANT]
> As a best practice, you should configure the Default Domain Policy GPO only to manage the default **Account Policies** settings, Password Policy, Account Lockout Policy, and Kerberos Policy. Additionally, you should configure the Default Domain Controllers Policy GPO only to set user rights and audit policies.

### Syntax

```
dcgpofix [/ignoreschema] [/target: {domain | dc | both}] [/?]
```

#### Parameters

| Parameter | Description |
| --------- | ----------- |
| /ignoreschema | Ignores the version of the Active Directory schema when you run this command. Otherwise, the command only works on the same schema version as the Windows version in which the command was shipped. |
| `/target {domain | dc | both` | Specifies whether to target the Default Domain policy, the Default Domain Controllers policy, or both types of policies. |
| /? | Displays Help at the command prompt. |

### Examples

To manage the default **Account Policies** settings, Password Policy, Account Lockout Policy, and Kerberos Policy, while ignoring the Active Directory schema version, type:

```
dcgpofix /ignoreschema /target:domain
```

To configure the Default Domain Controllers Policy GPO only to set user rights and audit policies, while ignoring the Active Directory schema version, type:

```
dcgpofix /ignoreschema /target:dc
```

### Additional References

- [Command-Line Syntax Key](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/command-line-syntax-key.md)

---



MIT License. Copyright (c) 2020 Strontic.


