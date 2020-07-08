---
title: dcgpofix.exe | Microsoft (C) Default Group Policy Object Restore Utility
---

# dcgpofix.exe 

* File Path: `C:\windows\system32\dcgpofix.exe`
* Description: Microsoft (C) Default Group Policy Object Restore Utility

## Hashes

Type | Hash
-- | --
MD5 | `CB65A3E11B359AA43126D58A012D70DE`
SHA1 | `DEAB74241F962BF362CFB489880EFEBAA922565A`
SHA256 | `47BF6EE4C567A90287AF05DC8FFEA98EAF1F908337F24B5C168473ABFCF31A1D`
SHA384 | `3262E3AEA2E711AEA211523531C5C1B4AB5E80F0FBD5C31862AF15D7B63628F04A38ACC7715069E76CE5B9380F791FC5`
SHA512 | `8073331511ED286E90F8923E0F10EAEA9FF13786529906F93B8C2963F66D8A71C6493AE372FCEB1FD6DA98FE420E2767130994D40D6BA1A259274249E3ACBC62`
SSDEEP | `768:LR5KfsXvepcZ2s6rEi6hylcz15IpdybiuHhAALbNgMKKSZjdhiCWMWruDqWcDy:TeUeRj6h5IM9HhvJgMK/jdhr3KXWcDy`

## Signature

* Status: The file C:\windows\system32\dcgpofix.exe is not digitally signed. You cannot run this script on the current system. For more information about running scripts and setting execution policy, see about_Execution_Policies at http://go.microsoft.com/fwlink/?LinkID=135170
* Serial: ``
* Thumbprint: ``
* Issuer: 
* Subject: 

## File Metadata

* Original Filename: DefaultGPOFix
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 6.3.9600.16384 (winblue_rtm.130821-1623)
* Product Version: 6.3.9600.16384
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


