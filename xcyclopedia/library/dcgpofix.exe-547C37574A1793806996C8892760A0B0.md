---
title: dcgpofix.exe | Microsoft (C) Default Group Policy Object Restore Utility
excerpt: What is dcgpofix.exe?
---

# dcgpofix.exe 

* File Path: `C:\Windows\SysWOW64\dcgpofix.exe`
* Description: Microsoft (C) Default Group Policy Object Restore Utility

## Hashes

Type | Hash
-- | --
MD5 | `547C37574A1793806996C8892760A0B0`
SHA1 | `2247E90EBE34B625C399FF23E379CC0126603BBF`
SHA256 | `BC85D2FCFFC0B1231A3C867DDC7F72C4715C39C94C94FE952932545691DD92DC`
SHA384 | `EB9DE0C7B72CED66F8DF692AF464985F0F04365665A0377BFB00EB29BAF5D7874B18BA512883A3D41EEC766D625A7648`
SHA512 | `B948D145329D097FC13DB0E5E5BD1F31F9BFCD095F37EC70CF0116C8C252EE52F395547F087EC78B75231E2E361C09E54BF4ECAEF265A3B04B86CAEE3E16183D`
SSDEEP | `1536:gd+GIbKXNiuVlDyfpFjEt4EFqEIOEyXB:gd+GguVlDg8qEwrQX`
IMP | `E5DBFF31C174826963755E2AB1E6C867`
PESHA1 | `0FA2958E565FC6E2B547661B75DDA3F22D9E1B04`
PE256 | `7DEE92307E4D2DC36BCE9F9D1F24FA5EAB19D827EB76145515A451B612F154DE`

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
C:\Windows\System32\wow64cpu.dll |
C:\Windows\System32\wow64win.dll |
C:\Windows\SysWOW64\dcgpofix.exe |


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
* Machine Type: 32-bit

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


