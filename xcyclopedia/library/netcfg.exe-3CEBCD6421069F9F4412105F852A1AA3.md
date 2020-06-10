
# netcfg.exe 
* File Path: `C:\Windows\system32\netcfg.exe`
* Description: WinPE network installer
* Comments: 

## Hashes
Type | Hash
-- | --
MD5 | `3CEBCD6421069F9F4412105F852A1AA3`
SHA1 | `BF8377E84F2159371CD1D4FA79DADB1AE06239D5`
SHA256 | `86AE098BDE1D1B9541FC66D8E066327B73BD220218E75DD2C26FA1D50A585C34`
SHA384 | `9F3859AD4EE5468DE2EA81B0352283AF2D8577A2589EAC7512444F3EF8FA938AAEDEA25B29AB2D4FF763EE6A488EA8BD`
SHA415 | `6919FAF0BC28FCCA53649DEDD1F68B6976168189EE5A8DE91B4DF1641229176F8F986B0FC1284F89BA33F774724A3025556DB21F26D57BB2C5857893952DFB0D`
SSDEEP | `768:S31r3JIFs6fiWR6faRjMW3z6bVm0o/tf:SJ5es4iWXBp6bVbEf`

## Runtime Data
### Usage (stdout):
```Batchfile
netcfg [-v] [-winpe] [-l <full-path-to-component-INF>] -c <p|s|c> 
       -i <comp-id>
    
    -winpe installs TCP/IP, NetBIOS and Microsoft Client for Windows 
           preinstallation environment
    -l	   provides the location of INF
    -c	   provides the class of the component to be installed (p == Protocol, 
           s == Service, c == Client)
    -i	   provides the component ID

    The arguments must be passed in the order shown.

    Examples:
    
    netcfg -l c:\oemdir\myprot.inf -c p -i myprot
    
        Installs protocol 'myprot' using c:\oemdir\myprot.inf

    netcfg -c s -i MS_Server
     
        Installs service 'MS_Server'
 
OR

netcfg [-v] -winpe

    Example:
    
    netcfg -v -winpe

        Installs TCP/IP, NetBIOS, and Microsoft Client for Windows 
        preinstallation environment

OR

netcfg [-v] -q <comp-id>

    Example:
    
    netcfg -q MS_IPX
    
        Displays if component 'MS_IPX' is installed

OR

netcfg [-v] -u <comp-id>

    Example:

    netcfg -u MS_IPX

        Uninstalls component 'MS_IPX'

OR

netcfg [-v] -s <a|n>

    -s  provides the type of components to show (a == adapters, 
        n == net components)

    Example:
    
    netcfg -s n

        Shows all installed net components

OR

netcfg [-v] -b <comp-id>

    Example:

    netcfg -b ms_tcpip

        Shows binding paths containing 'MS_TCPIP'

OR

netcfg [-v] -m

    Example:

    netcfg -m 

        Outputs the binding map to NetworkBindingMap.txt in the current directory.
        -v will also display the binding map to the console.

OR

netcfg -d

    Example:

    netcfg -d

        Performs a cleanup on all networking devices.
		This will require a reboot.

OR

netcfg -x

    Example:

    netcfg -x

        Performs a cleanup on networking devices, skipping those without physical
        object names.
		This will require a reboot.

General Notes:
  -v	Run in verbose (detailed) mode
  -?	Displays this help information


```

### Usage (stderr):
```Batchfile

```

### Child Processes:


## Signature

* Status: Signature verified.
* Serial: 3300000266BD1580EFA75CD6D3000000000266
* Thumbprint: A4341B9FD50FB9964283220A36A1EF6F6FAA7840
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: netcfg.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.14393.0 (rs1_release.160715-1616)
* Product Version: 10.0.14393.0
* Language: Language Neutral
* Legal Copyright:  Microsoft Corporation. All rights reserved.


