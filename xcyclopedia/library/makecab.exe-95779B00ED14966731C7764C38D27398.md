---
title: makecab.exe | Microsoft Cabinet Maker
excerpt: What is makecab.exe?
---

# makecab.exe 

* File Path: `C:\windows\SysWOW64\makecab.exe`
* Description: Microsoft Cabinet Maker

## Hashes

Type | Hash
-- | --
MD5 | `95779B00ED14966731C7764C38D27398`
SHA1 | `EA7496E752FCC3EADB4AE955B934F127001C08EA`
SHA256 | `2A0040B54311FB62153131D4B201150AB058B7F85F7F5A7F8751A6DB2B08669E`
SHA384 | `68EE2E47F28A130DDAD1B028A47CC32A8D7F4EEADDBB37689F246D4D158ED95B888DE84697F841FE52957EF903836656`
SHA512 | `99B500CC190FC585AEBD13E39E48F0B6EC01752903551CAAB02D4F4273B5125A3E0C77F62E9133D6C78A6A12B4CF86E26D4D885257F263213B67B6FC9CED6F57`
SSDEEP | `1536:eHETgiIgOJAxuz8+ZGFXpuHh5Nfxepbwq:QETLKv8+QFXpuZfxCb`

## Signature

* Status: The file C:\windows\SysWOW64\makecab.exe is not digitally signed. You cannot run this script on the current system. For more information about running scripts and setting execution policy, see about_Execution_Policies at http://go.microsoft.com/fwlink/?LinkID=135170
* Serial: ``
* Thumbprint: ``
* Issuer: 
* Subject: 

## File Metadata

* Original Filename: makecab.exe
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 6.3.9600.17415 (winblue_r4.141028-1500)
* Product Version: 6.3.9600.17415
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.



## Possible Misuse

*The following table contains possible examples of `makecab.exe` being misused. While `makecab.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_suspicious_remote_thread.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/sysmon/sysmon_suspicious_remote_thread.yml) | `- '\makecab.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Makecab.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Makecab.yml) | `Name: Makecab.exe`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Makecab.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Makecab.yml) | `- Command: makecab c:\ADS\autoruns.exe c:\ADS\cabtest.txt:autoruns.cab`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Makecab.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Makecab.yml) | `- Command: makecab \\webdavserver\webdav\file.exe C:\Folder\file.txt:file.cab`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Makecab.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Makecab.yml) | `- Command: makecab \\webdavserver\webdav\file.exe C:\Folder\file.cab`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Makecab.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Makecab.yml) | `- Path: C:\Windows\System32\makecab.exe`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Makecab.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Makecab.yml) | `- Path: C:\Windows\SysWOW64\makecab.exe`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Makecab.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Makecab.yml) | `- IOC: Makecab getting files from Internet`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Makecab.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Makecab.yml) | `- IOC: Makecab storing data into alternate data streams`{:.highlight .language-yaml} | 
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1564.004.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1564.004/T1564.004.md) | makecab #{path}\autoruns.exe #{path}\cabtest.txt:autoruns.cab | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)

## Additional Info*

**The information below is copied from [MicrosoftDocs](https://github.com/MicrosoftDocs/windowsserverdocs), which is maintained by [Microsoft](https://opensource.microsoft.com/codeofconduct/). Available under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) license.*

---

## makecab

> Applies to: Windows Server (Semi-Annual Channel), Windows Server 2019, Windows Server 2016, Windows Server 2012 R2, Windows Server 2012

Package existing files into a cabinet (.cab) file.


> [!NOTE]
> This command is the same as the [diantz command](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/diantz.md).

### Syntax

```
makecab [/v[n]] [/d var=<value> ...] [/l <dir>] <source> [<destination>]
makecab [/v[<n>]] [/d var=<value> ...] /f <directives_file> [...]
```

#### Parameters

| Parameter | Description |
| --------- | ----------- |
| `<source>` | File to compress. |
| `<destination>` | File name to give compressed file. If omitted, the last character of the source file name is replaced with an underscore (_) and used as the destination. |
| /f `<directives_file>` | A file with **makecab** directives (may be repeated). |
| /d var=`<value>` | Defines variable with specified value. |
| /l `<dir>` | Location to place destination (default is current directory). |
| /v[`<n>`] | Set debugging verbosity level (0=none,...,3=full). |
| /? | Displays help at the command prompt. |

### Additional References

- [Command-Line Syntax Key](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/command-line-syntax-key.md)

- [diantz command](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/diantz.md)

- [Microsoft Cabinet format](/previous-versions/bb417343(v=msdn.10))

---



MIT License. Copyright (c) 2020-2021 Strontic.


