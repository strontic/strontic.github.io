
# repair-bde.exe 

* File Path: `C:\WINDOWS\system32\repair-bde.exe`
* Description: BitLocker Drive Encryption: Repair Tool
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `7DE31602235A9B4A6C1EBCFB6E6E30E2`
SHA1 | `F323C9B4736505CBC949131F94C3A67290F8AC2C`
SHA256 | `58FC9D6F60E1B7B71132D3DB606011944B92D495E2BDFD61DE93A64A5D90C076`
SHA384 | `B00F0B0E25CAEBC71973321E4AD70170DC6CA343C6E08D36B9CF146CA09EE2ABD4A0FBCFCCE4A291DC0400FDD031A62B`
SHA415 | `71F9608FF33A75712BFE021B0E08D110968A36B89F9DBEB5B1D4DBAB23573D2FCB935743FC118AF4AC6CA5248251B73D0E919DCFC863CFF1AD4BE2316DE3366E`
SSDEEP | `3072:Gop5uhhKvlD1aAEwnVS570M9kdatGCO+xmBc+hMPhPsx:Gop5uDKFzVs7nyatGt+SYF`

## Runtime Data

### Usage (stdout):
```Batchfile
BitLocker Drive Encryption: Repair Tool version 10.0.18362
Copyright (C) 2013 Microsoft Corporation. All rights reserved.

Usage:

repair-bde[.exe] InputVolume
                  { OutputVolumeOrImage }
                  { {-RecoveryPassword|-rp} NumericalPassword |
                    {-RecoveryKey|-rk} PathToExternalKeyFile |
                    {-Password|-pw} }
                  [{-KeyPackage|-kp} PathToKeyPackage]
                  [{-LogFile|-lf} PathToLogFile]
                  [{-?|/?}]

Description:
  Attempts to repair or decrypt a damaged BitLocker-encrypted volume using the
  supplied recovery information. If BitLocker was in the process of encryption
  or decryption or had been suspended prior to volume failure a clear key will
  be present on the volume. Repair-bde attempts to use this clear key by
  default if another key is not specified.

  WARNING! To avoid additional data loss, you should have a spare hard drive
  available. Use this spare drive to store decrypted output or to back up the
  contents of the damaged volume.  

Parameters:
  InputVolume
                The BitLocker-encrypted volume to repair.
                Example: "C:",
                         "\\?\Volume{00000000-0000-0000-0000-000000000000}".

  OutputVolumeOrImage
                The volume to store decrypted contents, or the file
                location to create an image file of the contents.
                Examples: "D:", "D:\imagefile.img".
                
                WARNING! All information on this output volume will be
                overwritten.

  -rk  or -RecoveryKey
                Provide an external key to unlock the volume. 
                Example: "F:\RecoveryKey.bek".

  -rp  or -RecoveryPassword
                Provide a numerical password to unlock the volume.
                Example: "111111-222222-333333-...".

  -pw  or -Password
                Provide a password to unlock the volume.

  -kp  or -KeyPackage
                Optional. Provide a key package to unlock the volume.
                Example: "F:\ExportedKeyPackage"
                
            If this option is blank, the tool will look for the key package
            automatically. This option is needed only if required by the tool.
	
  -lf  or -LogFile
                Optional. Provide a path to a file that will store progress
                information. Example: "F:\log.txt".

  -f   or -Force
                Optional. When used, forces a volume to be dismounted even if
                it cannot be locked. This option is needed only if required by
                the tool.

  -?   or /?    
                Shows this screen.

Examples:
  repair-bde C: D: -rk F:\RecoveryKey.bek -Force
  repair-bde C: D: -rp 111111-222222-[...] -lf F:\log.txt
  repair-bde C: D: -kp F:\KeyPackage -rp 111111-222222-[...]
  repair-bde C: D:\imagefile.img -kp F:\KeyPackage -rk F:\RecoveryKey.bek
  repair-bde C: D: -pw


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

* Original Filename: repair-bde.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.18362.1 (WinBuild.160101.0800)
* Product Version: 10.0.18362.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.

MIT License. Copyright (c) 2020 Strontic.


