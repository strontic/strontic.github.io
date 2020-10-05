---
title: ServerCeipOptin.exe | Customer Experience Improvement Program opt-in command-line tool
excerpt: What is ServerCeipOptin.exe?
---

# ServerCeipOptin.exe 

* File Path: `C:\windows\system32\ServerCeipOptin.exe`
* Description: Customer Experience Improvement Program opt-in command-line tool

## Hashes

Type | Hash
-- | --
MD5 | `FF5F815F2A131A8F0C81D4996940F462`
SHA1 | `EB6DE8A4CBDCB19A52D3ECB1DEC57090BF541EAE`
SHA256 | `FEA559EA217255E913EC5587834E8D23235590B7FD70A92579C256FDE068591F`
SHA384 | `66C2CABBA026EFF8BFBA8AB5B6F6F16CE6F393BFFED26A0AA9264DD16B65B0FA9CF7D83D51BE37AE725A2A0078387FEA`
SHA512 | `2ACAE84F3E2F98B32895CF70DAFBD0533C3AA778B60D0F476A67944693AB57EB93A22AEAF8A48312DD5833BC83D5DBD1A000E28875DCEAFC09D4A28C6AAC7FB0`
SSDEEP | `192:N/sn3IxRFzwR3ace0vj6La4XPdjtBwpv7M5Md43B3uP9eAFZU6WN8UmrW:tjRFzwRbvj6LTLBy4SOAP9egNW6JrW`

## Signature

* Status: The file C:\windows\system32\ServerCeipOptin.exe is not digitally signed. You cannot run this script on the current system. For more information about running scripts and setting execution policy, see about_Execution_Policies at http://go.microsoft.com/fwlink/?LinkID=135170
* Serial: ``
* Thumbprint: ``
* Issuer: 
* Subject: 

## File Metadata

* Original Filename: serverCeipOptin.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 6.3.9600.16384 (winblue_rtm.130821-1623)
* Product Version: 6.3.9600.16384
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.


## File Similarity (ssdeep match)

File | Score
-- | --
[C:\windows\system32\ServerWerOptin.exe](ServerWerOptin.exe-A49912203F882DE98FDD9B8E0A1B84F5.md) | 38


## Additional Info*

**The information below is copied from [MicrosoftDocs](https://github.com/MicrosoftDocs/windowsserverdocs), which is maintained by [Microsoft](https://opensource.microsoft.com/codeofconduct/). Available under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) license.*

---

## serverceipoptin

> Applies to: Windows Server (Semi-Annual Channel), Windows Server 2019, Windows Server 2016, Windows Server 2012 R2, Windows Server 2012

Allows you to participate in the Customer Experience Improvement Program (CEIP).

### Syntax

```
serverceipoptin [/query] [/enable] [/disable]
```

#### Parameters

| Parameter | Description |
|--|--|
| /query | Verifies your current setting. |
| /enable | Turns on your participation in CEIP. |
| /disable | Turns off your participation in CEIP. |
| /? | Displays help at the command prompt. |

### Examples

To verify your current settings, type:

```
serverceipoptin /query
```

To turn on your participation, type:

```
serverceipoptin /enable
```

To turn off your participation, type:

```
serverceipoptin /disable
```

### Additional References

- [Command-Line Syntax Key](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/command-line-syntax-key.md)

---



MIT License. Copyright (c) 2020 Strontic.


