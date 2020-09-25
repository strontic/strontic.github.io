---
title: accesschk64.exe | Reports effective permissions for securable objects
excerpt: What is accesschk64.exe?
---

# accesschk64.exe 

* File Path: `C:\SysinternalsSuite\accesschk64.exe`
* Description: Reports effective permissions for securable objects

## Hashes

Type | Hash
-- | --
MD5 | `DBDCE12349B96F4C9747A4CD23312205`
SHA1 | `166BF5EB67EF473F8B90A5785F159BABED6CBFD1`
SHA256 | `938273BC3B905C1385CE5A16AE1A7AE148B0EE10D115735D261078E4BCEB69D4`
SHA384 | `891EFD116882476C03BE7EF5D7DA2983B0F00978D56D2BD6E5F81E8A8A23C3433641860142591E8ADF1FE357E6F98A2A`
SHA512 | `E448FCE4B6521D04F9BD5E5954ADC67655F600B81274FD1E2B22CA6D703136C4B760BDA14C72B5987796E3D2B34C902DF8DA6A0BA1AE4320F16AA32CF33DCFA7`
SSDEEP | `6144:73rvjs23EYkHB9+2in1TnwFJe0I05w3iz:73rvjs2PmYnr25bz`
IMP | `E80BC24C900FA3657FF0990B5DC84B06`
PESHA1 | `F2D92B603B99750FB29622E4CD6857924479342F`
PE256 | `F246182900ED53A1B3103A3FFFBCBB7C7F83EA12BABE63FEB74D13F4C4A38778`

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
C:\SysinternalsSuite\accesschk64.exe |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\SYSTEM32\ntdll.dll |


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
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/68
* VirusTotal Link: https://www.virustotal.com/gui/file/938273bc3b905c1385ce5a16ae1a7ae148b0ee10d115735d261078e4bceb69d4/detection/

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\SysinternalsSuite\accesschk.exe](accesschk.exe-2D865B8E72D49CD1D442E1F6D9BC694B.md) | 75




MIT License. Copyright (c) 2020 Strontic.


