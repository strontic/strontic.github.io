
# Robocopy.exe 

* File Path: `C:\WINDOWS\SysWOW64\Robocopy.exe`
* Description: Microsoft Robocopy
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `3270F8F87DF19AEFCE88F117F51F92C4`
SHA1 | `7E962E041CD80A68A2172D9F1AA5A8B4FF76C65D`
SHA256 | `34EF7DDC25AD476FE1AFC29FA6A961DCDFCB1CC3BF1FBB14162D16AAFE3B21D2`
SHA384 | `AED534ACEC7CF22E57C97357C5BE7F289EBE1F4DC5C97163D989E70E8C5B6DFADCDF8A84755BA2DA43CF48D84AEB7238`
SHA415 | `F26381E47CC6FA6AAB3E1DEA6CFEF3B06172822C0F952B0335019BA07A11B4CC7165AD3583DE78572F12C3A59858A810BAE589FB0F352FA3EDEE06E3BCA7E19C`
SSDEEP | `3072:IPpN18Y+qCVM8apAGjTEAUQ4hlgFWCyju2ECI+e:ipNTnBeqrhC`

## Runtime Data

### Usage (stdout):
```Batchfile

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

### Usage (stderr):
```Batchfile

```

### Child Processes:


## Signature

* Status: Signature verified.
* Serial: 330000023241FB59996DCC4DFF000000000232
* Thumbprint: FF82BC38E1DA5E596DF374C53E3617F7EDA36B06
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

MIT License. Copyright (c) 2020 Strontic.


