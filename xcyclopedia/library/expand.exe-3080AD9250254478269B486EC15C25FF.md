---
title: expand.exe | LZ Expansion Utility
excerpt: What is expand.exe?
---

# expand.exe 

* File Path: `C:\Windows\system32\expand.exe`
* Description: LZ Expansion Utility

## Hashes

Type | Hash
-- | --
MD5 | `3080AD9250254478269B486EC15C25FF`
SHA1 | `56F145B564EEE207A542C142FF9C2FE56A131985`
SHA256 | `210A43646B58A60035CEDC30281F3414DD6A551A62255AAC7EF828C5D7EA46CE`
SHA384 | `C3706377DFB3C528786D70D75C9D90C828DD9D1A15AAA50DD0B2507C6F233C66381F8370D68F4600A9DD38ED0E1AB69A`
SHA512 | `662F57AA91202AAA48282F099ED5DDCB9F7151E2E7733983F312823D4D5DDAE4506F3DB0F6BE7FE7D7DA49415197D3B982A0FB76777470A9A0B0E7EC004F4B9F`
SSDEEP | `1536:1HUJ90Qr1hzF2F5Tbmb+KEUlqHuikyMUn:qHh2fTSLfan`
IMP | `8BB8291E08A891E3DCA4B595B2F1D718`
PESHA1 | `1076B64C749875C6166A3C18EF122DB42472BACD`
PE256 | `24AFE74B2B157088844DBF2D034578D09EC1760F99197E68068569F4B2AC6E14`

## Runtime Data

### Usage (stdout):
```cmhg
Microsoft (R) File Expansion Utility
Copyright (c) Microsoft Corporation. All rights reserved.

Expands one or more compressed files.

EXPAND [-R] Source Destination
EXPAND -R Source [Destination]
EXPAND -I Source [Destination]
EXPAND -D Source.cab [-F:Files]
EXPAND Source.cab -F:Files Destination

  -R		Rename expanded files.
  -I		Rename expanded files but ignore directory structure.
  -D		Display list of files in source.
  Source	Source file specification.  Wildcards may be used.
  -F:Files	Name of files to expand from a .CAB.
  Destination	Destination file | path specification.
		Destination may be a directory.
		If Source is multiple files and -r is not specified,
		Destination must be a directory.

```

### Loaded Modules:

Path |
-- |
C:\Windows\system32\expand.exe |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\SYSTEM32\ntdll.dll |


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: expand
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 5.00 (WinBuild.160101.0800)
* Product Version: 5.00
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/76
* VirusTotal Link: https://www.virustotal.com/gui/file/210a43646b58a60035cedc30281f3414dd6a551a62255aac7ef828c5d7ea46ce/detection


## Possible Misuse

*The following table contains possible examples of `expand.exe` being misused. While `expand.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_suspicious_remote_thread.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/sysmon/sysmon_suspicious_remote_thread.yml) | `- '\expand.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Expand.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Expand.yml) | `Name: Expand.exe` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Expand.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Expand.yml) | `- Command: expand \\webdav\folder\file.bat c:\ADS\file.bat` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Expand.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Expand.yml) | `- Command: expand c:\ADS\file1.bat c:\ADS\file2.bat` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Expand.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Expand.yml) | `- Command: expand \\webdav\folder\file.bat c:\ADS\file.txt:file.bat` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Expand.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Expand.yml) | `- Path: C:\Windows\System32\Expand.exe` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Expand.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Expand.yml) | `- Path: C:\Windows\SysWOW64\Expand.exe` | 
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1003.001.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1003.001/T1003.001.md) | Expand-Archive $zippath $parentpath\wce -Force | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1003.001.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1003.001/T1003.001.md) | Expand-Archive $env:TEMP\Procdump.zip $env:TEMP\Procdump -Force | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1003.001.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1003.001/T1003.001.md) | Expand-Archive $env:TEMP\Mimi.zip $env:TEMP\Mimi -Force | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1003.004.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1003.004/T1003.004.md) | Expand-Archive $env:TEMP\PSTools.zip $env:TEMP\PSTools -Force | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1021.001.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1021.001/T1021.001.md) | Adversaries may connect to a remote system over RDP/RDS to expand access if the service is enabled and allows access to accounts with known credentials. Adversaries will likely use Credential Access techniques to acquire credentials to use with RDP. Adversaries may also use RDP in conjunction with the [Accessibility Features](https://attack.mitre.org/techniques/T1546/008) technique for Persistence.(Citation: Alperovitch Malware)</blockquote> | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1027.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1027/T1027.md) | Expand-Archive -path "$env:temp\T1027.zip" -DestinationPath "$env:temp\temp_T1027.zip\" -Force | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1055.012.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1055.012/T1055.012.md) | $ppid=Get-Process #{parent_process_name} \| select -expand id | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1071.001.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1071.001/T1071.001.md) | Expand-Archive -Path $env:temp\curl.zip -DestinationPath $env:temp\curl | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1095.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1095/T1095.md) | Expand-Archive $zippath $parentpath -Force | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1134.004.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1134.004/T1134.004.md) | $ppid=Get-Process #{parent_process_name} \| select -expand id | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1485.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1485/T1485.md) | Expand-Archive $env:TEMP\SDelete.zip $env:TEMP\Sdelete -Force | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1550.002.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1550.002/T1550.002.md) | Expand-Archive $env:TEMP\mimikatz.zip $env:TEMP\mimikatz -Force | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1555.003.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1555.003/T1555.003.md) | After acquiring credentials from web browsers, adversaries may attempt to recycle the credentials across different systems and/or accounts in order to expand access. This can result in significantly furthering an adversary's objective in cases where credentials gained from web browsers overlap with privileged accounts (e.g. domain administrator).</blockquote> | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1555.003.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1555.003/T1555.003.md) | Expand-Archive #{file_path}\Modified-SysInternalsSuite.zip #{file_path}\sysinternals -Force | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1562.001.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1562.001/T1562.001.md) | Expand-Archive $env:TEMP\Sysmon.zip $env:TEMP\Sysmon -Force | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1562.001.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1562.001/T1562.001.md) | Expand-Archive $zippath $parentpath -Force; Remove-Item $zippath | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1564.004.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1564.004/T1564.004.md) | expand \\webdav\folder\file.bat #{path}\file.txt:file.bat | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1569.002.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1569.002/T1569.002.md) | Expand-Archive $env:TEMP\PsTools.zip $env:TEMP\PsTools -Force | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_op_honeybee.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_op_honeybee.yar) | $x1 = "cmd /c expand %TEMP%\\setup.cab -F:* %SystemRoot%\\System32" | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [gen_pirpi.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/gen_pirpi.yar) | $x1 = "expand.exe1.gif" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [gen_pirpi.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/gen_pirpi.yar) | $c1 = "expand.exe" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)

## Additional Info*

**The information below is copied from [MicrosoftDocs](https://github.com/MicrosoftDocs/windowsserverdocs), which is maintained by [Microsoft](https://opensource.microsoft.com/codeofconduct/). Available under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) license.*

---

## expand

> Applies to: Windows Server (Semi-Annual Channel), Windows Server 2019, Windows Server 2016, Windows Server 2012 R2, Windows Server 2012

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



MIT License. Copyright (c) 2020 Strontic.


