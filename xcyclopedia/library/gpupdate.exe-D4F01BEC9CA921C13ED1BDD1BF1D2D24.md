---
title: gpupdate.exe | Microsoft Group Policy Update Utility
excerpt: What is gpupdate.exe?
---

# gpupdate.exe 

* File Path: `C:\WINDOWS\system32\gpupdate.exe`
* Description: Microsoft Group Policy Update Utility

## Hashes

Type | Hash
-- | --
MD5 | `D4F01BEC9CA921C13ED1BDD1BF1D2D24`
SHA1 | `1529CB7F7DFA798337F781A71B583371E1D43F2B`
SHA256 | `FE428F64B6920CBD542BF7097F009A576673888967CB5AE8803D310667ED428D`
SHA384 | `D77B0A254F9E11B410825D3276EBEEE37990201D4A4DABDE58E58689FC6B12EB4CBA2FEE37ED982AD19E3B0DA29FE06A`
SHA512 | `A264036B7043D475A9FB6A8C4D08860F3BC26036DF84173710B07E47D4B4272D20C2AE63A2F5FC0E89409A7DB3A247AF51E1C908B4181F17C1874CA9C893AFD5`
SSDEEP | `384:bFhlVqanxKd/cz0+i2nfXdtN2gGM+dVbFd5sBOuROnPl2R/WoDbyEV4uee0hKEou:b3qaxKVczmfdr8yPl0jVV4je0hKEof`

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

## Signature

* Status: Signature verified.
* Serial: `330000023241FB59996DCC4DFF000000000232`
* Thumbprint: `FF82BC38E1DA5E596DF374C53E3617F7EDA36B06`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: GPUpdate.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.18362.1 (WinBuild.160101.0800)
* Product Version: 10.0.18362.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.


## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Windows\system32\gpupdate.exe](gpupdate.exe-118729DD62B9422D21AFE5CEBD564F8A.md) | 27
[C:\Windows\system32\gpupdate.exe](gpupdate.exe-2F23BC7F66D9C1CA02F7777616285874.md) | 32
[C:\Windows\system32\gpupdate.exe](gpupdate.exe-5BC3021BF9F2787FA17442B68739755E.md) | 44
[C:\Windows\system32\gpupdate.exe](gpupdate.exe-EE5892A6168658FF9C7784FF94346AA2.md) | 30

## Possible Misuse

*The following table contains possible examples of `gpupdate.exe` being misused. While `gpupdate.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_suspicious_remote_thread.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/sysmon/sysmon_suspicious_remote_thread.yml) | `- '\gpupdate.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)

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


