﻿
# typeperf.exe 
* File Path: `C:\WINDOWS\system32\typeperf.exe`
* Description: Command line performance monitor
* Comments: 

## Hashes
Type | Hash
-- | --
MD5 | `0C25F8C87E72FB23C60646DBA70A6B50`
SHA1 | `101CF5D7F835802AE1DF45DB194A271246E730C8`
SHA256 | `1CD1D9C12E247C788E526A84576C9B2B06740C2C3618BF444C19DA1BDC38880C`
SHA384 | `78CA3939B57CA6288F7087F2EFBB0681F90E7779FC7DED3694FED83510DF19532D760CE4DBA388E7EE7BC94C37ACE440`
SHA415 | `8D8C654DA52EB0E87659156CBBC21A6D504E804E82329034222F7AF76637BD9C9B0118B97245674EB12422CB15D02644E020CD6033E7073BC8298779A1ADC134`
SSDEEP | `768:Fk7vbjdOeEMhDmPokX/3jtR+hs+yD8HzkTdcAfPkpnxqYioc7+DBOk1mMHroaXNs:oPXCbjD8TkT9PDYdckOkkEMaXNkfT`

## Runtime Data
### Usage (stdout):
```Batchfile

Microsoft r TypePerf.exe (10.0.18362.1)

Typeperf writes performance data to the command window or to a log file. To
stop Typeperf, press CTRL+C.

Usage:
C:\WINDOWS\system32\typeperf.exe { <counter [counter ...]> 
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
* Serial: 330000023241FB59996DCC4DFF000000000232
* Thumbprint: FF82BC38E1DA5E596DF374C53E3617F7EDA36B06
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: TypePerf.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.18362.1 (WinBuild.160101.0800)
* Product Version: 10.0.18362.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.

