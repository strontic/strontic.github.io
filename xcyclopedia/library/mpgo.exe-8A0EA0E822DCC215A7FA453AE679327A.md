---
title: mpgo.exe | mpgo.exe
excerpt: What is mpgo.exe?
---

# mpgo.exe 

* File Path: `C:\Program Files (x86)\Microsoft SDKs\Windows\v10.0A\bin\NETFX 4.8 Tools\mpgo.exe`
* Description: mpgo.exe

## Hashes

Type | Hash
-- | --
MD5 | `8A0EA0E822DCC215A7FA453AE679327A`
SHA1 | `CEF3996139FABC132C62587CB27304B466FBE4D8`
SHA256 | `33C11F4BA35CD4F04012134A4EECC730CD37D26163C3B84E7E76D0DC8FAE6EA0`
SHA384 | `8A762C6739C113848C99D2F38EB60F0A0D136201BB5161B6992419DCC62C861ED69A261DAA375CDF7635B17892E49480`
SHA512 | `5462F4329DA1CFEA6A9DB69E335B2DD9BFE9AEC4805126E99ED91B68B77D5DD4A202E7909FBBF0BE27EB387F88D0C527E2D0217C355AE696CB02691FDAE49FF7`
SSDEEP | `3072:BWZC6Kxje1uPOGpPBwrp1pIb1OGn3socs4kEsRne/FujeMm5pnWT+HJ1kz8V3b4b:Zzje1uPOGpPBC1asocs4k7n/mrbk`
IMP | `F34D5F2D4577ED6D9CEEC516C1F5A744`
PESHA1 | `5E5C6DDAADC4A972B76D5C61492BDC518480D67D`
PE256 | `8C297F482FF60F6731F57D6850F1974380A091BD067EEC12A43587D8412470BB`

## Runtime Data

### Usage (stdout):
```cmhg
Unknown command line argument '--help'

MPGO {arguments}
Required arguments:
-Scenario {scen}
{scen}:   The program, with arguments, to run to generate profile information.
          Include double-quotes around this to properly specify arguments.  If
          there are spaces in individual arguments, 2 double-quotes are needed:
          -Scenario """My App.exe"" ""Argument #1"" Arg#2"
  OR
-Scenario {package_name} -AppID {appid} -Timeout {seconds}
{package_name}: The package name for the Windows Store app to run to generate
          profile information. If the package family name or package name is
          specified instead of the full package name MPGO will attempt to 
          disambiguate by either prompting the user for a choice or by 
          selecting the only package that satisfies the name provided.
{appid}:  The application ID of the application in the package specified by
          {package_name}. If * is specified MPGO will attempt to enumerate
          AppIDs in the package and fallback to {package_family_name}!App
          if it fails. If a string prefixed by ! is specified MPGO will
          concatenate the package family name with the argument provided.
{seconds} The amount of time to allow the Windows Store app to run before
          termination. MUST be specified.
  OR
-Import {dir}
          Migrate previously collected profile data from assemblies specified
          by either -AssemblyList or -AssemblyListFile found in {dir} into the 
          location specified in -OutDir
-OutDir {dir}
{dir}:    The directory to put optimized assemblies in.  It is not recommended
          to be the location of the unoptimized assemblies, as the output files
          will be renamed with numeric suffixes.
-AssemblyList {asmlist}  OR  -AssemblyListFile {file}
{asmlist}:A list of assemblies (including .exe's & .dll's) to collect profile
          information about while running the scenario.  It cannot include
          any assemblies that begin with a '-' character.  Use an
          AssemblyListFile to specify that assembly (or rename your assembly).
{file}:   A text file containing the list of assemblies to collect profile
          information about, one assembly per line.
Both -AssemblyList and -AssemblyListFile can be used multiple times to build
up the list of assemblies to profile.

Optional arguments:
-ExeConfig {file}
{file}:   The config file which your scenario uses to specify version and
          loader information.  Check MSDN for more details.
-64bit
          Instrument the assemblies for 64 bit.  You MUST specify this, even
          if your assembly declares itself to be explicitly 64 bit.
-Reset
          Reset the environment to make certain that an aborted profiling
          session has no impact to your assemblies, and then quit.
          This is done by default before & after a profiling session.
-LeaveNativeImages
          Do not remove the instrumented native images after the scenario has
          been run.  This is useful primarily when you're getting your scenario
          up & working. It will prevent the recreation of native images for
          subsequent runs of MPGO.  When you are done, if you have passed this
          option, there may be orphaned native images in the cache, run MPGO
          with the same assembly list & scenario to remove them up.
-RemoveNativeImages
          Cleanup from a run where -LeaveNativeImages was specified.
          This will ignore any arguments except -64bit, -AssemblyList[File] and
          exit after cleaning up all instrumented native images.
-TimeOut {seconds}
          Collect profile data after {seconds} has elapsed.  This will not
          terminate the scenario, just collect the profile at the timeout point.
-f
          Force the inclusion of the profile data in a binary, even if it's
          signed.  Please note that this will require that the binary be 
          re-signed to work properly.  If this is not done, the binary will
          fail to load & run.

WARNING:  Assemblies in the GAC cannot be updated with profile information. 
          Please un-GAC assemblies before collecting profile data.
          Assemblies which are signed will not be updated with profile data,
          unless the -f option is specified. If -f is specified, binaries must
          be re-signed before they can be used.

```

### Loaded Modules:

Path |
-- |
C:\Program Files (x86)\Microsoft SDKs\Windows\v10.0A\bin\NETFX 4.8 Tools\mpgo.exe |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\wow64.dll |
C:\Windows\System32\wow64cpu.dll |
C:\Windows\System32\wow64win.dll |


## Signature

* Status: Signature verified.
* Serial: `33000001519E8D8F4071A30E41000000000151`
* Thumbprint: `62009AAABDAE749FD47D19150958329BF6FF4B34`
* Issuer: CN=Microsoft Code Signing PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Corporation, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: mpgo.exe
* Product Name: Microsoft Visual Studio 12 CTP
* Company Name: Microsoft Corporation
* File Version: 14.8.4084.0 built by: NET48REL1
* Product Version: 14.8.4084.0
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/72
* VirusTotal Link: https://www.virustotal.com/gui/file/33c11f4ba35cd4f04012134a4eecc730cd37d26163c3b84e7e76d0dc8fae6ea0/detection





MIT License. Copyright (c) 2020 Strontic.


