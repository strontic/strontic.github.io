
# powershell.exe 

* File Path: `C:\Windows\system32\WindowsPowerShell\v1.0\powershell.exe`
* Description: Windows PowerShell
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `097CE5761C89434367598B34FE32893B`
SHA1 | `044A0CF1F6BC478A7172BF207EEF1E201A18BA02`
SHA256 | `BA4038FD20E474C047BE8AAD5BFACDB1BFC1DDBE12F803F473B7918D8D819436`
SHA384 | `C5F93AC02BF3FB1A97C0AFAF22468FE4BBD7804B1ECD95A30025497B10163EDEE8E042E557CEC1BD1724D5758B7A87CB`
SHA512 | `129912EB88C744EAA56BCA899BB7B3271D41E029FBD83D6E9853D4200CA8408C79736E469D8D0B1AACF1DEB22A4C03AE9FFF84B5AF408028DBC4C342F5FAD939`
SSDEEP | `6144:J94+nr3in2CIbWwO9sV1yZywi/PzNKXzJ7BapCK5d3klRzULOnWyjLsPhAQzqO:Y+pW2KXzJ4pdd3klnnWosPhnzq`

## Runtime Data

### Usage (stdout):
```Batchfile

PowerShell[.exe] [-PSConsoleFile <file> | -Version <version>]
    [-NoLogo] [-NoExit] [-Sta] [-Mta] [-NoProfile] [-NonInteractive]
    [-InputFormat {Text | XML}] [-OutputFormat {Text | XML}]
    [-WindowStyle <style>] [-EncodedCommand <Base64EncodedCommand>]
    [-ConfigurationName <string>]
    [-File <filePath> <args>] [-ExecutionPolicy <ExecutionPolicy>]
    [-Command { - | <script-block> [-args <arg-array>]
                  | <string> [<CommandParameters>] } ]

PowerShell[.exe] -Help | -? | /?

-PSConsoleFile
    Loads the specified Windows PowerShell console file. To create a console
    file, use Export-Console in Windows PowerShell.

-Version
    Starts the specified version of Windows PowerShell. 
    Enter a version number with the parameter, such as "-version 2.0".

-NoLogo
    Hides the copyright banner at startup.

-NoExit
    Does not exit after running startup commands.

-Sta
    Starts the shell using a single-threaded apartment.
    Single-threaded apartment (STA) is the default.

-Mta
    Start the shell using a multithreaded apartment.

-NoProfile
    Does not load the Windows PowerShell profile.

-NonInteractive
    Does not present an interactive prompt to the user.

-InputFormat
    Describes the format of data sent to Windows PowerShell. Valid values are
    "Text" (text strings) or "XML" (serialized CLIXML format).

-OutputFormat
    Determines how output from Windows PowerShell is formatted. Valid values
    are "Text" (text strings) or "XML" (serialized CLIXML format).

-WindowStyle
    Sets the window style to Normal, Minimized, Maximized or Hidden.

-EncodedCommand
    Accepts a base-64-encoded string version of a command. Use this parameter 
    to submit commands to Windows PowerShell that require complex quotation 
    marks or curly braces.

-ConfigurationName
    Specifies a configuration endpoint in which Windows PowerShell is run.
    This can be any endpoint registered on the local machine including the
    default Windows PowerShell remoting endpoints or a custom endpoint having
    specific user role capabilities.
    
-File
    Runs the specified script in the local scope ("dot-sourced"), so that the 
    functions and variables that the script creates are available in the 
    current session. Enter the script file path and any parameters. 
    File must be the last parameter in the command, because all characters 
    typed after the File parameter name are interpreted 
    as the script file path followed by the script parameters.

-ExecutionPolicy
    Sets the default execution policy for the current session and saves it 
    in the $env:PSExecutionPolicyPreference environment variable. 
    This parameter does not change the Windows PowerShell execution policy 
    that is set in the registry.

-Command
    Executes the specified commands (and any parameters) as though they were
    typed at the Windows PowerShell command prompt, and then exits, unless 
    NoExit is specified. The value of Command can be "-", a string. or a
    script block.

    If the value of Command is "-", the command text is read from standard
    input.

    If the value of Command is a script block, the script block must be enclosed
    in braces ({}). You can specify a script block only when running PowerShell.exe
    in Windows PowerShell. The results of the script block are returned to the
    parent shell as deserialized XML objects, not live objects.

    If the value of Command is a string, Command must be the last parameter
    in the command , because any characters typed after the command are 
    interpreted as the command arguments.

    To write a string that runs a Windows PowerShell command, use the format:
	"& {<command>}"
    where the quotation marks indicate a string and the invoke operator (&)
    causes the command to be executed.

-Help, -?, /?
    Shows this message. If you are typing a PowerShell.exe command in Windows
    PowerShell, prepend the command parameters with a hyphen (-), not a forward
    slash (/). You can use either a hyphen or forward slash in Cmd.exe.

EXAMPLES
    PowerShell -PSConsoleFile SqlSnapIn.Psc1
    PowerShell -version 2.0 -NoLogo -InputFormat text -OutputFormat XML
    PowerShell -ConfigurationName AdminRoles
    PowerShell -Command {Get-EventLog -LogName security}
    PowerShell -Command "& {Get-EventLog -LogName security}"

    # To use the -EncodedCommand parameter:
    $command = 'dir "c:\program files" '
    $bytes = [System.Text.Encoding]::Unicode.GetBytes($command)
    $encodedCommand = [Convert]::ToBase64String($bytes)
    powershell.exe -encodedCommand $encodedCommand

```

### Usage (stderr):
```Batchfile

```

### Child Processes:


## Signature

* Status: Signature verified.
* Serial: `33000001733031072665B8B9B3000000000173`
* Thumbprint: `14590DC5C3AAF238FCFD7785B4B93F4071402C34`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: PowerShell.EXE.MUI
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.14393.0 (rs1_release.160715-1616)
* Product Version: 10.0.14393.0
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.


## Additional Info

*Source: [MicrosoftDocs](https://github.com/MicrosoftDocs/windowsserverdocs) by [Microsoft](https://opensource.microsoft.com/codeofconduct/), available under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) license. Some links modified.*

---

# PowerShell

Windows PowerShell is a task-based command-line shell and scripting language designed especially for system administration. Built on the .NET Framework, Windows PowerShell helps IT professionals and power users control and automate the administration of the Windows operating system and applications that run on Windows.

The **PowerShell.exe** command-line tool starts a Windows PowerShell session in a Command Prompt window. When you use **PowerShell.exe**, you can use its optional parameters to customize the session. For example, you can start a session that uses a particular execution policy or one that excludes a Windows PowerShell profile. Otherwise, the session is the same as any session that is started in the Windows PowerShell console.

## Using PowerShell.exe

You can use the **PowerShell.exe** command-line tool to start a Windows PowerShell session in a Command Prompt window.

- To start a Windows PowerShell session in a command prompt window, type `PowerShell`. A **PS** prefix is added to the command prompt to indicate that you are in a Windows PowerShell session.

- To start a session with a particular execution policy, use the **ExecutionPolicy** parameter.

    ```
    PowerShell.exe -ExecutionPolicy Restricted
    ```

- To start a Windows PowerShell session without your Windows PowerShell profiles, use the **NoProfile** parameter.

    ```
    PowerShell.exe -NoProfile
    ```

- To start a session , use the **ExecutionPolicy** parameter.

    ```
    PowerShell.exe -ExecutionPolicy Restricted
    ```

- To see the PowerShell.exe help file, use the following command format.

    ```
    PowerShell.exe -help, -?, /?
    ```

- To end a Windows PowerShell session in a Command Prompt window, type `exit`. The typical command prompt returns.

For a complete list of the **PowerShell.exe** command-line parameters, see [about_PowerShell.Exe](https://go.microsoft.com/fwlink/?LinkID=113439).

## Other Ways to Start Windows PowerShell

For information about other ways to start Windows PowerShell, see [Starting Windows PowerShell](https://go.microsoft.com/fwlink/?LinkID=135259).

## Remarks

Windows PowerShell runs on the Server Core installation option of Windows Server operating systems. However, features that require a graphic user interface, such as the [Windows PowerShell Integrated Scripting Environment (ISE)](https://technet.microsoft.com/library/hh849182), and the [Out-GridView](https://go.microsoft.com/fwlink/?LinkID=113364) and [Show-Command](https://go.microsoft.com/fwlink/?LinkID=217448) cmdlets, do not run on Server Core installations.

## Additional References

[about_PowerShell.Exe](https://go.microsoft.com/fwlink/?LinkID=113439)
[about_PowerShell_Ise.exe](https://go.microsoft.com/fwlink/?LinkId=256512)
[Windows PowerShell](https://go.microsoft.com/fwlink/?LinkID=107116)
[Scripting with Windows PowerShell](https://technet.microsoft.com/scriptcenter/dd742419)
See Also

---


MIT License. Copyright (c) 2020 Strontic.


