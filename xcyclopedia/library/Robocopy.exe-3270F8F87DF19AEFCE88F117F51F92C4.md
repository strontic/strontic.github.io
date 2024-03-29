﻿---
title: Robocopy.exe | Microsoft Robocopy
excerpt: What is Robocopy.exe?
---

# Robocopy.exe 

* File Path: `C:\WINDOWS\SysWOW64\Robocopy.exe`
* Description: Microsoft Robocopy

## Hashes

Type | Hash
-- | --
MD5 | `3270F8F87DF19AEFCE88F117F51F92C4`
SHA1 | `7E962E041CD80A68A2172D9F1AA5A8B4FF76C65D`
SHA256 | `34EF7DDC25AD476FE1AFC29FA6A961DCDFCB1CC3BF1FBB14162D16AAFE3B21D2`
SHA384 | `AED534ACEC7CF22E57C97357C5BE7F289EBE1F4DC5C97163D989E70E8C5B6DFADCDF8A84755BA2DA43CF48D84AEB7238`
SHA512 | `F26381E47CC6FA6AAB3E1DEA6CFEF3B06172822C0F952B0335019BA07A11B4CC7165AD3583DE78572F12C3A59858A810BAE589FB0F352FA3EDEE06E3BCA7E19C`
SSDEEP | `3072:IPpN18Y+qCVM8apAGjTEAUQ4hlgFWCyju2ECI+e:ipNTnBeqrhC`

## Runtime Data

### Usage (stdout):
```cmhg

-------------------------------------------------------------------------------
   ROBOCOPY     ::     Robust File Copy for Windows                              
-------------------------------------------------------------------------------

  Started : Thursday, June 4, 2020 3:40:13 PM
              Usage :: ROBOCOPY source destination [file [file]...] [options]

             source :: Source Directory (drive:\path or \\server\share\path).
        destination :: Destination Dir  (drive:\path or \\server\share\path).
               file :: File(s) to copy  (names/wildcards: default is "*.*").

::
:: Copy options :
::
                 /S :: copy Subdirectories, but not empty ones.
                 /E :: copy subdirectories, including Empty ones.
             /LEV:n :: only copy the top n LEVels of the source directory tree.

                 /Z :: copy files in restartable mode.
                 /B :: copy files in Backup mode.
                /ZB :: use restartable mode; if access denied use Backup mode.
                 /J :: copy using unbuffered I/O (recommended for large files).
            /EFSRAW :: copy all encrypted files in EFS RAW mode.

  /COPY:copyflag[s] :: what to COPY for files (default is /COPY:DAT).
                       (copyflags : D=Data, A=Attributes, T=Timestamps).
                       (S=Security=NTFS ACLs, O=Owner info, U=aUditing info).

 
               /SEC :: copy files with SECurity (equivalent to /COPY:DATS).
           /COPYALL :: COPY ALL file info (equivalent to /COPY:DATSOU).
            /NOCOPY :: COPY NO file info (useful with /PURGE).
            /SECFIX :: FIX file SECurity on all files, even skipped files.
            /TIMFIX :: FIX file TIMes on all files, even skipped files.

             /PURGE :: delete dest files/dirs that no longer exist in source.
               /MIR :: MIRror a directory tree (equivalent to /E plus /PURGE).

               /MOV :: MOVe files (delete from source after copying).
              /MOVE :: MOVE files AND dirs (delete from source after copying).

     /A+:[RASHCNET] :: add the given Attributes to copied files.
     /A-:[RASHCNET] :: remove the given Attributes from copied files.

            /CREATE :: CREATE directory tree and zero-length files only.
               /FAT :: create destination files using 8.3 FAT file names only.
               /256 :: turn off very long path (> 256 characters) support.

             /MON:n :: MONitor source; run again when more than n changes seen.
             /MOT:m :: MOnitor source; run again in m minutes Time, if changed.

      /RH:hhmm-hhmm :: Run Hours - times when new copies may be started.
                /PF :: check run hours on a Per File (not per pass) basis.

             /IPG:n :: Inter-Packet Gap (ms), to free bandwidth on slow lines.

                /SL :: copy symbolic links versus the target.

            /MT[:n] :: Do multi-threaded copies with n threads (default 8).
                       n must be at least 1 and not greater than 128.
                       This option is incompatible with the /IPG and /EFSRAW options.
                       Redirect output using /LOG option for better performance.

 /DCOPY:copyflag[s] :: what to COPY for directories (default is /DCOPY:DA).
                       (copyflags : D=Data, A=Attributes, T=Timestamps).

           /NODCOPY :: COPY NO directory info (by default /DCOPY:DA is done).

         /NOOFFLOAD :: copy files without using the Windows Copy Offload mechanism.

::
:: File Selection Options :
::
                 /A :: copy only files with the Archive attribute set.
                 /M :: copy only files with the Archive attribute and reset it.
    /IA:[RASHCNETO] :: Include only files with any of the given Attributes set.
    /XA:[RASHCNETO] :: eXclude files with any of the given Attributes set.

 /XF file [file]... :: eXclude Files matching given names/paths/wildcards.
 /XD dirs [dirs]... :: eXclude Directories matching given names/paths.

                /XC :: eXclude Changed files.
                /XN :: eXclude Newer files.
                /XO :: eXclude Older files.
                /XX :: eXclude eXtra files and directories.
                /XL :: eXclude Lonely files and directories.
                /IS :: Include Same files.
                /IT :: Include Tweaked files.

             /MAX:n :: MAXimum file size - exclude files bigger than n bytes.
             /MIN:n :: MINimum file size - exclude files smaller than n bytes.

          /MAXAGE:n :: MAXimum file AGE - exclude files older than n days/date.
          /MINAGE:n :: MINimum file AGE - exclude files newer than n days/date.
          /MAXLAD:n :: MAXimum Last Access Date - exclude files unused since n.
          /MINLAD:n :: MINimum Last Access Date - exclude files used since n.
                       (If n < 1900 then n = n days, else n = YYYYMMDD date).

                /XJ :: eXclude Junction points and symbolic links. (normally included by default).

               /FFT :: assume FAT File Times (2-second granularity).
               /DST :: compensate for one-hour DST time differences.

               /XJD :: eXclude Junction points and symbolic links for Directories.
               /XJF :: eXclude symbolic links for Files.

                /IM :: Include Modified files (differing change times).
::
:: Retry Options :
::
               /R:n :: number of Retries on failed copies: default 1 million.
               /W:n :: Wait time between retries: default is 30 seconds.

               /REG :: Save /R:n and /W:n in the Registry as default settings.

               /TBD :: wait for sharenames To Be Defined (retry error 67).

::
:: Logging Options :
::
                 /L :: List only - don't copy, timestamp or delete any files.
                 /X :: report all eXtra files, not just those selected.
                 /V :: produce Verbose output, showing skipped files.
                /TS :: include source file Time Stamps in the output.
                /FP :: include Full Pathname of files in the output.
             /BYTES :: Print sizes as bytes.

                /NS :: No Size - don't log file sizes.
                /NC :: No Class - don't log file classes.
               /NFL :: No File List - don't log file names.
               /NDL :: No Directory List - don't log directory names.

                /NP :: No Progress - don't display percentage copied.
               /ETA :: show Estimated Time of Arrival of copied files.

          /LOG:file :: output status to LOG file (overwrite existing log).
         /LOG+:file :: output status to LOG file (append to existing log).

       /UNILOG:file :: output status to LOG file as UNICODE (overwrite existing log).
      /UNILOG+:file :: output status to LOG file as UNICODE (append to existing log).

               /TEE :: output to console window, as well as the log file.

               /NJH :: No Job Header.
               /NJS :: No Job Summary.

           /UNICODE :: output status as UNICODE.

::
:: Job Options :
::
       /JOB:jobname :: take parameters from the named JOB file.
      /SAVE:jobname :: SAVE parameters to the named job file
              /QUIT :: QUIT after processing command line (to view parameters). 
              /NOSD :: NO Source Directory is specified.
              /NODD :: NO Destination Directory is specified.
                /IF :: Include the following Files.

::
:: Remarks :
::
       Using /PURGE or /MIR on the root directory of the volume formerly caused 
       robocopy to apply the requested operation on files inside the System 
       Volume Information directory as well. This is no longer the case; if 
       either is specified, robocopy will skip any files or directories with that 
       name in the top-level source and destination directories of the copy session.

       The modified files classification applies only when both source 
       and destination filesystems support change timestamps (e.g., NTFS) 
       and the source and destination files have different change times but are 
       otherwise the same. These files are not copied by default; specify /IM 
       to include them. 
```

## Signature

* Status: Signature verified.
* Serial: `330000023241FB59996DCC4DFF000000000232`
* Thumbprint: `FF82BC38E1DA5E596DF374C53E3617F7EDA36B06`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: robocopy.exe
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.18362.1 (WinBuild.160101.0800)
* Product Version: 10.0.18362.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.



## Possible Misuse

*The following table contains possible examples of `Robocopy.exe` being misused. While `Robocopy.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_suspicious_remote_thread.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/create_remote_thread/sysmon_suspicious_remote_thread.yml) | `- '\robocopy.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_multiple_suspicious_cli.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_multiple_suspicious_cli.yml) | `- robocopy.exe`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_copy_lateral_movement.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_copy_lateral_movement.yml) | `- '\robocopy.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Robocopy.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/Archive-Old-Version/LOLUtilz/OSBinaries/Robocopy.yml) | `Name: Robocopy.exe`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Robocopy.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/Archive-Old-Version/LOLUtilz/OSBinaries/Robocopy.yml) | `- Command: Robocopy.exe C:\SourceFolder C:\DestFolder`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Robocopy.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/Archive-Old-Version/LOLUtilz/OSBinaries/Robocopy.yml) | `- Command: Robocopy.exe \\SERVER\SourceFolder C:\DestFolder`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Robocopy.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/Archive-Old-Version/LOLUtilz/OSBinaries/Robocopy.yml) | `- https://social.technet.microsoft.com/wiki/contents/articles/1073.robocopy-and-a-few-examples.aspx`{:.highlight .language-yaml} | 

## Additional Info*

**The information below is copied from [MicrosoftDocs](https://github.com/MicrosoftDocs/windowsserverdocs), which is maintained by [Microsoft](https://opensource.microsoft.com/codeofconduct/). Available under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) license.*

---

## robocopy

Copies file data from one location to another.

### Syntax

```
robocopy <source> <destination> [<file>[ ...]] [<options>]
```

For example, to copy a file named *yearly-report.mov* from *c:\reports* to a file share *\\\\marketing\videos* while enabling multi-threading for higher performance (with the **/mt** parameter) and the ability to restart the transfer in case it's interrupted (with the **/z** parameter), type:

```dos
robocopy c:\reports '\\marketing\videos' yearly-report.mov /mt /z
```

#### Parameters

| Parameter | Description |
|--|--|
| `<source>` | Specifies the path to the source directory. |
| `<destination>` | Specifies the path to the destination directory. |
| `<file>` | Specifies the file or files to be copied. Wildcard characters (**&#42;** or **?**) are supported. If you don't specify this parameter, `*.*` is used as the default value. |
| `<options>` | Specifies the options to use with the **robocopy** command, including **copy**, **file**, **retry**, **logging**, and **job** options. |

##### Copy options

| Option | Description |
|--|--|
| /s | Copies subdirectories. This option automatically excludes empty directories. |
| /e | Copies subdirectories. This option automatically includes empty directories. |
| /lev:`<n>` | Copies only the top *n* levels of the source directory tree. |
| /z | Copies files in restartable mode. In restartable mode, should a file copy be interrupted, Robocopy can pick up where it left off rather than re-copying the entire file. |
| /b | Copies files in backup mode. Backup mode allows Robocopy to override file and folder permission settings (ACLs). This allows you to copy files you might otherwise not have access to, assuming it's being run under an account with sufficient privileges.|
| /zb | Copies files in restartable mode. If file access is denied, switches to backup mode. |
| /j | Copies using unbuffered I/O (recommended for large files). |
| /efsraw | Copies all encrypted files in EFS RAW mode. |
| /copy:`<copyflags>` | Specifies which file properties to copy. The valid values for this option are:<ul><li>**D** - Data</li><li>**A** - Attributes</li><li>**T** - Time stamps</li><li>**S** - NTFS access control list (ACL)</li><li>**O** - Owner information</li><li>**U** - Auditing information</li></ul>The default value for this option is **DAT** (data, attributes, and time stamps). |
| /dcopy:`<copyflags>`| Specifies what to copy in directories. The valid values for this option are:<ul><li>**D** - Data</li><li>**A** - Attributes</li><li>**T** - Time stamps</li></ul>The default value for this option is **DA** (data and attributes). |
| /sec | Copies files with security (equivalent to **/copy:DATS**). |
| /copyall | Copies all file information (equivalent to **/copy:DATSOU**). |
| /nocopy | Copies no file information (useful with **/purge**). |
| /secfix | Fixes file security on all files, even skipped ones. |
| /timfix | Fixes file times on all files, even skipped ones. |
| /purge | Deletes destination files and directories that no longer exist in the source. Using this option with the **/e** option and a destination directory, allows the destination directory security settings to not be overwritten. |
| /mir | Mirrors a directory tree (equivalent to **/e** plus **/purge**). Using this option with the **/e** option and a destination directory, overwrites the destination directory security settings. |
| /mov | Moves files, and deletes them from the source after they are copied. |
| /move | Moves files and directories, and deletes them from the source after they are copied. |
| /a+:[RASHCNET] | Adds the specified attributes to copied files.  The valid values for this option are: <ul><li>**R** - Read only</li><li>**A** - Archive</li><li>**S** - System</li><li>**H** - Hidden</li><li>**C** - Compressed</li><li>**N** - Not content indexed</li><li>**E** - Encrypted</li><li>**T** - Temporary</li></ul> |
| /a-:[RASHCNET] | Removes the specified attributes from copied files. The valid values for this option are: <ul><li>**R** - Read only</li><li>**A** - Archive</li><li>**S** - System</li><li>**H** - Hidden</li><li>**C** - Compressed</li><li>**N** - Not content indexed</li><li>**E** - Encrypted</li><li>**T** - Temporary</li></ul> |
| /create | Creates a directory tree and zero-length files only. |
| /fat | Creates destination files by using 8.3 character-length FAT file names only. |
| /256 | Turns off support for paths longer than 256 characters. |
| /mon:`<n>` | Monitors the source, and runs again when more than *n* changes are detected. |
| /mot:`<m>` | Monitors the source, and runs again in *m* minutes, if changes are detected. |
| /MT`[:n]` | Creates multi-threaded copies with *n* threads. *n* must be an integer between 1 and 128. The default value for *n* is 8. For better performance, redirect your output using **/log** option.<p>The **/mt** parameter can't be used with the **/ipg** and **/efsraw** parameters. |
| /rh:hhmm-hhmm | Specifies run times when new copies may be started. |
| /pf | Checks run times on a per-file (not per-pass) basis. |
| /ipg:n | Specifies the inter-packet gap to free bandwidth on slow lines. |
| /sl | Don't follow symbolic links and instead create a copy of the link. |
| /nodcopy | Copies no directory info (the default **/dcopy:DA** is done). |
| /nooffload | Copies files without using the Windows Copy Offload mechanism. |
| /compress | Requests network compression during file transfer, if applicable. |

> [!IMPORTANT]
> When using the **/secfix** copy option, specify the type of security information you want to copy, using one of these additional copy options:
>
>- **/copyall**
>- **/copy:o**
>- **/copy:s**
>- **/copy:u**
>- **/sec**

##### File selection options

| Option | Description |
|--|--|
| /a | Copies only files for which the **Archive** attribute is set. |
| /m | Copies only files for which the **Archive** attribute is set, and resets the **Archive** attribute. |
| /ia:`[RASHCNETO]` | Includes only files for which any of the specified attributes are set.  The valid values for this option are: <ul><li>**R** - Read only</li><li>**A** - Archive</li><li>**S** - System</li><li>**H** - Hidden</li><li>**C** - Compressed</li><li>**N** - Not content indexed</li><li>**E** - Encrypted</li><li>**T** - Temporary</li><li>**O** - Offline</li></ul> |
| /xa:`[RASHCNETO]` | Excludes files for which any of the specified attributes are set. The valid values for this option are: <ul><li>**R** - Read only</li><li>**A** - Archive</li><li>**S** - System</li><li>**H** - Hidden</li><li>**C** - Compressed</li><li>**N** - Not content indexed</li><li>**E** - Encrypted</li><li>**T** - Temporary</li><li>**O** - Offline</li></ul> |
| /xf `<filename>[ ...]` | Excludes files that match the specified names or paths. Wildcard characters (**&#42;** and **?**) are supported. |
| /xd `<directory>[ ...]` | Excludes directories that match the specified names and paths. |
| /xc | Excludes changed files. |
| /xn | Excludes newer files. |
| /xo | Excludes older files. |
| /xx | Excludes extra files and directories. |
| /xl | Excludes "lonely" files and directories. |
| /im | Include modified files (differing change times). |
| /is | Includes the same files. |
| /it | Includes tweaked files. |
| /xc | Excludes existing files with the same timestamp, but different file sizes. |
| /xn | Excludes existing files newer than the copy in the source directory. |
| /xo | Excludes existing files older than the copy in the source directory. |
| /xx | Excludes extra files and directories present in the destination but not the source. Excluding extra files will not delete files from the destination.  |
| /xl | Excludes "lonely" files and directories present in the source but not the destination. Excluding lonely files prevents any new files from being added to the destination. |
| /is | Includes the same files. Same files are identical in name, size, times, and all attributes. |
| /it | Includes "tweaked" files. Tweaked files have the same name, size, and times, but different attributes. |
| /max:`<n>` | Specifies the maximum file size (to exclude files bigger than *n* bytes). |
| /min:`<n>` | Specifies the minimum file size (to exclude files smaller than *n* bytes). |
| /maxage:`<n>` | Specifies the maximum file age (to exclude files older than *n* days or date). |
| /minage:`<n>` | Specifies the minimum file age (exclude files newer than *n* days or date). |
| /maxlad:`<n>` | Specifies the maximum last access date (excludes files unused since *n*). |
| /minlad:`<n>` | Specifies the minimum last access date (excludes files used since *n*) If *n* is less than 1900, *n* specifies the number of days. Otherwise, *n* specifies a date in the format YYYYMMDD. |
| /xj | Excludes junction points, which are normally included by default. |
| /fft | Assumes FAT file times (two-second precision). |
| /dst | Compensates for one-hour DST time differences. |
| /xjd | Excludes junction points for directories. |
| /xjf | Excludes junction points for files. |

##### Retry options

| Option | Description |
|--|--|
| /r:`<n>` | Specifies the number of retries on failed copies. The default value of *n* is 1,000,000 (one million retries). |
| /w:`<n>` | Specifies the wait time between retries, in seconds. The default value of *n* is 30 (wait time 30 seconds). |
| /reg | Saves the values specified in the **/r** and **/w** options as default settings in the registry. |
| /tbd | Specifies that the system will wait for share names to be defined (retry error 67). |

##### Logging options

| Option | Description |
|--|--|
| /l | Specifies that files are to be listed only (and not copied, deleted, or time stamped). |
| /x | Reports all extra files, not just those that are selected. |
| /v | Produces verbose output, and shows all skipped files. |
| /ts | Includes source file time stamps in the output. |
| /fp | Includes the full path names of the files in the output. |
| /bytes | Prints sizes, as bytes. |
| /ns | Specifies that file sizes are not to be logged. |
| /nc | Specifies that file classes are not to be logged. |
| /nfl | Specifies that file names are not to be logged. |
| /ndl | Specifies that directory names are not to be logged. |
| /np | Specifies that the progress of the copying operation (the number of files or directories copied so far) will not be displayed. |
| /eta | Shows the estimated time of arrival (ETA) of the copied files. |
| /log:`<logfile>` | Writes the status output to the log file (overwrites the existing log file). |
| /log+:`<logfile>` | Writes the status output to the log file (appends the output to the existing log file). |
| /unicode | Displays the status output as Unicode text. |
| /unilog:`<logfile>` | Writes the status output to the log file as Unicode text (overwrites the existing log file). |
| /unilog+:`<logfile>` | Writes the status output to the log file as Unicode text (appends the output to the existing log file). |
| /tee | Writes the status output to the console window, as well as to the log file. |
| /njh | Specifies that there is no job header. |
| /njs | Specifies that there is no job summary. |

##### Job options

| Option | Description |
|--|--|
| /job:`<jobname>` | Specifies that parameters are to be derived from the named job file. |
| /save:`<jobname>` | Specifies that parameters are to be saved to the named job file. |
| /quit | Quits after processing command line (to view parameters). |
| /nosd | Indicates that no source directory is specified. |
| /nodd | Indicates that no destination directory is specified. |
| /if | Includes the specified files. |

#### Exit (return) codes

| Value | Description |
|--|--|
| 0 | No files were copied. No failure was encountered. No files were mismatched. The files already exist in the destination directory; therefore, the copy operation was skipped. |
| 1 | All files were copied successfully. |
| 2 | There are some additional files in the destination directory that are not present in the source directory. No files were copied. |
| 3 | Some files were copied. Additional files were present. No failure was encountered. |
| 5 | Some files were copied. Some files were mismatched. No failure was encountered. |
| 6 | Additional files and mismatched files exist. No files were copied and no failures were encountered. This means that the files already exist in the destination directory. |
| 7 | Files were copied, a file mismatch was present, and additional files were present. |
| 8 | Several files did not copy. |

> [!NOTE]
> Any value greater than **8** indicates that there was at least one failure during the copy operation.

### Additional References

- [Command-Line Syntax Key](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/command-line-syntax-key.md)

---



MIT License. Copyright (c) 2020-2021 Strontic.


