---
title: tlist.exe | Microsoft Process List Utility
excerpt: What is tlist.exe?
---

# tlist.exe 

* File Path: `C:\Program Files (x86)\Windows Kits\10\Debuggers\x64\tlist.exe`
* Description: Microsoft Process List Utility

## Hashes

Type | Hash
-- | --
MD5 | `133DCA03D53C59A0E155366F89F77737`
SHA1 | `3203F776455CD75276035576C1C27426A091DA08`
SHA256 | `E9972E8DCEE65A5D851EED887716B8CE535BC9D439E5976958965C449E5F5750`
SHA384 | `C94C54EA8A90D25A421036D6168BB3F1D761FE646557871D1CF2DEC4CBFE4A12111BB0306E300FE5C9E16583BCE29AFB`
SHA512 | `CF904A593C6B9A87D035877F2D3BE2FF67A6B416D3566703B7235C6446C64DE16DEC6D3790953AF4705BA8D082AA462EEE56E1B741F135ECCD5559E9484FCA86`
SSDEEP | `768:kzeJADjZEWDItB97gZPq0v4Vj16MSVYmklaC8opnIhx:kcA3SNgZPq0vUKMACNnIL`
IMP | `995C499033953B28F84B5F09778C487A`
PESHA1 | `61A441AFA6A7459B014ECB5B00FDE8DEFC3B1766`
PE256 | `F880A2FB4FF77B922BF5D50E3140838FD5D6E6BCE801087C98BCB79D86C08FD9`

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
C:\Program Files (x86)\Windows Kits\10\Debuggers\x64\tlist.exe |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\SYSTEM32\ntdll.dll |


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
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/73
* VirusTotal Link: https://www.virustotal.com/gui/file/e9972e8dcee65a5d851eed887716b8ce535bc9d439e5976958965c449e5f5750/detection





MIT License. Copyright (c) 2020-2021 Strontic.


