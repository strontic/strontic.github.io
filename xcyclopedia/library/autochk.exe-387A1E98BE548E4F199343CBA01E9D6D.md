---
title: autochk.exe | Auto Check Utility
excerpt: What is autochk.exe?
---

# autochk.exe 

* File Path: `C:\windows\system32\autochk.exe`
* Description: Auto Check Utility

## Hashes

Type | Hash
-- | --
MD5 | `387A1E98BE548E4F199343CBA01E9D6D`
SHA1 | `B80DEFCE4D019832BF018E41D6C43BDC679CA9E5`
SHA256 | `4A2B66E5587BE0BDEC99C1EC758DB67F35D1988B1FCD916355D6473E3BCDD13E`
SHA384 | `45A32C849E084CF05416DE9D997FE7CD97652530160AD09292ACF4A518ECB02755143E4362B140D035207735036FA219`
SHA512 | `76E14AD9249F39FC63BDA3FE4667C1077854BA7806BC04537C7EA5A1B1751CA151598D7015AA4165F847BAD7A4348171255BB3A14519F7D9CD02C0B66030E7B8`
SSDEEP | `12288:VFB9rDh9sZjcNR/rd3WTW9r6anRzKOl5T+AZOtJ1a6Q:H3rDzIcNR/r8ErtR2UT+5JcD`

## Signature

* Status: The file C:\windows\system32\autochk.exe is not digitally signed. You cannot run this script on the current system. For more information about running scripts and setting execution policy, see about_Execution_Policies at http://go.microsoft.com/fwlink/?LinkID=135170
* Serial: ``
* Thumbprint: ``
* Issuer: 
* Subject: 

## File Metadata

* Original Filename: AutoChk.Exe.MUI
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 6.3.9600.16384 (winblue_rtm.130821-1623)
* Product Version: 6.3.9600.16384
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.



## Possible Misuse

*The following table contains possible examples of `autochk.exe` being misused. While `autochk.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_raw_disk_access_using_illegitimate_tools.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/sysmon/sysmon_raw_disk_access_using_illegitimate_tools.yml) | `- '\autochk.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[malware-ioc](https://github.com/eset/malware-ioc) | [misp_invisimole.json](https://github.com/eset/malware-ioc/blob/master/invisimole/misp_invisimole.json) | `"description": "Adding an entry to the \"run keys\" in the Registry or startup folder will cause the program referenced to be executed when a user logs in. (Citation: Microsoft Run Key) These programs will be executed under the context of the user and will have the account's associated permissions level.\n\nThe following run keys are created by default on Windows systems:\n* <code>HKEY_CURRENT_USER\\Software\\Microsoft\\Windows\\CurrentVersion\\Run</code>\n* <code>HKEY_CURRENT_USER\\Software\\Microsoft\\Windows\\CurrentVersion\\RunOnce</code>\n* <code>HKEY_LOCAL_MACHINE\\Software\\Microsoft\\Windows\\CurrentVersion\\Run</code>\n* <code>HKEY_LOCAL_MACHINE\\Software\\Microsoft\\Windows\\CurrentVersion\\RunOnce</code>\n\nThe <code>HKEY_LOCAL_MACHINE\\Software\\Microsoft\\Windows\\CurrentVersion\\RunOnceEx</code> is also available but is not created by default on Windows Vista and newer. Registry run key entries can reference programs directly or list them as a dependency. (Citation: Microsoft RunOnceEx APR 2018) For example, it is possible to load a DLL at logon using a \"Depend\" key with RunOnceEx: <code>reg add HKLM\\SOFTWARE\\Microsoft\\Windows\\CurrentVersion\\RunOnceEx\\0001\\Depend /v 1 /d \"C:\\temp\\evil[.]dll\"</code> (Citation: Oddvar Moe RunOnceEx Mar 2018)\n\nThe following Registry keys can be used to set startup folder items for persistence:\n* <code>HKEY_CURRENT_USER\\Software\\Microsoft\\Windows\\CurrentVersion\\Explorer\\User Shell Folders</code>\n* <code>HKEY_CURRENT_USER\\Software\\Microsoft\\Windows\\CurrentVersion\\Explorer\\Shell Folders</code>\n* <code>HKEY_LOCAL_MACHINE\\SOFTWARE\\Microsoft\\Windows\\CurrentVersion\\Explorer\\Shell Folders</code>\n* <code>HKEY_LOCAL_MACHINE\\SOFTWARE\\Microsoft\\Windows\\CurrentVersion\\Explorer\\User Shell Folders</code>\n\nThe following Registry keys can control automatic startup of services during boot:\n* <code>HKEY_LOCAL_MACHINE\\Software\\Microsoft\\Windows\\CurrentVersion\\RunServicesOnce</code>\n* <code>HKEY_CURRENT_USER\\Software\\Microsoft\\Windows\\CurrentVersion\\RunServicesOnce</code>\n* <code>HKEY_LOCAL_MACHINE\\Software\\Microsoft\\Windows\\CurrentVersion\\RunServices</code>\n* <code>HKEY_CURRENT_USER\\Software\\Microsoft\\Windows\\CurrentVersion\\RunServices</code>\n\nUsing policy settings to specify startup programs creates corresponding values in either of two Registry keys:\n* <code>HKEY_LOCAL_MACHINE\\Software\\Microsoft\\Windows\\CurrentVersion\\Policies\\Explorer\\Run</code>\n* <code>HKEY_CURRENT_USER\\Software\\Microsoft\\Windows\\CurrentVersion\\Policies\\Explorer\\Run</code>\n\nThe Winlogon key controls actions that occur when a user logs on to a computer running Windows 7. Most of these actions are under the control of the operating system, but you can also add custom actions here. The <code>HKEY_LOCAL_MACHINE\\Software\\Microsoft\\Windows NT\\CurrentVersion\\Winlogon\\Userinit</code> and <code>HKEY_LOCAL_MACHINE\\Software\\Microsoft\\Windows NT\\CurrentVersion\\Winlogon\\Shell</code> subkeys can automatically launch programs.\n\nPrograms listed in the load value of the registry key <code>HKEY_CURRENT_USER\\Software\\Microsoft\\Windows NT\\CurrentVersion\\Windows</code> run when any user logs on.\n\nBy default, the multistring BootExecute value of the registry key <code>HKEY_LOCAL_MACHINE\\System\\CurrentControlSet\\Control\\Session Manager</code> is set to autocheck autochk *. This value causes Windows, at startup, to check the file-system integrity of the hard disks if the system has been shut down abnormally. Adversaries can add other programs or processes to this registry value which will automatically launch at boot.\n\n\nAdversaries can use these configuration locations to execute malware, such as remote access tools, to maintain persistence through system reboots. Adversaries may also use [Masquerading](https://attack.mitre.org/techniques/T1036) to make the Registry entries look as if they are associated with legitimate programs.",`{:.highlight .language-cmhg} | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1547.001.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1547.001/T1547.001.md) | By default, the multistring <code>BootExecute</code> value of the registry key <code>HKEY_LOCAL_MACHINE\System\CurrentControlSet\Control\Session Manager</code> is set to <code>autocheck autochk *</code>. This value causes Windows, at startup, to check the file-system integrity of the hard disks if the system has been shut down abnormally. Adversaries can add other programs or processes to this registry value which will automatically launch at boot. | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)

## Additional Info*

**The information below is copied from [MicrosoftDocs](https://github.com/MicrosoftDocs/windowsserverdocs), which is maintained by [Microsoft](https://opensource.microsoft.com/codeofconduct/). Available under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) license.*

---

## autochk

Runs when the computer is started and prior to Windows Server starting to verify the logical integrity of a file system.

**Autochk.exe** is a version of **chkdsk** that runs only on NTFS disks and only before Windows Server starts. **autochk** cannot be run directly from the command-line. Instead, **autochk** runs in the following situations:

- If you try to run **chkdsk** on the boot volume.

- If **chkdsk** cannot gain exclusive use of the volume.

- If the volume is flagged as dirty.

### Remarks

> [!WARNING]
> The **autochk** command-line tool cannot be directly run from the command-line. Instead, use the **chkntfs** command-line tool to configure the way you want **autochk** to run at startup.
>
> - You can use **chkntfs** with the **/x** parameter to prevent **autochk** from running on a specific volume or multiple volumes.
>
> - Use the **chkntfs.exe** command-line tool with the **/t** parameter to change the autochk delay from 0 seconds to up to 3 days (259,200 seconds). However, a long delay means that the computer does not start until the time elapses or until you press a key to cancel **autochk**.

### Additional References

- [Command-Line Syntax Key](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/command-line-syntax-key.md)

- [chkdsk command](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/chkdsk.md)

- [chkntfs command](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/chkntfs.md)

---



MIT License. Copyright (c) 2020-2021 Strontic.


