
# WMIC.exe 

* File Path: `C:\Windows\SysWOW64\wbem\WMIC.exe`
* Description: WMI Commandline Utility
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `AC7D85F15AF7E892847AE2DB2CCC2B1D`
SHA1 | `1C38D311C6B2EFA06DD35A08CDAC6EDAFB8C7CAA`
SHA256 | `969D91FFA56C80F82F893559316F6E1F12DC6C023411C43DAEDC80E8F9AC2652`
SHA384 | `1AE6A1E97A9F2815BCFE5BBF7B06D49DF4027514F280A43B65547EA10B3C939326A5193F91AC59F0246D7CA06925BF7E`
SHA512 | `289A90ABF8593EAC03B82565C0800110687D9F5FF7487B509A41C30ECDFE6EE0400B194C5FBDE3248491090CDA63EEA111A6E7FEF6866D193F2DD14A660C8115`
SSDEEP | `6144:9CS+YxhOEYGg86uby54NWCE88uw/OzkYrmdGH5enhqw6MLQ:9CSXm7GuubQ4O88d5hdGH0nhquLQ`

## Runtime Data

### Usage (stdout):
```Batchfile

[global switches] <command>

The following global switches are available:
/NAMESPACE           Path for the namespace the alias operate against.
/ROLE                Path for the role containing the alias definitions.
/NODE                Servers the alias will operate against.
/IMPLEVEL            Client impersonation level.
/AUTHLEVEL           Client authentication level.
/LOCALE              Language id the client should use.
/PRIVILEGES          Enable or disable all privileges.
/TRACE               Outputs debugging information to stderr.
/RECORD              Logs all input commands and output.
/INTERACTIVE         Sets or resets the interactive mode.
/FAILFAST            Sets or resets the FailFast mode.
/USER                User to be used during the session.
/PASSWORD            Password to be used for session login.
/OUTPUT              Specifies the mode for output redirection.
/APPEND              Specifies the mode for output redirection.
/AGGREGATE           Sets or resets aggregate mode.
/AUTHORITY           Specifies the <authority type> for the connection.
/?[:<BRIEF|FULL>]    Usage information.

For more information on a specific global switch, type: switch-name /?


The following alias/es are available in the current role:
ALIAS                    - Access to the aliases available on the local system
BASEBOARD                - Base board (also known as a motherboard or system board) management.
BIOS                     - Basic input/output services (BIOS) management.
BOOTCONFIG               - Boot configuration management.
CDROM                    - CD-ROM management.
COMPUTERSYSTEM           - Computer system management.
CPU                      - CPU management.
CSPRODUCT                - Computer system product information from SMBIOS. 
DATAFILE                 - DataFile Management.  
DCOMAPP                  - DCOM Application management.
DESKTOP                  - User's Desktop management.
DESKTOPMONITOR           - Desktop Monitor management.
DEVICEMEMORYADDRESS      - Device memory addresses management.
DISKDRIVE                - Physical disk drive management. 
DISKQUOTA                - Disk space usage for NTFS volumes.
DMACHANNEL               - Direct memory access (DMA) channel management.
ENVIRONMENT              - System environment settings management.
FSDIR                    - Filesystem directory entry management. 
GROUP                    - Group account management. 
IDECONTROLLER            - IDE Controller management.  
IRQ                      - Interrupt request line (IRQ) management. 
JOB                      - Provides  access to the jobs scheduled using the schedule service. 
LOADORDER                - Management of system services that define execution dependencies. 
LOGICALDISK              - Local storage device management.
LOGON                    - LOGON Sessions.  
MEMCACHE                 - Cache memory management.
MEMORYCHIP               - Memory chip information.
MEMPHYSICAL              - Computer system's physical memory management. 
NETCLIENT                - Network Client management.
NETLOGIN                 - Network login information (of a particular user) management. 
NETPROTOCOL              - Protocols (and their network characteristics) management.
NETUSE                   - Active network connection management.
NIC                      - Network Interface Controller (NIC) management.
NICCONFIG                - Network adapter management. 
NTDOMAIN                 - NT Domain management.  
NTEVENT                  - Entries in the NT Event Log.  
NTEVENTLOG               - NT eventlog file management. 
ONBOARDDEVICE            - Management of common adapter devices built into the motherboard (system board).
OS                       - Installed Operating System/s management. 
PAGEFILE                 - Virtual memory file swapping management. 
PAGEFILESET              - Page file settings management. 
PARTITION                - Management of partitioned areas of a physical disk.
PORT                     - I/O port management.
PORTCONNECTOR            - Physical connection ports management.
PRINTER                  - Printer device management. 
PRINTERCONFIG            - Printer device configuration management.  
PRINTJOB                 - Print job management. 
PROCESS                  - Process management. 
PRODUCT                  - Installation package task management. 
QFE                      - Quick Fix Engineering.  
QUOTASETTING             - Setting information for disk quotas on a volume. 
RDACCOUNT                - Remote Desktop connection permission management.
RDNIC                    - Remote Desktop connection management on a specific network adapter.
RDPERMISSIONS            - Permissions to a specific Remote Desktop connection.
RDTOGGLE                 - Turning Remote Desktop listener on or off remotely.
RECOVEROS                - Information that will be gathered from memory when the operating system fails. 
REGISTRY                 - Computer system registry management.
SCSICONTROLLER           - SCSI Controller management.  
SERVER                   - Server information management. 
SERVICE                  - Service application management. 
SHADOWCOPY               - Shadow copy management.
SHADOWSTORAGE            - Shadow copy storage area management.
SHARE                    - Shared resource management. 
SOFTWAREELEMENT          - Management of the  elements of a software product installed on a system.
SOFTWAREFEATURE          - Management of software product subsets of SoftwareElement. 
SOUNDDEV                 - Sound Device management.
STARTUP                  - Management of commands that run automatically when users log onto the computer system.
SYSACCOUNT               - System account management.  
SYSDRIVER                - Management of the system driver for a base service.
SYSTEMENCLOSURE          - Physical system enclosure management.
SYSTEMSLOT               - Management of physical connection points including ports,  slots and peripherals, and proprietary connections points.
TAPEDRIVE                - Tape drive management.  
TEMPERATURE              - Data management of a temperature sensor (electronic thermometer).
TIMEZONE                 - Time zone data management. 
UPS                      - Uninterruptible power supply (UPS) management. 
USERACCOUNT              - User account management.
VOLTAGE                  - Voltage sensor (electronic voltmeter) data management.
VOLUME                   - Local storage volume management.
VOLUMEQUOTASETTING       - Associates the disk quota setting with a specific disk volume. 
VOLUMEUSERQUOTA          - Per user storage volume quota management.
WMISET                   - WMI service operational parameters management. 

For more information on a specific alias, type: alias /?

CLASS     - Escapes to full WMI schema.
PATH      - Escapes to full WMI object paths.
CONTEXT   - Displays the state of all the global switches.
QUIT/EXIT - Exits the program.

For more information on CLASS/PATH/CONTEXT, type: (CLASS | PATH | CONTEXT) /?


```

### Usage (stderr):
```Batchfile
help - Alias not found.

```

### Child Processes:


## Signature

* Status: Signature verified.
* Serial: `33000000BCE120FDD27CC8EE930000000000BC`
* Thumbprint: `E85459B23C232DB3CB94C7A56D47678F58E8E51E`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: wmic.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.14393.0 (rs1_release.160715-1616)
* Product Version: 10.0.14393.0
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.




## Additional Info*

**The information below is copied from [MicrosoftDocs](https://github.com/MicrosoftDocs/windowsserverdocs), which is maintained by [Microsoft](https://opensource.microsoft.com/codeofconduct/). Available under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) license.*

---

# wmic



Displays WMI information inside an interactive command shell.



## Syntax

```
wmic </parameter>
```

## Sub-commands

The following sub-commands are available at all times:

|Sub-command|Description|
|-----------|-----------|
|class|Escapes from the default alias mode of WMIC to access classes in the WMI schema directly.|
|path|Escapes from the default alias mode of WMIC to access instances in the WMI schema directly.|
|context|Displays the current values of all global switches.|
|[quit \| exit]|Exits the WMIC command shell.|

## Examples

To display the current values of all global switches, type:
```
wmic context
```
Output similar to the following displays:
```
NAMESPACE    : root\cimv2
ROLE         : root\cli
NODE(S)      : BOBENTERPRISE
IMPLEVEL     : IMPERSONATE
[AUTHORITY   : N/A]
AUTHLEVEL    : PKTPRIVACY
LOCALE       : ms_409
PRIVILEGES   : ENABLE
TRACE        : OFF
RECORD       : N/A
INTERACTIVE  : OFF
FAILFAST     : OFF
OUTPUT       : STDOUT
APPEND       : STDOUT
USER         : N/A
AGGREGATE    : ON
```
To change the language ID used by the command line to English (locale ID 409), type:
```
wmic /locale:ms_409
```

## Additional References

- [Command-Line Syntax Key](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/command-line-syntax-key.md)

---


MIT License. Copyright (c) 2020 Strontic.


