﻿---
title: gpupdate.exe | Microsoft Group Policy Update Utility
excerpt: What is gpupdate.exe?
---

# gpupdate.exe 

* File Path: `C:\Windows\system32\gpupdate.exe`
* Description: Microsoft Group Policy Update Utility

## Hashes

Type | Hash
-- | --
MD5 | `2F23BC7F66D9C1CA02F7777616285874`
SHA1 | `9AC41E28FE71AD2D045296021E2130E457B22177`
SHA256 | `14803CB04D08AD97C194A587273545627E729ACC747669A0F6F069E0655E2438`
SHA384 | `5477B9F81B40D99AFBDED645375D118660D9650E1CC3ED62EF47860CA1B56C1592827FD2B6033F065CBC3A5051FEE25A`
SHA512 | `2814A55AB2551163E93403A422C30E2AE3C18EA6D741F950EED272AE9D72C4E5C5C6D0AFE793BA3A534510BDC49AC9F2B2F5F655EA3386698B83CAD4979E0F2B`
SSDEEP | `384:4IUZjclU00Ko2IyfIFZNGFc5sz5c884QBs3xt6i9Qbxel2R/WoDoaKkC4heu9Ai7:FT10Ko2twF1A5c8XWdel0A6C4YL6`
IMP | `874ADC3991B152C2F8C8ABC6E3F65A5C`
PESHA1 | `741DD72B2BC8ED5918F1B62BF7EB2B578C9347B6`
PE256 | `F1FFD434BE541FE8AFBF2D530CA2CFCA1F43BD5C4BC579E9F6BBA32BBE10B4CC`

## Runtime Data

### Usage (stdout):
```cmhg
Description:  Updates multiple Group Policy settings.

Syntax:  Gpupdate [/Target:{Computer | User}] [/Force] [/Wait:<value>]
     [/Logoff] [/Boot] [/Sync] 

Parameters:

Value                      Description
/Target:{Computer | User}  Specifies that only User or only Computer
                            policy settings are updated. By default,
                            both User and Computer policy settings are
                            updated.

/Force                     Reapplies all policy settings. By default,
                            only policy settings that have changed are
                            applied.

/Wait:{value}              Sets the number of seconds to wait for policy
                            processing to finish. The default is 600
                            seconds. The value '0' means not to wait.
                            The value '-1' means to wait indefinitely.
                            When the time limit is exceeded, the command
                            prompt returns, but policy processing
                            continues.

/Logoff                    Causes a logoff after the Group Policy settings
                            have been updated. This is required for
                            those Group Policy client-side extensions
                            that do not process policy on a background
                            update cycle but do process policy when a
                            user logs on. Examples include user-targeted
                            Software Installation and Folder Redirection.
                            This option has no effect if there are no
                            extensions called that require a logoff.

/Boot                      Causes a computer restart after the Group Policy settings
                            are applied. This is required for those
                            Group Policy client-side extensions that do
                            not process policy on a background update cycle
                            but do process policy at computer startup.
                            Examples include computer-targeted Software
                            Installation. This option has no effect if
                            there are no extensions called that require
                            a restart.

/Sync                      Causes the next foreground policy application to
                            be done synchronously. Foreground policy
                            applications occur at computer start up and user
                            logon. You can specify this for the user,
                            computer or both using the /Target parameter.
                            The /Force and /Wait parameters will be ignored
                            if specified.


```

### Loaded Modules:

Path |
-- |
C:\Windows\system32\gpupdate.exe |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\SYSTEM32\ntdll.dll |


## Signature

* Status: Signature verified.
* Serial: `330000026551AE1BBD005CBFBD000000000265`
* Thumbprint: `E168609353F30FF2373157B4EB8CD519D07A2BFF`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: GPUpdate.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.117 (WinBuild.160101.0800)
* Product Version: 10.0.19041.117
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/72
* VirusTotal Link: https://www.virustotal.com/gui/file/14803cb04d08ad97c194a587273545627e729acc747669a0f6f069e0655e2438/detection/

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Windows\system32\gpupdate.exe](gpupdate.exe-118729DD62B9422D21AFE5CEBD564F8A.md) | 25
[C:\Windows\system32\gpupdate.exe](gpupdate.exe-5BC3021BF9F2787FA17442B68739755E.md) | 25
[C:\WINDOWS\system32\gpupdate.exe](gpupdate.exe-D4F01BEC9CA921C13ED1BDD1BF1D2D24.md) | 32
[C:\WINDOWS\system32\gpupdate.exe](gpupdate.exe-D632D949D09F861F3D1B1097BBC5E4B3.md) | 25
[C:\Windows\system32\gpupdate.exe](gpupdate.exe-EE5892A6168658FF9C7784FF94346AA2.md) | 30

## Possible Misuse

*The following table contains possible examples of `gpupdate.exe` being misused. While `gpupdate.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_suspicious_remote_thread.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/create_remote_thread/sysmon_suspicious_remote_thread.yml) | `- '\gpupdate.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_spoolsv_child_processes.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_spoolsv_child_processes.yml) | `- \gpupdate.exe`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)

## Additional Info*

**The information below is copied from [MicrosoftDocs](https://github.com/MicrosoftDocs/windowsserverdocs), which is maintained by [Microsoft](https://opensource.microsoft.com/codeofconduct/). Available under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) license.*

---

## gpupdate

Updates Group Policy settings.

### Syntax

```
gpupdate [/target:{computer | user}] [/force] [/wait:<VALUE>] [/logoff] [/boot] [/sync] [/?]
```

#### Parameters

| Parameter | Description |
| --------- |------------ |
| /target:`{computer|user}` | Specifies that only User or only Computer policy settings are updated. By default, both User and Computer policy settings are updated. |
| /force | Reapplies all policy settings. By default, only policy settings that have changed are applied. |
| /wait:`<VALUE>` | Sets the number of seconds to wait for policy processing to finish before returning to the command prompt. When the time limit is exceeded, the command prompt appears, but policy processing continues. The default value is 600 seconds. The value **0** means not to wait. The value **-1** means to wait indefinitely.<p>In a script, by using this command with a time limit specified, you can run **gpupdate** and continue with commands that do not depend upon the completion of **gpupdate**. Alternatively, you can use this command with no time limit specified to let **gpupdate** finish running before other commands that depend on it are run. |
| /logoff | Causes a logoff after the Group Policy settings are updated. This is required for those Group Policy client-side extensions that do not process policy on a background update cycle but do process policy when a user logs on. Examples include user-targeted Software Installation and Folder Redirection. This option has no effect if there are no extensions called that require a logoff. |
| /boot | Causes a computer restart after the Group Policy settings are applied. This is required for those Group Policy client-side extensions that do not process policy on a background update cycle but do process policy at computer startup. Examples include computer-targeted Software Installation. This option has no effect if there are no extensions called that require a restart. |
| /sync | Causes the next foreground policy application to be done synchronously. Foreground policy is applied at computer boot and user logon. You can specify this for the user, computer, or both, by using the **/target** parameter. The **/force** and **/wait** parameters are ignored if you specify them. |
| /? | Displays Help at the command prompt. |

#### Examples

To force a background update of all Group Policy settings, regardless of whether they've changed, type:

```
gpupdate /force
```

### Additional References

- [Command-Line Syntax Key](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/command-line-syntax-key.md)

---



MIT License. Copyright (c) 2020-2021 Strontic.


