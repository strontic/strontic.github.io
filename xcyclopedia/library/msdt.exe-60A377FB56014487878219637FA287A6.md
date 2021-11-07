---
title: msdt.exe | Diagnostics Troubleshooting Wizard
excerpt: What is msdt.exe?
---

# msdt.exe 

* File Path: `C:\WINDOWS\SysWOW64\msdt.exe`
* Description: Diagnostics Troubleshooting Wizard

## Screenshot

![msdt.exe](screenshots/msdt.exe-7FF1826697BAC1F6414FEF5A12D5A930-2.png)

## Hashes

Type | Hash
-- | --
MD5 | `60A377FB56014487878219637FA287A6`
SHA1 | `F415EC5283C82FBF2C4833CEC5E7CB595AA11A52`
SHA256 | `30CCA92B58621615572F1C9F37F3C6AE4DD6FE54F0BFC372A664FC5C554AA1E5`
SHA384 | `1081E07B52E16D9BE15F12A2E96BD2FED80644451EB318D1EB41C4DE92FDD52BA601637C8FC967641E7ECC8A6CFC0055`
SHA512 | `DB01D2B3CA435B2DA15593DB6A7F2341722D5C0DB35BCA1FD94250D7129FD2B14EC8CB0782EE06C226F3A2CC4310C22E32A7B6A6A1083FFC767A072173322A80`
SSDEEP | `6144:wBGliP5NYIuL/uzcYdt1r1nLrXujAlhKsjbAObd8fXrpirWMyL:wHU/uZNr1+AlhKsjbAW8f7pin`

## Signature

* Status: Signature verified.
* Serial: `330000023241FB59996DCC4DFF000000000232`
* Thumbprint: `FF82BC38E1DA5E596DF374C53E3617F7EDA36B06`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: msdt.exe
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.18362.1 (WinBuild.160101.0800)
* Product Version: 10.0.18362.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.



## Possible Misuse

*The following table contains possible examples of `msdt.exe` being misused. While `msdt.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_possible_applocker_bypass.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_possible_applocker_bypass.yml) | `- '\msdt.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Msdt.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Msdt.yml) | `Name: Msdt.exe`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Msdt.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Msdt.yml) | `- Command: msdt.exe -path C:\WINDOWS\diagnostics\index\PCWDiagnostic.xml -af C:\PCW8E57.xml /skip TRUE`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Msdt.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Msdt.yml) | `- Path: C:\Windows\System32\Msdt.exe`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Msdt.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Msdt.yml) | `- Path: C:\Windows\SysWOW64\Msdt.exe`{:.highlight .language-yaml} | 

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
| /id `<packagename>` | Specifies which diagnostic package to run. For a list of available packages, see [Available Troubleshooting packs](/previous-versions/windows/it-pro/windows-server-2012-r2-and-2012/ee424379(v=ws.11)#available-troubleshooting-packs). |
| /path `<directory|.diagpkg file|.diagcfg file>` | Specifies the full path to a diagnostic package. If you specify a directory, the directory must contain a diagnostic package. You cannot use the **/path** parameter in conjunction with the** /id**, **/dci**, or **/cab** parameters. |
| /dci `<passkey>` | Prepopulates the passkey field. This parameter is only used when a support provider has supplied a passkey. |
| /dt `<directory>` | Displays the troubleshooting history in the specified directory. Diagnostic results are stored in the userâ€™s **%LOCALAPPDATA%\Diagnostics** or **%LOCALAPPDATA%\ElevatedDiagnostics** directories. |
| /af `<answerfile>` | Specifies an answer file in XML format that contains responses to one or more diagnostic interactions. |
| /modal `<ownerHWND>` | Makes the troubleshooting pack modal to a window designated by the parent Console Window Handle (HWND), in decimal. This parameter is typically used by applications that launch a troubleshooting pack. For more information about obtaining Console Window Handles, see [How to Obtain a Console Window Handle (HWND)](https://support.microsoft.com/help/124103/how-to-obtain-a-console-window-handle-hwnd). |
| /moreoptions `<true|false>` | Enables (true) or suppresses (false) the final troubleshooting screen that asks if the user wants to explore additional options. This parameter is typically used when the troubleshooting pack is launched by a troubleshooter that isn't part of the operating system. |
| /param `<parameters>` | Specifies a set of interaction responses at the command line, similar to an answer file. This parameter isn't typically used within the context of troubleshooting packs created with TSP Designer. For more information about developing custom parameters, see [Windows Troubleshooting Platform](/previous-versions/windows/desktop/wintt/windows-troubleshooting-toolkit-portal). |
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

- [Available troubleshooting packs](/previous-versions/windows/it-pro/windows-server-2012-r2-and-2012/ee424379(v=ws.11)#available-troubleshooting-packs)

- [TroubleshootingPack Powershell reference](/powershell/module/troubleshootingpack/)

---



MIT License. Copyright (c) 2020-2021 Strontic.


