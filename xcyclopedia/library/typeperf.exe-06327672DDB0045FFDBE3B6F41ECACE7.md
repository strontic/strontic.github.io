---
title: typeperf.exe | Command line performance monitor
---

# typeperf.exe 

* File Path: `C:\Windows\system32\typeperf.exe`
* Description: Command line performance monitor
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `06327672DDB0045FFDBE3B6F41ECACE7`
SHA1 | `4289DB11F32514AD9C21A83592FFA14CB156CBAF`
SHA256 | `7DA4FB590C5BCB0A98BAB84BC587CCC728DEFDFFF7139FC7994734F192CAC385`
SHA384 | `FC4591CDE7318755D562EB76D6473DB7BFFC24C5B7EECFB47BA21C7C5ABD1CD068D2363C89966C63820864F3CD2E97E1`
SHA512 | `42022E771A4C19FBED2488953C7600544661259FD0C15F1F8B7DB692480E1E2768D4D1CFD43C5C77D8DFC4558D1BF1FB62910A052A5CDDDB24FE5E5ABF6994DE`
SSDEEP | `1536:h/BL4f+eh450dilLWuwUrt0uXjF2xtpLmiuMa4NS5EO:yE0IlZ9ItpLmiuMaiS53`

## Runtime Data

### Usage (stdout):
```Batchfile

Microsoft r TypePerf.exe (10.0.19041.1)

Typeperf writes performance data to the command window or to a log file. To
stop Typeperf, press CTRL+C.

Usage:
C:\Windows\system32\typeperf.exe { <counter [counter ...]> 
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

* Original Filename: TypePerf.exe.mui
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


