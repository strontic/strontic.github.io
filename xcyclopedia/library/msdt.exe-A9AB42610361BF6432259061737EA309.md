---
title: msdt.exe | Diagnostics Troubleshooting Wizard
---

# msdt.exe 

* File Path: `C:\Windows\SysWOW64\msdt.exe`
* Description: Diagnostics Troubleshooting Wizard
* Comments: 

## Screenshot

![msdt.exe](screenshots/msdt.exe-7FF1826697BAC1F6414FEF5A12D5A930-2.png)

## Hashes

Type | Hash
-- | --
MD5 | `A9AB42610361BF6432259061737EA309`
SHA1 | `25FA6252069395C5F923A22D40FCB0EC6D13A109`
SHA256 | `48103C8EE52D4CEFF0FB8974FFB17E6BFAB773B51F9D187A3A581401D6A7663B`
SHA384 | `B8002527584DB7D5D1B03A705593AD4F315BC43270E569F8FAA013DEB3A223A798BE2FAA59A71BBD38DE718659C15E9F`
SHA512 | `FDFA84A297A2492D98BE927E8A797227B2B19AE5EF4326DCA04E19A01D89054AC71330403C6195F056460498315133077FB9559AE054FB14AD36160301A2A2DB`
SSDEEP | `6144:vBGci6SDxNV7xLAeijxawdtuGjU8TdLO694gI1sicf7LpPtKXl:vW3V7pX8/XzjUILP94g0cD9Ptm`

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
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: msdt.exe
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.


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


