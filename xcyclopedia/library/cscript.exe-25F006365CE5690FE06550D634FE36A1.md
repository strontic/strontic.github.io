
# cscript.exe 

* File Path: `C:\Windows\SysWOW64\cscript.exe`
* Description: Microsoft  Console Based Script Host
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `25F006365CE5690FE06550D634FE36A1`
SHA1 | `E4FBC12ED94CFEA102F30ED5ECA4AB17F041EC7A`
SHA256 | `873A28C3A6D1D6278B4FA422F65FADF18150301D31B9AFA694BDB5E3BD6A165D`
SHA384 | `B340B725D60CF8EC0738702919A1A64A64EE5FCD14D2BBE07776D09666208F4024D000F115E8DC5B444F1EED3347D2F7`
SHA512 | `41AC4A9467E454B0FA85BE214FDE500B81442F523CCCBFA341ADC58FDDC62B2FECA7BCD5FC2B929904E481FCAF72AC2B759901146485E96F529DC591A2DD3CDA`
SSDEEP | `3072:jjwuzjgBKnIdnFhh9GD2qdmwEWxWKdGxB0yqTxt30IB:jx3nIdFhh9SEWxQB0lTH`

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
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
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


## Additional Info

*Source: [MicrosoftDocs](https://github.com/MicrosoftDocs/windowsserverdocs) by [Microsoft](https://opensource.microsoft.com/codeofconduct/), available under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) license. Some links modified.*

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


