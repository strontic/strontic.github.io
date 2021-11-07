---
title: Dism.exe | Dism Image Servicing Utility
excerpt: What is Dism.exe?
---

# Dism.exe 

* File Path: `C:\Windows\system32\Dism.exe`
* Description: Dism Image Servicing Utility

## Hashes

Type | Hash
-- | --
MD5 | `34E5C4F6C39482EAA98A952DEF864735`
SHA1 | `18FF045B29EDE2374790D4D1E32AC4B59197D0A7`
SHA256 | `769FE00942EB716EC99A7947CAB6B4C8B0647936C01AA27BC249BBEC61DE82B5`
SHA384 | `EBC7202C00957C47F6EC540A584DCA3D87E3FA42270C98E2D54C6EE1A8AEF367DB7EA4816F0F5B463C63AD76E4667805`
SHA512 | `BA8A04F0D161C08C94AFCC11DD55A643689F87E5DD6EEDA1918478A4F8AC1486111EA15FF7D7DF653A8A614A0EF03966D4BA41BFB570611BB6344FA3D3178FA5`
SSDEEP | `3072:CC2XHiiwoxmlb9nKVOx87DDYAsn0qI6r7RW0JjIEoY68C2pM/7WJVrbXu:4H5wXsTOI+lW0uY68C2CAri`
IMP | `7BDAA6809ABE1512EF489728EEBD5989`
PESHA1 | `509D93DAA9FEBF7189FC97EC92B85C6098964E09`
PE256 | `FC1D1594EDBB85A5212AB10FDA5122E5B92D373E076303D94161841AF5B5FCC1`

## Runtime Data

### Usage (stdout):
```cmhg

Deployment Image Servicing and Management tool
Version: 10.0.19041.572


DISM.exe [dism_options] {Imaging_command} [<Imaging_arguments>]
DISM.exe {/Image:<path_to_offline_image> | /Online} [dism_options] 
         {servicing_command} [<servicing_arguments>]

DESCRIPTION:

  DISM enumerates, installs, uninstalls, configures, and updates features
  and packages in Windows images. The commands that are available depend 
  on the image being serviced and whether the image is offline or running.


GENERIC IMAGING COMMANDS:

  /Split-Image            - Splits an existing .wim file into multiple 
                            read-only split WIM (SWM) files.
  /Apply-Image            - Applies an image.
  /Get-MountedImageInfo   - Displays information about mounted WIM and VHD
                            images.
  /Get-ImageInfo          - Displays information about images in a WIM, a VHD
                            or a FFU file.
  /Commit-Image           - Saves changes to a mounted WIM or VHD image.
  /Unmount-Image          - Unmounts a mounted WIM or VHD image.
  /Mount-Image            - Mounts an image from a WIM or VHD file.
  /Remount-Image          - Recovers an orphaned image mount directory.
  /Cleanup-Mountpoints    - Deletes resources associated with corrupted
                            mounted images.

WIM COMMANDS:

  /Apply-CustomDataImage  - Dehydrates files contained in the custom data image.
  /Capture-CustomImage    - Captures customizations into a delta WIM file on a 
                            WIMBoot system. Captured directories include all 
                            subfolders and data.
  /Get-WIMBootEntry       - Displays WIMBoot configuration entries for the 
                            specified disk volume.
  /Update-WIMBootEntry    - Updates WIMBoot configuration entry for the 
                            specified disk volume.
  /List-Image             - Displays a list of the files and folders in a 
                            specified image.
  /Delete-Image           - Deletes the specified volume image from a WIM file
                            that has multiple volume images.
  /Export-Image           - Exports a copy of the specified image to another
                            file.
  /Append-Image           - Adds another image to a WIM file.
  /Capture-Image          - Captures an image of a drive into a new WIM file.
                            Captured directories include all subfolders and 
                            data.
  /Get-MountedWimInfo     - Displays information about mounted WIM images.
  /Get-WimInfo            - Displays information about images in a WIM file.
  /Commit-Wim             - Saves changes to a mounted WIM image.
  /Unmount-Wim            - Unmounts a mounted WIM image.
  /Mount-Wim              - Mounts an image from a WIM file.
  /Remount-Wim            - Recovers an orphaned WIM mount directory.
  /Cleanup-Wim            - Deletes resources associated with mounted WIM 
                            images that are corrupted.

FFU COMMANDS:

  /Capture-Ffu            - Captures a physical disk image into a new FFU file.
  /Apply-Ffu              - Applies an .ffu image.
  /Split-Ffu              - Splits an existing .ffu file into multiple read-only
                            split FFU files.
  /Optimize-Ffu           - Optimizes a FFU file so that it can be applied to storage 
                            of a different size.

IMAGE SPECIFICATIONS:

  /Online                 - Targets the running operating system.
  /Image                  - Specifies the path to the root directory of an
                            offline Windows image.

DISM OPTIONS:

  /English                - Displays command line output in English.
  /Format                 - Specifies the report output format.
  /WinDir                 - Specifies the path to the Windows directory.
  /SysDriveDir            - Specifies the path to the system-loader file named
                            BootMgr.
  /LogPath                - Specifies the logfile path.
  /LogLevel               - Specifies the output level shown in the log (1-4).
  /NoRestart              - Suppresses automatic reboots and reboot prompts.
  /Quiet                  - Suppresses all output except for error messages.
  /ScratchDir             - Specifies the path to a scratch directory.

For more information about these DISM options and their arguments, specify an
option immediately before /?.

  Examples:     
    DISM.exe /Mount-Wim /?
    DISM.exe /ScratchDir /?
    DISM.exe /Image:C:\test\offline /?
    DISM.exe /Online /?



```

### Loaded Modules:

Path |
-- |
C:\Windows\system32\Dism.exe |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\SYSTEM32\ntdll.dll |


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: DISM.EXE.MUI
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/76
* VirusTotal Link: https://www.virustotal.com/gui/file/769fe00942eb716ec99a7947cab6b4c8b0647936c01aa27bc249bbec61de82b5/detection


## Possible Misuse

*The following table contains possible examples of `Dism.exe` being misused. While `Dism.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_user_driver_loaded.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/builtin/win_user_driver_loaded.yml) | `- '\Windows\System32\Dism.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_creation_system_file.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/file_event/sysmon_creation_system_file.yml) | `Image\|endswith: '\Windows\System32\dism.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_uac_bypass_via_dism.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/image_load/sysmon_uac_bypass_via_dism.yml) | `- '\dism.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_uac_bypass_ntfs_reparse_point.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_uac_bypass_ntfs_reparse_point.yml) | `ParentCommandLine: '"C:\Windows\system32\dism.exe" /online /quiet /norestart /add-package /packagepath:"C:\Windows\system32\pe386" /ignorecheck'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_uac_bypass_pkgmgr_dism.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_uac_bypass_pkgmgr_dism.yml) | `description: Detects the pattern of UAC Bypass using pkgmgr.exe and dism.exe (UACMe 23)`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_uac_bypass_pkgmgr_dism.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_uac_bypass_pkgmgr_dism.yml) | `Image\|endswith: '\dism.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020-2021 Strontic.


