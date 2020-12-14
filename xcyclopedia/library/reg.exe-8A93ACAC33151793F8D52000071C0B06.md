---
title: reg.exe | Registry Console Tool
excerpt: What is reg.exe?
---

# reg.exe 

* File Path: `C:\Windows\system32\reg.exe`
* Description: Registry Console Tool

## Hashes

Type | Hash
-- | --
MD5 | `8A93ACAC33151793F8D52000071C0B06`
SHA1 | `429DF8371B437209D79DC97978C33157D1A71C4B`
SHA256 | `19316D4266D0B776D9B2A05D5903D8CBC8F0EA1520E9C2A7E6D5960B6FA4DCAF`
SHA384 | `2C6EF95487F35401C121BBED23F686E976E0DCA52537E03542C44E0A3B3D84AC536ABE17D9D83F693EBFAC47F350B3E7`
SHA512 | `79B676C9E349E38AEF652271D406551F9C350CCAAAB01FAA305D9E40F11059E4F814A5FA91863AF1B94AB198B563D9F57009158CFA5E535ED1236FAEB163F7E5`
SSDEEP | `1536:CbKnXHpwaQBT4Tl9RuV9DXs11jy1Cz/Y1Z+2hGfVhtOXKnv86F1:CGb+4x9RwDXEW1CaMS8DOXqv86`
IMP | `BE482BE427FE212CFEF2CDA0E61F19AC`
PESHA1 | `2E1E9F034F57388A5401653C942CC8BA6A7D92AC`
PE256 | `44AB6478A02D197714785D1BB2CCD1B48C9B31F6D3491201738F954CEB7F604E`

## Runtime Data

### Usage (stdout):
```cmhg

REG Operation [Parameter List]

  Operation  [ QUERY   | ADD    | DELETE  | COPY    |
               SAVE    | LOAD   | UNLOAD  | RESTORE |
               COMPARE | EXPORT | IMPORT  | FLAGS ]

Return Code: (Except for REG COMPARE)

  0 - Successful
  1 - Failed

For help on a specific operation type:

  REG Operation /?

Examples:

  REG QUERY /?
  REG ADD /?
  REG DELETE /?
  REG COPY /?
  REG SAVE /?
  REG RESTORE /?
  REG LOAD /?
  REG UNLOAD /?
  REG COMPARE /?
  REG EXPORT /?
  REG IMPORT /?
  REG FLAGS /?

```

### Usage (stderr):
```cmhg
ERROR: Invalid Argument/Option - '--help'.
Type "REG /?" for usage.

```

## Signature

* Status: Signature verified.
* Serial: `33000001C422B2F79B793DACB20000000001C4`
* Thumbprint: `AE9C1AE54763822EEC42474983D8B635116C8452`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: reg.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.17763.1 (WinBuild.160101.0800)
* Product Version: 10.0.17763.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/70
* VirusTotal Link: https://www.virustotal.com/gui/file/19316d4266d0b776d9b2a05d5903d8cbc8f0ea1520e9c2a7e6d5960b6fa4dcaf/detection/


## Possible Misuse

*The following table contains possible examples of `reg.exe` being misused. While `reg.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_grabbing_sensitive_hives_via_reg.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_grabbing_sensitive_hives_via_reg.yml) | `description: Dump sam, system or security hives using REG.exe utility` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_grabbing_sensitive_hives_via_reg.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_grabbing_sensitive_hives_via_reg.yml) | `Image: '*\reg.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_mmc_spawn_shell.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_mmc_spawn_shell.yml) | `- '*\reg.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_mshta_spawn_shell.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_mshta_spawn_shell.yml) | `- '*\reg.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_multiple_suspicious_cli.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_multiple_suspicious_cli.yml) | `- reg.exe` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_query_registry.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_query_registry.yml) | `Image\|endswith: '\reg.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_direct_asep_reg_keys_modification.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_direct_asep_reg_keys_modification.yml) | `description: Detects direct modification of autostart extensibility point (ASEP) in registry using reg.exe.` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_direct_asep_reg_keys_modification.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_direct_asep_reg_keys_modification.yml) | `Image\|endswith: '*\reg.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Reg.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Reg.yml) | `Name: Reg.exe` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Reg.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Reg.yml) | `- Path: C:\Windows\System32\reg.exe` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Reg.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Reg.yml) | `- Path: C:\Windows\SysWOW64\reg.exe` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Reg.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Reg.yml) | `- IOC: reg.exe writing to an ADS` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Wmic.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Wmic.yml) | `- Command: wmic.exe process call create "C:\Windows\system32\reg.exe add \"HKLM\SOFTWARE\Microsoft\Windows NT\CurrentVersion\Image File Execution Options\osk.exe\" /v \"Debugger\" /t REG_SZ /d \"cmd.exe\" /f"` | 
[malware-ioc](https://github.com/eset/malware-ioc) | [misp_invisimole.json](https://github.com/eset/malware-ioc/blob/master/invisimole/misp_invisimole.json) | `"description": "Masquerading occurs when the name or location of an executable, legitimate or malicious, is manipulated or abused for the sake of evading defenses and observation. Several different variations of this technique have been observed.\n\nOne variant is for an executable to be placed in a commonly trusted directory or given the name of a legitimate, trusted program. Alternatively, the filename given may be a close approximation of legitimate programs or something innocuous. An example of this is when a common system utility or program is moved and renamed to avoid detection based on its usage.(Citation: FireEye APT10 Sept 2018) This is done to bypass tools that trust executables by relying on file name or path, as well as to deceive defenders and system administrators into thinking a file is benign by associating the name with something that is thought to be legitimate.\n\nA third variant uses the right-to-left override (RTLO or RLO) character (U+202E) as a means of tricking a user into executing what they think is a benign file type but is actually executable code. RTLO is a non-printing character that causes the text that follows it to be displayed in reverse.(Citation: Infosecinstitute RTLO Technique) For example, a Windows screensaver file named <code>March 25 \\u202Excod.scr</code> will display as <code>March 25 rcs.docx</code>. A JavaScript file named <code>photo_high_re\\u202Egnp.js</code> will be displayed as <code>photo_high_resj.png</code>. A common use of this technique is with spearphishing attachments since it can trick both end users and defenders if they are not aware of how their tools display and render the RTLO character. Use of the RTLO character has been seen in many targeted intrusion attempts and criminal activity.(Citation: Trend Micro PLEAD RTLO)(Citation: Kaspersky RTLO Cyber Crime) RTLO can be used in the Windows Registry as well, where regedit.exe displays the reversed characters but the command line tool reg.exe does not by default. \n\nAdversaries may modify a binary's metadata, including such fields as icons, version, name of the product, description, and copyright, to better blend in with the environment and increase chances of deceiving a security analyst or product.(Citation: Threatexpress MetaTwin 2017)\n\n### Windows\nIn another variation of this technique, an adversary may use a renamed copy of a legitimate utility, such as rundll32.exe. (Citation: Endgame Masquerade Ball) An alternative case occurs when a legitimate utility is moved to a different directory and also renamed to avoid detections based on system utilities executing from non-standard paths. (Citation: F-Secure CozyDuke)\n\nAn example of abuse of trusted locations in Windows would be the <code>C:\\Windows\\System32</code> directory. Examples of trusted binary names that can be given to malicious binares include \"explorer.exe\" and \"svchost.exe\".\n\n### Linux\nAnother variation of this technique includes malicious binaries changing the name of their running process to that of a trusted or benign process, after they have been launched as opposed to before. (Citation: Remaiten)\n\nAn example of abuse of trusted locations in Linux  would be the <code>/bin</code> directory. Examples of trusted binary names that can be given to malicious binaries include \"rsyncd\" and \"dbus-inotifier\". (Citation: Fysbis Palo Alto Analysis)  (Citation: Fysbis Dr Web Analysis)",` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [index.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Indexes-Markdown/index.md) | - Atomic Test #8: Disable UAC using reg.exe [windows] | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [index.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Indexes-Markdown/index.md) | - Atomic Test #2: Service ImagePath Change with reg.exe [windows] | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [windows-index.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Indexes-Markdown/windows-index.md) | - Atomic Test #8: Disable UAC using reg.exe [windows] | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [windows-index.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Indexes-Markdown/windows-index.md) | - Atomic Test #2: Service ImagePath Change with reg.exe [windows] | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1037.001.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1037.001/T1037.001.md) | REG.exe ADD HKCU\Environment /v UserInitMprLogonScript /t REG_SZ /d "#{script_path}" /f | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1037.001.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1037.001/T1037.001.md) | REG.exe DELETE HKCU\Environment /v UserInitMprLogonScript /f >nul 2>&1 | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1059.001.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1059.001/T1059.001.md) | reg.exe add "HKEY_CURRENT_USER\Software\Classes\AtomicRedTeam" /v ART /t REG_SZ /d "U2V0LUNvbnRlbnQgLXBhdGggIiRlbnY6U3lzdGVtUm9vdC9UZW1wL2FydC1tYXJrZXIudHh0IiAtdmFsdWUgIkhlbGxvIGZyb20gdGhlIEF0b21pYyBSZWQgVGVhbSI=" | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1112.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1112/T1112.md) | Modify the registry of the currently logged in user using reg.exe via cmd console. Upon execution, the message "The operation completed successfully." | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1546.002.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1546.002/T1546.002.md) | reg.exe add "HKEY_CURRENT_USER\Control Panel\Desktop" /v ScreenSaveActive /t REG_SZ /d 1 /f | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1546.002.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1546.002/T1546.002.md) | reg.exe add "HKEY_CURRENT_USER\Control Panel\Desktop" /v ScreenSaveTimeout /t REG_SZ /d 60 /f | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1546.002.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1546.002/T1546.002.md) | reg.exe add "HKEY_CURRENT_USER\Control Panel\Desktop" /v ScreenSaverIsSecure /t REG_SZ /d 0 /f | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1546.002.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1546.002/T1546.002.md) | reg.exe add "HKEY_CURRENT_USER\Control Panel\Desktop" /v SCRNSAVE.EXE /t REG_SZ /d "%SystemRoot%\System32\evilscreensaver.scr" /f | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1546.010.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1546.010/T1546.010.md) | reg.exe import #{registry_file} | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1546.010.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1546.010/T1546.010.md) | reg.exe import #{registry_cleanup_file} >nul 2>&1 | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1548.002.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1548.002/T1548.002.md) | - [Atomic Test #8 - Disable UAC using reg.exe](#atomic-test-8---disable-uac-using-regexe) | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1548.002.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1548.002/T1548.002.md) | reg.exe add hkcu\software\classes\mscfile\shell\open\command /ve /d "#{executable_binary}" /f | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1548.002.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1548.002/T1548.002.md) | reg.exe delete hkcu\software\classes\mscfile /f >nul 2>&1 | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1548.002.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1548.002/T1548.002.md) | reg.exe add hkcu\software\classes\ms-settings\shell\open\command /ve /d "#{executable_binary}" /f | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1548.002.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1548.002/T1548.002.md) | reg.exe add hkcu\software\classes\ms-settings\shell\open\command /v "DelegateExecute" /f | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1548.002.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1548.002/T1548.002.md) | reg.exe delete hkcu\software\classes\ms-settings /f >nul 2>&1 | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1548.002.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1548.002/T1548.002.md) | ## Atomic Test #8 - Disable UAC using reg.exe | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1548.002.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1548.002/T1548.002.md) | Disable User Account Conrol (UAC) using the builtin tool reg.exe by changing its registry key | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1548.002.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1548.002/T1548.002.md) | reg.exe ADD HKLM\SOFTWARE\Microsoft\Windows\CurrentVersion\Policies\System /v EnableLUA /t REG_DWORD /d 0 /f | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1548.002.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1548.002/T1548.002.md) | reg.exe ADD HKLM\SOFTWARE\Microsoft\Windows\CurrentVersion\Policies\System /v EnableLUA /t REG_DWORD /d 1 /f | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1574.011.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1574.011/T1574.011.md) | - [Atomic Test #2 - Service ImagePath Change with reg.exe](#atomic-test-2---service-imagepath-change-with-regexe) | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1574.011.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1574.011/T1574.011.md) | ## Atomic Test #2 - Service ImagePath Change with reg.exe | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1574.011.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1574.011/T1574.011.md) | reg.exe add "HKLM\SYSTEM\CurrentControlSet\Services\#{weak_service_name}" /f /v ImagePath /d "#{malicious_service_path}" | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)

## Additional Info*

**The information below is copied from [MicrosoftDocs](https://github.com/MicrosoftDocs/windowsserverdocs), which is maintained by [Microsoft](https://opensource.microsoft.com/codeofconduct/). Available under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) license.*

---

## reg commands

Performs operations on registry subkey information and values in registry entries.

Some operations enable you to view or configure registry entries on local or remote computers, while others allow you to configure only local computers. Using **reg** to configure the registry of remote computers limits the parameters that you can use in some operations. Check the syntax and parameters for each operation to verify that they can be used on remote computers.

> [!CAUTION]
> Don't edit the registry directly unless you have no alternative. The registry editor bypasses standard safeguards, allowing settings that can degrade performance, damage your system, or even require you to reinstall Windows. You can safely alter most registry settings by using the programs in Control Panel or Microsoft Management Console (MMC). If you must edit the registry directly, back it up first.

### Syntax

```
reg add
reg compare
reg copy
reg delete
reg export
reg import
reg load
reg query
reg restore
reg save
reg unload
```

#### Parameters

| Parameter | Description |
|--|--|
| [reg add](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/reg-add.md) | Adds a new subkey or entry to the registry. |
| [reg compare](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/reg-compare.md) | Compares specified registry subkeys or entries. |
| [reg copy](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/reg-copy.md) | Copies a registry entry to a specified location on the local or remote computer. |
| [reg delete](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/reg-delete.md) | Deletes a subkey or entries from the registry. |
| [reg export](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/reg-export.md) | Copies the specified subkeys, entries, and values of the local computer into a file for transfer to other servers. |
| [reg import](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/reg-import.md) | Copies the contents of a file that contains exported registry subkeys, entries, and values into the registry of the local computer. |
| [reg load](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/reg-load.md) | Writes saved subkeys and entries into a different subkey in the registry. |
| [reg query](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/reg-query.md) | Returns a list of the next tier of subkeys and entries that are located under a specified subkey in the registry. |
| [reg restore](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/reg-restore.md) | Writes saved subkeys and entries back to the registry. |
| [reg save](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/reg-save.md) | Saves a copy of specified subkeys, entries, and values of the registry in a specified file. |
| [reg unload](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/reg-unload.md) | Removes a section of the registry that was loaded using the **reg load** operation. |

### Additional References

- [Command-Line Syntax Key](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/command-line-syntax-key.md)

---



MIT License. Copyright (c) 2020 Strontic.


