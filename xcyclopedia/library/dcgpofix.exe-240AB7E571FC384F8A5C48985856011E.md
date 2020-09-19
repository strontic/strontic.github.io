---
title: dcgpofix.exe | Microsoft (C) Default Group Policy Object Restore Utility
---

# dcgpofix.exe 

* File Path: `C:\Windows\system32\dcgpofix.exe`
* Description: Microsoft (C) Default Group Policy Object Restore Utility

## Hashes

Type | Hash
-- | --
MD5 | `240AB7E571FC384F8A5C48985856011E`
SHA1 | `02677648C909F3DA4BE2C314F4A927A72F3594A6`
SHA256 | `32B2012C038DD49E96DD2F0DE5A2A2A17BC29E166B94C4B21B984B7A3B09A2F7`
SHA384 | `448E0A2AF5B90A2598A584696DDF7F4AFB2E58C2453B29169E7D1563BD0ECD088755AC520B779F8F557F9DE49EC75017`
SHA512 | `E665B41756464FD81618FA6972BAAB13A8213788186381A05C5FC5C287E5E28D6EB0FE2171802C92AAACA4BF48FB7B5B77B6FF9A605B71834CD70EE43CD03EA3`
SSDEEP | `1536:ZNYh3QQ1eb2045yZhteRKntUIc+aW8R77QVfI:kXet/7t4+aNR77iQ`

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

## Signature

* Status: Signature verified.
* Serial: `33000000BCE120FDD27CC8EE930000000000BC`
* Thumbprint: `E85459B23C232DB3CB94C7A56D47678F58E8E51E`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: DefaultGPOFix
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.14393.0 (rs1_release.160715-1616)
* Product Version: 10.0.14393.0
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


