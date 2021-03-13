---
title: livekd.exe | livekd
excerpt: What is livekd.exe?
---

# livekd.exe 

* File Path: `C:\SysinternalsSuite\livekd.exe`
* Description: livekd

## Hashes

Type | Hash
-- | --
MD5 | `CA9A18EEC3DD7543A56058975CE31987`
SHA1 | `9BB6FF0696DCAA5E164C6E31E9302E28B6EE4BFC`
SHA256 | `D705F0C95B37E801AFE698DF5F56833099F55F6563713E3B318499F579A5D1CF`
SHA384 | `97742AB55D17C72334A86559D1B728994CEED6BB2B272E246E361698251806C90FE5C27B7ECDD434B774FBF145632DB8`
SHA512 | `AEAD60A96BCB57AC9E6DA370F20ACD47174D40AF92503AFFF50A56182B6D0BF604710BFE0510ABE039B3D8FD5F340547209804C28F2444F1171B0EC2D903C27B`
SSDEEP | `24576:EDOY9CIysIR5XL7bX8o+5nfvPMQ9HlkvQW5iX5:T4pwfL7+FkYJJ`
IMP | `2EC43D81EFE93713D038B08B3F456F1F`
PESHA1 | `4C3817A705CA6E7EF92F70B2FE2D1C87D2ACD680`
PE256 | `B8D8C888FA6F87ED50790955D1CD591D4048A1060EFD25A3891E5A9F038CF2BA`

## Runtime Data

### Usage (stdout):
```cmhg

LiveKd v5.63 - Execute kd/windbg on a live system
Sysinternals - www.sysinternals.com
Copyright (C) 2000-2020 Mark Russinovich and Ken Johnson

usage:
  livekd [-w|-k debugger-path|-o dumpfile] [-m[flags]] [-mp process|pid] [-vsym] [-b] [debugger options]
  livekd [-w|-k debugger-path|-o dumpfile] -ml [-hvd] [-b] [debugger options]
  livekd -hvl
  livekd [-w|-k debugger-path|-o dumpfile] -hv guid|name [-p] [-vsym] [-b] [debugger options]
  livekd [-w|-k debugger-path] -hv guid|name -hvkl [-vsym] [-b] [debugger options]
   -hv     Specifies the name or GUID of the Hyper-V VM to debug.
   -hvd    Includes hypervisor pages (Windows 8.1 and above only).
   -hvl    Lists the names and GUIDs of running Hyper-V VMs.
   -k      Specifies complete path and filename of debugger image to execute
   -m      Creates a mirror dump, which is a consistent view of kernel memory
           Only kernel mode memory will be available, and this option may need
           significant amounts of available physical memory.  A flags mask that
           specifies which regions to include may optionally be provided (drawn
           from the following table, default 0x18F8):

           0001 - process private,  0002 - mapped file,   0004 - shared section
           0008 - page table pages, 0010 - paged pool,    0020 - non-paged pool
           0040 - system PTEs,      0080 - session pages, 0100 - metadata files
           0200 - AWE user pages,   0400 - driver pages,  0800 - kernel stacks
           1000 - WS metadata,      2000 - large pages

           The default captures most kernel memory contents and is recommended.
           This option may be used with -o to save faster, consistent dumps.
           Mirror dumps require Windows Vista or Windows Server 2008 or above.

           Sysinternals RamMap provides a graphical summary of the distribution
           of the available memory regions that can be selected for inclusion.
   -ml     Generate live dump using native support (Windows 8.1 and above only).
   -mp     Specifies a single process whose user mode memory contents should be
           included in a mirror dump.  Only effective with the -m option.
   -o      Saves a memory.dmp to disk instead of launching the debugger
   -p      Pauses the target Hyper-V VM while LiveKd is active
           (recommended for use with -o).
   -vsym   Displays verbose debugging information about symbol load operations.
   -w      Runs windbg instead of kd
   -b      Batch mode, don't prompt to execute kd again after completion

All other options are passed through to the debugger.
Note: Use Ctrl-Break to terminate and restart the debugger if it hangs.

By default LiveKd runs kd.exe.


```

### Loaded Modules:

Path |
-- |
C:\SysinternalsSuite\livekd.exe |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\wow64.dll |
C:\Windows\System32\wow64cpu.dll |
C:\Windows\System32\wow64win.dll |


## Signature

* Status: Signature verified.
* Serial: `3300000187721772155940C709000000000187`
* Thumbprint: `2485A7AFA98E178CB8F30C9838346B514AEA4769`
* Issuer: CN=Microsoft Code Signing PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Corporation, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: livekd.exe
* Product Name: Sysinternals LiveKd
* Company Name: Sysinternals - www.sysinternals.com
* File Version: 5.63
* Product Version: 5.63
* Language: English (United States)
* Legal Copyright: Copyright  2000-2020 Mark Russinovich and Ken Johnson
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/72
* VirusTotal Link: https://www.virustotal.com/gui/file/d705f0c95b37e801afe698df5f56833099f55f6563713e3b318499f579a5d1cf/detection/





MIT License. Copyright (c) 2020-2021 Strontic.


