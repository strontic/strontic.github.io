
# at.exe 
* File Path: `C:\WINDOWS\system32\at.exe`
* Description: Schedule service command line interface
* Comments: 

## Hashes
Type | Hash
-- | --
MD5 | `E2A9C62B47F64525F7EB0CB8D637FF90`
SHA1 | `82897C9427D84261E578DE8B3DC89ABBA51D218B`
SHA256 | `3375D519FB68BC608AB444D5A367DF55F3B2353AF9BE3E88462F08006FB846BC`
SHA384 | `59D85696370D204747A0A2A679F4A44F6A422B06C5473DD6707A7F3D9745DCB92D973EDDB821ABB954E08FACD2387FBE`
SHA415 | `06226759E7841D0631C5F74817AF675862004DF72DBF71B75824C93B2BF5853AD45A1D53C155AF9D5566C09C4B0E12DE14AB04CFA0C9AAFE5AD4B11BEBA16E33`
SSDEEP | `384:TEFmkSTH3NBvyGi8JOewh8y6vl7LShugR4iZspBJvYA7v3WxwW2:TEFvgH9BvvJHwKftmt4iqBJvj7m`

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
* Serial: 3300000266BD1580EFA75CD6D3000000000266
* Thumbprint: A4341B9FD50FB9964283220A36A1EF6F6FAA7840
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: AT.EXE.MUI
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.18362.1 (WinBuild.160101.0800)
* Product Version: 10.0.18362.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.


