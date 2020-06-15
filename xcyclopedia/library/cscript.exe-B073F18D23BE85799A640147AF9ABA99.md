
# cscript.exe 

* File Path: `C:\WINDOWS\system32\cscript.exe`
* Description: Microsoft  Console Based Script Host
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `B073F18D23BE85799A640147AF9ABA99`
SHA1 | `B6384FAFE0D30E4E897C318DB25D3CC167D9C413`
SHA256 | `4F059AC07F90E95BDAF0D7F0D1C54DDCDC0651A1E0D8AA5F03D11D6B0521177F`
SHA384 | `70E846AE0D13C44DC6106424FCC3E781C62C6769131565A6AD8EE9AA08D5CB3EA9EBE99E91FFF101F7258BB098821EFF`
SHA512 | `326729DE03A7A443393861CFAF33F69C11E4D5EEA048B8F90B0D6F6E37BDD62B20B6286105E6F4A5E8118EE19CF199B652082CA5629232C87C9AA799AA4B2B8D`
SSDEEP | `3072:94IxXaX+MPR9ZSwDBTK5kF9sAwaFOhjUrL2lT6IZxtt:94IMJZhR9sAyKCTfZh`

## Runtime Data

### Usage (stdout):
```Batchfile
Microsoft (R) Windows Script Host Version 5.812
Copyright (C) Microsoft Corporation. All rights reserved.

Usage: CScript scriptname.extension [option...] [arguments...]

Options:
 //B         Batch mode: Suppresses script errors and prompts from displaying
 //D         Enable Active Debugging
 //E:engine  Use engine for executing script
 //H:CScript Changes the default script host to CScript.exe
 //H:WScript Changes the default script host to WScript.exe (default)
 //I         Interactive mode (default, opposite of //B)
 //Job:xxxx  Execute a WSF job
 //Logo      Display logo (default)
 //Nologo    Prevent logo display: No banner will be shown at execution time
 //S         Save current command line options for this user
 //T:nn      Time out in seconds:  Maximum time a script is permitted to run
 //X         Execute script in debugger
 //U         Use Unicode for redirected I/O from the console

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

* Original Filename: cscript.exe.mui
* Product Name: Microsoft  Windows Script Host
* Company Name: Microsoft Corporation
* File Version: 5.812.10240.16384
* Product Version: 5.812.10240.16384
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.




## Additional Info*

**The information below is copied from [MicrosoftDocs](https://github.com/MicrosoftDocs/windowsserverdocs), which is maintained by [Microsoft](https://opensource.microsoft.com/codeofconduct/). Available under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) license.*

---
# cscript

> Applies to: Windows Server (Semi-Annual Channel), Windows Server 2019, Windows Server 2016, Windows Server 2012 R2, Windows Server 2012

Starts a script to run in a command-line environment.

>[!IMPORTANT]
> Performing this task does not require you to have administrative credentials. Therefore, as a security best practice, consider performing this task as a user without administrative credentials.

## Syntax

```
cscript <scriptname.extension> [/b] [/d] [/e:<engine>] [{/h:cscript | /h:wscript}] [/i] [/job:<identifier>] [{/logo | /nologo}] [/s] [/t:<seconds>] [x] [/u] [/?] [<scriptarguments>]
```

#### Parameters

| Parameter | Description |
| --------- | ----------- |
| scriptname.extension | Specifies the path and file name of the script file with optional file name extension. |
| /b | Specifies batch mode, which does not display alerts, scripting errors, or input prompts. |
| /d | Starts the debugger. |
| /e:`<engine>` | Specifies the engine that is used to run the script. |
| /h:cscript | Registers cscript.exe as the default script host for running scripts. |
| /h:wscript | Registers wscript.exe as the default script host for running scripts. This is the default. |
| /i | Specifies interactive mode, which displays alerts, scripting errors, and input prompts. This is the default and the opposite of `/b`. |
| /job:<identifier> | Runs the job identified by *identifier* in a .wsf script file. |
| /logo | Specifies that the Windows Script Host banner is displayed in the console before the script runs. This is the default and the opposite of `/nologo`. |
| /nologo | Specifies that the Windows Script Host banner is not displayed before the script runs. |
| /s | Saves the current command-prompt options for the current user. |
| /t:<seconds> | Specifies the maximum time the script can run (in seconds). You can specify up to 32,767 seconds. The default is no time limit. |
| /u | Specifies Unicode for input and output that is redirected from the console. |
| /x | Starts the script in the debugger. |
| /? | Displays available command parameters and provides help for using them. This is the same as typing **cscript.exe** with no parameters and no script. |
| scriptarguments | Specifies the arguments passed to the script. Each script argument must be preceded by a slash (**/**). |

#### Remarks

- Each parameter is optional; however, you can't specify script arguments without specifying a script. If you don't specify a script or any script arguments, cscript.exe displays the cscript.exe syntax and the valid host options.

- The **/t** parameter prevents excessive running of scripts by setting a timer. When the run time exceeds the specified value, cscript interrupts the script engine and ends the process.

- Windows script files usually have one of the following file name extensions: .wsf, .vbs, .js. Windows Script Host can use .wsf script files. Each .wsf file can use multiple scripting engines and perform multiple jobs.

- if you double-click a script file with an extension that has no association, the **Open With** dialog box appears. Select wscript or cscript, and then select **Always use this program to open this file type**. This registers wscript.exe or cscript as the default script host for files of this file type.

## Additional References

- [Command-Line Syntax Key](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/command-line-syntax-key.md)

---


MIT License. Copyright (c) 2020 Strontic.


