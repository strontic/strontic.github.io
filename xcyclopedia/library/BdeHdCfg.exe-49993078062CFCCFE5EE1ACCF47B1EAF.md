
# BdeHdCfg.exe 
* File Path: `C:\WINDOWS\system32\BdeHdCfg.exe`
* Description: BitLocker Drive Encryption: Drive Preparation Tool
* Comments: 

## Hashes
Type | Hash
-- | --
MD5 | `49993078062CFCCFE5EE1ACCF47B1EAF`
SHA1 | `34597C2BF5FA0BD247C74195B4D5A06FFD8BC461`
SHA256 | `B513A5CFF54702917DE47ADC85E717BAD75ADA41967253A55FB928365DF2E020`
SHA384 | `06CA05C82F119FC12922D0B20F9F02F2D9CD1218472D1C8790427F8EAC5AD0A940EB79440289D4BC595BF740E31B73D2`
SHA415 | `AA832DF6A6EC05C915EF5798B7577F5FF0968C4A2449D9019ABFF2FA64B61E502CFEBAAFE05D523CF5882E2C780BAB21DC331083BB15852ABD3D0D440157CC5E`
SSDEEP | `3072:qVSiRmzT/b1a+PKHVZzwnVS570M9kdatGCO+xmBc+hMPhPsx:q8x3KHVZ8Vs7nyatGt+SYF`

## Runtime Data
### Usage (stdout):
```Batchfile
BitLocker Drive Preparation Tool version 10.0.18362
Copyright (C) 2013 Microsoft Corporation. All rights reserved.

Usage:

BdeHdCfg[.exe] 
               [-driveinfo]
               [-target {default | unallocated | 
                         TargetDriveLetter {shrink | merge}}]
               [-newdriveletter DriveLetter]
               [-size SizeInMegabytes]
               [-quiet] [-restart] [{-? | /?}]

Description:
  This command prepares your hard drive for BitLocker Drive Encryption.

  Command line parameters are not case-sensitive.

Parameters:
  -driveinfo
        Displays information about valid target drives.

  -target
        Specifies the target and operation.

        Specify 'shrink' to create a new active partition.
        Specify 'merge' to make an existing partition active.
        Specify 'unallocated' to use unformatted space on disk.
        Specify 'default' for the target to be chosen automatically.

        Examples: -target D: merge
                  -target C: shrink
                  -target unallocated
                  -target default

  -newdriveletter
        Specifies the desired drive letter for the new drive. This option is
        only valid when a new drive is created.

        Example: -newdriveletter S:

  -size
        Specifies the desired size of the new drive. This option is only valid
        when a new drive is created.

        If not specified, the Drive Preparation Tool assumes the required
        minimum size of 550 megabytes.

        Example: -size 700
        
  -quiet
        Specifies operation in quiet mode. No output from the drive preparation
        tool is displayed.

  -restart
        Enables an automatic restart after drive preparation.

        You must restart your computer before enabling BitLocker.

  -? or /?
        Displays help for this command.

Examples:
    BdeHdCfg -target c: shrink -newdriveletter x: -size 550 -quiet -restart
    BdeHdCfg -target d: merge -quiet -restart
    BdeHdCfg -target unallocated -newdriveletter s:
    BdeHdCfg -target default


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

* Original Filename: BdeHdCfg.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.18362.1 (WinBuild.160101.0800)
* Product Version: 10.0.18362.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.


