
# at.exe 

* File Path: `C:\Windows\SysWOW64\at.exe`
* Description: Schedule service command line interface
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `98E0E72F1DE169DB1E2D85C4D93A011C`
SHA1 | `DAB503EDF518E58C03827AD4EF312702A0F37398`
SHA256 | `3616779903B0C2339744C3C69C264A0B69772B5B8CDADDC64FD1AAFB8321AFBA`
SHA384 | `CC4644FF1FF7A0C0AF2E584B569BD147E4B91243B24803C26C8CFEE42A14DA631162681EE6921242821B6A6D0291B02E`
SHA415 | `D31521C24EB66D9ACE7FE42801A040E90991D7AD6EE70EC04419696864DA9D7106E272E6A4C61FA9D4BDC179D955DCC97FFB853E16E8A1FF3EF7406EC44C8E3E`
SSDEEP | `384:OOA2Uq5LZ/IrP3RngxYk+w3sEXMF/XJtWi9uCHXjaTwnutDfmf1NupvAWfwWxR:OYlLZEhgxzdcFeehtMuf1Nupp`

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


