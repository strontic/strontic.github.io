---
title: psshutdown.exe | Shutdown, logoff and power manage local and remote systems
excerpt: What is psshutdown.exe?
---

# psshutdown.exe 

* File Path: `C:\SysinternalsSuite\psshutdown.exe`
* Description: Shutdown, logoff and power manage local and remote systems

## Hashes

Type | Hash
-- | --
MD5 | `6AA0305AF2C055AC6C94B5D24F6CEC35`
SHA1 | `1F0A68FA8ABE3ABBEDB2D52B24FD805AEB90F2F1`
SHA256 | `66885C2B1773A6D02C3937E67B94B786FC64AF17A7E8BAD050BE5149092A0117`
SHA384 | `4108A56FB8D4F2858C9A2DCEE820FA6EC897DB741E304952801E4AF7F4A5E8592F7278EAFA4BD883EFA49A2CBDF98A9C`
SHA512 | `16AC378BDC6630B39A43BDB2E831852E2ADF162F13824BFE80660BF41F786E58766AFEF0D23CAFA24D6C5F2F5C98A1D7E74C4849DFC136442F64020E3F73C85D`
SSDEEP | `3072:c1j29ITWXL5vjJngtJVcKkPzhwrbttgqWtjW/TxOZ2:ga9IT8hwJkPzhwrHFiW7+2`
IMP | `02069CDEB9EBC09DA43E4D2CD0D07E53`
PESHA1 | `6AEC9BC06A850530070BD56B7AE5D27ABBBA65E2`
PE256 | `832D39E55A90E8D0A67D7BC34618D1426F76E2DCB0979AF5209F6D72DE3E9BDB`

## Runtime Data

### Usage (stdout):
```cmhg
usage:
psshutdown -s|-r|-h|-d|-k|-a|-l|-o [-f] [-c] [-t [nn|h:m]] [-v nn] [-e [u|p]:xx:yy] [-m "message"] [-u Username [-p password]] [-n s] [\\computer[,computer[,...]|@file]
   -a          Abort a shutdown (only possible while countdown is in progress)
   -c          Allow the shutdown to be aborted by the interactive user
   -d          Suspend the computer
   -e          Shutdown reason code (available on Windows XP and higher).
               Specify 'u' for unplanned and 'p' for planned
               shutdown reason codes.
               xx is the major reason code (must be less than 256)
               yy is the minor reason code (must be less than 65536)
   -f          Forces running applications to close
   -h          Hibernate the computer
   -k          Poweroff the computer (reboot if poweroff is not supported)
   -l          Lock the computer
   -m          Message to display to logged on users
   -n          Specifies timeout in seconds connecting to remote computers
   -o          Logoff the console user
   -p          Specifies optional password for user name. If you omit this
               you will be prompted to enter a hidden password.
   -r          Reboot after shutdown
   -s          Shutdown without poweroff
   -t          Specifies countdown in seconds until shutdown (default is 20) or
               the time of shutdown (in 24 hour notation)
   -u          Specifies optional user name for login to remote
               computer.
   -v          Display message for the specified number of seconds before
               the shutdown. If you omit this parameter the shutdown
               notification dialog displays and specifying a value of 0
               omits the dialog.
   computer    Shutdown the computer or computers specified
   @file       Shutdown the computers listed in the file specified


Reasons defined on this computer (U = unplanned, P = planned):
Type   Major   Minor   Title
  U      0       0     Other (Unplanned)
  P      0       0     Other (Planned)
  U      1       1     Hardware: Maintenance (Unplanned)
  P      1       1     Hardware: Maintenance (Planned)
  U      1       2     Hardware: Installation (Unplanned)
  P      1       2     Hardware: Installation (Planned)
  U      2       2     Operating System: Recovery (Unplanned)
  P      2       2     Operating System: Recovery (Planned)
  P      2       3     Operating System: Upgrade (Planned)
  U      2       4     Operating System: Reconfiguration (Unplanned)
  P      2       4     Operating System: Reconfiguration (Planned)
  P      2      16     Operating System: Service pack (Planned)
  U      2      17     Operating System: Hot fix (Unplanned)
  P      2      17     Operating System: Hot fix (Planned)
  U      2      18     Operating System: Security fix (Unplanned)
  P      2      18     Operating System: Security fix (Planned)
  U      4       1     Application: Maintenance (Unplanned)
  P      4       1     Application: Maintenance (Planned)
  P      4       2     Application: Installation (Planned)
  U      4       5     Application: Unresponsive
  U      4       6     Application: Unstable
  U      5      19     Security issue (Unplanned)
  P      5      19     Security issue (Planned)
  U      5      20     Loss of network connectivity (Unplanned)
  P      7       0     Legacy API shutdown


```

### Usage (stderr):
```cmhg

PsShutdown v2.52 - Shutdown, logoff and power manage local and remote systems
Copyright (C) 1999-2006 Mark Russinovich
Sysinternals - www.sysinternals.com


```

### Loaded Modules:

Path |
-- |
C:\SysinternalsSuite\psshutdown.exe |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\wow64.dll |
C:\Windows\System32\wow64cpu.dll |
C:\Windows\System32\wow64win.dll |


## Signature

* Status: Signature verified.
* Serial: `61469ECB000400000065`
* Thumbprint: `564E01066387F26C912010D06BD78D3CF1E845AB`
* Issuer: CN=Microsoft Code Signing PCA, OU=Copyright (c) 2000 Microsoft Corp., O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Corporation, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: psshutdown.exe
* Product Name: Sysinternals PsShutdown
* Company Name: Sysinternals - www.sysinternals.com
* File Version: 2.52
* Product Version: 2.52
* Language: English (United States)
* Legal Copyright: Copyright (C) 1999-2006 Mark Russinovich
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/69
* VirusTotal Link: https://www.virustotal.com/gui/file/66885c2b1773a6d02c3937e67b94b786fc64af17a7e8bad050be5149092a0117/detection/





MIT License. Copyright (c) 2020-2021 Strontic.


