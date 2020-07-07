---
title: typeperf.exe | Command line performance monitor
---

# typeperf.exe 

* File Path: `C:\Windows\SysWOW64\typeperf.exe`
* Description: Command line performance monitor
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `F79CB8B640C8DEDA1896588BCBA690CE`
SHA1 | `D700BB47E27D861586DCC764F0B14A09759B43FF`
SHA256 | `6189863E404821412177546146BF39BE81603229F5FCC7D669E4737DD8FF7B7E`
SHA384 | `D0A4088C9A46802617A872B1C25381CE53A643D4FDA298FFBAA5B94BDCE325E2C2BA1917CC041994F03A307C3EDAA0BA`
SHA512 | `38D7C3C83AD071B6F23175F0E8A643D5CA7018044C1B0E2E327FA9D4470EF6911502BD88E825C6A965C195E81F8A5C41F5D0927CA8C5439AE9CC3F64F4AD424C`
SSDEEP | `768:Mrez2ecGi6KS8ak9ivuIwz8doMwQNd6YGvI3/YroadNoeHQV+UEhAz:MJGiWre1mdsaGw3AMadNoeWEhQ`

## Runtime Data

### Usage (stdout):
```Batchfile

Microsoft r TypePerf.exe (10.0.19041.1)

Typeperf
writes
performance data to the command window or to a log file. To stop Typeperf, press CTRL+C.

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
* Serial: `330000023241FB59996DCC4DFF000000000232`
* Thumbprint: `FF82BC38E1DA5E596DF374C53E3617F7EDA36B06`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: TypePerf.exe
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.



## Additional Info*

**The information below is copied from [MicrosoftDocs](https://github.com/MicrosoftDocs/windowsserverdocs), which is maintained by [Microsoft](https://opensource.microsoft.com/codeofconduct/). Available under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) license.*

---

## typeperf

The **typeperf** command writes performance data to the command window or to a log file. To stop **typeperf**, press CTRL+C.

### Syntax

```
typeperf <counter [counter ...]> [options]
typeperf -cf <filename> [options]
typeperf -q [object] [options]
typeperf -qx [object] [options]
```

#### Parameters

|Parameter|Description|
|---------|-----------|
|\<counter [counter [â€¦]]>|Specifies performance counters to monitor.|

> [!NOTE]
> **\<counter>** is the full name of a performance counter in *\\\\Computer\Object(Instance)\Counter* format, such as **\\\\Server1\Processor(0)\% User Time**.

### Options

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

### Examples

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


