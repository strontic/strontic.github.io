
# powershell.exe 

* File Path: `C:\WINDOWS\system32\WindowsPowerShell\v1.0\powershell.exe`
* Description: Windows PowerShell
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `CDA48FC75952AD12D99E526D0B6BF70A`
SHA1 | `36C5D12033B2EAF251BAE61C00690FFB17FDDC87`
SHA256 | `908B64B1971A979C7E3E8CE4621945CBA84854CB98D76367B791A6E22B5F6D53`
SHA384 | `B7EACEE2BBB4457420F6B5FD6B2A74D80E3D1905225C423D19523CC5914CBC7C1E25B64ABB75D64C77A99E7A39CC5515`
SHA415 | `31946A5C80088646FE951081E88A7478B804DA874236A44E845842404C9770450C9B1AC3BB1AF2B00B0102FE4983B5728FE4DF8C40D28F9BEF16230A28AE5DF0`
SSDEEP | `6144:kL2yOalAcQjQWwO9sV1yZywi/PzNKXzJ7BapCK5d3klRzULOnWyjLsPhAQzqO:wCalAcHW2KXzJ4pdd3klnnWosPhnzq`

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
* Serial: 330000023241FB59996DCC4DFF000000000232
* Thumbprint: FF82BC38E1DA5E596DF374C53E3617F7EDA36B06
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: PowerShell.EXE.MUI
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.18362.1 (WinBuild.160101.0800)
* Product Version: 10.0.18362.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.

MIT License. Copyright (c) 2020 Strontic.


