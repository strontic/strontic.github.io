---
title: msdt.exe | Diagnostics Troubleshooting Wizard
---

# msdt.exe 

* File Path: `C:\Windows\system32\msdt.exe`
* Description: Diagnostics Troubleshooting Wizard
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `BB98CE2BD520AC69CB3D2F830974CABE`
SHA1 | `D291F53DD2FF82F70EE758E6688C6A34CAD622FA`
SHA256 | `C1237BDD2B574C1CBBB4A0D990773BBED5B6FE3BD14F8011C0E79F9CDDCA2B4E`
SHA384 | `AD7E7A1DB2E6CBE40C7E5C6852AE20C5A7DFB5E61B0AE42CD7DE97D2637C671813D4397C4F98A325BEDB08C92D2172E3`
SHA512 | `2072AE28855D1211010E926859076B52BEFFFE46B00792A58CF41866BF8A6AC75E7CF0F5FAABF1F4E695249357103D91D2A8CD23765742BBAFCD3E37895B5AF9`
SSDEEP | `24576:PsEhiqCDdRNfY6XH4qvIReK1odddGdBnyE0k26kVZnBm:iD4qNK7utRB`

## Runtime Data

### Usage (stdout):
```Batchfile

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

* Original Filename: msdt.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.14393.0 (rs1_release.160715-1616)
* Product Version: 10.0.14393.0
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\windows\system32\msdt.exe](msdt.exe-71F99D108A429C131E8335B5E4FE01F9.md) | 71
[C:\Windows\system32\msdt.exe](msdt.exe-728A1A72370AF1A7641650FD43DB7DBE.md) | 79
[C:\windows\SysWOW64\msdt.exe](msdt.exe-3AAB3F3107C0F2FDE2AD082EB98A84EA.md) | 68
[C:\Windows\SysWOW64\msdt.exe](msdt.exe-4EBC38519675FB0BA6915D0D8A7FCD01.md) | 71
[C:\Windows\SysWOW64\msdt.exe](msdt.exe-7FF1826697BAC1F6414FEF5A12D5A930.md) | 72

## Possible Misuse

*The following table contains possible examples of `msdt.exe` being misused. While `msdt.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_possible_applocker_bypass.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_possible_applocker_bypass.yml) | `            - '\msdt.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Msdt.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Msdt.yml) | `Name: Msdt.exe` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Msdt.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Msdt.yml) | `  - Command: msdt.exe -path C:\WINDOWS\diagnostics\index\PCWDiagnostic.xml -af C:\PCW8E57.xml /skip TRUE` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Msdt.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Msdt.yml) | `  - Path: C:\Windows\System32\Msdt.exe` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Msdt.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Msdt.yml) | `  - Path: C:\Windows\SysWOW64\Msdt.exe` | 

## Additional Info*

**The information below is copied from [MicrosoftDocs](https://github.com/MicrosoftDocs/windowsserverdocs), which is maintained by [Microsoft](https://opensource.microsoft.com/codeofconduct/). Available under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) license.*

---

## msdt

Invokes a troubleshooting pack at the command line or as part of an automated script, and enables additional options without user input.

### Syntax

```
msdt </id <name> | /path <name> | /cab < name>> <</parameter> [options] â€¦ <parameter> [options]>>
```

#### Parameters

| Parameter | Description |
| --------- | ----------- |
| /id `<packagename>` | Specifies which diagnostic package to run. For a list of available packages, see [Available Troubleshooting packs](https://docs.microsoft.com/previous-versions/windows/it-pro/windows-server-2012-r2-and-2012/ee424379(v=ws.11)#available-troubleshooting-packs). |
| /path `<directory|.diagpkg file|.diagcfg file>` | Specifies the full path to a diagnostic package. If you specify a directory, the directory must contain a diagnostic package. You cannot use the **/path** parameter in conjunction with the** /id**, **/dci**, or **/cab** parameters. |                                                                                   |
| /dci `<passkey>` | Prepopulates the passkey field. This parameter is only used when a support provider has supplied a passkey. |
| /dt `<directory>` | Displays the troubleshooting history in the specified directory. Diagnostic results are stored in the userâ€™s **%LOCALAPPDATA%\Diagnostics** or **%LOCALAPPDATA%\ElevatedDiagnostics** directories. |
| /af `<answerfile>` | Specifies an answer file in XML format that contains responses to one or more diagnostic interactions. |
| /modal `<ownerHWND>` | Makes the troubleshooting pack modal to a window designated by the parent Console Window Handle (HWND), in decimal. This parameter is typically used by applications that launch a troubleshooting pack. For more information about obtaining Console Window Handles, see [How to Obtain a Console Window Handle (HWND)](https://support.microsoft.com/help/124103/how-to-obtain-a-console-window-handle-hwnd). |
| /moreoptions `<true|false>` | Enables (true) or suppresses (false) the final troubleshooting screen that asks if the user wants to explore additional options. This parameter is typically used when the troubleshooting pack is launched by a troubleshooter that isn't part of the operating system. |
| /param `<parameters>` | Specifies a set of interaction responses at the command line, similar to an answer file. This parameter isn't typically used within the context of troubleshooting packs created with TSP Designer. For more information about developing custom parameters, see [Windows Troubleshooting Platform](https://docs.microsoft.com/previous-versions/windows/desktop/wintt/windows-troubleshooting-toolkit-portal). |
| /advanced | Expands the advanced link on the Welcome page by default when the troubleshooting pack is started. |
| /custom | Prompts the user to confirm each possible resolution before it is applied. |

#### Return codes

Troubleshooting packs comprise a set of root causes, each of which describes a specific technical problem. After completing the troubleshooting pack tasks, each root cause returns a state of fixed, not fixed, detected (but not fixable), or not found. In addition to specific results reported in the troubleshooter user interface, the troubleshooting engine returns a code in the results describing, in general terms, whether or not the troubleshooter fixed the original problem. The codes are:

| Code | Description |
| ---- | ----------- |
| -1 | **Interruption:** The troubleshooter was closed before the troubleshooting tasks were completed. |
| 0 | **Fixed:** The troubleshooter identified and fixed at least one root cause, and no root causes remain in a not fixed state. |
| 1 | **Present, but not fixed:** The troubleshooter identified one or more root causes that remain in a not fixed state. This code is returned even if another root cause was fixed. |
| 2 | **Not found:** The troubleshooter did not identify any root causes. |

### Additional References

- [Command-Line Syntax Key](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/command-line-syntax-key.md)

- [Available troubleshooting packs](https://docs.microsoft.com/previous-versions/windows/it-pro/windows-server-2012-r2-and-2012/ee424379(v=ws.11)#available-troubleshooting-packs)

- [TroubleshootingPack Powershell reference](https://docs.microsoft.com/powershell/module/troubleshootingpack/?view=win10-ps)

---



MIT License. Copyright (c) 2020 Strontic.


