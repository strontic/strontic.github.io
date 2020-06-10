
# Robocopy.exe 
* File Path: `C:\Windows\system32\Robocopy.exe`
* Description: Microsoft Robocopy
* Comments: 

## Hashes
Type | Hash
-- | --
MD5 | `88A959D835808DA9FD394DCD56784F72`
SHA1 | `7D02D7400DB44D8E23A0F245593C3E8DEFB88187`
SHA256 | `CD428783F988CFC30E2F70B555C651E80DD7522E2DD19B663EC41CB8C4D9B167`
SHA384 | `33CB7BE0241A0AE9077BFBE8648CBA8D592F7DE08D39DCC9FB3EEF7630DB7414BCD46E610E65D728579A1EA89C022513`
SHA415 | `4D4B801A1964C227F49CB10D902F7428C0EB672D0F34A8457381E617C971565E16FEE0ED9B95F5581AD00A4C6333D23AD15AA8DB21D6FCC7DCC2219BAEA648F8`
SSDEEP | `3072:/LNJN7Bng6aRAREDkv+WZY/Xp7329sNUGaGO:jDpd5unkvCfpLNaG`

## Runtime Data
### Usage (stdout):
```Batchfile

-------------------------------------------------------------------------------
   ROBOCOPY     ::     Robust File Copy for Windows                              
-------------------------------------------------------------------------------

  Started : Thursday, June 4, 2020 4:22:48 PM
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
* Serial: 3300000266BD1580EFA75CD6D3000000000266
* Thumbprint: A4341B9FD50FB9964283220A36A1EF6F6FAA7840
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


