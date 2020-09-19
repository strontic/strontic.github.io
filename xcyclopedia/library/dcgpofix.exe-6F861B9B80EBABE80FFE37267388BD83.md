---
title: dcgpofix.exe | Microsoft (C) Default Group Policy Object Restore Utility
---

# dcgpofix.exe 

* File Path: `C:\Windows\SysWOW64\dcgpofix.exe`
* Description: Microsoft (C) Default Group Policy Object Restore Utility

## Hashes

Type | Hash
-- | --
MD5 | `6F861B9B80EBABE80FFE37267388BD83`
SHA1 | `F64DB12B22DEF010A6F322AF455384506CB8645F`
SHA256 | `0B95CDDF622D0EDFACA0EB88F798E7A3076C49C8ED860E90B776728345247CB3`
SHA384 | `1369043BC11AB4DE35014E6445AEE2615E7DB5B3A71C226D397AB526BD6F837216F5C2796839728A878171CB490092E8`
SHA512 | `0FFF767618259D3831BFA411B45F27555D4F13C63326347604640F0BC831889CEFE08C0EE74FFAEA6A829FD027E18F28AF41724C111D1BBFA3289E6C1DF3CBB1`
SSDEEP | `1536:8+Gbj4NiWiblDNQQUu0s1iFrFqEINE4S/:8+GZW4lDeQzcFrwrq4`

## Runtime Data

### Usage (stdout):
```cmhg

Microsoft(R) Windows(R) Operating System Default Group Policy Restore Utility v5.1

Copyright (C) Microsoft Corporation. 1981-2003

Description: Recreates the Default Group Policy Objects (GPOs) for a domain

Syntax: DcGPOFix [/ignoreschema] [/Target: Domain | DC | BOTH]

/target: {Domain | DC | BOTH}
Optional.  Specifies the GPO to be restored: the Default Domain Policy GPO, the Default Domain Controllers Policy GPO, or both.

/ignoreschema:
Optional. Use this switch to enable this tool to ignore the schema version of  Active Directory. Otherwise, this tool will only work on the same AD schema version as the Windows version in which the tool was shipped.


```

### Loaded Modules:

Path |
-- |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\wow64.dll |
C:\Windows\SysWOW64\dcgpofix.exe |


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


