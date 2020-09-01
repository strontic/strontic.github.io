---
title: upx.exe | UPX executable packer
---

# upx.exe 

* File Path: `C:\program files\PeaZip\res\upx\upx.exe`
* Description: UPX executable packer

## Hashes

Type | Hash
-- | --
MD5 | `8B8F4DFB276D2271BCB80E5E81EE7743`
SHA1 | `C3504EA080D5DF6CF361A386E90A37968AFD8755`
SHA256 | `3660FA3C1E91917E8388C85E222BF3973EDEBF89F5898B2908111C981481DD40`
SHA384 | `C861B31759AF8B55899BD8104B1DB8EB7446C3DF27B546533C9B3293C2612777B454709D4CDB2918EEF55643AC7AA01A`
SHA512 | `263B2229072BBBCE046619C9B1E9C61D6D64164AA0A2BED3E33E5D49E18E6D72E33234566A819A7EB5A2643602C5D87F0CD60D54312EC916FAC270CF86A4EFC2`
SSDEEP | `12288:MWGI81xb937Ez/h4YftwOjSwnS4KMsRm1nrrWt:MtI853u+YfPO2S4sRQat`

## Runtime Data

### Usage (stdout):
```Batchfile
                       Ultimate Packer for eXecutables
                          Copyright (C) 1996 - 2018
UPX 3.95w       Markus Oberhumer, Laszlo Molnar & John Reiser   Aug 26th 2018

Usage: upx [-123456789dlthVL] [-qvfk] [-o file] file..

Commands:
  -1     compress faster                   -9    compress better
  --best compress best (can be slow for big files)
  -d     decompress                        -l    list compressed file
  -t     test compressed file              -V    display version number
  -h     give this help                    -L    display software license

Options:
  -q     be quiet                          -v    be verbose
  -oFILE write output to 'FILE'
  -f     force compression of suspicious files
  --no-color, --mono, --color, --no-progress   change look

Compression tuning options:
  --brute             try all available compression methods & filters [slow]
  --ultra-brute       try even more compression variants [very slow]

Backup options:
  -k, --backup        keep backup files
  --no-backup         no backup files [default]

Overlay options:
  --overlay=copy      copy any extra data attached to the file [default]
  --overlay=strip     strip any extra data attached to the file [DANGEROUS]
  --overlay=skip      don't compress a file with an overlay

Options for djgpp2/coff:
  --coff              produce COFF output [default: EXE]

Options for dos/com:
  --8086              make compressed com work on any 8086

Options for dos/exe:
  --8086              make compressed exe work on any 8086
  --no-reloc          put no relocations in to the exe header

Options for dos/sys:
  --8086              make compressed sys work on any 8086

Options for ps1/exe:
  --8-bit             uses 8 bit size compression [default: 32 bit]
  --8mib-ram          8 megabyte memory limit [default: 2 MiB]
  --boot-only         disables client/host transfer compatibility
  --no-align          don't align to 2048 bytes [enables: --console-run]

Options for watcom/le:
  --le                produce LE output [default: EXE]

Options for win32/pe, win64/pe, rtm32/pe & arm/pe:
  --compress-exports=0    do not compress the export section
  --compress-exports=1    compress the export section [default]
  --compress-icons=0      do not compress any icons
  --compress-icons=1      compress all but the first icon
  --compress-icons=2      compress all but the first icon directory [default]
  --compress-icons=3      compress all icons
  --compress-resources=0  do not compress any resources at all
  --keep-resource=list    do not compress resources specified by list
  --strip-relocs=0        do not strip relocations
  --strip-relocs=1        strip relocations [default]

Options for linux/elf:
  --preserve-build-id     copy .gnu.note.build-id to compressed output

file..   executables to (de)compress

This version supports:
    amd64-darwin.dylib                   dylib/amd64
    amd64-darwin.macho                   macho/amd64
    amd64-linux.elf                      linux/amd64
    amd64-linux.kernel.vmlinux           vmlinux/amd64
    amd64-win64.pe                       win64/pe
    arm-darwin.macho                     macho/arm
    arm-linux.elf                        linux/arm
    arm-linux.kernel.vmlinux             vmlinux/arm
    arm-linux.kernel.vmlinuz             vmlinuz/arm
    arm-wince.pe                         arm/pe
    arm64-darwin.macho                   macho/arm64
    arm64-linux.elf                      linux/arm64
    armeb-linux.elf                      linux/armeb
    armeb-linux.kernel.vmlinux           vmlinux/armeb
    fat-darwin.macho                     macho/fat
    i086-dos16.com                       dos/com
    i086-dos16.exe                       dos/exe
    i086-dos16.sys                       dos/sys
    i386-bsd.elf.execve                  bsd.exec/i386
    i386-darwin.macho                    macho/i386
    i386-dos32.djgpp2.coff               djgpp2/coff
    i386-dos32.tmt.adam                  tmt/adam
    i386-dos32.watcom.le                 watcom/le
    i386-freebsd.elf                     freebsd/i386
    i386-linux.elf                       linux/i386
    i386-linux.elf.execve                linux.exec/i386
    i386-linux.elf.shell                 linux.sh/i386
    i386-linux.kernel.bvmlinuz           bvmlinuz/i386
    i386-linux.kernel.vmlinux            vmlinux/i386
    i386-linux.kernel.vmlinuz            vmlinuz/i386
    i386-netbsd.elf                      netbsd/i386
    i386-openbsd.elf                     openbsd/i386
    i386-win32.pe                        win32/pe
    m68k-atari.tos                       atari/tos
    mips-linux.elf                       linux/mips
    mipsel-linux.elf                     linux/mipsel
    mipsel.r3000-ps1                     ps1/exe
    powerpc-darwin.macho                 macho/ppc32
    powerpc-linux.elf                    linux/ppc32
    powerpc-linux.kernel.vmlinux         vmlinux/ppc32
    powerpc64-linux.elf                  linux/ppc64
    powerpc64le-darwin.macho             macho/ppc64le
    powerpc64le-linux.elf                linux/ppc64le
    powerpc64le-linux.kernel.vmlinux     vmlinux/ppc64le

UPX comes with ABSOLUTELY NO WARRANTY; for details visit https://upx.github.io

```

### Usage (stderr):
```Batchfile
                       Ultimate Packer for eXecutables
                          Copyright (C) 1996 - 2018
UPX 3.95w       Markus Oberhumer, Laszlo Molnar & John Reiser   Aug 26th 2018

Usage: upx [-123456789dlthVL] [-qvfk] [-o file] file..

Commands:
  -1     compress faster                   -9    compress better
  --best compress best (can be slow for big files)
  -d     decompress                        -l    list compressed file
  -t     test compressed file              -V    display version number
  -h     give this help                    -L    display software license

Options:
  -q     be quiet                          -v    be verbose
  -oFILE write output to 'FILE'
  -f     force compression of suspicious files
  --no-color, --mono, --color, --no-progress   change look

Compression tuning options:
  --brute             try all available compression methods & filters [slow]
  --ultra-brute       try even more compression variants [very slow]

Backup options:
  -k, --backup        keep backup files
  --no-backup         no backup files [default]

Overlay options:
  --overlay=copy      copy any extra data attached to the file [default]
  --overlay=strip     strip any extra data attached to the file [DANGEROUS]
  --overlay=skip      don't compress a file with an overlay

Options for djgpp2/coff:
  --coff              produce COFF output [default: EXE]

Options for dos/com:
  --8086              make compressed com work on any 8086

Options for dos/exe:
  --8086              make compressed exe work on any 8086
  --no-reloc          put no relocations in to the exe header

Options for dos/sys:
  --8086              make compressed sys work on any 8086

Options for ps1/exe:
  --8-bit             uses 8 bit size compression [default: 32 bit]
  --8mib-ram          8 megabyte memory limit [default: 2 MiB]
  --boot-only         disables client/host transfer compatibility
  --no-align          don't align to 2048 bytes [enables: --console-run]

Options for watcom/le:
  --le                produce LE output [default: EXE]

Options for win32/pe, win64/pe, rtm32/pe & arm/pe:
  --compress-exports=0    do not compress the export section
  --compress-exports=1    compress the export section [default]
  --compress-icons=0      do not compress any icons
  --compress-icons=1      compress all but the first icon
  --compress-icons=2      compress all but the first icon directory [default]
  --compress-icons=3      compress all icons
  --compress-resources=0  do not compress any resources at all
  --keep-resource=list    do not compress resources specified by list
  --strip-relocs=0        do not strip relocations
  --strip-relocs=1        strip relocations [default]

Options for linux/elf:
  --preserve-build-id     copy .gnu.note.build-id to compressed output

file..   executables to (de)compress

This version supports:
    amd64-darwin.dylib                   dylib/amd64
    amd64-darwin.macho                   macho/amd64
    amd64-linux.elf                      linux/amd64
    amd64-linux.kernel.vmlinux           vmlinux/amd64
    amd64-win64.pe                       win64/pe
    arm-darwin.macho                     macho/arm
    arm-linux.elf                        linux/arm
    arm-linux.kernel.vmlinux             vmlinux/arm
    arm-linux.kernel.vmlinuz             vmlinuz/arm
    arm-wince.pe                         arm/pe
    arm64-darwin.macho                   macho/arm64
    arm64-linux.elf                      linux/arm64
    armeb-linux.elf                      linux/armeb
    armeb-linux.kernel.vmlinux           vmlinux/armeb
    fat-darwin.macho                     macho/fat
    i086-dos16.com                       dos/com
    i086-dos16.exe                       dos/exe
    i086-dos16.sys                       dos/sys
    i386-bsd.elf.execve                  bsd.exec/i386
    i386-darwin.macho                    macho/i386
    i386-dos32.djgpp2.coff               djgpp2/coff
    i386-dos32.tmt.adam                  tmt/adam
    i386-dos32.watcom.le                 watcom/le
    i386-freebsd.elf                     freebsd/i386
    i386-linux.elf                       linux/i386
    i386-linux.elf.execve                linux.exec/i386
    i386-linux.elf.shell                 linux.sh/i386
    i386-linux.kernel.bvmlinuz           bvmlinuz/i386
    i386-linux.kernel.vmlinux            vmlinux/i386
    i386-linux.kernel.vmlinuz            vmlinuz/i386
    i386-netbsd.elf                      netbsd/i386
    i386-openbsd.elf                     openbsd/i386
    i386-win32.pe                        win32/pe
    m68k-atari.tos                       atari/tos
    mips-linux.elf                       linux/mips
    mipsel-linux.elf                     linux/mipsel
    mipsel.r3000-ps1                     ps1/exe
    powerpc-darwin.macho                 macho/ppc32
    powerpc-linux.elf                    linux/ppc32
    powerpc-linux.kernel.vmlinux         vmlinux/ppc32
    powerpc64-linux.elf                  linux/ppc64
    powerpc64le-darwin.macho             macho/ppc64le
    powerpc64le-linux.elf                linux/ppc64le
    powerpc64le-linux.kernel.vmlinux     vmlinux/ppc64le

UPX comes with ABSOLUTELY NO WARRANTY; for details visit https://upx.github.io

```

### Loaded Modules:

Path |
-- |
C:\program files\PeaZip\res\upx\upx.exe |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\SYSTEM32\ntdll.dll |


## Signature

* Status: The file C:\program files\PeaZip\res\upx\upx.exe is not digitally signed. You cannot run this script on the current system. For more information about running scripts and setting execution policy, see about_Execution_Policies at https:/go.microsoft.com/fwlink/?LinkID=135170
* Serial: ``
* Thumbprint: ``
* Issuer: 
* Subject: 

## File Metadata

* Original Filename: upx.exe
* Product Name: UPX
* Company Name: The UPX Team https://upx.github.io
* File Version: 3.95 (2018-08-26)
* Product Version: 3.95 (2018-08-26)
* Language: English (United States)
* Legal Copyright:  1996-2018 Markus F.X.J. Oberhumer





MIT License. Copyright (c) 2020 Strontic.


