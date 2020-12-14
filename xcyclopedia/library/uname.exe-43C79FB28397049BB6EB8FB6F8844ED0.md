---
title: uname.exe | 
excerpt: What is uname.exe?
---

# uname.exe 

* File Path: `C:\Users\user\AppData\Local\GitHubDesktop\app-2.5.3\resources\app\git\usr\bin\uname.exe`

## Hashes

Type | Hash
-- | --
MD5 | `43C79FB28397049BB6EB8FB6F8844ED0`
SHA1 | `B9FBE26896F7B59679769CE9E0C68228A6B302AF`
SHA256 | `AF5458D535148DF6C34A5120C43F1612B27DAB1000F5F24EE6246A2313780C71`
SHA384 | `96836D224F8FDBE26EAA544B24183CEF5842BBFF595368A51BC4BFC115E0C4B7A17F6D82EF246D19158D558858FBDC26`
SHA512 | `40154BC0BB72F45A19AD1EF8F3BAB4E8635108DE6512870C815C0F5E242AAE4D065B853135AAD96651A9EFA6CEEC394384C5416C7B3B5836DB8AA9BD1AA6856F`
SSDEEP | `768:ujG+Os/RSnQ4fDuEXViqboMDWccccccccccccccccccccccccccccccqZWwM3FXr:uK+OsInQ4bZNW9FXxUf`

## Runtime Data

### Usage (stdout):
```cmhg
Usage: /usr/bin/uname [OPTION]...
Print certain system information.  With no OPTION, same as -s.

  -a, --all                print all information, in the following order,
                             except omit -p and -i if unknown:
  -s, --kernel-name        print the kernel name
  -n, --nodename           print the network node hostname
  -r, --kernel-release     print the kernel release
  -v, --kernel-version     print the kernel version
  -m, --machine            print the machine hardware name
  -p, --processor          print the processor type (non-portable)
  -i, --hardware-platform  print the hardware platform (non-portable)
  -o, --operating-system   print the operating system
      --help     display this help and exit
      --version  output version information and exit

GNU coreutils online help: <https://www.gnu.org/software/coreutils/>
Report any translation bugs to <https://translationproject.org/team/>
Full documentation <https://www.gnu.org/software/coreutils/uname>
or available locally via: info '(coreutils) uname invocation'

```

### Usage (stderr):
```cmhg
/usr/bin/uname: extra operand 'help'
Try '/usr/bin/uname --help' for more information.

```

### Child Processes:
vmmem

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

*The following table contains possible examples of `uname.exe` being misused. While `uname.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [lnx_shell_priv_esc_prep.yml](https://github.com/Neo23x0/sigma/blob/master/rules/linux/lnx_shell_priv_esc_prep.yml) | `- 'uname -a'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [lnx_shell_priv_esc_prep.yml](https://github.com/Neo23x0/sigma/blob/master/rules/linux/lnx_shell_priv_esc_prep.yml) | `- 'uname -mrs'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [lnx_shell_susp_rev_shells.yml](https://github.com/Neo23x0/sigma/blob/master/rules/linux/lnx_shell_susp_rev_shells.yml) | `- 'uname -a; w; id; /bin/bash -i'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1014.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1014/T1014.md) | sudo rm /lib/modules/$(uname -r)/#{rootkit_name}.ko | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1014.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1014/T1014.md) | if [ -f /lib/modules/$(uname -r)/#{rootkit_name}.ko ]; then exit 0; else exit 1; fi;  | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1014.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1014/T1014.md) | sudo cp #{temp_folder}/#{rootkit_name}.ko /lib/modules/$(uname -r)/ | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1082.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1082/T1082.md) | uname -a >> #{output_file} | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1204.002.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1204.002/T1204.002.md) | \| uname \| Username for pathing \| String \| $env:Username\| | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1204.002.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1204.002/T1204.002.md) | if ("#{uname}" -ne "") { | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1204.002.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1204.002/T1204.002.md) | $sheet.Cells.Item(1,1) = "#{uname}" | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_apt41.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_apt41.yar) | $s3 = "uname -v" ascii fullword | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_apt41.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_apt41.yar) | $s4 = "uname -s" ascii fullword | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_derusbi.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_derusbi.yar) | $cmd = "unset LS_OPTIONS;uname -a" | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_laudanum_webshells.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_laudanum_webshells.yar) | $s7 = "$shell = 'uname -a; w; id; /bin/sh -i';" fullword ascii /* PEStudio Blacklist: strings */ | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_turbo_campaign.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_turbo_campaign.yar) | $b4 = "uname -a\n\n" wide ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [thor-webshells.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/thor-webshells.yar) | $s3 = "if ((!$_POST['cmd']) \|\| ($_POST['cmd']==\"\")) { $_POST['cmd']=\"id;pwd;uname -a" | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [thor-webshells.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/thor-webshells.yar) | $s2 = "echo $uname.\"</font><br><b>\";" fullword | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [thor-webshells.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/thor-webshells.yar) | $s16 = "$uname = posix_uname( );" fullword | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [thor-webshells.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/thor-webshells.yar) | $s14 = "print \"<tr><td><b>System type:</b></td><td>$UName</td></tr>\";" fullword | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [thor-webshells.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/thor-webshells.yar) | $s4 = "if ((!$_POST['cmd']) \|\| ($_POST['cmd']==\"\")) { $_POST['cmd']=\"id;pwd;uname -a" | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)



MIT License. Copyright (c) 2020 Strontic.


