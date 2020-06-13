
# print.exe 

* File Path: `C:\WINDOWS\SysWOW64\print.exe`
* Description: Print Utility
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `EBC1C49AD72CC320163A3EFAC0CCF5BB`
SHA1 | `A680E11F118E5F2132A1EA38CD81DE80660F7EA3`
SHA256 | `3A30D8E24CE0306CE442235C4D60423CEA3BA5369B744AFC384D502D97CFAA6A`
SHA384 | `B6482BC7B59FD57006D2966DFA7D5644D608EAB3ABE0F27B0C0144D160C69B813235DB736A10E8625C03A5FE4AE371EF`
SHA512 | `15C59A27BADCBA74179302CF9EFE1A811175989151A0ED1635F8A394D9CD389DF42B9F6C382697CEA5EF3C444721BA598C250029FEBF92D57A4320A8E17BF2B1`
SSDEEP | `192:Mq/n5s3ZO2SNxhavglQL/BRKupoDwliLlixtU3YtmYkVWuUW:Mq/5iLjKupZlWl8U0sVWuUW`

## Runtime Data

### Usage (stdout):
```Batchfile
Prints a text file.

PRINT [/D:device] [[drive:][path]filename[...]]

   /D:device   Specifies a print device.


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

* Original Filename: Print.Exe
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.18362.1 (WinBuild.160101.0800)
* Product Version: 10.0.18362.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.


## Additional Info*

**The information below is copied from [MicrosoftDocs](https://github.com/MicrosoftDocs/windowsserverdocs) by [Microsoft](https://opensource.microsoft.com/codeofconduct/), available under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) license. Some links modified.*

---

# print



Sends a text file to a printer.



## Syntax

```
Print [/d:<PrinterName>] [<Drive>:][<Path>]<FileName>[ ...]
```

### Parameters

|Parameter|Description|
|---------|-----------|
|/d:\<PrinterName>|Specifies the printer that you want to print the job. To print to a locally connected printer, specify the port on your computer where the printer is connected.</br>-   Valid values for parallel ports are LPT1, LPT2, and LPT3.</br>-   Valid values for serial ports are COM1, COM2, COM3, and COM4.</br>You can also specify a network printer by using its queue name (\\\\*ServerName*\*PrinterName*). If you do not specify a printer, the print job is sent to LPT1 by default.|
|\<Drive>:|Specifies the logical or physical drive where the file you want to print is located. This parameter is not required if the file you want to print is located on the current drive.|
|\<Path>|Specifies the location of the file you want to print. This parameter is not required if the file you want to print is located in the current directory.|
|\<FileName>[ ...]|Required. Specifies the file you want to print. You can include multiple files in one command.|
|/?|Displays help at the command prompt.|

## Remarks

-   A file can print in the background if you send it to a printer connected to a serial or parallel port on the local computer.
-   You can perform many configuration tasks from the command prompt by using the **Mode** command.

    See [Mode](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/mode.md) for more information about:  
    -   Configuring a printer connected to a parallel port
    -   Configuring a printer connected to a serial port
    -   Displaying the status of a printer
    -   Preparing a printer for code page switching

## Examples

To send the file Report.txt in the current directory to a printer connected to LPT2 on the local computer, type:
```
print /d:lpt2 report.txt
```
To send the file Report.txt in the c:\Accounting directory to the Printer1 print queue on the \\\\CopyRoom server, type:
```
print /d:\\copyroom\printer1 c:\accounting\report.txt 
```

## Additional References

- [Command-Line Syntax Key](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/command-line-syntax-key.md)

[Print Command Reference](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/print-command-reference.md)

[Mode](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/mode.md)

---


MIT License. Copyright (c) 2020 Strontic.


