---
title: mkdir.exe | 
excerpt: What is mkdir.exe?
---

# mkdir.exe 

* File Path: `C:\Users\user\AppData\Local\GitHubDesktop\app-2.5.4\resources\app\git\usr\bin\mkdir.exe`

## Hashes

Type | Hash
-- | --
MD5 | `CC886C3E132602FFE4BB7C0C33E2B405`
SHA1 | `20A9CF930BBD90D769F0DC10A53D9F2DA9A4AE63`
SHA256 | `639966348B75621A57D8B971818F0D6F6535F29129D4EA3567211FCC413BE3D5`
SHA384 | `DD17A96CA710E0F5C2ABE0DD93C51ADE293CB8CCE3C773648164A786780C25C2A48B49C8F52707CE6EF3C8FC4EEBDFD7`
SHA512 | `784D88667037882AA2CF8E6DA4754A4D0A56E310A961587756F7B4A2C4D90E97A021726150277B182F3E2185B19A7474283F6A2342D2B8497733A70B99B0E138`
SSDEEP | `1536:ihlXduSrEwHD9utmaW6l8RR2zfzBW9F6bUfad:ihlcSrEw5iCRszg9F6Nd`

## Runtime Data

### Usage (stdout):
```cmhg
Usage: /usr/bin/mkdir [OPTION]... DIRECTORY...
Create the DIRECTORY(ies), if they do not already exist.

Mandatory arguments to long options are mandatory for short options too.
  -m, --mode=MODE   set file mode (as in chmod), not a=rwx - umask
  -p, --parents     no error if existing, make parent directories as needed
  -v, --verbose     print a message for each created directory
  -Z                   set SELinux security context of each created directory
                         to the default type
      --context[=CTX]  like -Z, or if CTX is specified then set the SELinux
                         or SMACK security context to CTX
      --help     display this help and exit
      --version  output version information and exit

GNU coreutils online help: <https://www.gnu.org/software/coreutils/>
Report any translation bugs to <https://translationproject.org/team/>
Full documentation <https://www.gnu.org/software/coreutils/mkdir>
or available locally via: info '(coreutils) mkdir invocation'

```

### Usage (stderr):
```cmhg
mkdir: unknown option -- h
Try '/usr/bin/mkdir --help' for more information.

```

### Loaded Modules:

Path |
-- |
C:\Users\user\AppData\Local\GitHubDesktop\app-2.5.4\resources\app\git\usr\bin\mkdir.exe |
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



## Possible Misuse

*The following table contains possible examples of `mkdir.exe` being misused. While `mkdir.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[malware-ioc](https://github.com/eset/malware-ioc) | [windigo_signatures.pl](https://github.com/eset/malware-ioc/blob/master/sshdoor/windigo_signatures.pl) | `@sc = gc( 'mkdir -p %s', '-A 2' );` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [windigo_signatures.pl](https://github.com/eset/malware-ioc/blob/master/sshdoor/windigo_signatures.pl) | `@sc = gc( 'mkdir -p %s', '-B 1' );` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [windigo_signatures.pl](https://github.com/eset/malware-ioc/blob/master/sshdoor/windigo_signatures.pl) | `@sc = gc( 'mkdir -p %s', '-A 1' );` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [windigo_signatures.pl](https://github.com/eset/malware-ioc/blob/master/sshdoor/windigo_signatures.pl) | `@sd = gs( 'mkdir -p %s', '-C 1' );` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [windigo_signatures.pl](https://github.com/eset/malware-ioc/blob/master/sshdoor/windigo_signatures.pl) | `@sc = gs( 'mkdir -p %s',  '-A 2' );` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [windigo_signatures.pl](https://github.com/eset/malware-ioc/blob/master/sshdoor/windigo_signatures.pl) | `qw{ mkdir var aeiouy bcdfghklmnprstvzx bcdfghklmnprstvz 000 aeiouybcdfg hklmnprstv aeiouybcdfghklmnprstvzx klmnprstvzx bcdfg rstvzx bcdfghklmn \000 };` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1003.003.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1003.003/T1003.003.md) | mkdir #{extract_path} | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1003.003.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1003.003/T1003.003.md) | mkdir #{output_folder} | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1014.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1014/T1014.md) | if [ ! -d #{temp_folder} ]; then mkdir #{temp_folder}; touch #{temp_folder}/safe_to_delete; fi; | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1030.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1030/T1030.md) | if [ ! -d #{folder_path} ]; then mkdir -p #{folder_path}; touch #{folder_path}/safe_to_delete; fi;       | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1048.003.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1048.003/T1048.003.md) | mkdir /tmp/victim-staging-area | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1070.004.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1070.004/T1070.004.md) | mkdir #{folder_to_delete} | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1119.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1119/T1119.md) | mkdir %temp%\T1119_command_prompt_collection >nul 2>&1 | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1222.001.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1222.001/T1222.001.md) | mkdir #{file_folder_to_own} | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1222.001.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1222.001/T1222.001.md) | mkdir #{file_or_folder} | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1543.001.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1543.001/T1543.001.md) | if [ ! -d ~/Library/LaunchAgents ]; then mkdir ~/Library/LaunchAgents; fi; | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1547.006.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1547.006/T1547.006.md) | if [ ! -d #{temp_folder} ]; then mkdir #{temp_folder}; touch #{temp_folder}/safe_to_delete; fi; | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1548.002.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1548.002/T1548.002.md) | mkdir "\\?\C:\Windows \System32\" | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1552.004.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1552.004/T1552.004.md) | mkdir #{output_folder} | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1560.001.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1560.001/T1560.001.md) | mkdir .\tmp\victim-files | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1560.001.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1560.001/T1560.001.md) | mkdir $PathToAtomicsFolder\T1560.001\victim-files | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1560.001.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1560.001/T1560.001.md) | mkdir -p #{test_folder} | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1564.001.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1564.001/T1564.001.md) | mkdir /var/tmp/.hidden-directory | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_fancybear_osxagent.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_fancybear_osxagent.yar) | $s2 = "mkdir -p /Users/Shared/.local/ &> /dev/null" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_fvey_shadowbroker_dec16.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_fvey_shadowbroker_dec16.yar) | $s4 = "mkdir TEMP_DIR; cd TEMP_DIR; cat < /dev/tcp/REDIR_IP/RED" ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_fvey_shadowbroker_dec16.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_fvey_shadowbroker_dec16.yar) | $s1 = "/sbin/sh -c (mkdir /tmp/.X11R6; cd /tmp/.X11R6 && telnet" ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_shamoon2.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_shamoon2.yar) | $s1 = "mkdir %s%s > nul 2>&1" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [thor-webshells.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/thor-webshells.yar) | $s0 = "{mkdir(\"$dizin/$duzenx2\",777)" | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [thor-webshells.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/thor-webshells.yar) | $s11 = "<form action=<?=$script?>?act=mkdir method=POST>" fullword | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [thor-webshells.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/thor-webshells.yar) | $s9 = "if (mkdir($_POST['dir'], 0777) == false) {" fullword | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)

## Additional Info*

**The information below is copied from [MicrosoftDocs](https://github.com/MicrosoftDocs/windowsserverdocs), which is maintained by [Microsoft](https://opensource.microsoft.com/codeofconduct/). Available under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) license.*

---

## mkdir

Creates a directory or subdirectory. Command extensions, which are enabled by default, allow you to use a single **mkdir** command to create intermediate directories in a specified path.

> [!NOTE]
> This command is the same as the [md command](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/md.md).

### Syntax

```
mkdir [<drive>:]<path>
```

#### Parameters

| Parameter | Description |
| --------- | ----------- |
| `<drive>`: | Specifies the drive on which you want to create the new directory. |
| `<path>` | Specifies the name and location of the new directory. The maximum length of any single path is determined by the file system. This is a required parameter. |
| /? | Displays help at the command prompt. |

#### Examples

To create a directory named *Directory1* within the current directory, type:

```
mkdir Directory1
```

To create the directory tree *Taxes\Property\Current* within the root directory, with command extensions enabled, type:

```
mkdir \Taxes\Property\Current
```

To create the directory tree *Taxes\Property\Current* within the root directory as in the previous example, but with command extensions disabled, type the following sequence of commands:

```
mkdir \Taxes
mkdir \Taxes\Property
mkdir \Taxes\Property\Current
```

### Additional References

- [Command-Line Syntax Key](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/command-line-syntax-key.md)

- [md command](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/md.md)

---



MIT License. Copyright (c) 2020 Strontic.


