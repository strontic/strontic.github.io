﻿---
title: reset.exe | Remote Desktop Services Reset Utility
excerpt: What is reset.exe?
---

# reset.exe 

* File Path: `C:\Windows\system32\reset.exe`
* Description: Remote Desktop Services Reset Utility

## Hashes

Type | Hash
-- | --
MD5 | `EDE443A63F4A5914F87DFDC6F8F59697`
SHA1 | `596A5DD2803009763FB0AE7AA3AA8713AE2FF4D4`
SHA256 | `C1E2A96B5D73D08A52BC5A2E634D408C2D42071147D40A894C8B4606DE83484D`
SHA384 | `7C15DCADA03F53B2DEC6BB2FDE04DE8ACE3E5815DAB9895A94A46E8DFAE4A9D4A840B10D27AC546380114374F4A748DF`
SHA512 | `CA049EA57DA4A35539436586E115858B9253B65378997AE3B2C68CF20980B542345E4B78AC25EA5ABD15DD0F3E87BC054760E37FF2A97E70E78C0B5E2D712699`
SSDEEP | `384:P6k7EHdWH1ZMqxdBeEh+91XfGHK2ahyWQgW:P6kQSVBA914cU`
IMP | `CCC9DA4A55E90DFE34CBCDB066D6A6B3`
PESHA1 | `5FA733035807DB51AD18E44794460BA43881851C`
PE256 | `17625218764110E1D06656A96F39BEA39B116493E3D7DFEB6AD2879599BF2E19`

## Runtime Data

### Usage (stdout):
```cmhg
RESET { SESSION }

```

### Usage (stderr):
```cmhg
Invalid parameter(s)
RESET { SESSION }

```

## Signature

* Status: Signature verified.
* Serial: `33000001C422B2F79B793DACB20000000001C4`
* Thumbprint: `AE9C1AE54763822EEC42474983D8B635116C8452`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: reset.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.17763.1 (WinBuild.160101.0800)
* Product Version: 10.0.17763.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/69
* VirusTotal Link: https://www.virustotal.com/gui/file/c1e2a96b5d73d08a52bc5a2e634d408c2d42071147d40a894c8b4606de83484d/detection/

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Windows\system32\change.exe](change.exe-5171C542F9F07AE7D7068ED8FE0FADE0.md) | 75
[C:\Windows\system32\query.exe](query.exe-8A7520A6CC2A2968F4A8EE4DB946AD8D.md) | 74


## Additional Info*

**The information below is copied from [MicrosoftDocs](https://github.com/MicrosoftDocs/windowsserverdocs), which is maintained by [Microsoft](https://opensource.microsoft.com/codeofconduct/). Available under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) license.*

---

## reset

Resets DiskShadow.exe to the default state. This command is especially useful in separating compound DiskShadow operations, such as **create**, **import**, **backup**, or **restore**.

> [!IMPORTANT
> After you run this command, you will lose state information from commands, such as **add**, **set**, **load**, or **writer**. This command also releases IVssBackupComponent interfaces and loses non-persistent shadow copies.

### Syntax

```
reset
```

### Additional References

- [Command-Line Syntax Key](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/command-line-syntax-key.md)

- [create command](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/create.md)

- [import command](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/import_1.md)

- [backup command](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/begin-backup.md)

- [restore command](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/begin-restore.md)

- [add command](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/add.md)

- [set command](./set.md)

- [load command](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/reg-load.md)

- [writer command](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/writer.md)

---



MIT License. Copyright (c) 2020-2021 Strontic.


