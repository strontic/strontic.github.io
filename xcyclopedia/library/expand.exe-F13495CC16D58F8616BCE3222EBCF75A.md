﻿---
title: expand.exe | LZ Expansion Utility
excerpt: What is expand.exe?
---

# expand.exe 

* File Path: `C:\windows\SysWOW64\expand.exe`
* Description: LZ Expansion Utility

## Hashes

Type | Hash
-- | --
MD5 | `F13495CC16D58F8616BCE3222EBCF75A`
SHA1 | `05B2775C1D683D55C1F4D69BE81B8124D2CACF5C`
SHA256 | `F6C58FD43D203ECE69A80F8DAD51B85188BD138200CF2834798D7C5DE950564B`
SHA384 | `351C7C5D84C56F1083133E380B4FE67B3FE39EA5B80AF3B7A11A459D1B948C7F05E5D4E1FBA06BAB5DBC74B79E18C147`
SHA512 | `F9E0A8C44C080FA6BAF993D7072B89FD21E76DD16767BF7C94A976148A9874DD1C1E6F72902C29C62564EFFD62A5D87CFA94F4611AC79573D3D8D939E5950F4A`
SSDEEP | `768:wia8KdB5goEYtsmlxSotFFt8hJ7oeyXFbF33MVK6KCYmK6h:AbOEuQtgSXFbFnMVK6KCYmK6`

## Signature

* Status: The file C:\windows\SysWOW64\expand.exe is not digitally signed. You cannot run this script on the current system. For more information about running scripts and setting execution policy, see about_Execution_Policies at http://go.microsoft.com/fwlink/?LinkID=135170
* Serial: ``
* Thumbprint: ``
* Issuer: 
* Subject: 

## File Metadata

* Original Filename: expand
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 6.3.9600.16384 (winblue_rtm.130821-1623)
* Product Version: 6.3.9600.16384
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.



## Possible Misuse

*The following table contains possible examples of `expand.exe` being misused. While `expand.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_suspicious_remote_thread.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/create_remote_thread/sysmon_suspicious_remote_thread.yml) | `- '\expand.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [powershell_decompress_commands.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/powershell/powershell_module/powershell_decompress_commands.yml) | `Payload\|contains: 'Expand-Archive'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_expand_cabinet_files.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/sysmon_expand_cabinet_files.yml) | `description: Adversaries can use the inbuilt expand utility to decompress cab files as seen in recent Iranian MeteorExpress attack`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_expand_cabinet_files.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/sysmon_expand_cabinet_files.yml) | `- '\expand.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Expand.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Expand.yml) | `Name: Expand.exe`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Expand.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Expand.yml) | `- Command: expand \\webdav\folder\file.bat c:\ADS\file.bat`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Expand.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Expand.yml) | `- Command: expand c:\ADS\file1.bat c:\ADS\file2.bat`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Expand.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Expand.yml) | `- Command: expand \\webdav\folder\file.bat c:\ADS\file.txt:file.bat`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Expand.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Expand.yml) | `- Path: C:\Windows\System32\Expand.exe`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Expand.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Expand.yml) | `- Path: C:\Windows\SysWOW64\Expand.exe`{:.highlight .language-yaml} | 
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1003.001.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1003.001/T1003.001.md) | Expand-Archive $zippath $parentpath\wce -Force | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1003.001.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1003.001/T1003.001.md) | Expand-Archive $env:TEMP\Procdump.zip $env:TEMP\Procdump -Force | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1003.001.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1003.001/T1003.001.md) | Expand-Archive $env:TEMP\Mimi.zip $env:TEMP\Mimi -Force | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1003.004.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1003.004/T1003.004.md) | Expand-Archive $env:TEMP\PSTools.zip $env:TEMP\PSTools -Force | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1003.006.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1003.006/T1003.006.md) | Expand-Archive $env:TEMP\mimikatz.zip $env:TEMP\mimikatz -Force | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1021.001.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1021.001/T1021.001.md) | Adversaries may connect to a remote system over RDP/RDS to expand access if the service is enabled and allows access to accounts with known credentials. Adversaries will likely use Credential Access techniques to acquire credentials to use with RDP. Adversaries may also use RDP in conjunction with the [Accessibility Features](https://attack.mitre.org/techniques/T1546/008) technique for Persistence.(Citation: Alperovitch Malware)</blockquote> | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1021.002.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1021.002/T1021.002.md) | Expand-Archive $env:TEMP\PsTools.zip $env:TEMP\PsTools -Force | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1027.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1027/T1027.md) | Expand-Archive -path "$env:temp\T1027.zip" -DestinationPath "$env:temp\temp_T1027.zip\" -Force | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1055.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1055/T1055.md) | Expand-Archive $env:TEMP\mimikatz.zip $env:TEMP\mimikatz -Force | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1055.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1055/T1055.md) | Expand-Archive $env:TEMP\PsTools.zip $env:TEMP\PsTools -Force | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1055.012.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1055.012/T1055.012.md) | $ppid=Get-Process #{parent_process_name} \| select -expand id | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1071.001.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1071.001/T1071.001.md) | Expand-Archive -Path $env:temp\curl.zip -DestinationPath $env:temp\curl | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1095.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1095/T1095.md) | Expand-Archive $zippath $parentpath -Force | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1105.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1105/T1105.md) | Expand-Archive -Path $env:temp\curl.zip -DestinationPath $env:temp\curl | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1134.004.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1134.004/T1134.004.md) | $ppid=Get-Process #{parent_process_name} \| select -expand id | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1207.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1207/T1207.md) | Expand-Archive $env:TEMP\mimikatz.zip $env:TEMP\mimikatz -Force | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1207.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1207/T1207.md) | Expand-Archive $env:TEMP\PsTools.zip $env:TEMP\PsTools -Force | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1485.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1485/T1485.md) | Expand-Archive $env:TEMP\SDelete.zip $env:TEMP\Sdelete -Force | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1548.002.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1548.002/T1548.002.md) | Expand-Archive $env:TEMP\uacme.zip $env:TEMP\uacme -Force | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1550.002.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1550.002/T1550.002.md) | Expand-Archive $env:TEMP\mimikatz.zip $env:TEMP\mimikatz -Force | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1550.003.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1550.003/T1550.003.md) | Expand-Archive $env:TEMP\Mimi.zip $env:TEMP\Mimi -Force | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1555.003.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1555.003/T1555.003.md) | After acquiring credentials from web browsers, adversaries may attempt to recycle the credentials across different systems and/or accounts in order to expand access. This can result in significantly furthering an adversary's objective in cases where credentials gained from web browsers overlap with privileged accounts (e.g. domain administrator).</blockquote> | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1555.003.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1555.003/T1555.003.md) | Expand-Archive #{file_path}\Modified-SysInternalsSuite.zip #{file_path}\sysinternals -Force | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1558.001.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1558.001/T1558.001.md) | $domain = gwmi Win32_ComputerSystem \| Select -Expand Domain | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1558.001.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1558.001/T1558.001.md) | Expand-Archive $env:TEMP\mimikatz.zip $env:TEMP\mimikatz -Force | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1562.001.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1562.001/T1562.001.md) | Expand-Archive $env:TEMP\Sysmon.zip $env:TEMP\Sysmon -Force | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1562.001.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1562.001/T1562.001.md) | Expand-Archive $zippath $parentpath -Force; Remove-Item $zippath | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1564.004.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1564.004/T1564.004.md) | expand \\webdav\folder\file.bat #{path}\file.txt:file.bat | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1569.002.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1569.002/T1569.002.md) | Expand-Archive $env:TEMP\PsTools.zip $env:TEMP\PsTools -Force | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_op_honeybee.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_op_honeybee.yar) | $x1 = "cmd /c expand %TEMP%\\setup.cab -F:* %SystemRoot%\\System32" | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [gen_pirpi.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/gen_pirpi.yar) | $x1 = "expand.exe1.gif" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [gen_pirpi.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/gen_pirpi.yar) | $c1 = "expand.exe" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[stockpile](https://github.com/mitre/stockpile) | [cc191baa-7472-4386-a2f4-42f203f1acfd.yml](https://github.com/mitre/stockpile/blob/master/data/abilities/collection/cc191baa-7472-4386-a2f4-42f203f1acfd.yml) | `Expand-Archive -LiteralPath $download_folder"PSTools.zip" -DestinationPath $staging_folder;`{:.highlight .language-yaml} | [Apache-2.0](https://github.com/mitre/stockpile/blob/master/LICENSE)
[stockpile](https://github.com/mitre/stockpile) | [0ef4cc7b-611c-4237-b20b-db36b6906554.yml](https://github.com/mitre/stockpile/blob/master/data/abilities/credential-access/0ef4cc7b-611c-4237-b20b-db36b6906554.yml) | `Expand-Archive -LiteralPath $download_folder"Procdump.zip" -DestinationPath $staging_folder;`{:.highlight .language-yaml} | [Apache-2.0](https://github.com/mitre/stockpile/blob/master/LICENSE)
[stockpile](https://github.com/mitre/stockpile) | [46da2385-cf37-49cb-ba4b-a739c7a19de4.yml](https://github.com/mitre/stockpile/blob/master/data/abilities/impact/46da2385-cf37-49cb-ba4b-a739c7a19de4.yml) | `Expand-Archive -LiteralPath xmrig-6.11.2-msvc-win64.zip -DestinationPath .\;`{:.highlight .language-yaml} | [Apache-2.0](https://github.com/mitre/stockpile/blob/master/LICENSE)

## Additional Info*

**The information below is copied from [MicrosoftDocs](https://github.com/MicrosoftDocs/windowsserverdocs), which is maintained by [Microsoft](https://opensource.microsoft.com/codeofconduct/). Available under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) license.*

---

## expand

>Applies to: Windows Server 2022, Windows Server 2019, Windows Server 2016, Windows Server 2012 R2, Windows Server 2012

Expands one or more compressed files. You can also use this command to retrieve compressed files from distribution disks.

The **expand** command can also run from the Windows Recovery Console, using different parameters. For more information, see [Windows Recovery Environment (WinRE)](/windows-hardware/manufacture/desktop/windows-recovery-environment--windows-re--technical-reference).

### Syntax

```
expand [/r] <source> <destination>
expand /r <source> [<destination>]
expand /i <source> [<destination>]
expand /d <source>.cab [/f:<files>]
expand <source>.cab /f:<files> <destination>
```

#### Parameters

| Parameter | Description |
| --------- | ----------- |
| /r | Renames expanded files. |
| source | Specifies the files to expand. *Source* can consist of a drive letter and colon, a directory name, a file name, or a combination of these. You can use wildcards (**&#42;** or **?**). |
| destination | Specifies where files are to be expanded.<p>If *source* consists of multiple files and you don't specify **/r**, the *destination* must be a directory. *Destination* can consist of a drive letter and colon, a directory name, a file name, or a combination of these. Destination `file | path` specification. |
| /i | Renames expanded files but ignores the directory structure. |
| /d | Displays a list of files in the source location. Doesn't expand or extract the files. |
| /f:`<files>` | Specifies the files in a cabinet (.cab) file that you want to expand. You can use wildcards (**&#42;** or **?**). |
| /? | Displays help at the command prompt. |

### Additional References

- [Command-Line Syntax Key](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/command-line-syntax-key.md)

---



MIT License. Copyright (c) 2020-2021 Strontic.


