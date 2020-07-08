---
title: jetpack.exe | Off-line jet database compact app
---

# jetpack.exe 

* File Path: `C:\Windows\system32\jetpack.exe`
* Description: Off-line jet database compact app

## Hashes

Type | Hash
-- | --
MD5 | `3DADABB2146182931337393D5492FA2D`
SHA1 | `02CD2A52EAE7C48798892092FE0BC5EF41E9C5BD`
SHA256 | `9C3F26EDD0AF3BB48E647496793A472C3ADA29002E4D3DEAA2192509CDE60974`
SHA384 | `73690DE3EF38E03029E2C80BA35E53BDB36B0210F91A962CC15C7018FFC2DDE9797A83CA62E478A167275A6BE430B85E`
SHA512 | `0C716B4750EE307F862B320E0DC3BAA94324C9868B9EB20D4FE0C8F4402366181A891FCFBDED1B5F767A716ED879E4DB762D7802D0E3C6BFBD6A59251AE7A3EB`
SSDEEP | `192:1Csp6Unp3+Oqfz/eGjYsXSGIaXJwZ4G83UjnmDWGHW:MCnJvA2GMsXCWwZ4V4mDWGHW`

## Runtime Data

### Usage (stdout):
```Batchfile
usage: C:\Windows\system32\jetpack.exe [-351db] <database name> <temp database name>
     : Use -351db if you are compacting NTS3.51 or prior release database
     : Use -40db  if you are compacting NTS4.0 release database
     : Default - compacts NTS5.0 release database

```

## Signature

* Status: Signature verified.
* Serial: `33000001C422B2F79B793DACB20000000001C4`
* Thumbprint: `AE9C1AE54763822EEC42474983D8B635116C8452`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: jetpack.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.17763.1 (WinBuild.160101.0800)
* Product Version: 10.0.17763.1
* Language: Language Neutral
* Legal Copyright:  Microsoft Corporation. All rights reserved.


## Possible Misuse

*The following table contains possible examples of `jetpack.exe` being misused. While `jetpack.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[malware-ioc](https://github.com/eset/malware-ioc) | [turla](https://github.com/eset/malware-ioc/blob/master/turla/README.adoc) | ` * `hxxp://warrixmalaysia.com.my/wp-content/plugins/jetpack/modules/contact-form/grunion-table-form.php`` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)

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


