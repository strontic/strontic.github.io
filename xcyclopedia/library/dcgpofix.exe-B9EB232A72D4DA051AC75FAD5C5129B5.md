---
title: dcgpofix.exe | Microsoft (C) Default Group Policy Object Restore Utility
excerpt: What is dcgpofix.exe?
---

# dcgpofix.exe 

* File Path: `C:\Windows\system32\dcgpofix.exe`
* Description: Microsoft (C) Default Group Policy Object Restore Utility

## Hashes

Type | Hash
-- | --
MD5 | `B9EB232A72D4DA051AC75FAD5C5129B5`
SHA1 | `E63D8A94BFBF425E302B5E8281CC5AFDE38E4D30`
SHA256 | `E6C6951CCA541FF83DA924C6B15EFED8101A08F863CA44AFCC8128C63379E53B`
SHA384 | `87AD6019DFA4ACA066C109175FDF9E1369321F1440C2D98BAADDFE84AB3836D7557D44F75B4CD34F72CEA4AC0F1CB5AA`
SHA512 | `651C3F9493B7D3B283E9CE654F9F1AD64243FE18A1BAD2699C173BEB041FA4E650F3A1DC5E22B106D99C5C72EBEBDAA5818784F7B0DC26BA27E6DFF8D9736AA9`
SSDEEP | `1536:JMXeKJD8lAN7EYJFQJlrxx+p0boBqRVIJUy:AkriuJxT+p0boBaqJ`
IMP | `D58CDC9ADABD63CD50BB2E1BD9868ACA`
PESHA1 | `8A0DB0635ED958B31F4F08E8BB4B470A6105DDFA`
PE256 | `81F468EAEDBB620A156D570DC0EEB3A00508FB11EF642982AE30D7A1E5D3EEB2`

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
C:\Windows\system32\dcgpofix.exe |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\SYSTEM32\ntdll.dll |


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
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
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: Unknown



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


