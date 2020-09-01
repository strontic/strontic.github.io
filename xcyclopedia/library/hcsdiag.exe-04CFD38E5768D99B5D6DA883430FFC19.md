---
title: hcsdiag.exe | Hyper-V Host Compute Service Diagnostics Tool
---

# hcsdiag.exe 

* File Path: `C:\Windows\system32\hcsdiag.exe`
* Description: Hyper-V Host Compute Service Diagnostics Tool

## Hashes

Type | Hash
-- | --
MD5 | `04CFD38E5768D99B5D6DA883430FFC19`
SHA1 | `53AA9BB4494BE3C831E7A482FEEB617E58248A1B`
SHA256 | `22BF5143FA2B7B4E8CE0A8FD7A54354B7729D72B34F9BACA2B3844717C2FBBB1`
SHA384 | `093B76E61BF225808F7327692B0914E10C4C4D7BBD32B425BCEA8D6B511276A6A1EE9C683C074EC3D1697661F24A67EC`
SHA512 | `4BA72D96813B0B85189A35EA04C5E94F4F21E6C36863E0EFA25258A45EBECB8AD07FA24FE837A17949063B2ADBDE42D91864A8A3B8B4128C226C6825B33DE353`
SSDEEP | `6144:3Axd0mvvdMRSw24rNGniPiKZm2SlDbd3vx/kQnlm:qBvvKSw2RiXZm2+DNx/1E`

## Runtime Data

### Usage (stderr):
```Batchfile
Copyright (c) Microsoft Corporation. All rights reserved.

  hcsdiag <command> [options...]

  list
    Lists running containers and VMs.

  exec [-uvm] <id> <command line>
    Executes a process inside the container.

  console [-uvm] <id> [command line]
    Launches an interactive console inside the container.

  read [-uvm] <id> <container file> [host file]
    Reads a file from the container and outputs it to standard output or a file.

  write [-uvm] <id> [host file] <container file>
    Writes from standard input or a host file to a file in the container.

  kill <id>
    Terminates a running container.

  share [-uvm] [-readonly] [-asuser] [-port <portnumber>] <id> <host folder> <container folder>
    Shares a host folder into the container.

  vhd [-uvm] <id> <host vhdx file> <container folder>
    Shares a virtual hard disk file into the container.

  crash <id>
    Forces a crash of the virtual machine hosting the container (only works
    for containers hosted in a virtual machine).

```

### Loaded Modules:

Path |
-- |
C:\program files\HandBrake\HandBrake.exe |
C:\Windows\Microsoft.NET\Framework64\v4.0.30319\clr.dll |
C:\Windows\Microsoft.NET\Framework64\v4.0.30319\mscoreei.dll |
C:\Windows\System32\ADVAPI32.dll |
C:\Windows\System32\GDI32.dll |
C:\Windows\System32\gdi32full.dll |
C:\Windows\System32\IMM32.DLL |
C:\Windows\SYSTEM32\kernel.appcore.dll |
C:\Windows\System32\KERNEL32.dll |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\SYSTEM32\MSCOREE.DLL |
C:\Windows\System32\msvcp_win.dll |
C:\Windows\System32\msvcrt.dll |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\RPCRT4.dll |
C:\Windows\System32\sechost.dll |
C:\Windows\System32\SHLWAPI.dll |
C:\Windows\System32\ucrtbase.dll |
C:\Windows\SYSTEM32\ucrtbase_clr0400.dll |
C:\Windows\System32\USER32.dll |
C:\Windows\SYSTEM32\VCRUNTIME140_CLR0400.dll |
C:\Windows\SYSTEM32\VERSION.dll |
C:\Windows\System32\win32u.dll |


## Signature

* Status: Signature verified.
* Serial: `33000001C422B2F79B793DACB20000000001C4`
* Thumbprint: `AE9C1AE54763822EEC42474983D8B635116C8452`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: Hyper-V Host Compute Service Diagnostics Tool
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.17763.1 (WinBuild.160101.0800)
* Product Version: 10.0.17763.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.





MIT License. Copyright (c) 2020 Strontic.


