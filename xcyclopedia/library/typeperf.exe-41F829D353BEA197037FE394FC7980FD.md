
# typeperf.exe 

* File Path: `C:\Windows\SysWOW64\typeperf.exe`
* Description: Command line performance monitor
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `41F829D353BEA197037FE394FC7980FD`
SHA1 | `37055E69730BB557A7C27D6D5B6ECCA554163B91`
SHA256 | `1F7A57B166FAEB48E2C4475AF2A4D18327AAFB62D2B4A4A2B89A9EEE6309322A`
SHA384 | `A9E76F993BCB503A7D98F13553328E2E6AD0B0AD3BF680C1427C7B28C20918EF223F03D00B2B52319FAB068E1083B8C1`
SHA512 | `BBE632A7963C7673A472702577C76CF36DD736CB43B062D306A16D18657D94A339DF57D57C585D6D50677C4C5168571D01482D803CD2456495128F46C32B1EC8`
SSDEEP | `768:0rezMckiWjrC0mxRlmkMUaIXhZNKNQNGenli3ANroarX4oV2NZi:0DhiWZmlmqjhZsN203iMarXdVi`

## Runtime Data

### Usage (stdout):
```Batchfile

Microsoft r TypePerf.exe (10.0.14393.0)

Typeperf writes performance data to the command window or to a log file. To
stop Typeperf, press CTRL+C.

Usage:
C:\Windows\SysWOW64\typeperf.exe { <counter [counter ...]> 
                                | -cf <filename> 
                                | -q [object] 
                                | -qx [object] 
                                } [options]

Parameters:
  <counter [counter ...]>       Performance counters to monitor.

Options:
  -?                            Displays context sensitive help.
  -f <CSV|TSV|BIN|SQL>          Output file format. Default is CSV.
  -cf <filename>                File containing performance counters to
                                monitor, one per line.
  -si <[[hh:]mm:]ss>            Time between samples. Default is 1 second.
  -o <filename>                 Path of output file or SQL database. Default
                                is STDOUT.
  -q [object]                   List installed counters (no instances). To
                                list counters for one object, include the
                                object name, such as Processor.
  -qx [object]                  List installed counters with instances. To
                                list counters for one object, include the
                                object name, such as Processor.
  -sc <samples>                 Number of samples to collect. Default is to
                                sample until CTRL+C.
  -config <filename>            Settings file containing command options.
  -s <computer_name>            Server to monitor if no server is specified
                                in the counter path.
  -y                            Answer yes to all questions without prompting.

Note:
  Counter is the full name of a performance counter in
  "\\<Computer>\<Object>(<Instance>)\<Counter>" format,
  such as "\\Server1\Processor(0)\% User Time".

Examples:
  typeperf "\Processor(_Total)\% Processor Time"
  typeperf -cf counters.txt -si 5 -sc 50 -f TSV -o domain2.tsv
  typeperf -qx PhysicalDisk -o counters.txt

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

* Original Filename: TypePerf.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.14393.0 (rs1_release.160715-1616)
* Product Version: 10.0.14393.0
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.


## Additional Info

*Source: [MicrosoftDocs](https://github.com/MicrosoftDocs/windowsserverdocs) by [Microsoft](https://opensource.microsoft.com/codeofconduct/), available under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) license. Some links modified.*

---

# typeperf

The **typeperf** command writes performance data to the command window or to a log file. To stop **typeperf**, press CTRL+C.

## Syntax

```
typeperf <counter [counter ...]> [options]
typeperf -cf <filename> [options]
typeperf -q [object] [options]
typeperf -qx [object] [options]
```

### Parameters

|Parameter|Description|
|---------|-----------|
|\<counter [counter [â€¦]]>|Specifies performance counters to monitor.|

> [!NOTE]
> **\<counter>** is the full name of a performance counter in *\\\\Computer\Object(Instance)\Counter* format, such as **\\\\Server1\Processor(0)\% User Time**.

## Options

|                   Option                   |                                                         Description                                                          |
|--------------------------------------------|------------------------------------------------------------------------------------------------------------------------------|
|                     -?                     |                                               Displays context-sensitive help.                                               |
| -f \<CSV&verbar;TSV&verbar;BIN&verbar;SQL> |                                    Specifies the output file format. The default is CSV.                                     |
|              -cf \<filename>               |              Specifies a file containing a list of performance counters to monitor, with one counter per line.               |
|             -si <[[hh:]mm:]ss>             |                                  Specifies the sample interval. The default is one second.                                   |
|               -o \<filename>               |     Specifies the path for the output file, or the SQL database. The default is STDOUT (written to the command window).      |
|                -q [object]                 | Display a list of installed counters (no instances). To list counters for one object, include the object name. \*\*\*EXAMPLE |
|                -qx [object]                |        Display a list of installed counters with instances. To list counters for one object, include the object name.        |
|               -sc \<samples>               |             Specifies the number of samples to collect. The default is to collect data until CTRL+C is pressed.              |
|            -config \<filename>             |                                    Specifies a settings file containing command options.                                     |
|            -s \<computer_name>             |                   Specifies a remote computer to monitor if no computer is specified in the counter path.                    |
|                     -y                     |                                        Answer yes to all questions without prompting.                                        |

## Examples

- To writes the values for the local computer's performance counter **\\\\Processor(_Total)\% Processor Time** to the command window at a default sample interval of 1 second until CTRL+C is pressed.  
  ```
  typeperf \Processor(_Total)\% Processor Time
  ```  
- To writes the values for the list of counters in the file **counters.txt** to the tab-delimited file **domain2.tsv** at a sample interval of 5 seconds until 50 samples have been collected.  
  ```
  typeperf -cf counters.txt -si 5 -sc 50 -f TSV -o domain2.tsv
  ```  
- To queries installed counters with instances for the counter object **PhysicalDisk** and writes the resulting list to the file **counters.txt**.  
  ```
  typeperf -qx PhysicalDisk -o counters.txt
  ```

---


MIT License. Copyright (c) 2020 Strontic.


