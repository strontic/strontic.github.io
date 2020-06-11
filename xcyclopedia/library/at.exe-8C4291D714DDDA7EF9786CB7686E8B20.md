
# at.exe 

* File Path: `C:\Windows\system32\at.exe`
* Description: Schedule service command line interface
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `8C4291D714DDDA7EF9786CB7686E8B20`
SHA1 | `FE26135A938F4058F60106346833D1C3A25E7479`
SHA256 | `A60D4E00E9DF07AC09C8C607239DB08BB7D167299572E4436A5B14CC2BF2AD26`
SHA384 | `A8B86C450DEB438E4D6D09FED78DAA31624B8EF21FAD67D9623EF4CC2C7039467EBEA2A3D38CBA7679FCAB24DF657CB0`
SHA415 | `86AF53290DF291DB062AA0C51F4EC968DDC1F7E802A2504190B3FE25296F687CC50B4EFF6D6C590582863B5EDC40C6CA1A66A9B994E6A687FE0622EC9CE03B1A`
SSDEEP | `768:Cdagjj8+Dno7dR7gi8mAShL74iAeXuUjn/p:kWRxn8ZSiIug/p`

## Runtime Data

### Usage (stdout):
```Batchfile
The AT command has been deprecated. Please use schtasks.exe instead.

Invalid command.

The AT command schedules commands and programs to run on a computer at      
a specified time and date. The Schedule service must be running to use      
the AT command.
                                                           
AT [\\computername] [ [id] [/DELETE] | /DELETE [/YES]]                    
AT [\\computername] time [/INTERACTIVE]
    [ /EVERY:date[,...] | /NEXT:date[,...]] "command"

\\computername     Specifies a remote computer. Commands are scheduled on the
                   local computer if this parameter is omitted.             
id                 Is an identification number assigned to a scheduled      
                   command.                                                 
/delete            Cancels a scheduled command. If id is omitted, all the
                   scheduled commands on the computer are canceled.
/yes               Used with cancel all jobs command when no further
                   confirmation is desired.
time               Specifies the time when command is to run.
/interactive       Allows the job to interact with the desktop of the user   
                   who is logged on at the time the job runs.
/every:date[,...]  Runs the command on each specified day(s) of the week or
                   month. If date is omitted, the current day of the month
                   is assumed.                                              
/next:date[,...]   Runs the specified command on the next occurrence of the
                   day (for example, next Thursday).  If date is omitted, the
                   current day of the month is assumed.
"command"          Is the Windows NT command, or batch program to be run.


```

### Usage (stderr):
```Batchfile

```

### Child Processes:


## Signature

* Status: Signature verified.
* Serial: 33000000BCE120FDD27CC8EE930000000000BC
* Thumbprint: E85459B23C232DB3CB94C7A56D47678F58E8E51E
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: AT.EXE.MUI
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.14393.0 (rs1_release.160715-1616)
* Product Version: 10.0.14393.0
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.

MIT License. Copyright (c) 2020 Strontic.


