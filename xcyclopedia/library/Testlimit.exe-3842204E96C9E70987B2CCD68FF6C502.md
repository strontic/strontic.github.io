---
title: Testlimit.exe | Test Windows Limits
excerpt: What is Testlimit.exe?
---

# Testlimit.exe 

* File Path: `C:\SysinternalsSuite\Testlimit.exe`
* Description: Test Windows Limits

## Hashes

Type | Hash
-- | --
MD5 | `3842204E96C9E70987B2CCD68FF6C502`
SHA1 | `ABE651E98F2EDD2DC4449E66EEE7E37C733E2E50`
SHA256 | `81CE87149A14C466738903B6180D9B79EC8D3005C137870A05DAFA815714D394`
SHA384 | `DAF2A193950530C5A6E72139CDB9D9748F5CA91623C7856D017E4FDF79E58777840DCA3F25F2DD8D3E3FD958B56B83AA`
SHA512 | `95A5D7D1041FF156FB091FCF0BA3644E494E06A2E14E11D98B19EE874BB4DF521AF83F4D98AD01465D0D89F152991E94C92196FB31AE633D9311CF46D30C10C0`
SSDEEP | `3072:AR8o9cvNCRslkfw+v0OZKiphWnk0lnZUF4NLLY8hZdTycwvInEQkJ/:ARZdq+v0494xJV3CJ/`
IMP | `5B0D2C8A351C6D461AD97A49997CF8BA`
PESHA1 | `A58C77FD6F1D415A1DCD56FB65AD1073FBF06BE3`
PE256 | `5805B2EBE7BD89B69E8EFD732F68A7454A04FB2FC804D5663774501F964C3B10`

## Runtime Data

### Usage (stdout):
```cmhg

Testlimit v5.24 - test Windows limits
Copyright (C) 2012-2015 Mark Russinovich 
Sysinternals - www.sysinternals.com

Process ID: 5944

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
C:\SysinternalsSuite\Testlimit.exe |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\wow64.dll |
C:\Windows\System32\wow64cpu.dll |
C:\Windows\System32\wow64win.dll |


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
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/70
* VirusTotal Link: https://www.virustotal.com/gui/file/81ce87149a14c466738903b6180d9b79ec8d3005c137870a05dafa815714d394/detection/





MIT License. Copyright (c) 2020 Strontic.


