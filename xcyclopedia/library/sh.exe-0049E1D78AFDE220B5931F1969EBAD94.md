---
title: sh.exe | 
excerpt: What is sh.exe?
---

# sh.exe 

* File Path: `C:\Users\user\AppData\Local\GitHubDesktop\app-2.5.4\resources\app\git\usr\bin\sh.exe`

## Hashes

Type | Hash
-- | --
MD5 | `0049E1D78AFDE220B5931F1969EBAD94`
SHA1 | `0693E4981A1E38F2B2676393E1F168A31395621C`
SHA256 | `74FA78E454D95616117B835F0BD622D33531CBC7D300C01CA778EFFDF2C1BCF6`
SHA384 | `3689CAFF1CD95515C1C0DBEE6D9EF5D09E580CA41D0F6DAAABD1DA3CB0F7B2BD2B1592784CCBBF9B412FADF6057F3395`
SHA512 | `224DFC77B0F73C357EDC72AC011C46DA7D431AB9B9A7B3528A0AB995D287611009E1911902C89B713A2D3F616906CCC705E712E5A698E4A6E2C0474FE009C4F0`
SSDEEP | `49152:EIOxRHOL8T/SI4IeSCoRABAUZLYCEZGaXBuQQ9e:Qxo8TRVABAUZLw`

## Runtime Data

### Usage (stdout):
```cmhg
GNU bash, version 4.4.23(1)-release-(x86_64-pc-msys)
Usage:	/usr/bin/sh [GNU long option] [option] ...
	/usr/bin/sh [GNU long option] [option] script-file ...
GNU long options:
	--debug
	--debugger
	--dump-po-strings
	--dump-strings
	--help
	--init-file
	--login
	--noediting
	--noprofile
	--norc
	--posix
	--protected
	--rcfile
	--restricted
	--verbose
	--version
	--wordexp
Shell options:
	-ilrsD or -c command or -O shopt_option		(invocation only)
	-abefhkmnptuvxBCHP or -o option
Type `/usr/bin/sh -c "help set"' for more information about shell options.
Type `/usr/bin/sh -c help' for more information about shell builtin commands.
Use the `bashbug' command to report bugs.

bash home page: <http://www.gnu.org/software/bash>
General help using GNU software: <http://www.gnu.org/gethelp/>

```

### Usage (stderr):
```cmhg
/c/Windows/system32/help: /c/Windows/system32/help: cannot execute binary file

```

### Loaded Modules:

Path |
-- |
C:\Users\user\AppData\Local\GitHubDesktop\app-2.5.4\resources\app\git\usr\bin\sh.exe |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\SYSTEM32\ntdll.dll |


## Signature

* Status: Signature verified.
* Serial: `045D8F14A82147641722D4FAFC66BC80`
* Thumbprint: `FB713A60A7FA79DFC03CB301CA05D4E8C1BDD431`
* Issuer: CN=DigiCert SHA2 Assured ID Code Signing CA, OU=www.digicert.com, O=DigiCert Inc, C=US
* Subject: CN="GitHub, Inc.", O="GitHub, Inc.", L=San Francisco, S=California, C=US

## File Metadata

* Original Filename: 
* Product Name: 
* Company Name: 
* File Version: 
* Product Version: 
* Language: 
* Legal Copyright: 


## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Users\user\AppData\Local\GitHubDesktop\app-2.5.3\resources\app\git\usr\bin\sh.exe](sh.exe-CD721CF3000FE9CFD4E072AF57C8FD4B.md) | 97

## Possible Misuse

*The following table contains possible examples of `sh.exe` being misused. While `sh.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_shell_spawn_from_winrm.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_access/win_susp_shell_spawn_from_winrm.yml) | `- '*\sh.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_mmc_spawn_shell.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_mmc_spawn_shell.yml) | `- '\sh.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_mshta_spawn_shell.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_mshta_spawn_shell.yml) | `- '\sh.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_office_shell.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_office_shell.yml) | `- '\sh.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_servu_process_pattern.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_servu_process_pattern.yml) | `- '\sh.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_shell_spawn_from_mssql.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_shell_spawn_from_mssql.yml) | `- '\sh.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_webshell_spawn.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_webshell_spawn.yml) | `- '\sh.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020-2021 Strontic.


