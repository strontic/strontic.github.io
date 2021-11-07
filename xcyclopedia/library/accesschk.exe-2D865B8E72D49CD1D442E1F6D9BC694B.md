---
title: accesschk.exe | Reports effective permissions for securable objects
excerpt: What is accesschk.exe?
---

# accesschk.exe 

* File Path: `C:\SysinternalsSuite\accesschk.exe`
* Description: Reports effective permissions for securable objects

## Hashes

Type | Hash
-- | --
MD5 | `2D865B8E72D49CD1D442E1F6D9BC694B`
SHA1 | `018D0E5CEC627F8C7D880D4C67D5A0D236EDD8FE`
SHA256 | `E7289B333BD82CB3B720E8BF8564C4C141BCBE2592F4CDE1DFA7DB124C964C88`
SHA384 | `6F38906A93214A4E467A386183757E456F07BDC2B17C9459F8C31632DB4E65EB505D565EED581F3D4F150986671735EE`
SHA512 | `B44E5633C38C24C38C9BE4FCCF3A7A72F35697E9E7F7476ECC79EA8B4E2A9E0D9954A66127885D508E78F9CB3C7869211F88E1145981B969FBACF24B2B75FAEB`
SSDEEP | `6144:niOBsOLuduhzO05OX3rvjs23EYkHB9+2in1TnwFJe0I05w3il6P:nRBnLuEx583rvjs2PmYnr25bl6P`
IMP | `E325756A1C6D9DF5A7076A74F05EE8D6`
PESHA1 | `C59E8906B305413C01E4BE35EE4DD1CF79DE04D5`
PE256 | `E907FAB75EB7DC6F15F818B8B0197928B4EDF525FEA402B5638DAE56C1B13529`

## Runtime Data

### Usage (stdout):
```cmhg

Accesschk v6.12 - Reports effective permissions for securable objects
Copyright (C) 2006-2017 Mark Russinovich
Sysinternals - www.sysinternals.com

usage: accesschk [-s][-e][-u][-r][-w][-n][-v]-[f <account>,...][[-a]|[-k]|[-m]|[-p [-f] [-t]]|[-h][-o [-t <object type>]][-c]|[-d]] [[[-l|-L] [-i]]|[username]] <file, directory, event log, registry key, process, service, object>
   -a     Name is a Windows account right. Specify '*' as the name to show all
          rights assigned to a user. Note that when you specify a specific
          right, only groups and accounts directly assigned the right are
          displayed.
   -c     Name is a Windows Service e.g. ssdpsrv. Specify '*' as the
          name to show all services and 'scmanager' to check the security
          of the Service Control Manager.
   -d     Only process directories or top level key.
   -e     Only show explicitly set Integrity Levels (Windows Vista and
          higher only).
   -f     If following -p, shows full process token information including
          groups and privileges. Otherwise is a list of comma-separated
          accounts to filter from the output.
   -h     Name is a file or printer share. Specify '*' as the name to show
          all shares.
   -i     Ignore objects with only inherited ACEs when dumping full access
          control lists.
   -k     Name is a Registry key e.g. hklm\software
   -l     Show full security descriptor. Add -i to ignore inherited ACEs.
          Specify upper-case L to have the output format as SDDL.
   -m     Name is an event log (specify '*' as the name to show all event logs.
   -n     Show only objects that have no access.
   -o     Name is an object in the Object Manager namespace (default is root).
          To view the contents of a directory, specify the name with a trailing
          backslash or add -s. Add -t and an object type (e.g. section) to
          see only objects of a specific type.
   -p     Name is a process name or PID e.g. cmd.exe (specify '*' as the
          name to show all processes). Add -f to show full process
          token information including groups and privileges. Add -t to show
          threads.
   -nobanner
          Do not display the startup banner and copyright message.
   -r     Show only objects that have read access.
   -s     Recurse.
   -t     Object type filter e.g. "section"
   -u     Suppress errors.
   -v     Verbose (includes Windows Vista Integrity Level).
   -w     Show only objects that have write access.

If you specify a user or group name and path AccessChk will report the
effective permissions for that account; otherwise it will show the effective
access for accounts referenced in the security descriptor.

By default the path name is interpreted as a file system path (use the
"\pipe\" prefix to specify a named pipe path). For each object AccessChk
prints R if the account has read access, W for write access and nothing if
it has neither. The -v switch has AccessChk dump the specific
accesses granted to an account.

```

### Loaded Modules:

Path |
-- |
C:\SysinternalsSuite\accesschk.exe |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\wow64.dll |
C:\Windows\System32\wow64cpu.dll |
C:\Windows\System32\wow64win.dll |


## Signature

* Status: Signature verified.
* Serial: `33000001797C2E574E52E1CAD6000100000179`
* Thumbprint: `5EAD300DC7E4D637948ECB0ED829A072BD152E17`
* Issuer: CN=Microsoft Code Signing PCA, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Corporation, OU=MOPR, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: accesschk.exe
* Product Name: Sysinternals AccessChk
* Company Name: Sysinternals - www.sysinternals.com
* File Version: 6.12
* Product Version: 6.12
* Language: English (United States)
* Legal Copyright: Copyright (C) 2006-2017 Mark Russinovich
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/70
* VirusTotal Link: https://www.virustotal.com/gui/file/e7289b333bd82cb3b720e8bf8564c4c141bcbe2592f4cde1dfa7db124c964c88/detection/

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\SysinternalsSuite\accesschk64.exe](accesschk64.exe-DBDCE12349B96F4C9747A4CD23312205.md) | 75

## Possible Misuse

*The following table contains possible examples of `accesschk.exe` being misused. While `accesschk.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_accesschk_usage_after_priv_escalation.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/sysmon_accesschk_usage_after_priv_escalation.yml) | `title: Accesschk Usage After Privilege Escalation`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_accesschk_usage_after_priv_escalation.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/sysmon_accesschk_usage_after_priv_escalation.yml) | `description: Accesschk is an access and privilege audit tool developed by SysInternal and often being used by attacker to verify if a privilege escalation process successful or not `{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_accesschk_usage_after_priv_escalation.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/sysmon_accesschk_usage_after_priv_escalation.yml) | `Product\|endswith: 'AccessChk'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_spoolsv_child_processes.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_spoolsv_child_processes.yml) | `- \accesschk.exe`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1555.003.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1555.003/T1555.003.md) | A modified sysinternals suite will be downloaded and staged. The Chrome-password collector, renamed accesschk.exe, will then be executed from #{file_path}. | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1555.003.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1555.003/T1555.003.md) | ./accesschk.exe -accepteula .; | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)



MIT License. Copyright (c) 2020-2021 Strontic.


