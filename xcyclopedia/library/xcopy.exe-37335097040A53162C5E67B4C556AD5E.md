
# xcopy.exe 
* File Path: `C:\Windows\SysWOW64\xcopy.exe`
* Description: Extended Copy Utility
* Comments: 

## Hashes
Type | Hash
-- | --
MD5 | `37335097040A53162C5E67B4C556AD5E`
SHA1 | `43F27299C9892747E05191240A71897249EF1CBE`
SHA256 | `ADB4A07A567002816658087B3E053E1A1B847BE0216BE0627F2302F55FE2C63F`
SHA384 | `9A2FE730FAEB663F62E0554DE861027872359819865846D4E621582343F9A94BB2D6BAFEB96021E40526779AD6FE5CBA`
SHA415 | `34CB4D3399B7D44783CCE9B15222D58D322F7356AD30259E36CB471450331DF67A907B3676C4AD03F3ED2CE99F9D7D82B8BF106497FC115AAB497FD34992DC7B`
SSDEEP | `768:jA4s1qQlPs/vgbCEdnSMD2sZRMQ4MZ4JLj78B3DWkFfb/V8:j3sQQ+0C8TDZ6QlOp78BTWGfb/V8`

## Runtime Data
### Usage (stdout):
```Batchfile
Copies files and directory trees.

XCOPY source [destination] [/A | /M] [/D[:date]] [/P] [/S [/E]] [/V] [/W]
                           [/C] [/I] [/Q] [/F] [/L] [/G] [/H] [/R] [/T] [/U]
                           [/K] [/N] [/O] [/X] [/Y] [/-Y] [/Z] [/B] [/J]
                           [/EXCLUDE:file1[+file2][+file3]...]

  source       Specifies the file(s) to copy.
  destination  Specifies the location and/or name of new files.
  /A           Copies only files with the archive attribute set,
               doesn't change the attribute.
  /M           Copies only files with the archive attribute set,
               turns off the archive attribute.
  /D:m-d-y     Copies files changed on or after the specified date.
               If no date is given, copies only those files whose
               source time is newer than the destination time.
  /EXCLUDE:file1[+file2][+file3]...
               Specifies a list of files containing strings.  Each string
               should be in a separate line in the files.  When any of the
               strings match any part of the absolute path of the file to be
               copied, that file will be excluded from being copied.  For
               example, specifying a string like \obj\ or .obj will exclude
               all files underneath the directory obj or all files with the
               .obj extension respectively.
  /P           Prompts you before creating each destination file.
  /S           Copies directories and subdirectories except empty ones.
  /E           Copies directories and subdirectories, including empty ones.
               Same as /S /E. May be used to modify /T.
  /V           Verifies the size of each new file.
  /W           Prompts you to press a key before copying.
  /C           Continues copying even if errors occur.
  /I           If destination does not exist and copying more than one file,
               assumes that destination must be a directory.
  /Q           Does not display file names while copying.
  /F           Displays full source and destination file names while copying.
  /L           Displays files that would be copied.
  /G           Allows the copying of encrypted files to destination that does
               not support encryption.
  /H           Copies hidden and system files also.
  /R           Overwrites read-only files.
  /T           Creates directory structure, but does not copy files. Does not
               include empty directories or subdirectories. /T /E includes
               empty directories and subdirectories.
  /U           Copies only files that already exist in destination.
  /K           Copies attributes. Normal Xcopy will reset read-only attributes.
  /N           Copies using the generated short names.
  /O           Copies file ownership and ACL information.
  /X           Copies file audit settings (implies /O).
  /Y           Suppresses prompting to confirm you want to overwrite an
               existing destination file.
  /-Y          Causes prompting to confirm you want to overwrite an
               existing destination file.
  /Z           Copies networked files in restartable mode.
  /B           Copies the Symbolic Link itself versus the target of the link.
  /J           Copies using unbuffered I/O. Recommended for very large files.

The switch /Y may be preset in the COPYCMD environment variable.
This may be overridden with /-Y on the command line.

```

### Usage (stderr):
```Batchfile
File cannot be copied onto itself

```

### Child Processes:


## Signature

* Status: Signature verified.
* Serial: 33000000BCE120FDD27CC8EE930000000000BC
* Thumbprint: E85459B23C232DB3CB94C7A56D47678F58E8E51E
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: XCOPY.EXE
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.14393.0 (rs1_release.160715-1616)
* Product Version: 10.0.14393.0
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.


