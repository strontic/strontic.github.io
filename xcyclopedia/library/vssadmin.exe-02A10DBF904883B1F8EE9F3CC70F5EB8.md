
# vssadmin.exe 

* File Path: `C:\WINDOWS\system32\vssadmin.exe`
* Description: Command Line Interface for Microsoft Volume Shadow Copy Service 
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `02A10DBF904883B1F8EE9F3CC70F5EB8`
SHA1 | `980510AE54462EB2F892C002BB828EDB11D85C10`
SHA256 | `ACDCC96D628EE8FF7F07FC5D795A05C22EB239BE0D44A9F01727B6124A9619A9`
SHA384 | `234CB59B7CC24A71E11EECD9D250DA3C1D5A3016DE9B0FC7BC0D6CAEBEADEF1A80EBBD24488C5CE59F6D295F2EAA5F48`
SHA512 | `BF465F6FBEE3BA0865A90F461F7598E6113CE8986F2351DA3C5E2F50CDBA85D9C5FC5DD2C2FE54C1758FADB489DA9797A3C6328948795F8B9BD2D73B8D389D9A`
SSDEEP | `3072:MNB9JdZjbn9OW4mPuZm47pyv7xp8AkTI5f0g8vY:Mn9JDHn9OW4mYm47pYEAkTI5f0g8v`

## Runtime Data

### Usage (stdout):
```Batchfile
vssadmin 1.1 - Volume Shadow Copy Service administrative command-line tool
(C) Copyright 2001-2013 Microsoft Corp.

Error: Invalid command.
 
---- Commands Supported ----

Delete Shadows        - Delete volume shadow copies
List Providers        - List registered volume shadow copy providers
List Shadows          - List existing volume shadow copies
List ShadowStorage    - List volume shadow copy storage associations
List Volumes          - List volumes eligible for shadow copies
List Writers          - List subscribed volume shadow copy writers
Resize ShadowStorage  - Resize a volume shadow copy storage association

```

### Usage (stderr):
```Batchfile

```

### Child Processes:


## Signature

* Status: Signature verified.
* Serial: `330000023241FB59996DCC4DFF000000000232`
* Thumbprint: `FF82BC38E1DA5E596DF374C53E3617F7EDA36B06`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: VSSADMIN.EXE.MUI
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.18362.1 (WinBuild.160101.0800)
* Product Version: 10.0.18362.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.




## Additional Info*

**The information below is copied from [MicrosoftDocs](https://github.com/MicrosoftDocs/windowsserverdocs), which is maintained by [Microsoft](https://opensource.microsoft.com/codeofconduct/). Available under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) license.*

---
# Vssadmin

> Applies to: Windows 10, Windows 8.1, Windows Server 2016, Windows Server 2012 R2, Windows Server 2012, Windows Server 2008 R2, Windows Server 2008

Displays current volume shadow copy backups and all installed shadow copy writers and providers. Select a command name in the following table view its command syntax.

|Command|Description|Availability
|---|---|---
|[Vssadmin add shadowstorage](https://docs.microsoft.com/previous-versions/windows/it-pro/windows-server-2012-r2-and-2012/cc788051(v%3dws.11))|Adds a volume shadow copy storage association.| Server only
|[Vssadmin create shadow](https://docs.microsoft.com/previous-versions/windows/it-pro/windows-server-2012-r2-and-2012/cc788055(v%3dws.11))|Creates a new volume shadow copy.| Server only
|[Vssadmin delete shadows](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/vssadmin-delete-shadows.md)|Deletes volume shadow copies.| Client and Server
|[Vssadmin delete shadowstorage](https://docs.microsoft.com/previous-versions/windows/it-pro/windows-server-2012-r2-and-2012/cc785461(v%3dws.11))|Deletes volume shadow copy storage associations.| Server only
|[Vssadmin list providers](https://docs.microsoft.com/previous-versions/windows/it-pro/windows-server-2012-r2-and-2012/cc788108(v%3dws.11))|Lists registered volume shadow copy providers.| Client and Server
|[Vssadmin list shadows](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/vssadmin-list-shadows.md)|Lists existing volume shadow copies.| Client and Server
|[Vssadmin list shadowstorage](https://docs.microsoft.com/previous-versions/windows/it-pro/windows-server-2012-r2-and-2012/cc788045(v%3dws.11))|Lists all shadow copy storage associations on the system.| Client and Server
|[Vssadmin list volumes](https://docs.microsoft.com/previous-versions/windows/it-pro/windows-server-2012-r2-and-2012/cc788064(v%3dws.11))|Lists volumes that are eligible for shadow copies.| Client and Server
|[Vssadmin list writers](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/vssadmin-list-writers.md)|Lists all subscribed volume shadow copy writers on the system.| Client and Server
|[Vssadmin resize shadowstorage](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/vssadmin-resize-shadowstorage.md)|Resizes the maximum size for a shadow copy storage association.| Client and Server

---


MIT License. Copyright (c) 2020 Strontic.


