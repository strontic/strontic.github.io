
# wscript.exe 

* File Path: `C:\WINDOWS\SysWOW64\wscript.exe`
* Description: Microsoft  Windows Based Script Host
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `A3795A19543CCDD7A95CA71C8E553EF1`
SHA1 | `DCBD774A3504C724F13A0301AD0AA0C6481F7346`
SHA256 | `7D92ED1F65BB5AFE9FBDE8349E3BD55EC207A476C795A583A15A7A05C8320709`
SHA384 | `04B42DDACB91E3013C7F935DFE7E29F2B3441003485C37E6D8AE35280C2026E0B448D83877618B344DC54304A116C8B4`
SHA512 | `63F97BAEFF1A84C8D846BEB6A18AF8179021582F2359AF8751B2C49151450C7A318509AAE839D27CCEF84AFF70354042CACE0DB10F54A5FA1EE7B0A5AAAF6AE0`
SSDEEP | `3072:ITqLSkm7WhKM3/QYh19ujlNvXbDVqCjURGVruGTxt+5d:I0SksWhKuEJXF3BVrtTk`

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

* Original Filename: wscript.exe
* Product Name: Microsoft  Windows Script Host
* Company Name: Microsoft Corporation
* File Version: 5.812.10240.16384
* Product Version: 5.812.10240.16384
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.


## Additional Info

*Source: [MicrosoftDocs](https://github.com/MicrosoftDocs/windowsserverdocs) by [Microsoft](https://opensource.microsoft.com/codeofconduct/), available under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) license. Some links modified.*

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


