
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
SHA415 | `7086F8F42DA304896107923C7951FBFDFD7A3450DF4D36859E7C86F529EFEF657ECAA797807371B30066E11E423F908DA70CED0EEB9509341AC9BA925673F2FF`
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
* Serial: 330000023241FB59996DCC4DFF000000000232
* Thumbprint: FF82BC38E1DA5E596DF374C53E3617F7EDA36B06
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


