
# takeown.exe 

* File Path: `C:\WINDOWS\system32\takeown.exe`
* Description: Takes ownership of a file
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `3B62EF3A7FFB847A5DE4C4C0606C9C06`
SHA1 | `117CD4F0F9BE464E5B791CCE3A6EC35E3923E52E`
SHA256 | `90D519A81F59590742362461A730A67FA032806FCC53EE387B840FF04D056791`
SHA384 | `38FE2175A758DA2FEC888F2196748BE4C2501976DF8DCA54BD6FD0D112482FDDB2A245A5578A36901F593229FD6AAFEA`
SHA512 | `E7ACE90A57D90422DAF1538C63D6C7BE8403C2C0C0FF73EB2F2C5C5013F316AFFDCC65EFD9B076A67BE60C4712BA4B86013CBFFAFEEF87760DFCEAFC854BA062`
SSDEEP | `1536:Cd/zbnuhG3jxCfBfhW2VnG2UZOpWfiZamzAvl:uzbn9TshW8yOpOiZamm`

## Runtime Data

### Usage (stdout):
```Batchfile

TAKEOWN [/S system [/U username [/P [password]]]]
        /F filename [/A] [/R [/D prompt]]

Description:
    This tool allows an administrator to recover access to a file that
    was denied by re-assigning file ownership.

Parameter List: 
    /S           system          Specifies the remote system to
                                 connect to.

    /U           [domain\]user   Specifies the user context under
                                 which the command should execute.

    /P           [password]      Specifies the password for the
                                 given user context.
                                 Prompts for input if omitted.

    /F           filename        Specifies the filename or directory
                                 name pattern. Wildcard "*" can be used
                                 to specify the pattern. Allows
                                 sharename\filename.

    /A                           Gives ownership to the administrators
                                 group instead of the current user.

    /R                           Recurse: instructs tool to operate on
                                 files in specified directory and all 
                                 subdirectories.

    /D           prompt          Default answer used when the current user
                                 does not have the "list folder" permission
                                 on a directory.  This occurs while operating
                                 recursively (/R) on sub-directories. Valid 
                                 values "Y" to take ownership or "N" to skip.

    /SKIPSL                      Do not follow symbolic links.
                                 Only applicable with /R.

    /?                           Displays this help message.

    NOTE: 1) If /A is not specified, file ownership will be given to the
             current logged on user.

          2) Mixed patterns using "?" and "*" are not supported.

          3) /D is used to suppress the confirmation prompt.

Examples: 
    TAKEOWN /?
    TAKEOWN /F lostfile
    TAKEOWN /F \\system\share\lostfile /A
    TAKEOWN /F directory /R /D N
    TAKEOWN /F directory /R /A
    TAKEOWN /F *
    TAKEOWN /F C:\Windows\System32\acme.exe
    TAKEOWN /F %windir%\*.txt
    TAKEOWN /S system /F MyShare\Acme*.doc
    TAKEOWN /S system /U user /F MyShare\MyBinary.dll
    TAKEOWN /S system /U domain\user /P password /F share\filename
    TAKEOWN /S system /U user /P password /F Doc\Report.doc /A
    TAKEOWN /S system /U user /P password /F Myshare\* 
    TAKEOWN /S system /U user /P password /F Home\Logon /R
    TAKEOWN /S system /U user /P password /F Myshare\directory /R /A

```

### Usage (stderr):
```Batchfile
ERROR: Invalid argument/option - '-help'.
Type "TAKEOWN /?" for usage.

```

### Child Processes:


## Signature

* Status: Signature verified.
* Serial: `330000023241FB59996DCC4DFF000000000232`
* Thumbprint: `FF82BC38E1DA5E596DF374C53E3617F7EDA36B06`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: takeown.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.18362.1 (WinBuild.160101.0800)
* Product Version: 10.0.18362.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.


## Additional Info*

**The information below is copied from [MicrosoftDocs](https://github.com/MicrosoftDocs/windowsserverdocs) by [Microsoft](https://opensource.microsoft.com/codeofconduct/), available under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) license. Some links modified.*

---

# takeown

Enables an administrator to recover access to a file that previously was denied, by making the administrator the owner of the file.



## Syntax

```
takeown [/s <Computer> [/u [<Domain>\]<User name> [/p [<Password>]]]] /f <File name> [/a] [/r [/d {Y|N}]]
```

#### Parameters

|Parameter|Description|
|---------|-----------|
|/s \<Computer>|Specifies the name or IP address of a remote computer (do not use backslashes). The default value is the local computer. This parameter applies to all of the files and folders specified in the command.|
|/u [\<Domain>\]<User name>|Runs the script with the permissions of the specified user account. The default value is system permissions.|
|/p [\<Password>]|Specifies the password of the user account that is specified in the **/u** parameter.|
|/f \<File name>|Specifies the file name or directory name pattern. You can use the wildcard character * when specifying the pattern. You can also use the syntax *ShareName*\*FileName*.|
|/a|Gives ownership to the Administrators group instead of the current user.|
|/r|Performs a recursive operation on all files in the specified directory and subdirectories.|
|/d {Y \| N}|Suppresses the confirmation prompt that is displayed when the current user does not have the "List Folder" permission on a specified directory, and instead uses the specified default value. Valid values for the **/d** option are as follows:</br>-   Y: Take ownership of the directory.</br>-   N: Skip the directory.</br>Note that you must use this option in conjunction with the **/r** option.|
|/?|Displays help at the command prompt.|

## Remarks

-   This command is typically used in batch files.
-   If the **/a** parameter is not specified, file ownership is given to the user who is currently logged on to the computer.
-   Mixed patterns using (**?** and **&#42;**) are not supported by **takeown** command.
-   After deleting the lock with **takeown**, you might have to use Windows Explorer or the **cacls** command to give yourself full permissions to the files and directories before you can delete them. For more information about **cacls**, see "Additional References" at the end of this topic.

## <a name="BKMK_examples"></a>Examples

To take ownership of a file named Lostfile, type:
```
takeown /f lostfile
```

## Additional References

- [Command-Line Syntax Key](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/command-line-syntax-key.md)

---


MIT License. Copyright (c) 2020 Strontic.


