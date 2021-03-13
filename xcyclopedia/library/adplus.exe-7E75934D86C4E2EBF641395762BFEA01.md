---
title: adplus.exe |  
excerpt: What is adplus.exe?
---

# adplus.exe 

* File Path: `C:\Program Files (x86)\Windows Kits\10\Debuggers\arm\adplus.exe`
* Description:  

## Hashes

Type | Hash
-- | --
MD5 | `7E75934D86C4E2EBF641395762BFEA01`
SHA1 | `4B36443EC71078E9FE920F6483295C1416E2B985`
SHA256 | `AE72DE3D3F8F22AA8AF047A83BAF0F2D5BC745FCE882BFEFEC2597CCE9D30D25`
SHA384 | `2F90D252AE40D51F934DD31E547D93B6EBBD242E4CDC64BF50DF8B02DFA39F98B9D32DB96ED4BE872E5544C540A33A09`
SHA512 | `F09DB802CA8B59239EA7B3481C0D6AA922BC4AF68C52F46EC7FD4FC639C942BB9682B91AECC7EBAB6B8A4D407EB2F1CCB164F5D9AFD8CB3F020E5AE20092E25B`
SSDEEP | `1536:v8Kjkp0ynhPotyboYSQs1ieSs3YCTbqmC2zPCPXNwcZp3CWVq++FUUPPg:Er0yR/EoaX3YCTb42zPCPXNRxwBPg`
IMP | `F34D5F2D4577ED6D9CEEC516C1F5A744`
PESHA1 | `FF1D0E51995C25CCF23D681CB42CBEBD6BABB2F9`
PE256 | `CBD1A5D0FFA8FB774F7469A282AEDCABEE369749A7A4D6CE7451BFD31B9DB024`

## Runtime Data

### Usage (stdout):
```cmhg
Starting ADPlus
********************************************************
*                                                      *
* ADPLus Flash V 7.01.007 08/11/2011                   *
*                                                      *
*   For ADPlus documentation see ADPlus.doc            *
*   New command line options:                          *
*     -pmn <procname> - process monitor                *
*        waits for a process to start                  *
*     -po <procname> - optional process                *
*        won't fail if this process isn't running      *
*     -mss <LocalCachePath>                            *
*        Sets Microsoft's symbol server                *
*     -r <quantity> <interval in seconds>              *
*        Runs -hang multiple times                     *
*                                                      *
*   ADPlusManager - an additional tool to facilitate   *
*   the use of ADPlus in distributed environments like *
*   computer clusters.                                 *
*   Learn about ADPlusManager in ADPlus.doc            *
*                                                      *
********************************************************


ADPlus Version 7.01.007 08/11/2011

====================
|  ADPlus Usage    |
====================
 Command line syntax options
	ADPlus -?   or 'ADPlus -help
	    Displays this information.

	ADPlus -HelpConfig
	    Displays the built-in key-words and the
default behavior settings

	ADPlus <runmode> -o <OutputDirectory> [options]
	Run Modes:
	    -Crash    Runs ADPlus in Crash mode
	    -Hang     Runs ADPlus in Hang mode

Selecting processes to attach
	-p <PID>  Defines a Process ID to be attached
	-pn <ProcessName> Defines a process name to be attached
	-po <ProcessName> Defines an optional process name to be attached
	-pmn <ProcessName> Defines a process name to be monitored
		ADPlus will keep monitoring if a process with this name starts
		and attach
	-sc <spawning command> Defines the application and parameters to be
		   started in the debugger
		   The -sc switch, if used, must be the last one
	-iis All iis related processes will be attached
		  like inetinfo, dllhost,mtx, etc.

Symbol Path Options
-y <symbol path>   Defines the symbol path to be used
-yp <symbol path to add>   Defines an additional symbol path
-mss <local cache>   Adds Microsoft Symbol Server to the symbol path

Memory Dump Options
-FullOnFirst   Sets ADPlus to create full dumps on first chance exceptions
-MiniOnSecond  Sets ADPlus to create mini dumps on second chance exceptions
-NoDumpOnFirst Sets ADPlus to not create any dumps on first chance exceptions
-NoDumpOnSecond  Sets ADPlus to not create any dumps on second chance exceptions
-do Dump Only - changes default behavior to not include additional info, just a dump

Miscellaneous Options
-c <config file name>   Defines a configuration file to be used
-o <output directory>   Defines the directory where logs and dumps are
                         to be placed.
-r <quantity> <interval in seconds> for multiple attachments in hang mode
-dbg <debugger>  Allows you to select the debugger to be used
                    cdb, windbg or ntsd  (default is cdb)
-dp    Debuggers path
-gs    only generates the script file

-ce <custom exception code>   Defines a custom exception to be monitored
                 -ce 0x80501001

-bp <breakpoint parameters>   Sets a breakpoint
      Syntax: -bp address;optional_additional_parameters
                   -bp MyModule!MyClass::MyMethod
                   -bp MyModule!MyClass::MyMethod;MiniDump

-CTCF  Creates a full dump on CTL+C, and quits
-CTCFB  Creates a full dump on CTL+C, and breaks into the debugger
-CTCV  No special action on CTL+C, just breaks in for user interaction
-lcq  sets the last script command to Q (quit)
-lcg  sets the last script command to G (go)
-lcgn  sets the last script command to GN (go not handled)
-lcqd  sets the last script command to QD (quit and detach)
-lcv  sets the last script command to void (no command; waits for user input)
-q2  sets the return action for second chance exceptions to Q (quit)
-g2  sets the return action for second chance exceptions to GN (go not handled)


-quiet    No dialog boxes will be displayed (no more required)
-notify <destination>  Will send a message to the destination


Examples:
  ADPlus -hang -iis -o c:\dumps
      Produces memory dumps of IIS and all 
      MTS/COM+ packages currently running.

  ADPlus -crash -p 1896 -o c:\dumps -mss c:\symbols
      Attaches the debugger to process with PID 1896
      and monitors it for 1st and 2nd chance access violations and uses
      Microsoft's public symbol server with c:\symbols as a local cache

-------------------------------------------------------------------------------

  HELP and Documentation

  For more detailed information on how to use and config ADPlus please see
  the debugger's help file (debugger.chm) under Extra Tools
    However, be aware that this is a new version of ADPlus and debugger.chm
    may take some time to be updated
  Check for ADPlus.doc in the debuggers' folder
-------------------------------------------------------------------------------
Current log content

ADPlus Engine Version: 7.01.007 08/11/2011
Command line arguments used were: 
-help 


```

### Loaded Modules:

Path |
-- |
C:\Program Files (x86)\Windows Kits\10\Debuggers\arm\adplus.exe |
C:\Windows\System32\KERNEL32.dll |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\SYSTEM32\MSCOREE.DLL |
C:\Windows\SYSTEM32\ntdll.dll |


## Signature

* Status: Signature verified.
* Serial: `33000002B7E8E007A82AEF13150000000002B7`
* Thumbprint: `5A68625F1A516670A744F7EF919500A479D32A5B`
* Issuer: CN=Microsoft Code Signing PCA 2010, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows Kits Publisher, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: Adplus.exe
* Product Name: Microsoft (R) Windows (R) Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1
* Product Version: 10.0.19041.1
* Language: Language Neutral
* Legal Copyright: Copyright (c) Microsoft Corporation. All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: Unknown

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Program Files (x86)\Windows Kits\10\Debuggers\arm64\adplus.exe](adplus.exe-FBE03AA8E0CB7E1469F9A12EA10ECCFC.md) | 90
[C:\Program Files (x86)\Windows Kits\10\Debuggers\x64\adplus.exe](adplus.exe-8FC2163FC15F2EC5491ED58B1C54287F.md) | 91
[C:\Program Files (x86)\Windows Kits\10\Debuggers\x86\adplus.exe](adplus.exe-1285EB619EEBCBB8DC91B8D5389EDB29.md) | 96

## Possible Misuse

*The following table contains possible examples of `adplus.exe` being misused. While `adplus.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Adplus.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OtherMSBinaries/Adplus.yml) | `Name: adplus.exe`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Adplus.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OtherMSBinaries/Adplus.yml) | `- Command: adplus.exe -hang -pn lsass.exe -o c:\users\mr.d0x\output\folder -quiet`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Adplus.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OtherMSBinaries/Adplus.yml) | `- Path: C:\Program Files (x86)\Windows Kits\10\Debuggers\x64\adplus.exe`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Adplus.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OtherMSBinaries/Adplus.yml) | `- Path: C:\Program Files (x86)\Windows Kits\10\Debuggers\x86\adplus.exe`{:.highlight .language-yaml} | 



MIT License. Copyright (c) 2020-2021 Strontic.


