
# shutdown.exe 

* File Path: `C:\Windows\system32\shutdown.exe`
* Description: Windows Shutdown and Annotation Tool
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `547993395376742A437D3145AF6B0309`
SHA1 | `4DF5F5ACB1DB835163A79473CD83495916A33DC8`
SHA256 | `F96073C3442EA0A99B4945394007602772DB36732D1511DC2068519526678F8A`
SHA384 | `D4EADD778AF522331A26743BA6FF4CFC5AFF1A0F6D6BF59598CA2232C66DC0AEB0C6C48A1EA74FC1A745A4BB4458548C`
SHA512 | `47C3A0DB40BB18B5551B96154F270FB2CCB60B5707FD7234FC2EEADBD686C7B163C98A3B35FB1CFA3BCCC470911AECAC6FA44AB4BC7B45900F17AE1EC52F4FAB`
SSDEEP | `384:9A2Rd8HRzOIXAYPczJkHg88KzFkedQnlRcDhWum3+vtul83Q/Wm+SW:e00xOIHczOA88gdQnYcGtul83K+`

## Runtime Data

### Usage (stdout):
```Batchfile
Usage: C:\Windows\system32\shutdown.exe [/i | /l | /s | /r | /g | /a | /p | /h | /e | /o] [/hybrid] [/soft] [/fw] [/f]
    [/m \\computer][/t xxx][/d [p|u:]xx:yy [/c "comment"]]

    No args    Display help. This is the same as typing /?.
    /?         Display help. This is the same as not typing any options.
    /i         Display the graphical user interface (GUI).
               This must be the first option.
    /l         Log off. This cannot be used with /m or /d options.
    /s         Shutdown the computer.
    /r         Full shutdown and restart the computer.
    /g         Full shutdown and restart the computer. After the system is
               rebooted, restart any registered applications.
    /a         Abort a system shutdown.
               This can only be used during the time-out period.
               Combine with /fw to clear any pending boots to firmware.
    /p         Turn off the local computer with no time-out or warning.
               Can be used with /d and /f options.
    /h         Hibernate the local computer.
               Can be used with the /f option.
    /hybrid    Performs a shutdown of the computer and prepares it for fast startup.
               Must be used with /s option.
    /fw        Combine with a shutdown option to cause the next boot to go to the
               firmware user interface.
    /e         Document the reason for an unexpected shutdown of a computer.
    /o         Go to the advanced boot options menu and restart the computer.
               Must be used with /r option.
    /m \\computer Specify the target computer.
    /t xxx     Set the time-out period before shutdown to xxx seconds.
               The valid range is 0-315360000 (10 years), with a default of 30.
               If the timeout period is greater than 0, the /f parameter is
               implied.
    /c "comment" Comment on the reason for the restart or shutdown.
               Maximum of 512 characters allowed.
    /f         Force running applications to close without forewarning users.
               The /f parameter is implied when a value greater than 0 is
               specified for the /t parameter.
    /d [p|u:]xx:yy  Provide the reason for the restart or shutdown.
               p indicates that the restart or shutdown is planned.
               u indicates that the reason is user defined.
               If neither p nor u is specified the restart or shutdown is
               unplanned.
               xx is the major reason number (positive integer less than 256).
               yy is the minor reason number (positive integer less than 65536).

Reasons on this computer:
(E = Expected U = Unexpected P = planned, C = customer defined)
Type	Major	Minor	Title

 U  	0	0	Other (Unplanned)
E   	0	0	Other (Unplanned)
E P 	0	0	Other (Planned)
 U  	0	5	Other Failure: System Unresponsive
E   	1	1	Hardware: Maintenance (Unplanned)
E P 	1	1	Hardware: Maintenance (Planned)
E   	1	2	Hardware: Installation (Unplanned)
E P 	1	2	Hardware: Installation (Planned)
E   	2	2	Operating System: Recovery (Unplanned)
E P 	2	2	Operating System: Recovery (Planned)
  P 	2	3	Operating System: Upgrade (Planned)
E   	2	4	Operating System: Reconfiguration (Unplanned)
E P 	2	4	Operating System: Reconfiguration (Planned)
  P 	2	16	Operating System: Service pack (Planned)
    	2	17	Operating System: Hot fix (Unplanned)
  P 	2	17	Operating System: Hot fix (Planned)
    	2	18	Operating System: Security fix (Unplanned)
  P 	2	18	Operating System: Security fix (Planned)
E   	4	1	Application: Maintenance (Unplanned)
E P 	4	1	Application: Maintenance (Planned)
E P 	4	2	Application: Installation (Planned)
E   	4	5	Application: Unresponsive
E   	4	6	Application: Unstable
 U  	5	15	System Failure: Stop error
 U  	5	19	Security issue (Unplanned)
E   	5	19	Security issue (Unplanned)
E P 	5	19	Security issue (Planned)
E   	5	20	Loss of network connectivity (Unplanned)
 U  	6	11	Power Failure: Cord Unplugged
 U  	6	12	Power Failure: Environment
  P 	7	0	Legacy API shutdown

```

### Usage (stderr):
```Batchfile

```

### Child Processes:


## Signature

* Status: Signature verified.
* Serial: `33000000BCE120FDD27CC8EE930000000000BC`
* Thumbprint: `E85459B23C232DB3CB94C7A56D47678F58E8E51E`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: SHUTDOWN.EXE.MUI
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.14393.0 (rs1_release.160715-1616)
* Product Version: 10.0.14393.0
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.




## Additional Info*

**The information below is copied from [MicrosoftDocs](https://github.com/MicrosoftDocs/windowsserverdocs), which is maintained by [Microsoft](https://opensource.microsoft.com/codeofconduct/). Available under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) license.*

---

# shutdown

Enables you to shut down or restart local or remote computers one at a time.



## Syntax

```
shutdown [/i | /l | /s | /r | /a | /p | /h | /e] [/f] [/m \\<ComputerName>] [/t <XXX>] [/d [p|u:]<XX>:<YY> [/c comment]] 
```

### Parameters

|Parameter|Description|
|---------|-----------|
|/i|Displays the **Remote Shutdown Dialog** box. The **/i** option must be the first parameter following the command. If **/i** is specified, all other options are ignored.|
|/l|Logs off the current user immediately, with no time-out period. You cannot use **/l** with **/m** or **/t**.|
|/s|Shuts down the computer.|
|/r|Restarts the computer after shutdown.|
|/a|Aborts a system shutdown. Effective only during the timeout period. To use **/a**, you must also use the **/m** option.|
|/p|Turns off the local computer only (not a remote computer)â€”with no time-out period or warning. You can use **/p** only with **/d** or **/f**. If your computer does not support power-off functionality, it will shut down when you use **/p**, but the power to the computer will remain on.|
|/h|Puts the local computer into hibernation, if hibernation is enabled. You can use **/h** only with **/f**.|
|/e|Enables you to document the reason for the unexpected shutdown on the target computer.|
|/f|Forces running applications to close without warning users.</br>Caution: Using the **/f** option might result in loss of unsaved data.|
|/m \\\\\<ComputerName>|Specifies the target computer. Cannot be used with the **/l** option.|
|/t \<XXX>|Sets the time-out period or delay to *XXX* seconds before a restart or shutdown. This causes a warning to display on the local console. You can specify 0-600 seconds. If you do not use **/t**, the time-out period is 30 seconds by default.|
|/d [p\|u:]\<XX>:\<YY>|Lists the reason for the system restart or shutdown. The following are the parameter values:</br>**p** Indicates that the restart or shutdown is planned.</br>**u** Indicates that the reason is user defined.</br>Note: If **p** or **u** are not specified, the restart or shutdown is unplanned.</br>*XX* Specifies the major reason number (positive integer less than 256).</br>*YY* Specifies the minor reason number (positive integer less than 65536).|
|/c \<Comment>|Enables you to comment in detail about the reason for the shutdown. You must first provide a reason by using the **/d** option. You must enclose comments in quotation marks. You can use a maximum of 511 characters.|
|/?|Displays help at the command prompt, including a list of the major and minor reasons that are defined on your local computer.|

## Remarks

-   Users must be assigned the **Shut down the system** user right to shut down a local or remotely administered computer that is using the **shutdown** command.
-   Users must be members of the Administrators group to annotate an unexpected shutdown of a local or remotely administered computer. If the target computer is joined to a domain, members of the Domain Admins group might be able to perform this procedure. For more information, see:  
    -   [Default local groups](https://technet.microsoft.com/library/cc785098(v=ws.10).aspx)
    -   [Default groups](https://technet.microsoft.com/library/cc756898(v=ws.10).aspx)
-   If you want to shut down more than one computer at a time, you can call **shutdown** for each computer by using a script, or you can use **shutdown** **/i** to display the Remote Shutdown Dialog box.
-   If you specify major and minor reason codes, you must first define these reason codes on each computer where you plan to use the reasons. If the reason codes are not defined on the target computer, Shutdown Event Tracker cannot log the correct reason text.
-   Remember to indicate that a shutdown is planned by using the **p:** parameter. Omitting **p:** indicates that a shutdown is unplanned. If you type **p:** followed by the reason code for an unplanned shutdown, the command will not carry out the shutdown. Conversely, if you omit **p:** and type in the reason code for a planned shutdown, the command will not carry out the shutdown.

## Examples

To force applications to close and restart the local computer after a one-minute delay with the reason Application: Maintenance (Planned) and the comment Reconfiguring myapp.exe type:
```
shutdown /r /t 60 /c Reconfiguring myapp.exe /f /d p:4:1
```
To restart the remote computer \\\\ServerName with the same parameters, type:
```
shutdown /r /m \\servername /t 60 /c Reconfiguring myapp.exe /f /d p:4:1
```

## Additional References

- [Command-Line Syntax Key](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/command-line-syntax-key.md)

---


MIT License. Copyright (c) 2020 Strontic.


