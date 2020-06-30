---
title: qprocess.exe | Query Process Utility
---

# qprocess.exe 

* File Path: `C:\Windows\SysWOW64\qprocess.exe`
* Description: Query Process Utility
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `6C731AF0B86FA5ADF1B3E75556FF7D2A`
SHA1 | `6F4F6C36379E86B3E22A5E568D968D71D0E0E341`
SHA256 | `23E556151BCA6472A7885AA78A812EC783B4498D036CB2BAAE1D22442111CDD9`
SHA384 | `D663C0AFF111510BF0B341616CD6DCBC40AD1A6830E1F6DD7C692170F220CAD2F29DE31B619C6034D7CC898D35385DF9`
SHA512 | `EE6A997BF5F0C78A40DC802C6D212FFA948390E16E81395FEAA47809A93E4EB78F95A95DBCEEB46EE51C47BACE67D675C5A297EA3879266D9167B523CB74D3F0`
SSDEEP | `384:yAFeyeTX4z4D2CKk8FrSPEDKJhoE882eaU2H9JWLME+2We9q:9Eyerlqk8W2dcV9`

## Runtime Data

### Usage (stdout):
```Batchfile
Displays information about processes.

QUERY PROCESS [* | processid | username | sessionname | /ID:nn | programname]
  [/SERVER:servername]

  *                  Display all visible processes.
  processid          Display process specified by processid.
  username           Display all processes belonging to username.
  sessionname        Display all processes running at sessionname.
  /ID:nn             Display all processes running at session nn.
  programname        Display all processes associated with programname.
  /SERVER:servername The Remote Desktop Session Host server to be queried.

```

### Usage (stderr):
```Batchfile
Invalid parameter(s)
Displays information about processes.

QUERY PROCESS [* | processid | username | sessionname | /ID:nn | programname]
  [/SERVER:servername]

  *                  Display all visible processes.
  processid          Display process specified by processid.
  username           Display all processes belonging to username.
  sessionname        Display all processes running at sessionname.
  /ID:nn             Display all processes running at session nn.
  programname        Display all processes associated with programname.
  /SERVER:servername The Remote Desktop Session Host server to be queried.

```

### Child Processes:


## Signature

* Status: Signature verified.
* Serial: `33000001C422B2F79B793DACB20000000001C4`
* Thumbprint: `AE9C1AE54763822EEC42474983D8B635116C8452`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: qprocess.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.17763.1 (WinBuild.160101.0800)
* Product Version: 10.0.17763.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.


## Possible Misuse

*The following table contains possible examples of `qprocess.exe` being misused. While `qprocess.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_commands_recon_activity.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_commands_recon_activity.yml) | `            - qprocess` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)

## Additional Info*

**The information below is copied from [MicrosoftDocs](https://github.com/MicrosoftDocs/windowsserverdocs), which is maintained by [Microsoft](https://opensource.microsoft.com/codeofconduct/). Available under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) license.*

---

## qprocess

> Applies to: Windows Server (Semi-Annual Channel), Windows Server 2019, Windows Server 2016, Windows Server 2012 R2, Windows Server 2012

Displays information about processes that are running on a Remote Desktop Session Host server. To find out what's new in the latest version, see [What's New in Remote Desktop Services in Windows Server](https://docs.microsoft.com/previous-versions/windows/it-pro/windows-server-2012-R2-and-2012/dn283323(v=ws.11)).

> [!NOTE]
> This command is the same as the [query process command](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/query-process.md).

### Additional References

- [Command-Line Syntax Key](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/command-line-syntax-key.md)

- [query process command](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/query-process.md)

- [Remote Desktop Services (Terminal Services) Command Reference](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/remote-desktop-services-terminal-services-command-reference.md)

---



MIT License. Copyright (c) 2020 Strontic.


