---
title: typeperf.exe | Command line performance monitor
---

# typeperf.exe 

* File Path: `C:\windows\SysWOW64\typeperf.exe`
* Description: Command line performance monitor

## Hashes

Type | Hash
-- | --
MD5 | `99B1218099684D33D15582BBED966A94`
SHA1 | `679453E755EAC97F39CA16CFE6F81BFCF8B27E46`
SHA256 | `2747462E89FCDBF41AB73F46A8EFB67057792FD659D5AF9F54F1F8CF19F555D9`
SHA384 | `1DA500B4E5180F902C1C14B8C94C386874E2A0CE1A6E90A1E45F69FE609158A33F4C972EA3697355A3D8F9E408D8B4B2`
SHA512 | `1F5E8ED58D817E28436B6B553E909B1E0DBF574FC8F559F73C3C5964CE93395C41D6F1B38A420D2300CD610D2F424613CC26D1B3BE434DDA37940F1B06CA03AE`
SSDEEP | `768:Nrezwcfcj+r0V1xh+h1JnWd7ozrBSuZC1GNwtSqnw23j5roa5NjAJWHv0q:NoEjUQZSTWl5uEec3lMa5NkJ48`

## Runtime Data

### Usage (stdout):
```Batchfile

Microsoft r TypePerf.exe (10.0.17763.1)

Typeperf writes performance data to the command window or to a log file. To
stop Typeperf, press CTRL+C.

Usage:
C:\windows\SysWOW64\typeperf.exe { <counter [counter ...]> 
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

## Signature

* Status: Signature verified.
* Serial: `33000001C422B2F79B793DACB20000000001C4`
* Thumbprint: `AE9C1AE54763822EEC42474983D8B635116C8452`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: TypePerf.exe
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.17763.1 (WinBuild.160101.0800)
* Product Version: 10.0.17763.1
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


