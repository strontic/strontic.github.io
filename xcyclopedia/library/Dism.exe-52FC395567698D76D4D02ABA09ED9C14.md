---
title: Dism.exe | Dism Image Servicing Utility
excerpt: What is Dism.exe?
---

# Dism.exe 

* File Path: `C:\Windows\SysWOW64\Dism.exe`
* Description: Dism Image Servicing Utility

## Hashes

Type | Hash
-- | --
MD5 | `52FC395567698D76D4D02ABA09ED9C14`
SHA1 | `D551D5A0EBB7CA9AB1E3432AAAAAD1DB10298A6E`
SHA256 | `2583198AAABBDD48923A9A5CCC6543475311B9BD10988FB77230EE46F02C0C5C`
SHA384 | `039301BB32BAA767D08D376D2F24DB319D68AD29B5C5C12D0CE496E5303C8D942385EE734CEA38BBE0FF22B911B53C82`
SHA512 | `352CDD6BB21655097BB81B4F318F67C2A08EAF10E4F4A5B75B613B3FF0F75012A63E0BD82B73A33B299DFEBEAB0E1B0D477A31499DBA749C414A7BE08038D9D4`
SSDEEP | `3072:1e75RF5307Hfryg/NBO0c5TcjpcfQmd+kx/1Jl4B3UeCotCzL5MwQVr2RTyb:0vF53o/rygFcYmdtLe3rC/zLKr2RT2`

## Runtime Data

### Usage (stdout):
```cmhg

Deployment Image Servicing and Management tool
Version: 10.0.17763.1282


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
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\wow64.dll |
C:\Windows\System32\wow64cpu.dll |
C:\Windows\System32\wow64win.dll |
C:\Windows\SysWOW64\Dism.exe |


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
* File Version: 10.0.17763.1 (WinBuild.160101.0800)
* Product Version: 10.0.17763.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.



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


