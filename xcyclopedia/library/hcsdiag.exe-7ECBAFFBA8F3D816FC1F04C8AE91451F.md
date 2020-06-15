
# hcsdiag.exe 

* File Path: `C:\WINDOWS\system32\hcsdiag.exe`
* Description: Hyper-V Host Compute Service Diagnostics Tool
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `7ECBAFFBA8F3D816FC1F04C8AE91451F`
SHA1 | `2C53A266CDB159925A4A6C8C2E338995C30DDCE6`
SHA256 | `278D57D46FA9A5CD4098115397469270FEFA66E0B8206E242A0772CC0C064220`
SHA384 | `91AC5C6160CEA1D383C3B4789313051DA65E6211C48351BC0D3770A4AAA769E93ADF8A3C778E9330EA2D868BEB6C14ED`
SHA512 | `FA06DC906835D9F39CD76D680488FF2AB6C0168CB15B9AB09C3A2ABF158EF71370AE41E380F556BA552C0E444DD17BE21BB5AC58E3098B0715BC8712A47C52F2`
SSDEEP | `6144:WzrrbHubsHAjOccJSgz01ELJpKY07ua4ncfVirOuWqEajNC/qx:2buWAyccccKY07ua4nc0ORqdg/`

## Runtime Data

### Usage (stdout):
```Batchfile

```

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

### Child Processes:


## Signature

* Status: Signature verified.
* Serial: `330000023241FB59996DCC4DFF000000000232`
* Thumbprint: `FF82BC38E1DA5E596DF374C53E3617F7EDA36B06`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: Hyper-V Host Compute Service Diagnostics Tool
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.18362.1 (WinBuild.160101.0800)
* Product Version: 10.0.18362.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.





MIT License. Copyright (c) 2020 Strontic.


