---
title: gpupdate.exe | Microsoft Group Policy Update Utility
excerpt: What is gpupdate.exe?
---

# gpupdate.exe 

* File Path: `C:\Windows\system32\gpupdate.exe`
* Description: Microsoft Group Policy Update Utility

## Hashes

Type | Hash
-- | --
MD5 | `118729DD62B9422D21AFE5CEBD564F8A`
SHA1 | `0638FC81AC1545D9A324460DE4CA6AE234C2A005`
SHA256 | `B76CE2BBA63BD2949FA6E36FBA963379B9D682F7642CD3782D9818FCD30A3E00`
SHA384 | `992097EDD8AC6F4224F2176A17CC7DF6093627A9E8191DF87885D091A664E039B61682E3C7939B2B44D293E55B925B36`
SHA512 | `7CA53ECDAF4F72948370E74224544DB5C3106B829B329C912B77D41E0969B521276135D13A652DA8FED326DBB8B6238207BC66B764C03C11B9BB46B5C30DADEE`
SSDEEP | `384:c4ce5DsF6pQMT5TLSUK9EJ8r/eOdqClM+RCTXOPlU3JF26XI/N6rMSnl2R/WoD4T:cJdET5TL5zOrePQCTXqhSnl0QC4CGer`
IMP | `D2466CD4C38ECEF8AAB0EE78B79FC8B8`
PESHA1 | `3355447AA2D6C929D3168CFCC4939A15C2F9AB12`
PE256 | `F9853A7A8AA26B1B84FAE4E97D4FEDBD2BE0CAA2717C4A8C31C1C80E9600DB0F`

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
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
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

* VirusTotal Detections: 0/75
* VirusTotal Link: https://www.virustotal.com/gui/file/b76ce2bba63bd2949fa6e36fba963379b9d682f7642cd3782d9818fcd30a3e00/detection

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Windows\system32\gpupdate.exe](gpupdate.exe-2F23BC7F66D9C1CA02F7777616285874.md) | 25
[C:\Windows\system32\gpupdate.exe](gpupdate.exe-5BC3021BF9F2787FA17442B68739755E.md) | 27
[C:\WINDOWS\system32\gpupdate.exe](gpupdate.exe-D4F01BEC9CA921C13ED1BDD1BF1D2D24.md) | 27
[C:\Windows\system32\gpupdate.exe](gpupdate.exe-EE5892A6168658FF9C7784FF94346AA2.md) | 24

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


