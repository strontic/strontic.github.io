---
title: replace.exe | Replace File Utility
excerpt: What is replace.exe?
---

# replace.exe 

* File Path: `C:\Windows\system32\replace.exe`
* Description: Replace File Utility

## Hashes

Type | Hash
-- | --
MD5 | `5ACE617B14602EF7CEDD2FCF9332F26E`
SHA1 | `0591B8DF497C30ABE26BA0A5B1468E4B3EAAF3FB`
SHA256 | `83E2714735C365C3C01D8D8D56434983C1238A2A806D23AB48F42F59E2DF8093`
SHA384 | `D720EA84ECCD0B8CCA75CCB3E92A30ACFFE0F0F5606C7419DFAD2B9B7CF5500658AA711F32811E137D5C432A16BD3DA3`
SHA512 | `45E9A5AEC15BA8FB92A69DD9FEBA56ED878DA895C001F317573383BBA562BBD045E514014631A17D62CC64E3B16CD39DAF892333C31709150D8CFDF3EDD93874`
SSDEEP | `384:Ug5VC14y5FqaPDONbolmoznbvGll6rk0/jnU/jw16PZNWRh/W:ohevCljbvgkk0bnUsIZQ`
IMP | `7F915E73EEE8F7CA67BD9BA9264315DA`
PESHA1 | `F71C81DF63ED9DA0D61FC8840DD7D2EBD0629145`
PE256 | `268A1D43E26E016B817E04862700FC2559A0F7E61AD8DC353DABB7A684ECF103`

## Runtime Data

### Usage (stdout):
```cmhg
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
```cmhg
Invalid switch - --help

```

## Signature

* Status: Signature verified.
* Serial: `33000001C422B2F79B793DACB20000000001C4`
* Thumbprint: `AE9C1AE54763822EEC42474983D8B635116C8452`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: REPLACE.EXE.MUI
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.17763.1 (WinBuild.160101.0800)
* Product Version: 10.0.17763.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/70
* VirusTotal Link: https://www.virustotal.com/gui/file/83e2714735c365c3c01d8d8d56434983c1238a2a806d23ab48f42f59e2df8093/detection/


## Possible Misuse

*The following table contains possible examples of `replace.exe` being misused. While `replace.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [cisco_cli_moving_data.yml](https://github.com/Neo23x0/sigma/blob/master/rules/network/cisco/aaa/cisco_cli_moving_data.yml) | `- 'configure replace'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [AcroRd32.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/LOLUtilz/OtherBinaries/AcroRd32.yml) | `- Command: Replace C:\Program Files (x86)\Adobe\Acrobat Reader DC\Reader\AcroCEF\RdrCEF.exe by your binary` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [ROCCAT_Swarm.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/LOLUtilz/OtherBinaries/ROCCAT_Swarm.yml) | `- Command: Replace ROCCAT_Swarm_Monitor.exe with your binary.exe` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Replace.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Replace.yml) | `Name: Replace.exe` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Replace.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Replace.yml) | `Description: Used to replace file with another file ` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Replace.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Replace.yml) | `- Command: replace.exe C:\Source\File.cab C:\Destination /A` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Replace.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Replace.yml) | `- Command: replace.exe \\webdav.host.com\foo\bar.exe c:\outdir /A` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Replace.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Replace.yml) | `- Path: C:\Windows\System32\replace.exe` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Replace.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Replace.yml) | `- Path: C:\Windows\SysWOW64\replace.exe` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Replace.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Replace.yml) | `- IOC: Replace.exe getting files from remote server` | 
[malware-ioc](https://github.com/eset/malware-ioc) | [misp_invisimole.json](https://github.com/eset/malware-ioc/blob/master/invisimole/misp_invisimole.json) | `"description": "Shortcuts or symbolic links are ways of referencing other files or programs that will be opened or executed when the shortcut is clicked or executed by a system startup process. Adversaries could use shortcuts to execute their tools for persistence. They may create a new shortcut as a means of indirection that may use [Masquerading](https://attack.mitre.org/techniques/T1036) to look like a legitimate program. Adversaries could also edit the target path or entirely replace an existing shortcut so their tools will be executed instead of the intended legitimate program.",` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [nouns.txt](https://github.com/eset/malware-ioc/blob/master/kryptocibule/nouns.txt) | `replace` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [stantinko](https://github.com/eset/malware-ioc/blob/master/stantinko/README.adoc) | `var c = a[b].toLocaleLowerCase().replace(/(\n)/g, " ").replace(/(\r)/g, "");` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [stantinko](https://github.com/eset/malware-ioc/blob/master/stantinko/README.adoc) | `a = a.toLowerCase().replace(/(\n)/g, " ").replace(/(\r)/g, "");` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [misp-turla-outlook-event.json](https://github.com/eset/malware-ioc/blob/master/turla/misp-turla-outlook-event.json) | `"description": "The Microsoft Component Object Model (COM) is a system within Windows to enable interaction between software components through the operating system.[[Citation: Microsoft Component Object Model]] Adversaries can use this system to insert malicious code that can be executed in place of legitimate software through hijacking the COM references and relationships as a means for persistence. Hijacking a COM object requires a change in the Windows Registry to replace a reference to a legitimate system component which may cause that component to not work when executed. When that system component is executed through normal system operation the adversary's code will be executed instead.[[Citation: GDATA COM Hijacking]] An adversary is likely to hijack objects that are used frequently enough to maintain a consistent level of persistence, but are unlikely to break noticeable functionality within the system as to avoid system instability that could lead to detection.\n\nDetection: There are opportunities to detect COM hijacking by searching for Registry references that have been replaced and through Registry operations replacing know binary paths with unknown paths. Even though some third party applications define user COM objects, the presence of objects within <code>HKEY_CURRENT_USER\\Software\\Classes\\CLSID\\<\/code> may be anomalous and should be investigated since user objects will be loaded prior to machine objects in <code>HKEY_LOCAL_MACHINE\\SOFTWARE\\Classes\\CLSID\\<\/code>.[[Citation: Endgame COM Hijacking]] Registry entries for existing COM objects may change infrequently. When an entry with a known good path and binary is replaced or changed to an unusual value to point to an unknown binary in a new location, then it may indicate suspicious behavior and should be investigated. Likewise, if software DLL loads are collected and analyzed, any unusual DLL load that can be correlated with a COM object Registry modification may indicate COM hijacking has been performed.\n\nPlatforms: Windows Server 2003, Windows Server 2008, Windows Server 2012, Windows XP, Windows 7, Windows 8, Windows Server 2003 R2, Windows Server 2008 R2, Windows Server 2012 R2, Windows Vista, Windows 8.1, Windows 10\n\nData Sources: Windows Registry, DLL monitoring, Loaded DLLs\n\nContributors: ENDGAME",` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [windigo](https://github.com/eset/malware-ioc/blob/master/windigo/README.adoc) | `replace:` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [problem_report.md](https://github.com/redcanaryco/atomic-red-team/blob/master/.github/ISSUE_TEMPLATE/problem_report.md) | ℹ Please replace this with what you did. | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [problem_report.md](https://github.com/redcanaryco/atomic-red-team/blob/master/.github/ISSUE_TEMPLATE/problem_report.md) | ℹ Please replace this with what you expected to happen. | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [problem_report.md](https://github.com/redcanaryco/atomic-red-team/blob/master/.github/ISSUE_TEMPLATE/problem_report.md) | ℹ Please replace this with of what happened instead. | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [index.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Indexes-Markdown/index.md) | - Atomic Test #1: Cron - Replace crontab with referenced file [macos, linux] | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [linux-index.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Indexes-Markdown/linux-index.md) | - Atomic Test #1: Cron - Replace crontab with referenced file [macos, linux] | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [macos-index.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Indexes-Markdown/macos-index.md) | - Atomic Test #1: Cron - Replace crontab with referenced file [macos, linux] | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1003.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1003/T1003.md) | $cleanupUpdatedValue = $cleanupUpdatedValue -replace ',NPPSpy','' | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1053.003.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1053.003/T1053.003.md) | - [Atomic Test #1 - Cron - Replace crontab with referenced file](#atomic-test-1---cron---replace-crontab-with-referenced-file) | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1053.003.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1053.003/T1053.003.md) | ## Atomic Test #1 - Cron - Replace crontab with referenced file | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1070.006.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1070.006/T1070.006.md) | \| target_date_time \| Date/time to replace original timestamps with \| String \| 01/01/1970 00:00:00\| | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1098.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1098/T1098.md) | $account = $member.Name -replace ".+\\\","" # strip computername\ | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1547.009.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1547.009/T1547.009.md) | Adversaries could use shortcuts to execute their tools for persistence. They may create a new shortcut as a means of indirection that may use [Masquerading](https://attack.mitre.org/techniques/T1036) to look like a legitimate program. Adversaries could also edit the target path or entirely replace an existing shortcut so their tools will be executed instead of the intended legitimate program.</blockquote> | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1574.001.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1574.001/T1574.001.md) | Programs that fall victim to path hijacking may appear to behave normally because malicious DLLs may be configured to also load the legitimate DLLs they were meant to replace.</blockquote> | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_apt29_grizzly_steppe.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_apt29_grizzly_steppe.yar) | $s2 = "Repeat last find command)Replace specific text with different text" fullword wide | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_oilrig.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_oilrig.yar) | $x1 = "Get-Content $env:Public\\Libraries\\update.vbs) -replace" ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_oilrig.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_oilrig.yar) | $x3 = "CreateObject(\"WScript.Shell\").Run Replace(DownloadExecute,\"-_\",\"bat\")" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_oilrig.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_oilrig.yar) | $s4 = "') -replace '__',('DNS'+$id) \| " fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_oilrig.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_oilrig.yar) | $s7 = "') -replace '__',('HTP'+$id) \| " fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_oilrig.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_oilrig.yar) | $x1 = "wss.Run \"powershell.exe \" & Chr(34) & \"& {(Get-Content $env:Public\\Libraries\\update.vbs) -replace '__',(Get-Random) \| Set-C" ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_oilrig.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_oilrig.yar) | $x1 = "(Get-Content $env:Public\\Libraries\\dns.ps1) -replace ('#'+'##'),$botid \| Set-Content $env:Public\\Libraries\\dns.ps1" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_oilrig.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_oilrig.yar) | $one5 = "cu = Replace(cu, \"$\", \"\")" ascii wide | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_winnti_hdroot.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_winnti_hdroot.yar) | $s8 = "tera replace dll config" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [cn_pentestset_webshells.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/cn_pentestset_webshells.yar) | $s2 = "strReturn=Replace(strReturn,chr(43),\"%2B\")  'JMDCW" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [crime_goldeneye.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/crime_goldeneye.yar) | $x1 = "fso.GetTempName();tmp_path = tmp_path.replace('.tmp', '.exe')" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [gen_cert_payloads.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/gen_cert_payloads.yar) | $fp1 = "replace it with the PEM-encoded root certificate" | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [gen_invoke_thehash.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/gen_invoke_thehash.yar) | $s1 = "$process_ID = $process_ID -replace \"-00-00\",\"\"" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [gen_mimikatz.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/gen_mimikatz.yar) | $x9 = "\\_ *Password replace ->" fullword wide ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [gen_powershell_empire.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/gen_powershell_empire.yar) | $s3 = "$PersistantScript = $PersistantScript.ToString().Replace('EXECUTEFUNCTION', \"$PersistenceScriptName -Persist\")" fullword ascii  | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [thor-webshells.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/thor-webshells.yar) | $s3 = "MorfiCoder=Replace(Replace(StrReverse(Code),\"/*/\",\"\"\"\"),\"\\*\\\",vbCrlf)" fullword | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [thor-webshells.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/thor-webshells.yar) | $s4 = "echo \"&nbsp;<a href=\"\"/\"&encodeForUrl(theHref,false)&\"\"\" target=_blank>\"&replace" | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [thor-webshells.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/thor-webshells.yar) | $s8 = "theHref=mid(replace(lcase(list.path),lcase(server.mapPath(\"/\")),\"\"),2)" | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [thor-webshells.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/thor-webshells.yar) | $s3 = "echo \"&nbsp;<a href=\"\"/\"&encodeForUrl(theHref,false)&\"\"\" target=_blank>\"&replace" | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [thor-webshells.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/thor-webshells.yar) | $s9 = "theHref=mid(replace(lcase(list.path),lcase(server.mapPath(\"/\")),\"\"),2)" | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [thor-webshells.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/thor-webshells.yar) | $s3 = "If ProxyData <> \"\" Then ProxyData = Replace(ProxyData, DATA_SEPERATOR, \"<br />\")" | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [thor-webshells.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/thor-webshells.yar) | $s7 = "theHref=encodeForUrl(mid(replace(lcase(list.path),lcase(server.mapPath(\"/\")),\"\")" | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [thor-webshells.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/thor-webshells.yar) | $s8 = "Obviously you replace the ip address with that of the target." | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)

## Additional Info*

**The information below is copied from [MicrosoftDocs](https://github.com/MicrosoftDocs/windowsserverdocs), which is maintained by [Microsoft](https://opensource.microsoft.com/codeofconduct/). Available under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) license.*

---

## replace

Replace existing files in a directory. If used with the **/a** option, this command adds new files to a directory instead of replacing existing files.

### Syntax

```
replace [<drive1>:][<path1>]<filename> [<drive2>:][<path2>] [/a] [/p] [/r] [/w]
replace [<drive1>:][<path1>]<filename> [<drive2>:][<path2>] [/p] [/r] [/s] [/w] [/u]
```

#### Parameters

| Parameter | Description |
|--|--|
| `[<drive1>:][<path1>]<filename>` | Specifies the location and name of the source file or set of files. The *filename* option is required, and can include wildcard characters (**&#42;** and **?**). |
| `[<drive2>:][<path2>]` | Specifies the location of the destination file. You can't specify a file name for files you replace. If you don't specify a drive or path, this command uses the current drive and directory as the destination. |
| /a | Adds new files to the destination directory instead of replacing existing files. You can't use this command-line option with the **/s** or **/u** command-line option. |
| /p | Prompts you for confirmation before replacing a destination file or adding a source file. |
| /r | Replaces Read-only and unprotected files. If you attempt to replace a Read-only file, but you don't specify **/r**, an error results and stops the replacement operation. |
| /w | Waits for you to insert a disk before the search for source files begins. If you don't specify **/w**, this command begins replacing or adding files immediately after you press ENTER. |
| /s | Searches all subdirectories in the destination directory and replaces matching files. You can't use **/s** with the **/a** command-line option. The command doesn't search subdirectories that are specified in *Path1*. |
| /u | Replaces only those files on the destination directory that are older than those in the source directory. You can't use **/u** with the **/a** command-line option. |
| /? | Displays help at the command prompt. |

##### Remarks

- As this command adds or replaces files, the file names appear on the screen. After this command is done, a summary line is displayed in one of the following formats:

  ```
  nnn files added
  nnn files replaced
  no file added
  no file replaced
  ```

- If you're using floppy disks and you need to switch disks while running this command, you can specify the **/w** command-line option so that this command waits for you to switch the disks.

- You can't use this command to update hidden files or system files.

- The following table shows each exit code and a brief description of its meaning:

  | Exit code | Description |
  |--|--|
  | 0 | This command successfully replaced or added the files. |
  | 1 | This command encountered an incorrect version of MS-DOS. |
  | 2 | This command couldn't find the source files. |
  | 3 | This command couldn't find the source or destination path. |
  | 5 | The user doesn't have access to the files that you want to replace. |
  | 8 | There is insufficient system memory to carry out the command. |
  | 11 | The user used the wrong syntax on the command line. |

> [!NOTE]
> You can use the ERRORLEVEL parameter on the **if** command line in a batch program to process exit codes that are returned by this command.

### Examples

To update all the versions of a file named *Phones.cli* (which appear in multiple directories on drive C:), with the latest version of the *Phones.cli* file from a floppy disk in drive A:, type:

```
replace a:\phones.cli c:\ /s
```

### Additional References

- [Command-Line Syntax Key](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/command-line-syntax-key.md)

---



MIT License. Copyright (c) 2020 Strontic.


