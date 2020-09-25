---
title: Testlimit64.exe | Test Windows Limits
excerpt: What is Testlimit64.exe?
---

# Testlimit64.exe 

* File Path: `C:\SysinternalsSuite\Testlimit64.exe`
* Description: Test Windows Limits

## Hashes

Type | Hash
-- | --
MD5 | `110197E4076BCD7CDC97066F73566EC0`
SHA1 | `14412A4188C4FF8DB5EFA03B4CE5CC4C55C8CF39`
SHA256 | `F1564B3C3EEE87D62EF04CCF2C6B453020D3547FAA2CCC5C9E2CEF94FE659F2F`
SHA384 | `33CA3E28EBF4D7D775D9E2B4E66E569E9F42784BB8769480E09B6080F7FDB885308AF03FEF742913D2DEDEBDF4DCD689`
SHA512 | `C86FF179C084A9BEA03E355310AFDDD3D3D38F5E0FBDA1C84F95B11F491D8C5388647293AE35392C0BCA62E61D745021F1BF5673CAAEA811495942F24B16DAF9`
SSDEEP | `3072:jj8HiODN40wSWZkglMYoY8MZT64N9/1A0BPDIRObj5UFYZFvgGZriIipNV+GPyMA:n8HiOVwxpoY1TP9/aK6VYHl4khIs`
IMP | `6CAFE31FAA06152D26FAB31DE1C700B8`
PESHA1 | `12296CE3E0DBEC2FBEAA0DC437CE68914B4BEC83`
PE256 | `2BBA1ECEB07FE261129FF67C4C4916157CCA14106C923C6D385A413227E58C3C`

## Runtime Data

### Usage (stdout):
```cmhg

Testlimit v5.24 - test Windows limits
Copyright (C) 2012-2015 Mark Russinovich 
Sysinternals - www.sysinternals.com

Process ID: 6904

usage: testlimit [[-h [-u]] | [-p [-n]] | [-t [-n [KB]]] | [-u [-i]] | [-g [object size]] | [-a|-d|-l|-m|-r|-s|-v [MB]] | [-w]] [-c [count]] [-e [seconds]]
  -a       Leak Address Windowing Extensions (AWE) memory in
           specified MBs (default is 1).
  -c       Count of number of objects to allocate (default is as many as
           possible). This must be the last option specified.
  -d       Leak and touch memory in specified MBs (default is 1).
  -e       Seconds elapsed between allocations (default is 0).
  -g       Create GDI handles of specified size (default 1 byte).
           Specify a size of 0 to cause GDI object exhaustion.
  -h       Create handles. Specify -u to also allocate file objects.
  -i       Exhaust USER desktop heap.
  -l       Allocate the specified amount of large pages (rounded to large
           size multiple.
  -m       Leak memory in specified MBs (default is 1).
  -p       Create processes - add -n to set min working set. Add -n to
           set min working set of processes to smallest.
  -r       Reserve memory in specified MBs (default is 1).
  -s       Leak shared memory in specified MBs (default is 1).
  -t       Create threads - add -n to specify minimum stack reserve (in KB).
  -u       Create USER handles to menus.
  -v       VirtualLock memory in specified MBs (default is 1).
  -w       Reset working set minimum to highest possible value.

```

### Loaded Modules:

Path |
-- |
C:\SysinternalsSuite\Testlimit64.exe |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\SYSTEM32\ntdll.dll |


## Signature

* Status: Signature verified.
* Serial: `330000014096A9EE7056FECC07000100000140`
* Thumbprint: `98ED99A67886D020C564923B7DF25E9AC019DF26`
* Issuer: CN=Microsoft Code Signing PCA, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Corporation, OU=MOPR, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: Testlimit
* Product Name: Sysinternals Testlimit
* Company Name: Sysinternals - www.sysinternals.com
* File Version: 5.24
* Product Version: 5.24
* Language: English (United States)
* Legal Copyright: Copyright (C) 2008-2015 Mark Russinovich
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/67
* VirusTotal Link: https://www.virustotal.com/gui/file/f1564b3c3eee87d62ef04ccf2c6b453020d3547faa2ccc5c9e2cef94fe659f2f/detection/





MIT License. Copyright (c) 2020 Strontic.


