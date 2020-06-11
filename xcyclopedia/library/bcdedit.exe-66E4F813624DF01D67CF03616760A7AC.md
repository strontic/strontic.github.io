
# bcdedit.exe 

* File Path: `C:\WINDOWS\system32\bcdedit.exe`
* Description: Boot Configuration Data Editor
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `66E4F813624DF01D67CF03616760A7AC`
SHA1 | `D599661803654109EB927CFF6245527A468ACFF7`
SHA256 | `1EE229900C128119A122F9A7B3FF8CA2AB35154B314FC6B37CDA6CE041E4277D`
SHA384 | `23B69B7CD60A7585F4B34DFAB95E4F49454EDCCB00572C11983C104FCB6DA1B56176F24C5863FE17DF97C6FCB6977561`
SHA415 | `D66427D200F9E65753CAB578D8A50008A4967D2E286F72B24C9E3E1FD7F03D5D164006FDFE7945BA80CCACEBB1E5CF870AD3AD66D361FACB1B46718D06E5C706`
SSDEEP | `6144:ON3c/dVFQtQDneFIrMZxhxm1JjzIpx7YOAr:ON3clXLDP4UznIz7YF`

## Runtime Data

### Usage (stdout):
```Batchfile

BCDEDIT - Boot Configuration Data Store Editor

The Bcdedit.exe command-line tool modifies the boot configuration data store.
The boot configuration data store contains boot configuration parameters and
controls how the operating system is booted. These parameters were previously
in the Boot.ini file (in BIOS-based operating systems) or in the nonvolatile
RAM entries (in Extensible Firmware Interface-based operating systems). You can
use Bcdedit.exe to add, delete, edit, and append entries in the boot
configuration data store.

For detailed command and option information, type bcdedit.exe /? <command>. For
example, to display detailed information about the /createstore command, type:

     bcdedit.exe /? /createstore

For an alphabetical list of topics in this help file, run "bcdedit /? TOPICS".

Commands that operate on a store
================================
/store          Used to specify a BCD store other than the current system default.
/createstore    Creates a new and empty boot configuration data store.
/export         Exports the contents of the system store to a file. This file
                can be used later to restore the state of the system store.
/import         Restores the state of the system store using a backup file
                created with the /export command.
/sysstore       Sets the system store device (only affects EFI systems, does
                not persist across reboots, and is only used in cases where
                the system store device is ambiguous).

Commands that operate on entries in a store
===========================================
/copy           Makes copies of entries in the store.
/create         Creates new entries in the store.
/delete         Deletes entries from the store.
/mirror         Creates mirror of entries in the store.

Run bcdedit /? ID for information about identifiers used by these commands.

Commands that operate on entry options
======================================
/deletevalue    Deletes entry options from the store.
/set            Sets entry option values in the store.

Run bcdedit /? TYPES for a list of datatypes used by these commands.
Run bcdedit /? FORMATS for a list of valid data formats.

Commands that control output
============================
/enum           Lists entries in the store.
/v              Command-line option that displays entry identifiers in full,
                rather than using names for well-known identifiers.
                Use /v by itself as a command to display entry identifiers
                in full for the ACTIVE type.

Running "bcdedit" by itself is equivalent to running "bcdedit /enum ACTIVE".

Commands that control the boot manager
======================================
/bootsequence   Sets the one-time boot sequence for the boot manager.
/default        Sets the default entry that the boot manager will use.
/displayorder   Sets the order in which the boot manager displays the
                multiboot menu.
/timeout        Sets the boot manager time-out value.
/toolsdisplayorder  Sets the order in which the boot manager displays
                    the tools menu.

Commands that control Emergency Management Services for a boot application
==========================================================================
/bootems        Enables or disables Emergency Management Services
                for a boot application.
/ems            Enables or disables Emergency Management Services for an
                operating system entry.
/emssettings    Sets the global Emergency Management Services parameters.

Command that control debugging
==============================
/bootdebug      Enables or disables boot debugging for a boot application.
/dbgsettings    Sets the global debugger parameters.
/debug          Enables or disables kernel debugging for an operating system
                entry.
/hypervisorsettings  Sets the hypervisor parameters.

Command that control remote event logging
=========================================
/eventsettings  Sets the global remote event logging parameters.
/event          Enables or disables remote event logging for an operating 
                system entry.


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

* Original Filename: bcdedit.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.18362.1 (WinBuild.160101.0800)
* Product Version: 10.0.18362.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.

MIT License. Copyright (c) 2020 Strontic.


