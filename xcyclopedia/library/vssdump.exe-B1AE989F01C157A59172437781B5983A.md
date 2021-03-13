---
title: vssdump.exe | Microsoft VSS Folder Dumper
excerpt: What is vssdump.exe?
---

# vssdump.exe 

* File Path: `C:\Program Files (x86)\Windows Kits\10\Debuggers\x86\srcsrv\vssdump.exe`
* Description: Microsoft VSS Folder Dumper

## Hashes

Type | Hash
-- | --
MD5 | `B1AE989F01C157A59172437781B5983A`
SHA1 | `6226634D60D6F2C93B08C2736492BF01B0BF81BA`
SHA256 | `E9CF573BEFBF4366665139CE2D36A419EFEFB9CCBEC3745D8800626233D6866E`
SHA384 | `120F4CB95CB52AD78144D9B3B048E6AE6659D4D2B7F3E722727E472EC28CE9CD4C2A6045B5675D89020858226BD91475`
SHA512 | `36D1A041908370718D3FD250C692DAFEC80D239D61E168F80CFA381AA1B04C1046E1D2FC5BE41EBD4EB7E8F801ACDE98F22BDD5DAA5B01BC79C86945C5DFFA94`
SSDEEP | `384:ggHUK1WTPgzpAS1xnYfHV7RvIzlArUTB9ffIGWYRzWiOJv1NwGyAAJllN42:RvWTPgzCo9fQEpEXNi4`
IMP | `443B9BDBA2773E6E1A824E19FD3967A0`
PESHA1 | `AD8D194D0E47F23E8F4E5D715ED870AC66DD4CE5`
PE256 | `359E9A2502E4B35C68DFA569A67A4E61B685C3965FA63318C8A8C7E663D01BB3`

## Runtime Data

### Usage (stdout):
```cmhg
vssdump: enumerates files in the current VSS project.
      -a                ignores the current project and lists all projects.
      -p:<projectname>  specifies a VSS project to use.
                        not to be used -with '-a'
      -d:<directory>    specifies a root directory
                        otherwise the current directory is used.
      -l:<label>        specifies a version label
      -t                don't test version to match a passed label
      -v:<sharepath>    specifies location of the VSS database - overrides SSDIR
      -r                recurse subdirectories
      -f                don't list files - just directories
      -i                ignore current directory and list entire project
                        not to be used with '-r'
      -s                format output for scripting
      -c                display only the VSS configuration info

```

### Loaded Modules:

Path |
-- |
C:\Program Files (x86)\Windows Kits\10\Debuggers\x86\srcsrv\vssdump.exe |
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

* Original Filename: vssdump.dll
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: Unknown





MIT License. Copyright (c) 2020-2021 Strontic.


