---
title: tlist.exe | Microsoft Process List Utility
excerpt: What is tlist.exe?
---

# tlist.exe 

* File Path: `C:\Program Files (x86)\Windows Kits\10\Debuggers\x86\tlist.exe`
* Description: Microsoft Process List Utility

## Hashes

Type | Hash
-- | --
MD5 | `4301EE791540B7AC5D85C4B7A383B8CB`
SHA1 | `3F6610D07373C7B8C29DC97D47D2A4ACB2AB810A`
SHA256 | `FAD6CD51C18466760C84D2235F8A514E318AF52D60C3F288A234F5B2BE987691`
SHA384 | `CFD55D89ED49ED3E48139F93BCC4B6837C2201E32B22C404E028EF0B233AB397A353EDC49194C6E4A87794C3000522B9`
SHA512 | `50D8FF92F3F05C74DA928A675AB909D532AC52E633A478D6E13CAA199558B31E10CF0EA9C207F4346091A65EC7D188950C37F46230A8C766350E42FB37F6C3B7`
SSDEEP | `768:/j16MPBSHAWL99/nDE8GT/pDmkt6tqTaLOyse8o+VwX7Z:77BSgWLju3eDi7eiVw`
IMP | `DBEC6EB5DF480CCCC407090C46E85A27`
PESHA1 | `E18DEA803717C3C17130E44D46ECDD74B31A0CE9`
PE256 | `923AFE97DD117D2CC6ECDA6E8BA5B68B7F5B372EBCF2885DA5DC458AAB4E3C86`

## Runtime Data

### Usage (stderr):
```cmhg
Microsoft (R) Windows NT (TM) Version 5.1 TLIST
Copyright (c) Microsoft Corporation. All rights reserved.

usage: TLIST <<-m <pattern>> | <-t> | <pid> | <pattern> | <-p <processname>>> | <-k> | <-s>
           [options]:
           -t
              Print Task Tree

           <pid>
              List module information for this task.

           <pattern>
              The pattern can be a complete task
              name or a regular expression pattern
              to use as a match.  Tlist matches the
              supplied pattern against the task names
              and the window titles.

           -c
              Show command lines for each process

           -e
              Show session IDs for each process

           -g
              Show group affinity for each process (Win7+)

           -k
              Show MTS packages active in each process.

           -m <pattern>
              Lists all tasks that have DLL modules loaded
              in them that match the given pattern name

           -s
              Show services active in each process.

           -p <processname>
              Returns the PID of the process specified or -1
              if the specified process doesn't exist.  If there
              are multiple instances of the process running only
              the instance with the first PID value is returned.

           -v
              Show all process information

           -w
              Show Wow64 process information


```

### Loaded Modules:

Path |
-- |
C:\Program Files (x86)\Windows Kits\10\Debuggers\x86\tlist.exe |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\wow64.dll |
C:\Windows\System32\wow64cpu.dll |
C:\Windows\System32\wow64win.dll |


## Signature

* Status: Signature verified.
* Serial: `33000002CF6D2CC57CAA65A6D80000000002CF`
* Thumbprint: `1A221B3B4FEF088B17BA6704FD088DF192D9E0EF`
* Issuer: CN=Microsoft Code Signing PCA 2010, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Corporation, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: tlist.exe
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: Unknown
* VirusTotal Link: n/a





MIT License. Copyright (c) 2020 Strontic.


