
# Robocopy.exe 

* File Path: `C:\Windows\SysWOW64\Robocopy.exe`
* Description: Microsoft Robocopy
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `AF707013DB5416E4CBD73652CEB1E784`
SHA1 | `13765328945FCF393D3BD2659825EDE812339B93`
SHA256 | `9B249C54707B822D797C974743458DEE9EE7F335ED12EC18BCCC978CD16DEBB7`
SHA384 | `6698DC6B6E15D47400C0007BCF62ECAADBDF07A27DF2574377DD12A98CE63ECBE6B9527CE1777E1961510B3AFBB258DF`
SHA512 | `D0AB971753FF683862D464508E4459B343AF07AF1C753E208BC0B4EE4CC3F6406B31689CAB30A4BEAF9F7AF3AFFDE419978EE61E3FE2BBE77A15622EA2A16B94`
SSDEEP | `3072:ajpskxediYR4xFCKYRFXntbFgIZfcRbksA+:YpLU9Jg5Rbk`

## Runtime Data

### Usage (stdout):
```Batchfile

-------------------------------------------------------------------------------
   ROBOCOPY     ::     Robust File Copy for Windows                              
-------------------------------------------------------------------------------

  Started : Thursday, June 4, 2020 4:45:57 PM
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

                /XJ :: eXclude Junction points. (normally included by default).

               /FFT :: assume FAT File Times (2-second granularity).
               /DST :: compensate for one-hour DST time differences.

               /XJD :: eXclude Junction points for Directories.
               /XJF :: eXclude Junction points for Files.

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
       Using /PURGE or /MIR on the root directory of the volume will 
       cause robocopy to apply the requested operation on files inside 
       the System Volume Information directory as well. If this is not 
       intended then the /XD switch may be used to instruct robocopy 
       to skip that directory.

```

### Usage (stderr):
```Batchfile

```

### Child Processes:


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: robocopy.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.14393.2636 (rs1_release_1.181031-1836)
* Product Version: 10.0.14393.2636
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.




## Additional Info*

**The information below is copied from [MicrosoftDocs](https://github.com/MicrosoftDocs/windowsserverdocs), which is maintained by [Microsoft](https://opensource.microsoft.com/codeofconduct/). Available under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) license.*

---
# robocopy

Copies file data.

## Syntax

```
robocopy <Source> <Destination> [<File>[ ...]] [<Options>]
```

For example, to copy a file named *yearly-report.mov* from c:\reports to a file share (*\\marketing\videos*) while enabling multi-threading for higher performance (with the /mt parameter) and the ability to restart the transfer in case it's interrupted (with the /z parameter), you'd use the following syntax:

```dos
robocopy C:\reports '\\marketing\videos' yearly-report.mov /mt /z
```

### Parameters

|   Parameter    |                                                                                            Description                                                                                           |
|----------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
|   \<Source>    |                                                                            Specifies the path to the source directory.                                                                           |
| \<Destination> |                                                                          Specifies the path to the destination directory.                                                                        |
|    \<File>     | Specifies the file or files to be copied. You can use wildcard characters (**&#42;** or **?**), if you want. If the **File** parameter is not specified, **\*.\*** is used as the default value. |
|   \<Options>   |                                                                    Specifies options to be used with the **robocopy** command.                                                                   |

### Copy options

|Option|Description|
|------|-----------|
|/s|Copies subdirectories. Note that this option excludes empty directories.|
|/e|Copies subdirectories. Note that this option includes empty directories. For additional information, see [Remarks](#remarks).|
|/lev:\<N>|Copies only the top *N* levels of the source directory tree.|
|/z|Copies files in restartable mode.|
|/b|Copies files in Backup mode.|
|/zb|Uses restartable mode. If access is denied, this option uses Backup mode.|
|/efsraw|Copies all encrypted files in EFS RAW mode.|
|/copy:\<CopyFlags>|Specifies the file properties to be copied. The following are the valid values for this option:</br>**D** Data</br>**A** Attributes</br>**T** Time stamps</br>**S** NTFS access control list (ACL)</br>**O** Owner information</br>**U** Auditing information</br>The default value for **CopyFlags** is **DAT** (data, attributes, and time stamps).|
|/dcopy:\<copyflags\>|Defines what to copy for directories. Default is DA. Options are D = data, A = attributes, and T = timestamps.|
|/sec|Copies files with security (equivalent to **/copy:DATS**).|
|/copyall|Copies all file information (equivalent to **/copy:DATSOU**).|
|/nocopy|Copies no file information (useful with **/purge**).|
|/secfix|Fixes file security on all files, even skipped ones.|
|/timfix|Fixes file times on all files, even skipped ones.|
|/purge|Deletes destination files and directories that no longer exist in the source. For additional information, see [Remarks](#remarks).|
|/mir|Mirrors a directory tree (equivalent to **/e** plus **/purge**). For additional information, see [Remarks](#remarks).|
|/mov|Moves files, and deletes them from the source after they are copied.|
|/move|Moves files and directories, and deletes them from the source after they are copied.|
|/a+:[RASHCNET]|Adds the specified attributes to copied files.|
|/a-:[RASHCNET]|Removes the specified attributes from copied files.|
|/create|Creates a directory tree and zero-length files only.|
|/fat|Creates destination files by using 8.3 character-length FAT file names only.|
|/256|Turns off support for very long paths (longer than 256 characters).|
|/mon:\<N>|Monitors the source, and runs again when more than *N* changes are detected.|
|/mot:\<M>|Monitors source, and runs again in *M* minutes if changes are detected.|
|/MT[:N]|Creates multi-threaded copies with *N* threads. *N* must be an integer between 1 and 128. The default value for *N* is 8.</br>The **/MT** parameter cannot be used with the **/IPG** and **/EFSRAW** parameters.</br>Redirect output using **/LOG** option for better performance.</br>Note: The /MT parameter applies to Windows Server 2008 R2 and Windows 7.|
|/rh:hhmm-hhmm|Specifies run times when new copies may be started.|
|/pf|Checks run times on a per-file (not per-pass) basis.|
|/ipg:n|Specifies the inter-packet gap to free bandwidth on slow lines.|
|/sl|Don't follow symbolic links and instead create a copy of the link.|

> [!IMPORTANT]
> When using the **/SECFIX** copy option, specify the type of security information you want to copy by also using one of these additional copy options:
>- **/COPYALL**
>- **/COPY:O**
>- **/COPY:S**
>- **/COPY:U**
>- **/SEC**

### File selection options

|Option|Description|
|------|-----------|
|/a|Copies only files for which the **Archive** attribute is set.|
|/m|Copies only files for which the **Archive** attribute is set, and resets the **Archive** attribute.|
|/ia:[RASHCNETO]|Includes only files for which any of the specified attributes are set.|
|/xa:[RASHCNETO]|Excludes files for which any of the specified attributes are set.|
|/xf \<FileName>[ ...]|Excludes files that match the specified names or paths. Note that *FileName* can include wildcard characters (**&#42;** and **?**).|
|/xd \<Directory>[ ...]|Excludes directories that match the specified names and paths.|
|/xc|Excludes changed files.|
|/xn|Excludes newer files.|
|/xo|Excludes older files.|
|/xx|Excludes extra files and directories.|
|/xl|Excludes "lonely" files and directories.|
|/is|Includes the same files.|
|/it|Includes "tweaked" files.|
|/max:\<N>|Specifies the maximum file size (to exclude files bigger than *N* bytes).|
|/min:\<N>|Specifies the minimum file size (to exclude files smaller than *N* bytes).|
|/maxage:\<N>|Specifies the maximum file age (to exclude files older than *N* days or date).|
|/minage:\<N>|Specifies the minimum file age (exclude files newer than *N* days or date).|
|/maxlad:\<N>|Specifies the maximum last access date (excludes files unused since *N*).|
|/minlad:\<N>|Specifies the minimum last access date (excludes files used since *N*) If *N* is less than 1900, *N* specifies the number of days. Otherwise, *N* specifies a date in the format YYYYMMDD.|
|/xj|Excludes junction points, which are normally included by default.|
|/fft|Assumes FAT file times (two-second precision).|
|/dst|Compensates for one-hour DST time differences.|
|/xjd|Excludes junction points for directories.|
|/xjf|Excludes junction points for files.|

### Retry options

|Option|Description|
|------|-----------|
|/r:\<N>|Specifies the number of retries on failed copies. The default value of *N* is 1,000,000 (one million retries).|
|/w:\<N>|Specifies the wait time between retries, in seconds. The default value of *N* is 30  (wait time 30 seconds).|
|/reg|Saves the values specified in the **/r** and **/w** options as default settings in the registry.|
|/tbd|Specifies that the system will wait for share names to be defined (retry error 67).|

### Logging options

|Option|Description|
|------|-----------|
|/l|Specifies that files are to be listed only (and not copied, deleted, or time stamped).|
|/x|Reports all extra files, not just those that are selected.|
|/v|Produces verbose output, and shows all skipped files.|
|/ts|Includes source file time stamps in the output.|
|/fp|Includes the full path names of the files in the output.|
|/bytes|Prints sizes, as bytes.|
|/ns|Specifies that file sizes are not to be logged.|
|/nc|Specifies that file classes are not to be logged.|
|/nfl|Specifies that file names are not to be logged.|
|/ndl|Specifies that directory names are not to be logged.|
|/np|Specifies that the progress of the copying operation (the number of files or directories copied so far) will not be displayed.|
|/eta|Shows the estimated time of arrival (ETA) of the copied files.|
|/log:\<LogFile>|Writes the status output to the log file (overwrites the existing log file).|
|/log+:\<LogFile>|Writes the status output to the log file (appends the output to the existing log file).|
|/unicode|Displays the status output as Unicode text.|
|/unilog:\<LogFile>|Writes the status output to the log file as Unicode text (overwrites the existing log file).|
|/unilog+:\<LogFile>|Writes the status output to the log file as Unicode text (appends the output to the existing log file).|
|/tee|Writes the status output to the console window, as well as to the log file.|
|/njh|Specifies that there is no job header.|
|/njs|Specifies that there is no job summary.|

### Job options

|Option|Description|
|------|-----------|
|/job:\<JobName>|Specifies that parameters are to be derived from the named job file.|
|/save:\<JobName>|Specifies that parameters are to be saved to the named job file.|
|/quit|Quits after processing command line (to view parameters).|
|/nosd|Indicates that no source directory is specified.|
|/nodd|Indicates that no destination directory is specified.|
|/if|Includes the specified files.|

### Exit (return) codes

Value | Description
-- | --
0 | No files were copied. No failure was encountered.  No files were mismatched. The files already exist in the destination directory; therefore, the copy operation was skipped.
1 | All files were copied successfully.
2 | There are some additional files in the destination directory that are not present in the source directory. No files were copied.
3 | Some files were copied. Additional files were present. No failure was encountered.
5 | Some files were copied. Some files were mismatched. No failure was encountered.
6 | Additional  files and mismatched files exist. No files were copied and no failures were encountered. This means that the files already exist in the destination directory.
7 | Files were copied, a file mismatch was present, and additional files were present.
8 | Several files did not copy.

> [!NOTE]
> Any value greater than 8 indicates that there was at least one failure during the copy operation.

### Remarks

-   The **/mir** option is equivalent to the **/e** plus **/purge** options with one small difference in behavior:  
    -   With the **/e** plus **/purge** options, if the destination directory exists, the destination directory security settings are not overwritten.
    -   With the **/mir** option, if the destination directory exists, the destination directory security settings are overwritten.

## Additional References

- [Command-Line Syntax Key](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/command-line-syntax-key.md)

---


MIT License. Copyright (c) 2020 Strontic.


