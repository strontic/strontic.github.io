---
title: Arc.exe | 
---

# Arc.exe 

* File Path: `C:\program files\PeaZip\res\arc\Arc.exe`

## Hashes

Type | Hash
-- | --
MD5 | `B57977528C92003A4BF710A735663065`
SHA1 | `CA38A95466C1201AD60B760F006A2DB9AFF7228A`
SHA256 | `B36B1BE0A3C329675AF4EECE3193F08CF343EDE57A6933033BF6004A50AB2A65`
SHA384 | `0DCE57A498104486345A7949C382F429FB8666A7E7B36D3BA4C913E67DCEF6B96731963642A59818396ED60F32761810`
SHA512 | `DC436A2B017945DABA993510B90A701C767A236749F5F1CE0C367CBAF8F21A39E751DB51FCBEE82613B7CE0DA361B28119D3466700BE5BD37BA80956D3F4B175`
SSDEEP | `49152:Sk/sHkvi8CyK79VRt9/PN7cIZ4hSs+BuW:ebtZRVRD/PNPKhSsSu`

## Runtime Data

### Usage (stdout):
```Batchfile
FreeArc 0.67 (March 15 2014)  http://freearc.org  March 15 2014
High-performance archiver. Free as well for commercial as for non-commercial use
Usage: Arc command [options...] archive [files... @listfiles...]
Commands:
  a        add files to archive
  c        add comment to archive
  ch       modify archive (recompress, encrypt and so on)
  create   create new archive
  cw       write archive comment to file
  d        delete files from archive
  e        extract files from archive ignoring pathnames
  f        freshen archive
  j        join archives
  k        lock archive
  l        list files in archive
  lb       bare list of files in archive
  lt       technical archive listing
  m        move files and dirs to archive
  mf       move files to archive
  modify   modify archive using +/-/* actions
  r        recover archive using recovery record
  rr       add recovery record to archive
  s        convert archive to SFX
  t        test archive integrity
  u        update files in archive
  v        verbosely list files in archive
  x        extract files from archive
Options:
  --                                        stop processing options
  -ac           --ClearArchiveBit           clear Archive bit on files succesfully (de)archived
  -ad           --adddir                    add arcname to extraction path
  -aeALGORITHM  --encryption=ALGORITHM      encryption ALGORITHM (aes, blowfish, serpent, twofish)
  -agFMT        --autogenerate=FMT          autogenerate archive name with FMT
  -ao           --SelectArchiveBit          select only files with Archive bit set
  -apDIR        --arcpath=DIR               base DIR in archive
  -baMODE       --BrokenArchive=MODE        deal with badly broken archive using MODE
  -cfgFILES     --config=FILES              use configuration FILES (default: arc*.ini)
  -d            --delete                    delete files & dirs after successful archiving
  -df           --delfiles                  delete only files after successful archiving
  -diAMOUNT     --display=AMOUNT            control AMOUNT of information displayed: [hoacmnwrfdtske]*
  -dmMETHOD     --dirmethod=METHOD          compression METHOD for archive directory
  -dpDIR        --diskpath=DIR              base DIR on disk
  -dsORDER      --sort=ORDER                sort files in ORDER
  -ed           --nodirs                    don't add empty dirs to archive
  -envVAR                                   read default options from environment VAR (default: FREEARC)
  -epMODE       --ExcludePath=MODE          Exclude/expand path MODE
  -f            --freshen                   freshen files
  -fn           --fullnames                 match with full names
  -hpPASSWORD   --HeadersPassword=PASSWORD  encrypt/decrypt archive headers and data using PASSWORD
  -iTYPE        --indicator=TYPE            select progress indicator TYPE (0/1/2)
  -ioff         --shutdown                  shutdown computer when operation completed
  -k            --lock                      lock archive
  -kb           --keepbroken                keep broken extracted files
  -kfKEYFILE    --keyfile=KEYFILE           encrypt/decrypt using KEYFILE
  -lcN          --LimitCompMem=N            limit memory usage for compression to N mbytes
  -ldN          --LimitDecompMem=N          limit memory usage for decompression to N mbytes
  -mMETHOD      --method=METHOD             compression METHOD (-m0..-m9, -m1x..-m9x)
  -maLEVEL                                  set filetype detection LEVEL (+/-/1..9)
  -max                                      maximum compression using external precomp, ecm, ppmonstr
  -mc                                       disable compression algorithms (-mcd-, -mc-rep...)
  -mdN          --dictionary=N              set compression dictionary to N mbytes
  -mmMODE       --multimedia=MODE           set multimedia compression to MODE
  -ms           --StoreCompressed           store already compressed files
  -mtTHREADS    --MultiThreaded=THREADS     number of compression THREADS
  -mx                                       maximum internal compression mode
  -nFILESPECS   --include=FILESPECS         include only files matching FILESPECS
  -oMODE        --overwrite=MODE            existing files overwrite MODE (+/-/p)
  -okfKEYFILE   --OldKeyfile=KEYFILE        old KEYFILE used only for decryption
  -opPASSWORD   --OldPassword=PASSWORD      old PASSWORD used only for decryption
  -pPASSWORD    --password=PASSWORD         encrypt/decrypt compressed data using PASSWORD
  -r            --recursive                 recursively collect files
  -rrSIZE       --recovery=SIZE             add recovery information of specified SIZE to archive
  -sGROUPING    --solid=GROUPING            GROUPING for solid compression
  -scCHARSETS   --charset=CHARSETS          CHARSETS used for listfiles and comment files
  -sfxMODULE                                add sfx MODULE ("freearc.sfx" by default)
  -slSIZE       --SizeLess=SIZE             select files smaller than SIZE
  -smSIZE       --SizeMore=SIZE             select files larger than SIZE
  -t            --test                      test archive after operation
  -tTYPE        --type=TYPE                 archive TYPE (arc/zip/rar/...)
  -taTIME       --TimeAfter=TIME            select files modified after specified TIME
  -tbTIME       --TimeBefore=TIME           select files modified before specified TIME
  -tk           --keeptime                  keep original archive time
  -tl           --timetolast                set archive time to latest file
  -tnPERIOD     --TimeNewer=PERIOD          select files newer than specified time PERIOD
  -toPERIOD     --TimeOlder=PERIOD          select files older than specified time PERIOD
  -tpMODE       --pretest=MODE              test archive before operation using MODE
  -u            --update                    update files
  -vSIZE        --volume=SIZE               split archive to volumes each of SIZE bytes
  -wDIRECTORY   --workdir=DIRECTORY         DIRECTORY for temporary files
  -xFILESPECS   --exclude=FILESPECS         exclude FILESPECS from operation
  -y            --yes                       answer Yes to all queries
  -zFILE        --arccmt=FILE               read archive comment from FILE or stdin
                --append                    add new files to the end of archive
                --archive-comment=COMMENT   input archive COMMENT in cmdline
                --bypass=URL                setups proxy bypass list for URL access
                --cache=N                   use N mbytes for read-ahead cache
                --crconly                   save/check CRC, but don't store data
                --create-in-workdir         create archive in workdir and then move to final location
                --dirs                      add empty dirs to archive
                --groups=FILE               name of groups FILE
                --language=FILE             load localisation from FILE
                --logfile=FILE              duplicate all information displayed to this FILE
                --noarcext                  don't add default extension to archive name
                --nodata                    don't store data in archive
                --nodates                   don't store filetimes in archive
                --nodir                     don't write archive directories
                --original=URL              redownload broken parts of archive from the URL
                --pause-before-exit=PAUSE   make a PAUSE just before closing program window
                --print-config              display built-in definitions of compression methods
                --proxy=URL                 setups proxy(s) for URL access
                --queue                     queue operations across multiple FreeArc copies
                --recompress                recompress archive contents
                --save-bad-ranges=FILE      save list of broken archive parts to the FILE
                --sync                      synchronize archive and disk contents
All OK


```

### Loaded Modules:

Path |
-- |
C:\program files\PeaZip\res\arc\Arc.exe |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\wow64.dll |
C:\Windows\System32\wow64cpu.dll |
C:\Windows\System32\wow64win.dll |


## Signature

* Status: The file C:\program files\PeaZip\res\arc\Arc.exe is not digitally signed. You cannot run this script on the current system. For more information about running scripts and setting execution policy, see about_Execution_Policies at https:/go.microsoft.com/fwlink/?LinkID=135170
* Serial: ``
* Thumbprint: ``
* Issuer: 
* Subject: 

## File Metadata

* Original Filename: 
* Product Name: 
* Company Name: 
* File Version: 
* Product Version: 
* Language: 
* Legal Copyright: 





MIT License. Copyright (c) 2020 Strontic.


