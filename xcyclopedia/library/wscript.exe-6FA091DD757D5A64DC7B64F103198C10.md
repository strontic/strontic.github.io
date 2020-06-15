
# wscript.exe 

* File Path: `C:\Windows\SysWOW64\wscript.exe`
* Description: Microsoft  Windows Based Script Host
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `6FA091DD757D5A64DC7B64F103198C10`
SHA1 | `D26A907EEFE2D0299DF8DB81F6A46F2E1615BD04`
SHA256 | `F451827D9D32C792C821EF0B89FEBF002D29004605B20CAACE53467EC01D2FAC`
SHA384 | `AC7D7B94740D72FDE743906F9E5DBD15FE13B80232E3F498D2B44F40ED5F5C763370C9179A9ADB5C6197F584A79B8110`
SHA512 | `B5AD127B3BBE63EA9284E8E03BA02A23F9929AAF679F18E17DBA995A9794E1B86D7D044320452F972D9E4D759A8E05F2A4C88FB6D2C35779BE0A3ABEFDC19545`
SSDEEP | `3072:uDuGci1o2ialMm+aZ2KdGQMs7uGTxtKlLU:ujcaoOZRMs7tT2L`

## Runtime Data

### Usage (stdout):
```Batchfile

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

* Original Filename: wscript.exe.mui
* Product Name: Microsoft  Windows Script Host
* Company Name: Microsoft Corporation
* File Version: 5.812.10240.16384
* Product Version: 5.812.10240.16384
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.




## Additional Info*

**The information below is copied from [MicrosoftDocs](https://github.com/MicrosoftDocs/windowsserverdocs), which is maintained by [Microsoft](https://opensource.microsoft.com/codeofconduct/). Available under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) license.*

---

# wscript



Windows Script Host provides an environment in which users can execute scripts in a variety of languages that use a variety of object models to perform tasks.

## Syntax

```
wscript [<scriptname>] [/b] [/d] [/e:<engine>] [{/h:cscript|/h:wscript}] [/i] [/job:<identifier>] [{/logo|/nologo}] [/s] [/t:<number>] [/x] [/?] [<ScriptArguments>]
```

#### Parameters

|Parameter|Description|
|---------|-----------|
|scriptname|Specifies the path and file name of the script file.|
|/b|Specifies batch mode, which does not display alerts, scripting errors, or input prompts. This is the opposite of **/i**.|
|/d|Starts the debugger.|
|/e|Specifies the engine that is used to run the script. This lets you run scripts that use a custom file name extension. Without the /e parameter, you can only run scripts that use registered file name extensions. For example, if you try to run this command:<br>```cscript test.admin```<br>You will receive this error message: Input Error: There is no script engine for file extension .admin.<br>One advantage of using nonstandard file name extensions is that it guards against accidentally double-clicking a script and running something you really did not want to run. <br>This does not create a permanent association between the .admin file name extension and VBScript. Each time you run a script that uses a .admin file name extension, you will need to use the /e parameter.|
|/h:cscript|Registers **cscript.exe** as the default script host for running scripts.|
|/h:wscript|Registers **wscript.exe** as the default script host for running scripts. This is the default when the **/h** option is omitted.|
|/i|Specifies interactive mode, which displays alerts, scripting errors, and input prompts.</br>This is the default and the opposite of **/b**.|
|/job:\<identifier>|Runs the job identified by *identifier* in a **.wsf** script file.|
|/logo|Specifies that the Windows Script Host banner is displayed in the console before the script runs.</br>This is the default and the opposite of **/nologo**.|
|/nologo|Specifies that the Windows Script Host banner is not displayed before the script runs. This is the opposite of **/logo**.|
|/s|Saves the current command prompt options for the current user.|
|/t:\<number>|Specifies the maximum time the script can run (in seconds). You can specify up to 32,767 seconds.</br>The default is no time limit.|
|/x|Starts the script in the debugger.|
|ScriptArguments|Specifies the arguments passed to the script. Each script argument must be preceded by a slash (/).|
|/?|Displays Help at the command prompt.|

## Remarks

-   Performing this task does not require you to have administrative credentials. Therefore, as a security best practice, consider performing this task as a user without administrative credentials.
-   To open a command prompt, on the **Start** screen, type **cmd**, and then click **command prompt**.
-   Each parameter is optional; however, you cannot specify script arguments without specifying a script. If you do not specify a script or any script arguments, **wscript.exe** displays the **Windows Script Host Settings** dialog box, which you can use to set global scripting properties for all scripts that **wscript.exe** runs on the local computer.
-   The **/t** parameter prevents excessive running of scripts by setting a timer. When the time exceeds the specified value, **wscript** interrupts the script engine and ends the process.
-   Windows script files usually have one of the following file name extensions: **.wsf**, **.vbs**, **.js**.
-   If you double-click a script file with an extension that has no association, the **Open With** dialog box appears. Select **wscript** or **cscript**, and then select **Always use this program to open this file type**. This registers **wscript.exe** or **cscript.exe** as the default script host for files of this file type.
-   You can set properties for individual scripts. See [Windows Script Host overview](https://technet.microsoft.com/library/cc738350(v=ws.10).aspx) for more information.
-   Windows Script Host can use **.wsf** script files. Each **.wsf** file can use multiple scripting engines and perform multiple jobs.

## Additional References

- [Command-Line Syntax Key](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/command-line-syntax-key.md)

---


MIT License. Copyright (c) 2020 Strontic.


