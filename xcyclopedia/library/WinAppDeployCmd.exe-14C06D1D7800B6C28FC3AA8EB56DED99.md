---
title: WinAppDeployCmd.exe |  
excerpt: What is WinAppDeployCmd.exe?
---

# WinAppDeployCmd.exe 

* File Path: `C:\Program Files (x86)\Windows Kits\10\bin\10.0.19041.0\x86\WinAppDeployCmd.exe`
* Description:  

## Hashes

Type | Hash
-- | --
MD5 | `14C06D1D7800B6C28FC3AA8EB56DED99`
SHA1 | `1442B3002DAF5675D72041A2FB1303DBD9E136EE`
SHA256 | `F9CE7F1128015060E41C73BD78EBCB07161F069934D98E0D2743C8018CE8C9B8`
SHA384 | `77EA1CE1A9ECFF8E4BB4D609E5DE20BB2F1F3A94D178FA4E6D4F7BF43C8209CE2DBD04C4932B6E540F20792423740831`
SHA512 | `4B072E387FA7D615AFFF9857DB55F38A6DBF1BC474CA539ACD3200D8CD37BFE858FC04AB1E831D8FCBE1CD3DA16D0C11ADACDE32BD87A0509974E9ACE4B090AD`
SSDEEP | `768:afYY+d53psClc4iggeXM4wseoxRm5+XRuvjggKR1:ot+d5SClc4iggh4wsXxRm5+ovsgq1`
IMP | `F34D5F2D4577ED6D9CEEC516C1F5A744`
PESHA1 | `6F39CDF55A0C3C86619887C3E1102CB851C1970B`
PE256 | `FE0B13F5DFB42326DE70306B4FC2A0F8B748D4CBD9492BB8E6B5A87DB6BD2199`

## Runtime Data

### Usage (stdout):
```cmhg
Windows App Deployment Tool
Version 10.0.0.0
Copyright (c) Microsoft Corporation. All rights reserved.

Utility for deploying applications to remote Windows devices.

WinAppDeployCmd [command] [-ip address|-guid address] [-pin pin]
  [-option <argument>] ...

Commands:

Discovery:
    devices         Show the list of available network devices.
      WinAppDeployCmd devices [timeoutSecs]

Loose file applications:
    deployfiles     Deploy/Copy loose package files.
        Required Options: 
                    -file  Full path to the appx manifest .xml file for the app to be installed, updated, or
                    uninstalled.
                    -remotedeploydir Relative directory path/name to copy files over on remote device;
                    This will be relative to a well-known, automatically determined remote deployment folder.
        Optional:
                    -deleteextrafiles Causes the tool to delete extra files from 
                    the remote target path if they are not found in the source layout
                    -pin The paired pin generated as a result of Developer Unlocking 
                    and enabling Device Discovery on the remote device.
                    -preserveAppData Preserves app data when uninstalling an app.
        WinAppDeployCmd deployfiles -file localmanifestpath -remotedeploydir remoterelativepath 
        -ip TargetIPAddress [-deleteextrafiles]
    
    registerfiles   Register loose package files from local app layout folder.
        Required Options:
                    -remotedeploydir Relative directory path/name specified in the previous corresponding
                    deployfiles command.
        WinAppDeployCmd registerfiles -remotedeploydir RemoteRelativePath -ip TargetIPAddress
                    
Packaged Appx applications:
    install         Install a Windows app to the target device.
        Required Options: 
                    -file  Full path to the .appx or .appx bundle for the app to be installed.
        Optional:
                    -dependency Optional path to appx dependency packages
                    -requiredContentGroupOnly Only install the required content groups
        WinAppDeployCmd install -file appxpath [-dependency dep1 [dep2] [dep3] ...]
        
    update          Update a Windows app installed on the target device.
        Required Options: 
                    -file  Full path to the .appx or .appx bundle for the app to be updated.
        Optional:           
                     -requiredContentGroupOnly Only install the required content groups
        WinAppDeployCmd update -file appxpath
        
Other application utilities:
    list            Show the list of app packages installed on the target
                    device. Handy to retrieve package name assigned when registering loose files
                    to use in the subsequent uninstall command.
        WinAppDeployCmd list             
        
    uninstall       Uninstall the specified appx package from the target
                    device.
        Required Options:
                    -package Name of the appx
        Optional:
                    -preserveAppData Preserves app data when uninstalling an app.
        WinAppDeployCmd uninstall -package pkgname [-preserveAppData]
        
Commands to help with deploying/registering applications from a remote network share:
    addcreds        Add network credentials for the target to use when running
                    an application from a network share.
        Required Options:
                    -credserver hostname of the remote share or server
                    -credusername username associated with the remote share/server
                    -credpassword password associated witht the remote share/server credentials
        WinAppDeployCmd addcreds -credserver server -credusername username -credpassword password            
        
    getcreds        Get network credentials for the target uses when running
                    an application from a network share.
        Required Options:
                    -credserver hostname of the remote share or server
        WinAppDeployCmd getcreds -credserver server
        
    deletecreds     Delete network credentials the target uses when running an
                    application from a network share.
        Required Options:
                    -credserver hostname of the remote share or server
       WinAppDeployCmd deletecreds -credserver server

Options: (Details)
    -h -help        Show this screen.
    -ip             IP address of the target device
    -g -guid        Unique identifier of the target device
    -d -dependency  Optional to specify the dependency path for each of the
                    package dependencies. If none are specified, by default,
                    this tool will search for dependencies in the app root and
                    SDK directories.
    -f -file        File path for the app package to be installed, updated, or
                    uninstalled.
    -p -package     The Package Full Name for the app package to be
                    uninstalled. You can use the list command to find the
                    names for packages already installed on the device.
    -pin            A pin may be required to establish connection with the
                    target device. You will be prompted to retry with -pin
                    option if authentication is required.
    -credserver     The server name of the network credentials for use by the
                    target.
    -credusername   The user name of the network credentials for use by the
                    target.
    -credpassword   The password of the network credentials for use by the
                    target.
    -connecttimeout The timeout in seconds that should be used for sync Connect() calls to 
                    the remote device.
    -remotedeploydir  Relative directory path/name to copy files over on remote device; This will be
                    relative to a well-known, automatically determined remote deployment folder.
    -deleteextrafile Switch to indicate whether existing files in the remote directory should be purged to match the source directory
    
Examples:
    WinAppDeployCmd devices 10
    WinAppDeployCmd deployfiles -file c:\apps\App1\AppxManifest.xml -remotedeploydir app1_F5 -ip 192.168.0.1 [-pin userpin]
    WinAppDeployCmd registerfiles -remotedeploydir app1_F5 -ip 192.168.0.1
    WinAppDeployCmd install -file "Downloads\SampleApp.appx" -ip 192.168.0.1 [-dependency c:\temp\dep\x86\*.appx]
    WinAppDeployCmd update -file "Downloads\SampleApp.appx" -ip 192.168.0.1
    WinAppDeployCmd list -ip 192.168.0.1
    WinAppDeployCmd uninstall -package Company.SampleApp_1.0.0.1_x64__qwertyuiop -ip 192.168.0.1
    WinAppDeployCmd addcreds -credserver myserver -credusername myname -credpassword mypassword -ip 192.168.0.1
    WinAppDeployCmd getcreds -credserver myserver -ip 192.168.0.1
    WinAppDeployCmd deletecreds -credserver myserver -ip 192.168.0.1
   

```

### Loaded Modules:

Path |
-- |
C:\Program Files (x86)\Windows Kits\10\bin\10.0.19041.0\x86\WinAppDeployCmd.exe |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\wow64.dll |
C:\Windows\System32\wow64cpu.dll |
C:\Windows\System32\wow64win.dll |


## Signature

* Status: The file C:\Program Files (x86)\Windows Kits\10\bin\10.0.19041.0\x86\WinAppDeployCmd.exe is not digitally signed. You cannot run this script on the current system. For more information about running scripts and setting execution policy, see about_Execution_Policies at https:/go.microsoft.com/fwlink/?LinkID=135170
* Serial: ``
* Thumbprint: ``
* Issuer: 
* Subject: 

## File Metadata

* Original Filename: WinAppDeployCmd.exe
* Product Name: Microsoft (R) Windows (R) Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1
* Product Version: 10.0.19041.1
* Language: Language Neutral
* Legal Copyright: Copyright (c) Microsoft Corporation. All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: Unknown





MIT License. Copyright (c) 2020-2021 Strontic.


