
# xcopy.exe 

* File Path: `C:\WINDOWS\SysWOW64\xcopy.exe`
* Description: Extended Copy Utility
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `44B0448DD3DE7E9A1E80BD22954D9537`
SHA1 | `3C62897DDAF54DFA3717CE22768A3E9946DA5425`
SHA256 | `309BAD3C84C4830B6C71F8212A0CB13A44CC119BB4EBEC57DFBA0625CCDAEC26`
SHA384 | `8A3194B980CFD6D850D44F02E41EE5BF39C1EAE77B5A5DF1005F53B8C3756C3FE58917B5DA40548F2FAEB56EA3E62EE3`
SHA415 | `6A3855CBE25A1C5CEA4974622143D3D94281149A4E70C78A211DDA0176F01A4B4A685A8EABC0C7F4FBC45F4F89A49F87724C823F1638DE621F2F934AEE931BBB`
SSDEEP | `768:ER2YywVd4sPYZmmvisPJVZ1VxJympOo4pE1RjcrToMbR1:ERNDVKlBviWJbdJymUo4pojcrT`

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
* Serial: 330000023241FB59996DCC4DFF000000000232
* Thumbprint: FF82BC38E1DA5E596DF374C53E3617F7EDA36B06
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: XCOPY.EXE
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.18362.1 (WinBuild.160101.0800)
* Product Version: 10.0.18362.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.

MIT License. Copyright (c) 2020 Strontic.


