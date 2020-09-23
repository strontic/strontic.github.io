---
title: jetpack.exe | Off-line jet database compact app
excerpt: What is jetpack.exe?
---

# jetpack.exe 

* File Path: `C:\windows\system32\jetpack.exe`
* Description: Off-line jet database compact app

## Hashes

Type | Hash
-- | --
MD5 | `7D2D4B73BD182B40DEFF7892675E34B0`
SHA1 | `B71EE6F29A3D13144113CAFF4F25E8DAEDEA2C9A`
SHA256 | `A870E42E157063EB871F6E1876EED567F2716A087F1B4570FAD572C1DE771FAB`
SHA384 | `2DA662AF432250841E388F1588BF74A41E8F643DA630778A1538AEE32C5B8588537F919BBD11D1C0364C989E6FE53200`
SHA512 | `B2C69C0F54EB969A195E0B38464A1BD5910AFDF1FF8F1DFE0A371F53F0C56C447DAA751D8151C610C266DEFBBD83C9C73F73DBA93E8C32674B76AB21C503BB27`
SSDEEP | `192:Na/lsoPWyW7dW1fpkicPP0DkV8ZWe3eAaUQmsW0UcHW:Na+TyKDP0G8ZWe3eysW0PHW`

## Signature

* Status: The file C:\windows\system32\jetpack.exe is not digitally signed. You cannot run this script on the current system. For more information about running scripts and setting execution policy, see about_Execution_Policies at http://go.microsoft.com/fwlink/?LinkID=135170
* Serial: ``
* Thumbprint: ``
* Issuer: 
* Subject: 

## File Metadata

* Original Filename: jetpack.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 6.3.9600.16384 (winblue_rtm.130821-1623)
* Product Version: 6.3.9600.16384
* Language: Language Neutral
* Legal Copyright:  Microsoft Corporation. All rights reserved.



## Possible Misuse

*The following table contains possible examples of `jetpack.exe` being misused. While `jetpack.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[malware-ioc](https://github.com/eset/malware-ioc) | [turla](https://github.com/eset/malware-ioc/blob/master/turla/README.adoc) | `* `hxxp://warrixmalaysia.com.my/wp-content/plugins/jetpack/modules/contact-form/grunion-table-form.php`` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)

## Additional Info*

**The information below is copied from [MicrosoftDocs](https://github.com/MicrosoftDocs/windowsserverdocs), which is maintained by [Microsoft](https://opensource.microsoft.com/codeofconduct/). Available under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) license.*

---

## jetpack

> Applies to: Windows Server (Semi-Annual Channel), Windows Server 2019, Windows Server 2016, Windows Server 2012 R2, Windows Server 2012

Compacts a Windows Internet Name Service (WINS) or Dynamic Host Configuration Protocol (DHCP) database. We recommend you compact the WINS database whenever it approaches 30 MB.

Jetpack.exe compacts the database by:

1. Copying the database information to a temporary database file.

2. Deleting the original database file, either WINS or DHCP.

3. Renames the temporary database files to the original filename.

### Syntax

```
jetpack.exe <database_name> <temp_database_name>
```

#### Parameters

| Parameter | Description |
| ------- | -------- |
| `<database_name>` | Specifies the name of the original database file. |
| `<temp_database_name>` | Specifies the name of the temporary database file to be created by jetpack.exe.<p>Note: This temporary file is removed when the compact process is complete. For this command to work properly, you must make sure your temp file name is unique and that a file with that name doesn't already exist. |
| /? | Displays help at the command prompt. |

#### Examples

To compact the WINS database, where **Tmp.mdb** is a temporary database and **Wins.mdb** is the WINS database, type:

```
cd %SYSTEMROOT%\SYSTEM32\WINS
NET STOP WINS
jetpack Wins.mdb Tmp.mdb
NET start WINS
```

To compact the DHCP database, where **Tmp.mdb** is a temporary database and **Dhcp.mdb** is the DHCP database, type:

```
cd %SYSTEMROOT%\SYSTEM32\DHCP
NET STOP DHCPSERVER
jetpack Dhcp.mdb Tmp.mdb
NET start DHCPSERVER
```

### Additional References

- [Command-Line Syntax Key](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/command-line-syntax-key.md)

---



MIT License. Copyright (c) 2020 Strontic.


