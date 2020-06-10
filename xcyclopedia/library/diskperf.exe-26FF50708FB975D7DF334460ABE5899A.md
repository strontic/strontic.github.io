
# diskperf.exe 
* File Path: `C:\Windows\system32\diskperf.exe`
* Description: Disk Performance Configuration Utility
* Comments: 

## Hashes
Type | Hash
-- | --
MD5 | `26FF50708FB975D7DF334460ABE5899A`
SHA1 | `CC45C6D879622CD9810467930A93684F33952D3D`
SHA256 | `BFAA29161F3A1C6B7E427EA7A7BD39FCF47BF84448B3800E2ED686B062453F71`
SHA384 | `06A85DDCC755F5B3C2C7E1FFB31529D4CC1D6DAFD058E736F3228F9DE70C11C160885BC62BC400D66DF99E552E7EBCE3`
SHA415 | `A10BE643CC0C0A6A8BE85B4D667E502A0B7DF0F03630CBE39B4CB1A339E605BF697022C66275FA37BB96271158C1FEA6C5380F71FDC71D9C93A817C19EAF8DB1`
SSDEEP | `384:79rok9TCGqAaRXvKnORtGbUfjSXRy5goyiOMNbZNisLP9eJ9W8JW:7T9TCGqAQKnORX0iiiOMNzimP9m9`

## Runtime Data
### Usage (stdout):
```Batchfile


DISKPERF=====================

Starts and stops system disk performance counters.

Used without the command switches, DISKPERF reports what disk
performance counters are enabled on the specified Windows 2000 computer.

Disk performance counters can be specified to report the
performance of the individual physical drives, or the individual
logical drives or storage volumes. Note that these two sets of
performance counters are measured independently. The user
has the option of enabling and disabling them independently
using the command line switches.
NOTE: This command can only be used to control remote
Windows 2000 systems. In newer systems, these performance counters
are automatically enabled.

DISKPERF [-Y[D|V] | -N[D|V]] [\\computername]

  -Y  Sets the system to start all disk performance counters
      when the system is restarted.

  -YD Enables the disk performance counters for physical drives.
      when the system is restarted.
  -YV Enables the disk performance counters for logical drives
      or storage volumes when the system is restarted.
  -N  Sets the system to disable all disk performance counters
      when the system is restarted.

  -ND Disables the disk performance counters for physical drives.
  -NV Disables the disk performance counters for logical drives.
  \\computername        Is the name of the computer you want to
                        see or set disk performance counter use.
                        The computer must be a Windows 2000 system.
  NOTE: Disk performance counters are permanently enabled on
        systems beyond Windows 2000.

```

### Usage (stderr):
```Batchfile

```

### Child Processes:


## Signature

* Status: Signature verified.
* Serial: 33000000BCE120FDD27CC8EE930000000000BC
* Thumbprint: E85459B23C232DB3CB94C7A56D47678F58E8E51E
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: DISKPERF.EXE.MUI
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.14393.0 (rs1_release.160715-1616)
* Product Version: 10.0.14393.0
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.


