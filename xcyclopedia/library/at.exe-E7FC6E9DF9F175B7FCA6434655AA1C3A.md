
# at.exe 

* File Path: `C:\WINDOWS\SysWOW64\at.exe`
* Description: Schedule service command line interface
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `E7FC6E9DF9F175B7FCA6434655AA1C3A`
SHA1 | `C6EA77C7F5D2ED82779E877273B0FD7C06CECDFA`
SHA256 | `7EA14E4186AD9771F5572CF364D1801521551B2C482C5E9945D56A54093BB773`
SHA384 | `1B7E5173359116817C6C31DCF437FD34520B948D48A32C4EEDB44293D3F04CE1D8B125D70025798BFB76AFE4F49B7CE1`
SHA415 | `D5832F6583C8AD5CE4C88B763FC51C0D61220AD18A17B36E63DF819C4A547EF81F40FD8470934433A6C9C48CF80600BCB2E5F84D6AC4FB00FE61AA83E54FBDE2`
SSDEEP | `384:BeOCq/oHKXbeoFBNiUd/2SRy9Wh/HCa1okag+7lwUcXc/fspkJ7v3WxwWlmF4:MwMKqoFBNiUgl9WhPkiVM/gkJ7mR`

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

MIT License. Copyright (c) 2020 Strontic.


