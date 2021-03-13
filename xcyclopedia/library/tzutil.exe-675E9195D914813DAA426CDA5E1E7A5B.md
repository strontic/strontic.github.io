---
title: tzutil.exe | Windows Time Zone Utility
excerpt: What is tzutil.exe?
---

# tzutil.exe 

* File Path: `C:\windows\system32\tzutil.exe`
* Description: Windows Time Zone Utility

## Hashes

Type | Hash
-- | --
MD5 | `675E9195D914813DAA426CDA5E1E7A5B`
SHA1 | `4F6A6C89999F5BB16B36E486381F44C5D72485F8`
SHA256 | `FA0F83A95C15A1B348E621E4736CB860815D1DB334EA5058C60B2DC0F4BA11EF`
SHA384 | `6D21783FB6A081C770D12CE8EE5A3F060D60C15EF8666B45F83A60012C21321FF409200FB1059232A13E5F3286012C9A`
SHA512 | `DC6229A15DEBEC8F3F2D3FEDC17130823EEAE472B54D307FE87EB113FE83C03B6976E4114A7471F7AE03F274A7976C9DDE58D1A53E63A9441D7BAF7D06FBD281`
SSDEEP | `768:ojpoFlWx391GRW8fYQvIcUyeG4dA0026w/j97GmaRDTk2araJBill0KUXxC3c:A7ORBfEcnh4s5w/jBpwiOJNKIY3c`

## Signature

* Status: The file C:\windows\system32\tzutil.exe is not digitally signed. You cannot run this script on the current system. For more information about running scripts and setting execution policy, see about_Execution_Policies at http://go.microsoft.com/fwlink/?LinkID=135170
* Serial: ``
* Thumbprint: ``
* Issuer: 
* Subject: 

## File Metadata

* Original Filename: tzutil.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 6.3.9600.16384 (winblue_rtm.130821-1623)
* Product Version: 6.3.9600.16384
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.


## File Similarity (ssdeep match)

File | Score
-- | --
[C:\windows\system32\CertEnrollCtrl.exe](CertEnrollCtrl.exe-725CF081FFF84BE7C95E0958E21338E2.md) | 35
[C:\windows\system32\expand.exe](expand.exe-E46CDE2B20C7CA09D7D882DFDCD2C941.md) | 33
[C:\windows\system32\MuiUnattend.exe](MuiUnattend.exe-9F9EB0FF33E8D683C6BD84B0862E27D7.md) | 30


## Additional Info*

**The information below is copied from [MicrosoftDocs](https://github.com/MicrosoftDocs/windowsserverdocs), which is maintained by [Microsoft](https://opensource.microsoft.com/codeofconduct/). Available under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) license.*

---
## tzutil

> Applies to: Windows Server (Semi-Annual Channel), Windows Server 2019, Windows Server 2016, Windows Server 2012 R2, Windows Server 2012

Displays the Windows Time Zone utility.

### Syntax

```
tzutil [/?] [/g] [/s <timezoneID>[_dstoff]] [/l]
```

#### Parameters

| Parameter | Description |
|--|--|
| /g | Displays the current time zone ID. |
| /s `<timezoneID>[_dstoff]` | Sets the current time zone using the specified time zone ID. The **_dstoff** suffix disables Daylight Saving time adjustments for the time zone (where applicable). Your value must be surrounded by quotes. |
| /l | Lists all valid time zone IDs and display names. The output appears as:<ul><li>`<display name>`</li><li>`<time zone ID>`</li></ul> |
| /? | Displays help at the command prompt. |

##### Remarks

An exit code of **0** indicates the command completed successfully.

### Examples

To display the current time zone ID, type:

```
tzutil /g
```

To set the current time zone to Pacific Standard time, type:

```
tzutil /s "Pacific Standard time"
```

To set the current time zone to Pacific Standard time and disable Daylight Saving time adjustments, type:

```
tzutil /s "Pacific Standard time_dstoff"
```

### Additional References

- [Command-Line Syntax Key](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/command-line-syntax-key.md)

---



MIT License. Copyright (c) 2020-2021 Strontic.


