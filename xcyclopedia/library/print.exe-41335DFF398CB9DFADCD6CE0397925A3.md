﻿---
title: print.exe | GNU Image Manipulation Program Plug-In
excerpt: What is print.exe?
---

# print.exe 

* File Path: `C:\program files\GIMP 2\lib\gimp\2.0\plug-ins\print\print.exe`
* Description: GNU Image Manipulation Program Plug-In

## Hashes

Type | Hash
-- | --
MD5 | `41335DFF398CB9DFADCD6CE0397925A3`
SHA1 | `4FBCC632A5EFDA7631A93A4392C9F60899D950A5`
SHA256 | `652D9F7456FE61BFCE664DE8B372BE2A6EAC217C707326FFE432301DB014682E`
SHA384 | `1EC919C4D0A49FA098ECEC539C2B4CE3352C2864F8DF2E5474F57FAF5C2DC075B4C1C374ACBE3014B6C50E7FE9DED59A`
SHA512 | `09A8DEE1A7465660192FDA02907D74EFCA6C053B647F435A1760E3F96883671D24FAE76CBE46CC01928FB23208EB7CCFBFE75B634F504A53064D0DEF23AA127D`
SSDEEP | `1536:FhhJe7V5fJKJPD5E5YweGgZiwxRm/aipiPW2ai6yWXiT:27f4P1UEGgZxjm/fm1Uyg6`

## Runtime Data

### Open Handles:

Path | Type
-- | --
(RW-)   C:\Users\user\Documents | File
\BaseNamedObjects\NLS_CodePage_1252_3_2_0_0 | Section
\BaseNamedObjects\NLS_CodePage_437_3_2_0_0 | Section


### Loaded Modules:

Path |
-- |
C:\program files\GIMP 2\lib\gimp\2.0\plug-ins\print\print.exe |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\System32\msvcrt.dll |
C:\Windows\SYSTEM32\ntdll.dll |


## Signature

* Status: Signature verified.
* Serial: `00E7E6FE263192D15EAC485B4198E64488`
* Thumbprint: `3A427356A24983C1C8211C07CF766D4726A33E4F`
* Issuer: CN=COMODO RSA Code Signing CA, O=COMODO CA Limited, L=Salford, S=Greater Manchester, C=GB
* Subject: CN=Jernej Simoni, O=Jernej Simoni, STREET=Herbersteinova 29, L=Ljubljana, S=-, PostalCode=1000, C=SI

## File Metadata

* Original Filename: print.exe
* Product Name: GNU Image Manipulation Program
* Company Name: Spencer Kimball, Peter Mattis and the GIMP Development Team
* File Version: 2.10.20.0
* Product Version: 2.10.20
* Language: English (United States)
* Legal Copyright: Copyright  1995-2020


## File Similarity (ssdeep match)

File | Score
-- | --
[C:\program files\GIMP 2\lib\gimp\2.0\plug-ins\file-ico\file-ico.exe](file-ico.exe-9BA606F588D200015B05318E88E44B9E.md) | 41
[C:\program files\GIMP 2\lib\gimp\2.0\plug-ins\file-sunras\file-sunras.exe](file-sunras.exe-78A6C6D98674E6F26D10F0632295D323.md) | 44
[C:\program files\GIMP 2\lib\gimp\2.0\plug-ins\gradient-map\gradient-map.exe](gradient-map.exe-C7F26A2FD518038620D73B699F69948B.md) | 44
[C:\program files\GIMP 2\lib\gimp\2.0\plug-ins\grid\grid.exe](grid.exe-48DF0DE72E8C95E8815DC53686DD579D.md) | 47

## Possible Misuse

*The following table contains possible examples of `print.exe` being misused. While `print.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [lnx_shell_susp_rev_shells.yml](https://github.com/Neo23x0/sigma/blob/master/rules/linux/lnx_shell_susp_rev_shells.yml) | `- ';while(cmd=c.gets);IO.popen(cmd,"r"){\|io\|c.print'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Print.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Print.yml) | `Name: Print.exe` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Print.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Print.yml) | `- Command: print /D:C:\ADS\File.txt:file.exe C:\ADS\File.exe` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Print.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Print.yml) | `- Command: print /D:C:\ADS\CopyOfFile.exe C:\ADS\FileToCopy.exe` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Print.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Print.yml) | `- Command: print /D:C:\OutFolder\outfile.exe \\WebDavServer\Folder\File.exe` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Print.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Print.yml) | `- Path: C:\Windows\System32\print.exe` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Print.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Print.yml) | `- Path: C:\Windows\SysWOW64\print.exe` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Print.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Print.yml) | `- IOC: Print.exe getting files from internet` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Print.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Print.yml) | `- IOC: Print.exe creating executable files on disk` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Mshtml.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSLibraries/Mshtml.yml) | `Description: Invoke an HTML Application via mshta.exe (Note - Pops a security warning and a print dialogue box).` | 
[malware-ioc](https://github.com/eset/malware-ioc) | [deprimon](https://github.com/eset/malware-ioc/blob/master/deprimon/README.adoc) | `https://www.welivesecurity.com/2019/11/21/deprimon-default-print-monitor-malicious-downloader/[WeLiveSecurity].` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [deprimon](https://github.com/eset/malware-ioc/blob/master/deprimon/README.adoc) | `[HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Control\Print\Monitors\Windows Default Print Monitor]` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [nouns.txt](https://github.com/eset/malware-ioc/blob/master/kryptocibule/nouns.txt) | `print` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [mumblehard](https://github.com/eset/malware-ioc/blob/master/mumblehard/README.adoc) | `under the Perl interpreter. The following command ran as root will print the` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [mumblehard](https://github.com/eset/malware-ioc/blob/master/mumblehard/README.adoc) | `ps -ef \| grep -e ' httpd$' -e ' mail$' -e ' init$' \| awk '{print $2}' \| xargs -I '{}' ls -l '/proc/{}/exe' \| grep perl \| cut -d/ -f 3` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [vf_ioc_linux_rakos.py](https://github.com/eset/malware-ioc/blob/master/rakos/vf_ioc_linux_rakos.py) | `print("Suspected PID: {0:8s} {1:<16}:{2:>5} {3:<16}:{4:>5} {5:<15s} {6:>17s}/{7:<5d}\n".format(proto, saddr, sport, daddr, dport, state, task.comm, task.pid))` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [windigo_signatures.pl](https://github.com/eset/malware-ioc/blob/master/sshdoor/windigo_signatures.pl) | `print "mod_str_ : ";` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [windigo_signatures.pl](https://github.com/eset/malware-ioc/blob/master/sshdoor/windigo_signatures.pl) | `print "$f : crypted, skip\n";` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [windigo_signatures.pl](https://github.com/eset/malware-ioc/blob/master/sshdoor/windigo_signatures.pl) | `print $fc. "\n";` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [windigo_signatures.pl](https://github.com/eset/malware-ioc/blob/master/sshdoor/windigo_signatures.pl) | `print "mod_ssh: \n";` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [windigo_signatures.pl](https://github.com/eset/malware-ioc/blob/master/sshdoor/windigo_signatures.pl) | `print` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [windigo_signatures.pl](https://github.com/eset/malware-ioc/blob/master/sshdoor/windigo_signatures.pl) | `print "mod_sshd1: '$sd[1]':'$sd[2]'\n";` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [windigo_signatures.pl](https://github.com/eset/malware-ioc/blob/master/sshdoor/windigo_signatures.pl) | `print "mod_sshc1: '$sc[1]':'$sc[2]'\n";` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [windigo_signatures.pl](https://github.com/eset/malware-ioc/blob/master/sshdoor/windigo_signatures.pl) | `print "mod_sshd1a: file:'$sd[4]'; hash:'$sd[15]'; cvs:'$sd[1]'\n";` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [windigo_signatures.pl](https://github.com/eset/malware-ioc/blob/master/sshdoor/windigo_signatures.pl) | `print "mod_sshd2: '$sd[1]':'$sd[2]':'$sd[3]'\n";` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [windigo_signatures.pl](https://github.com/eset/malware-ioc/blob/master/sshdoor/windigo_signatures.pl) | `print "mod_sshc4: '$sc[1]':'$sc[0]'\n" if @sc and f $sc[1];` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [windigo_signatures.pl](https://github.com/eset/malware-ioc/blob/master/sshdoor/windigo_signatures.pl) | `print "mod_sshd4: '$sd[0]':'$sd[1]':'$sd[2]'\n";` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [windigo_signatures.pl](https://github.com/eset/malware-ioc/blob/master/sshdoor/windigo_signatures.pl) | `print "mod_sshd5: " . join( '\|', @sd ) . "\n";` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [windigo_signatures.pl](https://github.com/eset/malware-ioc/blob/master/sshdoor/windigo_signatures.pl) | `print "mod_sshd6: '$sd[2]':'$sd[0]'\nmod_sshc6: '$sc[0]'\n";` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [windigo_signatures.pl](https://github.com/eset/malware-ioc/blob/master/sshdoor/windigo_signatures.pl) | `print "mod_sshd7: '$sd[0]':'$sd[4]'\nmod_sshc7: '$sc[0]'\n";` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [windigo_signatures.pl](https://github.com/eset/malware-ioc/blob/master/sshdoor/windigo_signatures.pl) | `print "mod_sshd8: '$sd[1]':'$sd[2]'\nmod_sshc8: '$sc[1]'\n";` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [windigo_signatures.pl](https://github.com/eset/malware-ioc/blob/master/sshdoor/windigo_signatures.pl) | `print` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [windigo_signatures.pl](https://github.com/eset/malware-ioc/blob/master/sshdoor/windigo_signatures.pl) | `if (@sd) { print "mod_sshd12: GET, no params"; ssh_ls() }` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [windigo_signatures.pl](https://github.com/eset/malware-ioc/blob/master/sshdoor/windigo_signatures.pl) | `print "mod_sshd14: hash:'$sd[3]':'$sd[4]':'$sd[2]'\n";` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [windigo_signatures.pl](https://github.com/eset/malware-ioc/blob/master/sshdoor/windigo_signatures.pl) | `print "mod_sshc14: hash:'$sd[3]':'$sd[4]':'$sd[2]'\n";` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [windigo_signatures.pl](https://github.com/eset/malware-ioc/blob/master/sshdoor/windigo_signatures.pl) | `else { print "mod_sshd14: unknown hash; fpass:'$sd[1]';'$sd[3]'\n" }` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [windigo_signatures.pl](https://github.com/eset/malware-ioc/blob/master/sshdoor/windigo_signatures.pl) | `print "mod14p: $d\n";` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [windigo_signatures.pl](https://github.com/eset/malware-ioc/blob/master/sshdoor/windigo_signatures.pl) | `print "mod_sshd15: '$sd[0]':'$sd[2]'\n";` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [windigo_signatures.pl](https://github.com/eset/malware-ioc/blob/master/sshdoor/windigo_signatures.pl) | `print "mod_sshc15: '$sc[38]':'$sc[0]'\n";` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [windigo_signatures.pl](https://github.com/eset/malware-ioc/blob/master/sshdoor/windigo_signatures.pl) | `print "mod_sshd16: '$sd[0]':'$sd[1]'\n";` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [windigo_signatures.pl](https://github.com/eset/malware-ioc/blob/master/sshdoor/windigo_signatures.pl) | `print "mod_sshc16: '$sc[1]':'$sc[0]'\n";` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [windigo_signatures.pl](https://github.com/eset/malware-ioc/blob/master/sshdoor/windigo_signatures.pl) | `print "mod_sshd17: crypt:'$sd[2]':'$sd[0]'\n";` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [windigo_signatures.pl](https://github.com/eset/malware-ioc/blob/master/sshdoor/windigo_signatures.pl) | `print "mod_sshc17: '$sc[0]':'$sc[1]'\n";` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [windigo_signatures.pl](https://github.com/eset/malware-ioc/blob/master/sshdoor/windigo_signatures.pl) | `print "mod_sshd17: client_string:'$q[1]'\n";` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [windigo_signatures.pl](https://github.com/eset/malware-ioc/blob/master/sshdoor/windigo_signatures.pl) | `print "mod_sshd18: md5:'$sd[3]':'$sd[0]'\n";` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [windigo_signatures.pl](https://github.com/eset/malware-ioc/blob/master/sshdoor/windigo_signatures.pl) | `print "mod_sshc18: md5:'$sc[3]':'$sc[0]'\n";` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [windigo_signatures.pl](https://github.com/eset/malware-ioc/blob/master/sshdoor/windigo_signatures.pl) | `print "mod_sshd19: '$sd[0]':'$sd[1]' url:'$sd[5] '$sd[4]'\n";` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [windigo_signatures.pl](https://github.com/eset/malware-ioc/blob/master/sshdoor/windigo_signatures.pl) | `print "mod_sshd20: '$sd[0]':'$sd[1]'\n";` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [windigo_signatures.pl](https://github.com/eset/malware-ioc/blob/master/sshdoor/windigo_signatures.pl) | `print "mod_sshc20: '$sc[0]':'$sc[1]'\n";` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [windigo_signatures.pl](https://github.com/eset/malware-ioc/blob/master/sshdoor/windigo_signatures.pl) | `print "mod_sshd21: '$sd[0]' mod_sshc21: '$sc[0]':'$sc[1]'\n";` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [windigo_signatures.pl](https://github.com/eset/malware-ioc/blob/master/sshdoor/windigo_signatures.pl) | `print "mod_sshc22: '$sd[0]':'$sd[1]':'$sd[2]'\n";` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [windigo_signatures.pl](https://github.com/eset/malware-ioc/blob/master/sshdoor/windigo_signatures.pl) | `print "mod_sshd23: '$sd[2]':'$sd[0]'\n";` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [windigo_signatures.pl](https://github.com/eset/malware-ioc/blob/master/sshdoor/windigo_signatures.pl) | `print "mod_sshc23: '$sc[0]':'$sc[1]'\n";` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [windigo_signatures.pl](https://github.com/eset/malware-ioc/blob/master/sshdoor/windigo_signatures.pl) | `print "mod_sshd24: '$sd[0]':'$sd[17]':'$sd[18]:$sd[20]'\n";` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [windigo_signatures.pl](https://github.com/eset/malware-ioc/blob/master/sshdoor/windigo_signatures.pl) | `print "mod_sshc24: '$sc[1]':'$sc[0]'\n";` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [windigo_signatures.pl](https://github.com/eset/malware-ioc/blob/master/sshdoor/windigo_signatures.pl) | `print "mod_sshd25: '$sd[2]':'$sd[0]' mod_sshc25: '$sc[0]'\n";` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [windigo_signatures.pl](https://github.com/eset/malware-ioc/blob/master/sshdoor/windigo_signatures.pl) | `print "mod_sshd27: '$sd[0]':'$sd[2]':'$sd[1]'\nmod_sshc27: '$sc[0]'\n";` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [windigo_signatures.pl](https://github.com/eset/malware-ioc/blob/master/sshdoor/windigo_signatures.pl) | `print "mod_sshd31: hash:'$sd[2]':'$sd[1]':'$sd[0]'\n";` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [windigo_signatures.pl](https://github.com/eset/malware-ioc/blob/master/sshdoor/windigo_signatures.pl) | `print "mod_sshd32: md5:'$sd1[0]:'$sd[0]':'$sc[0]'\n";` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [windigo_signatures.pl](https://github.com/eset/malware-ioc/blob/master/sshdoor/windigo_signatures.pl) | `print "mod_sshd33: '$sd[0]':'$sd[1]':'$sc[0]'\n";` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [windigo_signatures.pl](https://github.com/eset/malware-ioc/blob/master/sshdoor/windigo_signatures.pl) | `print $q. "\n";` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [windigo_signatures.pl](https://github.com/eset/malware-ioc/blob/master/sshdoor/windigo_signatures.pl) | `print "mod_sshd36: md5:'$sd[0]':'$sc[0]'; '$sd[1]':'$sc[1]'\n";` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [windigo_signatures.pl](https://github.com/eset/malware-ioc/blob/master/sshdoor/windigo_signatures.pl) | `print "mod_sshd37: md5:'$sd[0]'; '$sd[1]':'$sd[3]'\n";` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [windigo_signatures.pl](https://github.com/eset/malware-ioc/blob/master/sshdoor/windigo_signatures.pl) | `while (<$fn>) { chomp; print $_ ^ "\x14" x length $_ }` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [windigo_signatures.pl](https://github.com/eset/malware-ioc/blob/master/sshdoor/windigo_signatures.pl) | `print "mod_ssh41_cstr: " . join( '\|', sort keys %ostr ) . "\n";` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [windigo_signatures.pl](https://github.com/eset/malware-ioc/blob/master/sshdoor/windigo_signatures.pl) | `print "mod_sshd41: '$sd[1]' '$sd[0]', crypted\n";` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [windigo_signatures.pl](https://github.com/eset/malware-ioc/blob/master/sshdoor/windigo_signatures.pl) | `print "mod_sshc41: '$sc[1]' '$sc[0]', crypted\n";` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [windigo_signatures.pl](https://github.com/eset/malware-ioc/blob/master/sshdoor/windigo_signatures.pl) | `print "mod_sshd42: detected; log_useragent:passwd_file:passwd\n" if @sd;` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [windigo_signatures.pl](https://github.com/eset/malware-ioc/blob/master/sshdoor/windigo_signatures.pl) | `print "mod_sshc42: detected\n"                                   if @sc;` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [windigo_signatures.pl](https://github.com/eset/malware-ioc/blob/master/sshdoor/windigo_signatures.pl) | `print "mod_sshd44: pass:'$sd[1]' '$sd[0]', '$sd[2]'\n";` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [windigo_signatures.pl](https://github.com/eset/malware-ioc/blob/master/sshdoor/windigo_signatures.pl) | `if ( $sc[0] ) { print "mod_sshc44: '$sc[0]' '$sc[13]'\n"; ssh_ls( $sd[0] ) }` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [windigo_signatures.pl](https://github.com/eset/malware-ioc/blob/master/sshdoor/windigo_signatures.pl) | `print "mod_sshd45: pass:'$sd[1]' host:'$sd[0]', '$sd[2]'\n";` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [windigo_signatures.pl](https://github.com/eset/malware-ioc/blob/master/sshdoor/windigo_signatures.pl) | `if ( $sc[0] ) { print "mod_sshc45: host:'$sc[0]' '$sc[1]'\n"; ssh_ls() }` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [windigo_signatures.pl](https://github.com/eset/malware-ioc/blob/master/sshdoor/windigo_signatures.pl) | `print "mod_sshd46: crypt:'$sc[1]' v1:'$sd[1]' v2:'$sd[2]'\n";` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [windigo_signatures.pl](https://github.com/eset/malware-ioc/blob/master/sshdoor/windigo_signatures.pl) | `print "mod_sshd47: pass:'$sd[0]' '$sd[1]', '$sd[2]'\n";` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [windigo_signatures.pl](https://github.com/eset/malware-ioc/blob/master/sshdoor/windigo_signatures.pl) | `if (@sc) { print "mod_sshc47: host:'$sc[0]' '$sc[-1]'\n"; ssh_ls( $sc[0] ) }` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [windigo_signatures.pl](https://github.com/eset/malware-ioc/blob/master/sshdoor/windigo_signatures.pl) | `for (@sd)    { print "mod_md5_sshd: '$_'\n" }` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [windigo_signatures.pl](https://github.com/eset/malware-ioc/blob/master/sshdoor/windigo_signatures.pl) | `for (@sc)    { print "mod_md5_ssh: '$_'\n" }` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [windigo_signatures.pl](https://github.com/eset/malware-ioc/blob/master/sshdoor/windigo_signatures.pl) | `print "mod_md5_static_ssl: $static_ssl\n" if $static_ssl;` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [windigo_signatures.pl](https://github.com/eset/malware-ioc/blob/master/sshdoor/windigo_signatures.pl) | `print "mod_hack_strd: possible hacked, " . join( "\|", @sd ) . "\n";` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [windigo_signatures.pl](https://github.com/eset/malware-ioc/blob/master/sshdoor/windigo_signatures.pl) | `print "mod_hack_strc: possible hacked, " . join( "\|", @sc ) . "\n";` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [windigo_signatures.pl](https://github.com/eset/malware-ioc/blob/master/sshdoor/windigo_signatures.pl) | `for (@sd) { print "mod_md5_sshd1: '$_'\n" }` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [windigo_signatures.pl](https://github.com/eset/malware-ioc/blob/master/sshdoor/windigo_signatures.pl) | `print "mod_str_sshd_str: '" . join( "':'", keys %ostr ) . "'\n";` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [windigo_signatures.pl](https://github.com/eset/malware-ioc/blob/master/sshdoor/windigo_signatures.pl) | `print "mod_str_sshd_str1: '" . join( "':'", keys %ostr ) . "'\n";` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [windigo_signatures.pl](https://github.com/eset/malware-ioc/blob/master/sshdoor/windigo_signatures.pl) | `if (@sd) { print "sshd_str: " . join( '\|', @sd ) . "\n" }` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [windigo_signatures.pl](https://github.com/eset/malware-ioc/blob/master/sshdoor/windigo_signatures.pl) | `if (@sc) { print "sshc_str: " . join( '\|', @sc ) . "\n" }` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
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
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [index.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Indexes-Markdown/index.md) | - T1547.012 Print Processors [CONTRIBUTE A TEST](https://atomicredteam.io/contributing) | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [windows-index.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Indexes-Markdown/windows-index.md) | - T1547.012 Print Processors [CONTRIBUTE A TEST](https://atomicredteam.io/contributing) | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [matrix.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Matrices/matrix.md) | \|  \|  \| Outlook Forms [CONTRIBUTE A TEST](https://atomicredteam.io/contributing) \| Print Processors [CONTRIBUTE A TEST](https://atomicredteam.io/contributing) \| Indicator Removal from Tools [CONTRIBUTE A TEST](https://atomicredteam.io/contributing) \|  \|  \|  \|  \|  \|  \|  \| | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [matrix.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Matrices/matrix.md) | \|  \|  \| Print Processors [CONTRIBUTE A TEST](https://atomicredteam.io/contributing) \| [Screensaver](../../T1546.002/T1546.002.md) \| [Masquerade Task or Service](../../T1036.004/T1036.004.md) \|  \|  \|  \|  \|  \|  \|  \| | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [windows-matrix.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Matrices/windows-matrix.md) | \|  \|  \| Outlook Rules [CONTRIBUTE A TEST](https://atomicredteam.io/contributing) \| Print Processors [CONTRIBUTE A TEST](https://atomicredteam.io/contributing) \| Indicator Blocking [CONTRIBUTE A TEST](https://atomicredteam.io/contributing) \|  \|  \|  \|  \|  \|  \|  \| | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [windows-matrix.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Matrices/windows-matrix.md) | \|  \|  \| Print Processors [CONTRIBUTE A TEST](https://atomicredteam.io/contributing) \| [Security Support Provider](../../T1547.005/T1547.005.md) \| Make and Impersonate Token [CONTRIBUTE A TEST](https://atomicredteam.io/contributing) \|  \|  \|  \|  \|  \|  \|  \| | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1016.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1016/T1016.md) | if [ -x "$(command -v netstat)" ]; then netstat -ant \| awk '{print $NF}' \| grep -v '[a-z]' \| sort \| uniq -c; else echo "netstat is missing from the machine. skipping..."; fi; | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1018.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1018/T1018.md) | Upon successful execution, cmd.exe will execute `net.exe view` and display results of local systems on the network that have file and print sharing enabled. | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1018.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1018/T1018.md) | adidnsdump -u #{user_name} -p #{acct_pass} --print-zones #{host_name} | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1027.004.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1027.004/T1027.004.md) | Upon execution, the exe will print 'T1027.004 Dynamic Compile'. | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1036.006.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1036.006/T1036.006.md) | 1. 1. echo '#!/bin/bash\necho "print \"hello, world!\"" \| /usr/bin/python\nexit' > execute.txt && chmod +x execute.txt | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1083.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1083/T1083.md) | cd $HOME && find . -print \| sed -e 's;[^/]*/;\|__;g;s;__\|; \|;g' > #{output_file} | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1110.003.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1110.003/T1110.003.md) | This atomic attempts to map the IPC$ share on one of the Domain Controllers using a password of Spring2020 for each user in the %temp%\users.txt list. Any successful authentications will be printed to the screen with a message like "[*] username:password", whereas a failed auth will simply print a period. Use the input arguments to specify your own password to use for the password spray. | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1489.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1489/T1489.md) | Stops a specified service using the net.exe command. Upon execution, if the service was running "The Print Spooler service was stopped successfully." | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1489.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1489/T1489.md) | will be displayed. If the service was not running, "The Print Spooler service is not started." will be displayed and it can be | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1518.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1518/T1518.md) | /usr/libexec/PlistBuddy -c "print :CFBundleShortVersionString" /Applications/Safari.app/Contents/Info.plist | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1518.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1518/T1518.md) | /usr/libexec/PlistBuddy -c "print :CFBundleVersion" /Applications/Safari.app/Contents/Info.plist | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1546.001.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1546.001/T1546.001.md) | * <code>HKEY_CLASSES_ROOT\txtfile\shell\print\command</code> | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1564.004.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1564.004/T1564.004.md) | print /D:#{path}\file.txt:autoruns.exe #{path}\Autoruns.exe | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [apis.md](https://github.com/redcanaryco/atomic-red-team/blob/master/docs/apis.md) | ### Example: print all the Atomic Tests by ATT&CK technique | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_backdoor_ssh_python.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_backdoor_ssh_python.yar) | $s1 = "print '[-] (Failed to load moduli -- gex will be unsupported.)'" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_backdoor_ssh_python.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_backdoor_ssh_python.yar) | $s2 = "print '[-] Listen/bind/accept failed: ' + str(e)" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_backdoor_ssh_python.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_backdoor_ssh_python.yar) | $s4 = "print '[-] SSH negotiation failed.'" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_eqgrp.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_eqgrp.yar) | $x2 = "print \"Gimme hex: \";" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_eqgrp.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_eqgrp.yar) | $s3 = "print \"$hex in decimal=$dec\\n\\n\";" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_eqgrp.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_eqgrp.yar) | $s2 = "print \"ERROR: the filename or hex representation needs to be one argument try using \\\"'s\\n\";" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_eqgrp.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_eqgrp.yar) | $s5 = "print hextoIP($ARGV[0]);" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_eqgrp.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_eqgrp.yar) | $s2 = "print >>out, \"%s%04x  \" % (lead,i)," fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_eqgrp.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_eqgrp.yar) | $s3 = "print >>out, \"%02X\" % ord(x[i+j])," fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_eqgrp.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_eqgrp.yar) | $s4 = "print >>out, sane(x[i:i+16])" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_eqgrp.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_eqgrp.yar) | $s1 = "print \"[+] Connecting to %s:%s\" % (self.params.dst['ip'], self.params.dst['port'])" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_eqgrp.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_eqgrp.yar) | $s6 = "print \"[-] keyboard interrupt before response received\"" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_eqgrp.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_eqgrp.yar) | $s8 = "print 'Debug info ','='*40" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_eqgrp_apr17.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_eqgrp_apr17.yar) | $s2 = "print \"java -jar jscanner.jar$scanth$list\\n\";" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_eqgrp_apr17.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_eqgrp_apr17.yar) | $x1 = "print '  -s storebin  use storebin as the Store executable\\n'" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_eqgrp_apr17.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_eqgrp_apr17.yar) | $x3 = "print '  -k keyfile   the key text file to inject'" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_op_wocao.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_op_wocao.yar) | $a = "out.print(\"All seems fine.\");" | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_op_wocao.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_op_wocao.yar) | $e = "out.print((char)c);}in.close()" | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_op_wocao.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_op_wocao.yar) | $f = "out.print((char)c);}er.close()" | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_project_sauron_extras.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_project_sauron_extras.yar) | $s2 = "Print only replying Ips" | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [cn_pentestset_scripts.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/cn_pentestset_scripts.yar) | $s0 = "print \"[*] Connected to remote host \\n\"; " fullword ascii /* PEStudio Blacklist: strings */ | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [cn_pentestset_scripts.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/cn_pentestset_scripts.yar) | $s1 = "print \"Usage: $0 [Host] [Port] \\n\\n\";  " fullword ascii /* PEStudio Blacklist: strings */ | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [cn_pentestset_scripts.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/cn_pentestset_scripts.yar) | $s5 = "print \"[*] Resolving HostName\\n\"; " fullword ascii /* PEStudio Blacklist: strings */ | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [exploit_shitrix.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/exploit_shitrix.yar) | $s07 = "template.new({'BLOCK'='print readpipe(" ascii /* TrustedSec templae */ | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [gen_cn_webshells.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/gen_cn_webshells.yar) | $s3 = "out.print(\"Hi,Man 2015<br /><!--?Confpwd=023&Conn=ls-->\");" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [gen_cn_webshells.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/gen_cn_webshells.yar) | $s6 = "out.print(\"</pre>\");" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [gen_cn_webshells.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/gen_cn_webshells.yar) | $s7 = "out.print(\"<pre>\");" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [gen_cn_webshells.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/gen_cn_webshells.yar) | $s4 = "out.print(\"Hi,Man 2015\");" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [thor-webshells.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/thor-webshells.yar) | $s4 = "print \"<a href=\\\"$_SERVER[PHP_SELF]?s=$s&login=$login&passwd=$passwd&" | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [thor-webshells.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/thor-webshells.yar) | $s0 = "      out.print(\"<tr><td width='60%'>\"+strCut(convertPath(list[i].getPath()),7" | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [thor-webshells.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/thor-webshells.yar) | $s0 = "</font><%out.print(request.getRealPath(request.getServletPath())); %>" fullword | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [thor-webshells.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/thor-webshells.yar) | $s4 = "print \"<form action=\\\"\".$me.\"?p=cmd&dir=\".realpath('.').\"" | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [thor-webshells.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/thor-webshells.yar) | $s8 = "print \"<td id=f><a href=\\\"?p=rename&file=\".realpath($file).\"&di" | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [thor-webshells.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/thor-webshells.yar) | $s1 = "print \"\\n\".'Tip: to view the file \"as is\" - open the page in <a href=\"'.Dx" | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [thor-webshells.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/thor-webshells.yar) | $s9 = "if(cmd.equals(\"Szh0ZWFt\")){out.print(\"[S]\"+dir+\"[E]\");}" fullword | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [thor-webshells.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/thor-webshells.yar) | $s2 = "out.print(\") <A Style='Color: \" + fcolor.toString() + \";' HRef='?file=\" + fn" | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [thor-webshells.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/thor-webshells.yar) | $s7 = "if(flist[i].canRead() == true) out.print(\"r\" ); else out.print(\"-\");" fullword | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [thor-webshells.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/thor-webshells.yar) | $s5 = "print \"<font face=\\\"Verdana\\\" size=\\\"1\\\" color=\\\"#990000\\\">Filenam" | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [thor-webshells.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/thor-webshells.yar) | $s8 = "print \"<font face=\\\"Verdana\\\" size=\\\"1\\\" color=\\\"#990000\\\">File: </" | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [thor-webshells.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/thor-webshells.yar) | $s0 = "copy ( $dosya_gonder2, \"$dir/$dosya_gonder2_name\") ? print(\"$dosya_gonder2_na" | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [thor-webshells.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/thor-webshells.yar) | $s2 = "python -c\"import md5;x=md5.new('you_password');print x.hexdigest()\"" fullword | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [thor-webshells.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/thor-webshells.yar) | $s0 = "print \"\\n\".'Tip: to view the file \"as is\" - open the page in <a href=\"'.Dx" | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [thor-webshells.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/thor-webshells.yar) | $s1 = "print \"Sending mail to $to....... \";" | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [thor-webshells.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/thor-webshells.yar) | $s2 = "print \"Asmodeus Perl Remote Shell" | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [thor-webshells.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/thor-webshells.yar) | $s2 = "print \"\\n\".'<tr><td width=100pt class=linelisting><nobr>POST (php eval)</td><" | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [thor-webshells.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/thor-webshells.yar) | $s1 = "print \"<tr><td><b>Server is:</b></td><td>\".$_SERVER['SERVER_SIGNATURE'].\"</td" | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [thor-webshells.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/thor-webshells.yar) | $s2 = "print \"<tr><td><b>Execute command:</b></td><td><input size=100 name=\\\"_cmd" | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [thor-webshells.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/thor-webshells.yar) | $s3 = "print \"error; help: head -n 16 d00r.py\"" fullword | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [thor-webshells.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/thor-webshells.yar) | $s4 = "print \"PW:\",PW,\"PORT:\",PORT,\"HOST:\",HOST" fullword | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [thor-webshells.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/thor-webshells.yar) | $s3 = "print \"<a href=\\\"$_SERVER[PHP_SELF]?s=$s&login=$login&passwd=$passwd&" | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [thor-webshells.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/thor-webshells.yar) | $s2 = "print \"Set-Cookie: SAVEDPWD=;\\n\"; # remove password cookie" | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [thor-webshells.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/thor-webshells.yar) | $s2 = "print(\"<br>Provenance du mail : <input type=\\\"text\\\" name=\\\"provenanc" | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [thor-webshells.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/thor-webshells.yar) | $s3 = "<? if($cmd != \"\") print Shell_Exec($cmd);?>" fullword | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [thor-webshells.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/thor-webshells.yar) | $s8 = "print \"<form action=\\\"\".$me.\"?p=chmod&file=\".$content.\"&d" | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [thor-webshells.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/thor-webshells.yar) | $s18 = "print shell_exec($command);" fullword | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [thor-webshells.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/thor-webshells.yar) | $s5 = "print \"<center><h1>#worst @dal.net</h1></center>\";" fullword | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [thor-webshells.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/thor-webshells.yar) | $s7 = "print \"<center><h1>Linux Shells</h1></center>\";" fullword | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [thor-webshells.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/thor-webshells.yar) | $s14 = "print \"<tr><td><b>System type:</b></td><td>$UName</td></tr>\";" fullword | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [thor-webshells.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/thor-webshells.yar) | $s20 = "print \"Transfered $TargetFileSize Bytes.<br>\";" fullword | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [thor-webshells.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/thor-webshells.yar) | $s12 = "print \"Sending mail to $to....... \"; " fullword | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [thor-webshells.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/thor-webshells.yar) | $s4 = "<? if($cmd != \"\") print Shell_Exec($cmd);?>" fullword | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [thor-webshells.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/thor-webshells.yar) | $s12 = "print << \"[kalabanga]\";" fullword | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [thor-webshells.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/thor-webshells.yar) | $s5 = "print \"<center>[ Generation time: \".round(getTime()-startTime,4).\" second" | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [thor-webshells.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/thor-webshells.yar) | $s6 = "print \"Sorry, none of the command functions works.\";" fullword | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [thor-webshells.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/thor-webshells.yar) | $s3 = "print(\"<p align=\\\"center\\\"><font size=\\\"5\\\">Exploit include " | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)

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

