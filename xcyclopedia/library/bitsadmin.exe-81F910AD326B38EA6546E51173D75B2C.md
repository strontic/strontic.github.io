
# bitsadmin.exe 

* File Path: `C:\WINDOWS\SysWOW64\bitsadmin.exe`
* Description: BITS administration utility
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `81F910AD326B38EA6546E51173D75B2C`
SHA1 | `E6D261BA73FDC5623CEAA04EAF39C0AF5A2D815E`
SHA256 | `C5ADC38E0CE99A16CBBFCC10F16AA3A340CA0DCFF836607D6F6152322013A129`
SHA384 | `4B2BEF81BCD7893CE86DF048B996E98F3C76AF1DF72D1E4CFA159F3E34BAF1DFF25C14C6719D4E1C0D67B0B5CC9BB553`
SHA512 | `7086F8F42DA304896107923C7951FBFDFD7A3450DF4D36859E7C86F529EFEF657ECAA797807371B30066E11E423F908DA70CED0EEB9509341AC9BA925673F2FF`
SSDEEP | `3072:g8D853+Y/8tEONgK2SzecuFPOJrFzspK1en4NWc0jRuEiWM:glKZzuFPu1Gz/`

## Runtime Data

### Usage (stdout):
```Batchfile

BITSADMIN version 3.0
BITS administration utility.
(C) Copyright Microsoft Corp.

Invalid command
USAGE: BITSADMIN [/RAWRETURN] [/WRAP | /NOWRAP] command
The following commands are available:

/HELP           Prints this help 
/?              Prints this help 
/UTIL /?        Prints the list of utilities commands 
/PEERCACHING /?   Prints the list of commands to manage Peercaching
/CACHE /?       Prints the list of cache management commands 
/PEERS /?       Prints the list of peer management commands

/LIST    [/ALLUSERS] [/VERBOSE]     List the jobs
/MONITOR [/ALLUSERS] [/REFRESH sec] Monitors the copy manager
/RESET   [/ALLUSERS]                Deletes all jobs in the manager

/TRANSFER <job name> [type] [/PRIORITY priority] [/ACLFLAGS flags] [/DYNAMIC] 
          remote_url local_name
    Transfers one of more files.
    [type] may be /DOWNLOAD or /UPLOAD; default is download
    Multiple URL/file pairs may be specified.
    Unlike most commands, <job name> may only be a name and not a GUID.
    /DYNAMIC configures the job with BITS_JOB_PROPERTY_DYNAMIC_CONTENT, which relaxes the server-side requirements.

/CREATE [type] <job name>               Creates a job
    [type] may be /DOWNLOAD, /UPLOAD, or /UPLOAD-REPLY; default is download
    Unlike most commands, <job name> may only be a name and not a GUID.

/INFO <job> [/VERBOSE]                   Displays information about the job
/ADDFILE <job> <remote_url> <local_name> Adds a file to the job
/ADDFILESET <job> <textfile>             Adds multiple files to the job
   Each line of <textfile> lists a file's remote name and local name, separated
   by spaces.  A line beginning with '#' is treated as a comment.
   Once the file set is read into memory, the contents are added to the job.

/ADDFILEWITHRANGES  <job> <remote_url> <local_name range_list>
   Like /ADDFILE, but BITS will read only selected byte ranges of the URL.
   range_list is a comma-delimited series of offset and length pairs.
   For example,

       0:100,2000:100,5000:eof

   instructs BITS to read 100 bytes starting at offset zero, 100 bytes starting
   at offset 2000, and the remainder of the URL starting at offset 5000.

/REPLACEREMOTEPREFIX <job> <old_prefix> <new_prefix>
    All files whose URL begins with <old_prefix> are changed to use <new_prefix>

Note that BITS currently supports HTTP/HTTPS downloads and uploads.
It also supports UNC paths and file:// paths as URLS

/LISTFILES <job>                     Lists the files in the job
/SUSPEND <job>                       Suspends the job
/RESUME <job>                        Resumes the job
/CANCEL <job>                        Cancels the job
/COMPLETE <job>                      Completes the job

/GETTYPE <job>                       Retrieves the job type
/GETACLFLAGS <job>                   Retrieves the ACL propagation flags

/SETACLFLAGS <job> <ACL_flags>       Sets the ACL propagation flags for the job
  O - OWNER       G - GROUP 
  D - DACL        S - SACL  

  Examples:
      bitsadmin /setaclflags MyJob OGDS
      bitsadmin /setaclflags MyJob OGD

/GETBYTESTOTAL <job>                 Retrieves the size of the job
/GETBYTESTRANSFERRED <job>           Retrieves the number of bytes transferred
/GETFILESTOTAL <job>                 Retrieves the number of files in the job
/GETFILESTRANSFERRED <job>           Retrieves the number of files transferred
/GETCREATIONTIME <job>               Retrieves the job creation time
/GETMODIFICATIONTIME <job>           Retrieves the job modification time
/GETCOMPLETIONTIME <job>             Retrieves the job completion time
/GETSTATE <job>                      Retrieves the job state
/GETERROR <job>                      Retrieves detailed error information
/GETOWNER <job>                      Retrieves the job owner
/GETDISPLAYNAME <job>                Retrieves the job display name
/SETDISPLAYNAME <job> <display_name> Sets the job display name
/GETDESCRIPTION <job>                Retrieves the job description
/SETDESCRIPTION <job> <description>  Sets the job description
/GETPRIORITY    <job>                Retrieves the job priority
/SETPRIORITY    <job> <priority>     Sets the job priority
   Priority usage choices:
      FOREGROUND 
      HIGH
      NORMAL
      LOW
/GETNOTIFYFLAGS <job>                 Retrieves the notify flags
/SETNOTIFYFLAGS <job> <notify_flags>  Sets the notify flags
    For more help on this option, please refer to the MSDN help page for SetNotifyFlags/GETNOTIFYINTERFACE <job>             Determines if notify interface is registered
/GETMINRETRYDELAY <job>               Retrieves the retry delay in seconds
/SETMINRETRYDELAY <job> <retry_delay> Sets the retry delay in seconds
/GETNOPROGRESSTIMEOUT <job>           Retrieves the no progress timeout in seconds
/SETNOPROGRESSTIMEOUT <job> <timeout> Sets the no progress timeout in seconds
/GETMAXDOWNLOADTIME <job>             Retrieves the download timeout in seconds
/SETMAXDOWNLOADTIME <job> <timeout>   Sets the download timeout in seconds
/GETERRORCOUNT <job>                  Retrieves an error count for the job

/SETPROXYSETTINGS <job> <usage>      Sets the proxy usage
   usage choices:
    PRECONFIG   - Use the owner's default Internet settings.
    AUTODETECT  - Force autodetection of proxy.
    NO_PROXY    - Do not use a proxy server.
    OVERRIDE    - Use an explicit proxy list and bypass list. 
                  Must be followed by a proxy list and a proxy bypass list.
                  NULL or "" may be used for an empty proxy bypass list.
  Examples:
      bitsadmin /setproxysettings MyJob PRECONFIG
      bitsadmin /setproxysettings MyJob AUTODETECT
      bitsadmin /setproxysettings MyJob NO_PROXY
      bitsadmin /setproxysettings MyJob OVERRIDE proxy1:80 "<local>" 
      bitsadmin /setproxysettings MyJob OVERRIDE proxy1,proxy2,proxy3 NULL 

/GETPROXYUSAGE <job>                 Retrieves the proxy usage setting
/GETPROXYLIST <job>                  Retrieves the proxy list
/GETPROXYBYPASSLIST <job>            Retrieves the proxy bypass list

/TAKEOWNERSHIP <job>                 Take ownership of the job

/SETNOTIFYCMDLINE <job> <program_name> [program_parameters] 
    Sets a program to execute for notification, and optionally parameters.
    The program name and parameters can be NULL.
    IMPORTANT: if parameters are non-NULL, then the program name should be the
               first parameter.

  Examples:
    bitsadmin /SetNotifyCmdLine MyJob c:\winnt\system32\notepad.exe  NULL
    bitsadmin /SetNotifyCmdLine MyJob c:\callback.exe "c:\callback.exe parm1 parm2" 
    bitsadmin /SetNotifyCmdLine MyJob NULL NULL

/GETNOTIFYCMDLINE <job>              Returns the job's notification command line

/SETCREDENTIALS <job> <target> <scheme> <username> <password>
  Adds credentials to a job.
  <target> may be either SERVER or PROXY
  <scheme> may be BASIC, DIGEST, NTLM, NEGOTIATE, or PASSPORT. 

/REMOVECREDENTIALS <job> <target> <scheme> 
  Removes credentials from a job.
/GETCUSTOMHEADERS <job>                           Gets the Custom HTTP Headers
/SETCUSTOMHEADERS <job> <header1> <header2> <...> Sets the Custom HTTP Headers
/MAKECUSTOMHEADERSWRITEONLY <job>                 Make a job's Custom HTTP Headers write-only (cannot be undone).

/GETHTTPMETHOD <job>                           Gets the HTTP verb to use.
/SETHTTPMETHOD <job> <HTTPMethod>              Sets the HTTP verb to use.

/GETCLIENTCERTIFICATE <job>                       Gets the job's Client Certificate Information
/SETCLIENTCERTIFICATEBYID <job> <store_location> <store_name> <hexa-decimal_cert_id>
  Sets a client authentication certificate to a job.
  <store_location> may be 
	1(CURRENT_USER), 2(LOCAL_MACHINE), 3(CURRENT_SERVICE),
	4(SERVICES), 5(USERS), 6(CURRENT_USER_GROUP_POLICY),
	7(LOCAL_MACHINE_GROUP_POLICY) or 8(LOCAL_MACHINE_ENTERPRISE). 

/SETCLIENTCERTIFICATEBYNAME <job> <store_location> <store_name> <subject_name>
  Sets a client authentication certificate to a job.
  <store_location> may be 
	1(CURRENT_USER), 2(LOCAL_MACHINE), 3(CURRENT_SERVICE),
	4(SERVICES), 5(USERS), 6(CURRENT_USER_GROUP_POLICY),
	7(LOCAL_MACHINE_GROUP_POLICY) or 8(LOCAL_MACHINE_ENTERPRISE). 

/REMOVECLIENTCERTIFICATE <job>                Removes the Client Certificate Information from the job

/SETSECURITYFLAGS <job> <value>   
   Sets the HTTP security flags for URL redirection and checks performed on the server certificate during the transfer.
   The value is an unsigned integer with the following interpretation for the bits in the binary representation.
     Enable CRL Check                                 : Set the least significant bit
     Ignore invalid common name in server certificate : Set the 2nd bit from right
     Ignore invalid date in  server certificate       : Set the 3rd bit from right
     Ignore invalid certificate authority in server
       certificate                                    : Set the 4th bit from right
     Ignore invalid usage of certificate              : Set the 5th bit from right
     Redirection policy                               : Controlled by the 9th-11th bits from right
         0,0,0  - Redirects will be automatically allowed.
         0,0,1  - Remote name in the IBackgroundCopyFile interface will be updated if a redirect occurs.
         0,1,0  - BITS will fail the job if a redirect occurs.

     Allow redirection from HTTPS to HTTP             : Set the 12th bit from right

/GETSECURITYFLAGS <job>   
   Reports the HTTP security flags for URL redirection and checks performed on the server certificate during the transfer.

/SETVALIDATIONSTATE  <job>  <file-index> <true|false>
      <file-index> starts from 0          
    Sets the content-validation state of the given file within the job.

/GETVALIDATIONSTATE  <job>  <file-index>  
      <file-index> starts from 0          
    Reports the content-validation state of the given file within the job.

/GETTEMPORARYNAME  <job>  <file-index>  
      <file-index> starts from 0          
    Reports the temporary filename of the given file within the job.

The following options control peercaching of a particular job:

/SETPEERCACHINGFLAGS  <job> <value>   
    Sets the flags for the job's peercaching behavior.
    The value is an unsigned integer with the following interpretation for the bits in the binary representation.
        Allow the job's data to be downloaded from a peer : Set the least significant bit
        Allow the job's data to be served to peers        : Set the 2nd bit from right

/GETPEERCACHINGFLAGS  <job>               
    Reports the flags for the job's peercaching behavior.

The following options are valid for UPLOAD-REPLY jobs only:

/GETREPLYFILENAME <job>        Gets the path of the file containing the server reply
/SETREPLYFILENAME <job> <path> Sets the path of the file containing the server reply
/GETREPLYPROGRESS <job>        Gets the size and progress of the server reply
/GETREPLYDATA     <job>        Dumps the server's reply data in hex format

/SETHELPERTOKEN <job>          Sets the current command prompt's primary token as a job's helper token
/GETHELPERTOKENSID <job>       Reports the user account SID of a job's helper token, if one is set

/SETHELPERTOKENFLAGS <job> <flags> 
    Sets the helper token usage flags for a job. Possible values are:
        1 - The helper token is used when accessing the local filesystem.
        2 - The helper token is used when accessing the network.
        3 - The helper token is used when accessing both the local filesystem and the network.

/GETHELPERTOKENFLAGS <job> 
    Reports a job's helper token usage flags.

/GETPEERSTATS <job> <file-index> 
    <file-index> starts from 0 
    Reports statistics about the amount of data downloaded from peers and origin servers for a specific file within a job.

The following options can be placed before the command:
/RAWRETURN                     Return data more suitable for parsing
/WRAP                          Wrap output around console (default)
/NOWRAP                        Don't wrap output around console

The /RAWRETURN option strips new line characters and formatting.
It is recognized by the /CREATE and /GET* commands.

Commands that take a <job> parameter will accept either a job name or a job ID
GUID inside braces.  BITSADMIN reports an error if a name is ambiguous.

```

### Usage (stderr):
```Batchfile

```

### Child Processes:


## Signature

* Status: Signature verified.
* Serial: `330000023241FB59996DCC4DFF000000000232`
* Thumbprint: `FF82BC38E1DA5E596DF374C53E3617F7EDA36B06`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: bitsadmin.exe
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 7.8.18362.1 (WinBuild.160101.0800)
* Product Version: 7.8.18362.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.


## Additional Info

*Source: [MicrosoftDocs](https://github.com/MicrosoftDocs/windowsserverdocs) by [Microsoft](https://opensource.microsoft.com/codeofconduct/), available under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) license. Some links modified.*

---
# bitsadmin

> Applies to: Windows Server (Semi-Annual Channel), Windows Server 2019, Windows Server 2016, Windows Server 2012 R2, Windows Server 2012, Windows 10

Bitsadmin is a command-line tool used to create, download or upload jobs, and to monitor their progress. The bitsadmin tool uses switches to identify the work to perform. You can call `bitsadmin /?` or `bitsadmin /help` to get a list of switches.

Most switches require a `<job>` parameter, which you set to the job's display name, or GUID. A job's display name doesn't have to be unique. The **/create** and **/list** switches return a job's GUID.

By default, you can access information about your own jobs. To access information for another user's jobs, you must have administrator privileges. If the job was created in an elevated state, then you must run **bitsadmin** from an elevated window; otherwise, you'll have read-only access to the job.

Many of the switches correspond to methods in the [BITS interfaces](https://docs.microsoft.com/windows/win32/bits/bits-interfaces). For additional details that may be relevant to using a switch, see the corresponding method.

Use the following switches to create a job, set and retrieve the properties of a job, and monitor the status of a job. For examples that show how to use some of these switches to perform tasks, see [bitsadmin examples](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/bitsadmin-examples.md).

## Available switches

- [bitsadmin /addfile](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/bitsadmin-addfile.md)
- [bitsadmin /addfileset](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/bitsadmin-addfileset.md)
- [bitsadmin /addfilewithranges](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/bitsadmin-addfilewithranges.md)
- [bitsadmin /cache](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/bitsadmin-cache.md)
- [bitsadmin /cache /delete](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/bitsadmin-cache-and-delete.md)
- [bitsadmin /cache /deleteurl](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/bitsadmin-cache-and-deleteurl.md)
- [bitsadmin /cache /getexpirationtime](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/bitsadmin-cache-and-getexpirationtime.md)
- [bitsadmin /cache /getlimit](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/bitsadmin-cache-and-getlimit.md)
- [bitsadmin /cache /help](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/bitsadmin-cache-and-help.md)
- [bitsadmin /cache /info](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/bitsadmin-cache-and-info.md)
- [bitsadmin /cache /list](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/bitsadmin-cache-and-list.md)
- [bitsadmin /cache /setexpirationtime](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/bitsadmin-cache-and-setexpirationtime.md)
- [bitsadmin /cache /setlimit](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/bitsadmin-cache-and-setlimit.md)
- [bitsadmin /cache /clear](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/bitsadmin-cache-clear.md)
- [bitsadmin /cancel](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/bitsadmin-cancel.md)
- [bitsadmin /complete](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/bitsadmin-complete.md)
- [bitsadmin /create](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/bitsadmin-create.md)
- [bitsadmin /examples](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/bitsadmin-examples.md)
- [bitsadmin /getaclflags](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/bitsadmin-getaclflags.md)
- [bitsadmin /getbytestotal](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/bitsadmin-getbytestotal.md)
- [bitsadmin /getbytestransferred](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/bitsadmin-getbytestransferred.md)
- [bitsadmin /getclientcertificate](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/bitsadmin-getclientcertificate.md)
- [bitsadmin /getcompletiontime](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/bitsadmin-getcompletiontime.md)
- [bitsadmin /getcreationtime](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/bitsadmin-getcreationtime.md)
- [bitsadmin /getcustomheaders](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/bitsadmin-getcustomheaders.md)
- [bitsadmin /getdescription](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/bitsadmin-getdescription.md)
- [bitsadmin /getdisplayname](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/bitsadmin-getdisplayname.md)
- [bitsadmin /geterror](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/bitsadmin-geterror.md)
- [bitsadmin /geterrorcount](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/bitsadmin-geterrorcount.md)
- [bitsadmin /getfilestotal](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/bitsadmin-getfilestotal.md)
- [bitsadmin /getfilestransferred](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/bitsadmin-getfilestransferred.md)
- [bitsadmin /gethelpertokenflags](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/bitsadmin-gethelpertokenflags.md)
- [bitsadmin /gethelpertokensid](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/bitsadmin-gethelpertokensid.md)
- [bitsadmin /gethttpmethod](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/bitsadmin-gethttpmethod.md)
- [bitsadmin /getmaxdownloadtime](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/bitsadmin-getmaxdownloadtime.md)
- [bitsadmin /getminretrydelay](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/bitsadmin-getminretrydelay.md)
- [bitsadmin /getmodificationtime](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/bitsadmin-getmodificationtime.md)
- [bitsadmin /getnoprogresstimeout](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/bitsadmin-getnoprogresstimeout.md)
- [bitsadmin /getnotifycmdline](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/bitsadmin-getnotifycmdline.md)
- [bitsadmin /getnotifyflags](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/bitsadmin-getnotifyflags.md)
- [bitsadmin /getnotifyinterface](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/bitsadmin-getnotifyinterface.md)
- [bitsadmin /getowner](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/bitsadmin-getowner.md)
- [bitsadmin /getpeercachingflags](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/bitsadmin-getpeercachingflags.md)
- [bitsadmin /getpriority](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/bitsadmin-getpriority.md)
- [bitsadmin /getproxybypasslist](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/bitsadmin-getproxybypasslist.md)
- [bitsadmin /getproxylist](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/bitsadmin-getproxylist.md)
- [bitsadmin /getproxyusage](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/bitsadmin-getproxyusage.md)
- [bitsadmin /getreplydata](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/bitsadmin-getreplydata.md)
- [bitsadmin /getreplyfilename](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/bitsadmin-getreplyfilename.md)
- [bitsadmin /getreplyprogress](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/bitsadmin-getreplyprogress.md)
- [bitsadmin /getsecurityflags](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/bitsadmin-getsecurityflags.md)
- [bitsadmin /getstate](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/bitsadmin-getstate.md)
- [bitsadmin /gettemporaryname](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/bitsadmin-gettemporaryname.md)
- [bitsadmin /gettype](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/bitsadmin-gettype.md)
- [bitsadmin /getvalidationstate](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/bitsadmin-getvalidationstate.md)
- [bitsadmin /help](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/bitsadmin-help.md)
- [bitsadmin /info](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/bitsadmin-info.md)
- [bitsadmin /list](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/bitsadmin-list.md)
- [bitsadmin /listfiles](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/bitsadmin-listfiles.md)
- [bitsadmin /makecustomheaderswriteonly](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/bitsadmin-makecustomheaderswriteonly.md)
- [bitsadmin /monitor](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/bitsadmin-monitor.md)
- [bitsadmin /nowrap](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/bitsadmin-nowrap.md)
- [bitsadmin /peercaching](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/bitsadmin-peercaching.md)
- [bitsadmin /peercaching /getconfigurationflags](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/bitsadmin-peercaching-and-getconfigurationflags.md)
- [bitsadmin /peercaching /help](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/bitsadmin-peercaching-and-help.md)
- [bitsadmin /peercaching /setconfigurationflags](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/bitsadmin-peercaching-and-setconfigurationflags.md)
- [bitsadmin /peers](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/bitsadmin-peers.md)
- [bitsadmin /peers /clear](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/bitsadmin-peers-and-clear.md)
- [bitsadmin /peers /discover](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/bitsadmin-peers-and-discover.md)
- [bitsadmin /peers /help](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/bitsadmin-peers-and-help.md)
- [bitsadmin /peers /list](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/bitsadmin-peers-and-list.md)
- [bitsadmin /rawreturn](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/bitsadmin-rawreturn.md)
- [bitsadmin /removeclientcertificate](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/bitsadmin-removeclientcertificate.md)
- [bitsadmin /removecredentials](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/bitsadmin-removecredentials.md)
- [bitsadmin /replaceremoteprefix](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/bitsadmin-replaceremoteprefix.md)
- [bitsadmin /reset](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/bitsadmin-reset.md)
- [bitsadmin /resume](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/bitsadmin-resume.md)
- [bitsadmin /setaclflag](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/bitsadmin-setaclflag.md)
- [bitsadmin /setclientcertificatebyid](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/bitsadmin-setclientcertificatebyid.md)
- [bitsadmin /setclientcertificatebyname](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/bitsadmin-setclientcertificatebyname.md)
- [bitsadmin /setcredentials](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/bitsadmin-setcredentials.md)
- [bitsadmin /setcustomheaders](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/bitsadmin-setcustomheaders.md)
- [bitsadmin /setdescription](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/bitsadmin-setdescription.md)
- [bitsadmin /setdisplayname](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/bitsadmin-setdisplayname.md)
- [bitsadmin /sethelpertoken](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/bitsadmin-sethelpertoken.md)
- [bitsadmin /sethelpertokenflags](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/bitsadmin-sethelpertokenflags.md)
- [bitsadmin /sethttpmethod](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/bitsadmin-sethttpmethod.md)
- [bitsadmin /setmaxdownloadtime](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/bitsadmin-setmaxdownloadtime.md)
- [bitsadmin /setminretrydelay](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/bitsadmin-setminretrydelay.md)
- [bitsadmin /setnoprogresstimeout](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/bitsadmin-setnoprogresstimeout.md)
- [bitsadmin /setnotifycmdline](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/bitsadmin-setnotifycmdline.md)
- [bitsadmin /setnotifyflags](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/bitsadmin-setnotifyflags.md)
- [bitsadmin /setpeercachingflags](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/bitsadmin-setpeercachingflags.md)
- [bitsadmin /setpriority](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/bitsadmin-setpriority.md)
- [bitsadmin /setproxysettings](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/bitsadmin-setproxysettings.md)
- [bitsadmin /setreplyfilename](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/bitsadmin-setreplyfilename.md)
- [bitsadmin /setsecurityflags](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/bitsadmin-setsecurityflags.md)
- [bitsadmin /setvalidationstate](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/bitsadmin-setvalidationstate.md)
- [bitsadmin /suspend](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/bitsadmin-suspend.md)
- [bitsadmin /takeownership](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/bitsadmin-takeownership.md)
- [bitsadmin /transfer](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/bitsadmin-transfer.md)
- [bitsadmin /util](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/bitsadmin-util.md)
- [bitsadmin /util /enableanalyticchannel](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/bitsadmin-util-and-enableanalyticchannel.md)
- [bitsadmin /util /getieproxy](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/bitsadmin-util-and-getieproxy.md)
- [bitsadmin /util /help](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/bitsadmin-util-and-help.md)
- [bitsadmin /util /repairservice](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/bitsadmin-util-and-repairservice.md)
- [bitsadmin /util /setieproxy](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/bitsadmin-util-and-setieproxy.md)
- [bitsadmin /util /version](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/bitsadmin-util-and-version.md)
- [bitsadmin /wrap](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/bitsadmin-wrap.md)

---


MIT License. Copyright (c) 2020 Strontic.


