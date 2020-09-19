---
title: sh.exe | 
---

# sh.exe 

* File Path: `C:\Users\user\AppData\Local\GitHubDesktop\app-2.5.3\resources\app\git\usr\bin\sh.exe`

## Hashes

Type | Hash
-- | --
MD5 | `CD721CF3000FE9CFD4E072AF57C8FD4B`
SHA1 | `5D353A2F0BBDD87CCB9F9ABBCDA058238DDAFAD7`
SHA256 | `B49635BEBA631B45CB6CE0AB1350BEFAE7852C8D937F49ABEE25360A185D654C`
SHA384 | `B40DD813D7FCB1BB54C1B2A1B13A0B08ED79F2E6DBFD2DF287E92C24981527AD8822BE3B55535A4CEFDB511CA0505339`
SHA512 | `9AD7E1D09660C8E37678DE364DA3435A6A9E3BD57F516280237EBB597F399324F794F57CFF942E201C0280E8DA111F6D31FE83AFC6D6F715F17513284A05F73B`
SSDEEP | `49152:1IOxRHOL8T/SI4IeSCoRABAUZLYCEZGaXBuQQ9ee:pxo8TRVABAUZLwM`

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
[C:\Users\WDAGUtilityAccount\AppData\Local\GitHubDesktop\app-2.5.4\resources\app\git\usr\bin\sh.exe](sh.exe-0049E1D78AFDE220B5931F1969EBAD94.md) | 97

## Possible Misuse

*The following table contains possible examples of `sh.exe` being misused. While `sh.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_mmc_spawn_shell.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_mmc_spawn_shell.yml) | `            - '*\sh.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_mshta_spawn_shell.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_mshta_spawn_shell.yml) | `            - '*\sh.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_office_shell.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_office_shell.yml) | `            - '*\sh.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_webshell_spawn.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_webshell_spawn.yml) | `            - '*\sh.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020 Strontic.


