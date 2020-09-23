---
title: zstd.exe | Zstandard - Fast and efficient compression algorithm
excerpt: What is zstd.exe?
---

# zstd.exe 

* File Path: `C:\program files\PeaZip\res\zstd\zstd.exe`
* Description: Zstandard - Fast and efficient compression algorithm

## Hashes

Type | Hash
-- | --
MD5 | `2A3B017B493DB3A2B66E5C97908633F7`
SHA1 | `78AF19C6345478C372400DEB8B9D238FC8AD5AB4`
SHA256 | `35F5563F68E73A2EF37F7BB23E398909992B791DF9EB020C52335CC26D4C279D`
SHA384 | `A68F4B8495B339BFB62BDF209B8CF034E43E5FD45A75574BA9CCDB36D40ED7C64FF30DAC4D6EA4752026D3F4A320D489`
SHA512 | `19286211839D9901A01B7E0C9F2769DB9B7A6D905B81D76F2585AC6789C7E9A4F66BC2CCE38EB454010A5129B4F7DCA11AA0565570D73565AF3071D7D260EF60`
SSDEEP | `24576:5OIB8yD6+2als05NVXmqPhJ8ctyO0mdoTAbfSlMIbBTyhtxr3:5lB8yDK05NVWqPhmEoTAbfTIFTOtxr3`

## Runtime Data

### Usage (stdout):
```cmhg
*** zstd command line interface 64-bits v1.4.5, by Yann Collet ***
Usage : 
      zstd.exe [args] [FILE(s)] [-o file] 

FILE    : a filename 
          with no FILE, or when FILE is - , read standard input
Arguments : 
 -#     : # compression level (1-19, default: 3) 
 -d     : decompression 
 -D DICT: use DICT as Dictionary for compression or decompression 
 -o file: result stored into `file` (only 1 output file) 
 -f     : overwrite output without prompting, also (de)compress links 
--rm    : remove source file(s) after successful de/compression 
 -k     : preserve source file(s) (default) 
 -h/-H  : display help/long help and exit 

Advanced arguments : 
 -V     : display Version number and exit 
 -c     : force write to standard output, even if it is the console 
 -v     : verbose mode; specify multiple times to increase verbosity 
 -q     : suppress warnings; specify twice to suppress errors too 
--no-progress : do not display the progress counter 
 -r     : operate recursively on directories 
--filelist=FILE : read list of files to operate upon from FILE 
--output-dir-flat=DIR : all resulting files are stored into DIR 
--      : All arguments after "--" are treated as files 

Advanced compression arguments : 
--ultra : enable levels beyond 19, up to 22 (requires more memory) 
--long[=#]: enable long distance matching with given window log (default: 27) 
--fast[=#]: switch to very fast compression levels (default: 1) 
--adapt : dynamically adapt compression level to I/O conditions 
 -T#    : spawns # compression threads (default: 1, 0==# cores) 
 -B#    : select size of each job (default: 0==automatic) 
--single-thread : use a single thread for both I/O and compression (result slightly different than -T1) 
--rsyncable : compress using a rsync-friendly method (-B sets block size) 
--exclude-compressed: only compress files that are not already compressed 
--stream-size=# : specify size of streaming input from `stdin` 
--size-hint=# optimize compression parameters for streaming input of approximately this size 
--target-compressed-block-size=# : generate compressed block of approximately targeted size 
--no-dictID : don't write dictID into header (dictionary compression only) 
--[no-]check : add XXH64 integrity checksum to frame (default: enabled) 
--[no-]compress-literals : force (un)compressed literals 
--format=zstd : compress files to the .zst format (default) 
--format=gzip : compress files to the .gz format 

Advanced decompression arguments : 
 -l     : print information about zstd compressed files 
--test  : test compressed file integrity 
 -M#    : Set a memory usage limit for decompression 
--[no-]sparse : sparse mode (default: enabled on file, disabled on stdout) 

Dictionary builder : 
--train ## : create a dictionary from a training set of files 
--train-cover[=k=#,d=#,steps=#,split=#,shrink[=#]] : use the cover algorithm with optional args 
--train-fastcover[=k=#,d=#,f=#,steps=#,split=#,accel=#,shrink[=#]] : use the fast cover algorithm with optional args 
--train-legacy[=s=#] : use the legacy algorithm with selectivity (default: 9) 
 -o DICT : DICT is dictionary name (default: dictionary) 
--maxdict=# : limit dictionary to specified size (default: 112640) 
--dictID=# : force dictionary ID to specified value (default: random) 

Benchmark arguments : 
 -b#    : benchmark file(s), using # compression level (default: 3) 
 -e#    : test all compression levels successively from -b# to -e# (default: 1) 
 -i#    : minimum evaluation time in seconds (default: 3s) 
 -B#    : cut file into independent blocks of size # (default: no block) 
 -S     : output one benchmark result per input file (default: consolidated result) 
--priority=rt : set process priority to real-time 

```

### Usage (stderr):
```cmhg
zstd: can't stat help : No such file or directory -- ignored 

```

### Loaded Modules:

Path |
-- |
C:\program files\PeaZip\res\zstd\zstd.exe |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\SYSTEM32\ntdll.dll |


## Signature

* Status: The file C:\program files\PeaZip\res\zstd\zstd.exe is not digitally signed. You cannot run this script on the current system. For more information about running scripts and setting execution policy, see about_Execution_Policies at https:/go.microsoft.com/fwlink/?LinkID=135170
* Serial: ``
* Thumbprint: ``
* Issuer: 
* Subject: 

## File Metadata

* Original Filename: zstd.exe
* Product Name: Zstandard
* Company Name: Yann Collet, Facebook, Inc.
* File Version: 1.4.4
* Product Version: 1.4.4
* Language: English (United States)
* Legal Copyright: Copyright (c) 2013-present, Yann Collet, Facebook, Inc.






MIT License. Copyright (c) 2020 Strontic.


