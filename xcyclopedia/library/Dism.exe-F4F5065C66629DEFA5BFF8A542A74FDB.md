
# Dism.exe 
* File Path: `C:\Windows\SysWOW64\Dism.exe`
* Description: Dism Image Servicing Utility
* Comments: 

## Hashes
Type | Hash
-- | --
MD5 | `F4F5065C66629DEFA5BFF8A542A74FDB`
SHA1 | `66E84E8DBFC0E96AE6758C4F13355DCB43E7997D`
SHA256 | `9F085677C2E919C712C2BF025E0A7FA3F07CEEBE76EC81B72C17ED54DD5F330E`
SHA384 | `20DAAC0BFAB0304C8B244B0B16322B44CC699A38AD8EF4ED448677B30A27087A58848E6FFF51A8D78B1D4F1D811C6AED`
SHA415 | `3A31CF71BF1B22F0999E5BC4A888D7DAD8E30640B64C31BED5416B0F6A8E5444CBCC0B3C0EE56D21415196C3F045AA6DD88BA91BCD98B13F804ED5B81D716A39`
SSDEEP | `3072:oT75uF5aut0c/gYnV/uZCk9pj2Q2mnAJuvuuo0aw4nrXCA/B:oPwF5KKdnV/9k9pj2Q2GG+uuoPr1J`

## Runtime Data
### Usage (stdout):
```Batchfile

Deployment Image Servicing and Management tool
Version: 10.0.14393.3241


DISM.exe [dism_options] {Imaging_command} [<Imaging_arguments>]
DISM.exe {/Image:<path_to_offline_image> | /Online} [dism_options] 
         {servicing_command} [<servicing_arguments>]

DESCRIPTION:

  DISM enumerates, installs, uninstalls, configures, and updates features
  and packages in Windows images. The commands that are available depend 
  on the image being serviced and whether the image is offline or running.

GENERIC IMAGING COMMANDS:

  /Split-Image            - Splits an existing .wim or .ffu file into multiple 
                            read-only split WIM/FFU files.
  /Apply-Image            - Applies an image.
  /Get-MountedImageInfo   - Displays information about mounted WIM and VHD
                            images.
  /Get-ImageInfo          - Displays information about images in a WIM or VHD
                            file.
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

* Original Filename: DISM.EXE.MUI
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.14393.0 (rs1_release.160715-1616)
* Product Version: 10.0.14393.0
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.


