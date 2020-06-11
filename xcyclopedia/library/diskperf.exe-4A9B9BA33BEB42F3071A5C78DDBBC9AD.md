
# diskperf.exe 

* File Path: `C:\WINDOWS\system32\diskperf.exe`
* Description: Disk Performance Configuration Utility
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `4A9B9BA33BEB42F3071A5C78DDBBC9AD`
SHA1 | `51B85BEF571A443CE02DBCB987BC4C0CC20279E6`
SHA256 | `B75F91AB4BB8411EE2C01C3F80E8565257AC223B9755276797AFCAB0A0FE0B3B`
SHA384 | `A9D5FC42450F97E4D2180D7519CED906DF5D28737E69892C1F1BF46B669AF0A67844985BB632CC6C5B90F1EA9C5DF594`
SHA415 | `6DBE69D4327218EE2896B4DD0664B2EF5D810C88CC7AEDD7D3FD28AA024F805723273D03B6A3E38C3272D530BF8C516BDA04D9B947C811E80689228459E4CE01`
SSDEEP | `384:9xEB938kEwctfXzJDpetM47N7WfMbyAAiZgiOMVAsNq4KerZ4lMFWuJW:9BkE9JDpepWAAOgiOMV5ZKgZ4yr`

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
* Serial: 330000023241FB59996DCC4DFF000000000232
* Thumbprint: FF82BC38E1DA5E596DF374C53E3617F7EDA36B06
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: DISKPERF.EXE.MUI
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.18362.1 (WinBuild.160101.0800)
* Product Version: 10.0.18362.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.

MIT License. Copyright (c) 2020 Strontic.


