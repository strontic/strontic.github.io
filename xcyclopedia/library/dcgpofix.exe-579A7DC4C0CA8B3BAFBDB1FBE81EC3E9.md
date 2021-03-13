---
title: dcgpofix.exe | Microsoft (C) Default Group Policy Object Restore Utility
excerpt: What is dcgpofix.exe?
---

# dcgpofix.exe 

* File Path: `C:\windows\SysWOW64\dcgpofix.exe`
* Description: Microsoft (C) Default Group Policy Object Restore Utility

## Hashes

Type | Hash
-- | --
MD5 | `579A7DC4C0CA8B3BAFBDB1FBE81EC3E9`
SHA1 | `A93CC2354A2B2FDE1B91351979DE848A57955516`
SHA256 | `F2E81AB35F0E9F78A75B2A3A92C92F5A53B8138A686F672F5196BC5115DA4FAB`
SHA384 | `B3F74983CA5BC85C894CE7A05097127907BFBE653CD7F31891B615B9890A880F837DCA2A7310A672DBF2AF1862D286A7`
SHA512 | `9843ACF50166F6C63B1B010D2E601FA69AC5D06741F783C9FDA5AB572F7AA74206C91B6777AAA93F9721E51FC4290EC583BBF16E4235160E1AC8F71B0536B7FC`
SSDEEP | `768:irR5jcEwMO76OTpwB3KCtwjFlxNN83pki7FrU/:iTjcEf/MpA3KaoUpki7B`

## Signature

* Status: The file C:\windows\SysWOW64\dcgpofix.exe is not digitally signed. You cannot run this script on the current system. For more information about running scripts and setting execution policy, see about_Execution_Policies at http://go.microsoft.com/fwlink/?LinkID=135170
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



MIT License. Copyright (c) 2020-2021 Strontic.


