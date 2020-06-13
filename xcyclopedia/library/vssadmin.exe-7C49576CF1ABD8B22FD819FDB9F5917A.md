
# vssadmin.exe 

* File Path: `C:\Windows\SysWOW64\vssadmin.exe`
* Description: Command Line Interface for Microsoft Volume Shadow Copy Service 
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `7C49576CF1ABD8B22FD819FDB9F5917A`
SHA1 | `E50CADA1AB0F487D73C02D5EA2D8DE2A4557A281`
SHA256 | `8A597914C4481C7C78936E0E581107A96C5AD02F7353E12D0666F330CA89F051`
SHA384 | `0BE126A3B0DF53554B1CCCF1627D09E8106D72E09F26A9A66CCD5B64D6226D232C17235F3614819BF778ECD657EA7D37`
SHA512 | `0F915B425C76C7A66FAB1EC0F9D4D2DAF3E6B9DCFF77113925806C6F03EF948D99382AD924B6FED5A330C91FA7F3BDABE0381E47447E4C78E87090527CFC5CED`
SSDEEP | `3072:+G4LJaB3Wlz3cPMXBFy+iSNoT45lkWPanAtb:+G4LJM3Wlz3cPMRLNXlwA1`

## Runtime Data

### Usage (stdout):
```Batchfile
vssadmin 1.1 - Volume Shadow Copy Service administrative command-line tool
(C) Copyright 2001-2013 Microsoft Corp.

Error: Invalid command.
 
---- Commands Supported ----

Add ShadowStorage     - Add a new volume shadow copy storage association
Create Shadow         - Create a new volume shadow copy
Delete Shadows        - Delete volume shadow copies
Delete ShadowStorage  - Delete volume shadow copy storage associations
List Providers        - List registered volume shadow copy providers
List Shadows          - List existing volume shadow copies
List ShadowStorage    - List volume shadow copy storage associations
List Volumes          - List volumes eligible for shadow copies
List Writers          - List subscribed volume shadow copy writers
Resize ShadowStorage  - Resize a volume shadow copy storage association
Revert Shadow         - Revert a volume to a shadow copy
Query Reverts         - Query the progress of in-progress revert operations.

```

### Usage (stderr):
```Batchfile

```

### Child Processes:


## Signature

* Status: Signature verified.
* Serial: `33000000BCE120FDD27CC8EE930000000000BC`
* Thumbprint: `E85459B23C232DB3CB94C7A56D47678F58E8E51E`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: VSSADMIN.EXE.MUI
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.14393.0 (rs1_release.160715-1616)
* Product Version: 10.0.14393.0
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.


## Additional Info

*Source: [MicrosoftDocs](https://github.com/MicrosoftDocs/windowsserverdocs) by [Microsoft](https://opensource.microsoft.com/codeofconduct/), available under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) license. Some links modified.*

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


