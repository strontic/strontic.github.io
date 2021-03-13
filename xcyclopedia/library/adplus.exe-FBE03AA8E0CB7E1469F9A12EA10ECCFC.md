---
title: adplus.exe |  
excerpt: What is adplus.exe?
---

# adplus.exe 

* File Path: `C:\Program Files (x86)\Windows Kits\10\Debuggers\arm64\adplus.exe`
* Description:  

## Hashes

Type | Hash
-- | --
MD5 | `FBE03AA8E0CB7E1469F9A12EA10ECCFC`
SHA1 | `45A57B9F45CDF3D80E68522BFFB57E4614A78FCB`
SHA256 | `9DAEE0BDE6608EFE2A6E564EBDC716013ED79AEFA65C8266597D5BB989FE683E`
SHA384 | `C9A8ED853A9D3EF074AF47AD4EC07B5FD40924B9C52000B8EDF2C06C2D37E793F897475E30CA7FB003B3108BDB36E28A`
SHA512 | `5AF17485E7F5DC9D02FB612B76298BD1205EDCA21B4FFBE1225D07F3711D15DB23C733AC4EB300E3C0831572B3E0AF74F47FC5F6BC3FE2B0F2539763053BB893`
SSDEEP | `1536:F8Kjkp0ynhPotyboYSQs12eSsBYCTbqmC2zPCPXNwcZp3CWVq++FUALPYo:yr0yR/EoabBYCTb42zPCPXNRxwBPYo`
IMP | `F34D5F2D4577ED6D9CEEC516C1F5A744`
PESHA1 | `2EF3E1B74509010CBAD61957280D1190E3BEE231`
PE256 | `FE0C2EFD75BE09631CC6475ABA8F421DBD5CFB4C276CF4FDA78F97F58338E4B1`

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
C:\Program Files (x86)\Windows Kits\10\Debuggers\arm64\adplus.exe |
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
[C:\Program Files (x86)\Windows Kits\10\Debuggers\arm\adplus.exe](adplus.exe-7E75934D86C4E2EBF641395762BFEA01.md) | 90
[C:\Program Files (x86)\Windows Kits\10\Debuggers\x64\adplus.exe](adplus.exe-8FC2163FC15F2EC5491ED58B1C54287F.md) | 94
[C:\Program Files (x86)\Windows Kits\10\Debuggers\x86\adplus.exe](adplus.exe-1285EB619EEBCBB8DC91B8D5389EDB29.md) | 91

## Possible Misuse

*The following table contains possible examples of `adplus.exe` being misused. While `adplus.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Adplus.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OtherMSBinaries/Adplus.yml) | `Name: adplus.exe`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Adplus.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OtherMSBinaries/Adplus.yml) | `- Command: adplus.exe -hang -pn lsass.exe -o c:\users\mr.d0x\output\folder -quiet`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Adplus.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OtherMSBinaries/Adplus.yml) | `- Path: C:\Program Files (x86)\Windows Kits\10\Debuggers\x64\adplus.exe`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Adplus.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OtherMSBinaries/Adplus.yml) | `- Path: C:\Program Files (x86)\Windows Kits\10\Debuggers\x86\adplus.exe`{:.highlight .language-yaml} | 



MIT License. Copyright (c) 2020-2021 Strontic.


