---
title: muirct.exe | Muirct.exe MUI build tool
excerpt: What is muirct.exe?
---

# muirct.exe 

* File Path: `C:\Program Files (x86)\Windows Kits\10\bin\10.0.19041.0\x86\muirct.exe`
* Description: Muirct.exe MUI build tool

## Hashes

Type | Hash
-- | --
MD5 | `7553D72095C0AA7C67BF2058BD93F99F`
SHA1 | `1038B1282FD8A70CEBD44E69DCBCDE7AC9791B3A`
SHA256 | `2CCE7EA27A46FDF03148DFC3E1CD6EC52A37D1CFDB8EB0CC7F4C8B0C2F16F194`
SHA384 | `C1C40327FDDD4A1E3187F51A8F5F2B12CA83F3B896A1DADFC312C60AC071E70E08A77DFCECE90EBB394708F694515EFB`
SHA512 | `50071B633A9F0F659955CDD01F7EDE6939EB8D976A9CE7AA2DB816AE0636E348B66A8D0B68FB055EB4A536F9475735AEAF1B1B2D9C857DA964E3C4B9A3E3ADC3`
SSDEEP | `3072:6spzPYuPTgAsI4s8OnnkzCUBYgUtHG4JGbgkXtWoeFQPEA+KPPXnIzw4bVH:lVmcGbVtbeFmETKnYzbd`
IMP | `BD4B220AE7A320EA5953B0A038419700`
PESHA1 | `BFF381BA01AEE1C2FDF6B354210B27D9EDDE7B66`
PE256 | `69DDD69E60463049A078C1FCF56EA22E29499BE7E77070D46E21651B96AE54B2`

## Runtime Data

### Usage (stderr):
```cmhg
Description

MUIRCT (Muirct.exe) is a command-line utility for splitting a standard Win32
portable executable file into a language-neutral (LN) file and a language
specific .mui file based on a resource configuration file (rc_config file).
In addition to this main functionality, MUIRCT provides options to extract or
calculate resource checksum information from one binary file and copy it to
another and to display the contents of the resource configuration data
contained in a given binary.

MUIRCT usages

1. Split binary into main binary and mui file based on rc_config file
   Muirct -q rc_config [-c checksum_file [-b LangID]] [-x LangID] [-g LangId]
   [-f] [-m] [-v level] source_file [output_LN_file] [output_MUI_file]

2. Extract checksum from checksum_file and insert it in output_file
   Muirct -c checksum_file [-b LangID] -e output_file

3. Calculate checksum based on checksum_file and insert it in output_file
   Muirct  -c checksum_file [-b LangID] -q rc_config  -z output_file

4. Dump resource configuration data contents from input_file.
   Muirct -d input_file

Switches and arguments

-b  Specifies the language to be used when the checksum_file specified with
    -c contains resources in multiple languages. This switch can only be
    used in conjunction with the -c switch. The language identifier can be in
    decimal or hexadecimal format. MUIRCT fails if the checksum_file contains
    resources in multiple language and the -b is not specified or if the
    language specified by the -b switch cannot be found in the checksum_file.

-c  Specifies the input checksum_file from which to extract or calculate the
    resource checksum. Checksum_file must be a Win32 binary file containing
    localizable resources.  If checksum_file contains resources for more than
    one language, the -b switch must be used to specify which of these
    should be used otherwise MUIRCT fails.

-d  Locates and displays embedded resource configuration data in the source
    file. When -d is specified, MUIRCT ignores all other switches.

-e  Extracts the resource checksum contained in the checksum_file provided
    with the -c switch and inserts it in the specified output_file. When -e
    is specified, MUIRCT ignores all switches other than the -c switch.
    In this case the checksum_file must be a Win32 binary file that contains a
    resource configuration data section with a checksum value.
    The output_file must be an existing LN file or .mui file.

-f  Enables creating a .mui file with the version resource being the only
    localizable resource. By default, MUIRCT does not allow this.

-g  Specifies the language ID to be included as the ultimate fallback language
    in the resource configuration data section of the LN file. If the resource
    loader fails to load a requested .mui file from the thread preferred UI
    languages, it uses the ultimate fallback language as its last attempt.
    The LangID value can be specified in decimal or hexadecimal format.
    For example English (United States) can be specified by -g 0x409 or
    -g  1033.

-h | -? Shows the help screen.

-m  Specifies the version number to use when calculating the checksum for
    associating the output_LN_file and output_MUI_file.

-q  Specifies that the source_file is to be split into the output_LN_file and
    the output_MUI_file according to the rc_config file layout. The rc_config
    file is an XML formatted file that specifies which resources will be
    extracted to the .mui file and which will be left in the LN file. The
    rc_config can specify the distribution of resource types and individual
    named items between the output_LN_file and output_MUI_file.
    source_file must be a Win32 binary that contains resources in a
    single language otherwise MUIRCT fails. MUIRCT does not split the file
    if it is language neutral which is indicated by having only language ID
    value 0 in the file.output_LN_file and output_mui_file are the names of
    the language neutral and .mui file into which the source_file is split.
    These file names are optional. If they are not specified, MUIRCT
    appends the extensions .ln and .mui to source_file.
    Typically you should remove the ".ln" extension before
    deploying the file. MUIRCT associates the output_LN_file and
    output_MUI_file by calculating a checksum based on the source_file
    name and file version and inserting the result into the resource
    configuration section of each output file. When used in conjunction
    with the -c switch, the -q switch takes precedence.
    If the rc_config file supplied with the -q switch contains a checksum
    MUIRCT ignores the -c switch and inserts the checksum value from the
    value, rc_config file into the LN and.mui files. If no checksum value is
    found in the rc_config, MUIRCT calculates the resource checksum based on
    the behavior of the -c switch.

-v  Specifies the level of verboseness for logging. Specify 1 to print all
    basic error messages and operation results. Specify 2 to also include the
    resource information (type, name, language identifier) included in the
    .mui file and LN file. The default is -v 1

-x  Specifies the language ID with which MUIRCT marks all resource types added
    to the resource section of the .mui file. The LangID value can be specified
    in decimal or hexadecimal format.
    For example English (United States) can be specified by -x 0x409 or
    -x 1033.
-z  Calculates the resource checksum based on the checksum_file specified
    with the -c switch (and optionally -b switch) and inserts it in the
    specified output_file. The output_file must be an existing LN file or .mui
    file.


```

### Loaded Modules:

Path |
-- |
C:\Program Files (x86)\Windows Kits\10\bin\10.0.19041.0\x86\muirct.exe |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\wow64.dll |
C:\Windows\System32\wow64cpu.dll |
C:\Windows\System32\wow64win.dll |


## Signature

* Status: Signature verified.
* Serial: `33000002CF6D2CC57CAA65A6D80000000002CF`
* Thumbprint: `1A221B3B4FEF088B17BA6704FD088DF192D9E0EF`
* Issuer: CN=Microsoft Code Signing PCA 2010, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Corporation, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: muirct.exe
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: Unknown
* VirusTotal Link: n/a





MIT License. Copyright (c) 2020 Strontic.


