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
MD5 | `9D670E39C17B5E6375EA17B41CF3A47A`
SHA1 | `DB7558C23CF0B603C48F89D1424F4BBBF9AF5BA2`
SHA256 | `86352060D90D48AFFABDED6F50BA676F25C472AABF421B17A2B19C0B8C29A1FB`
SHA384 | `7FB46156BAFDB89A68FE9D3347A39B867F6BC7A67660C9BF3AFA998FC5A3526E83677994C5B8090A13511472259009B1`
SHA512 | `25CF5DA672D53E953513B5C3C9AAFE39E10FE659F0B3B362131399D757F8182E1A18D3B9A2F865C4F000A97AD122614D726AAEE08CBD60D656937137E7A2A464`
SSDEEP | `3072:Cgu75RF5ZQ582+GHGFi3oZmNxsK3WRSX7AdwTqBUIhzcTzL/M0MVrT3RT0b:C9vF5m82Hb3oB5RSEwWUIJ2zLgro`
IMP | `73B26C2319D9DCA391B1F2968C70999C`
PESHA1 | `16AB956B028E33DBE498F507F309CFFDC37CCB31`
PE256 | `FE1448A0FA370EAF87138BEEFD9D73EE292F058EBBE4EBB09E46F704F90BCD0C`

## Runtime Data

### Usage (stdout):
```cmhg

Deployment Image Servicing and Management tool
Version: 10.0.17763.1518


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
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: Unknown
* VirusTotal Link: n/a


## Possible Misuse

*The following table contains possible examples of `Dism.exe` being misused. While `Dism.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_user_driver_loaded.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/builtin/win_user_driver_loaded.yml) | `- '*\Windows\System32\Dism.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020 Strontic.


