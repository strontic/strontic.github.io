---
title: appcert.exe | Command Line Interface
excerpt: What is appcert.exe?
---

# appcert.exe 

* File Path: `C:\Program Files (x86)\Windows Kits\10\App Certification Kit\appcert.exe`
* Description: Command Line Interface

## Hashes

Type | Hash
-- | --
MD5 | `CA526E704DDFEF1E3E24276FBBF0B4CF`
SHA1 | `BBBAADC01B079A171462A6FEC4D125EAA5CD9653`
SHA256 | `1C94217ACD0B918409170B3764BC3B5771C1C2DE2DAFCB09B5E7D9BFF9C226B4`
SHA384 | `3DCBA5113C39808B8655F9B13EF41F48766C74EA1914D5B41D3EEF6EAD59EA259E31B2D4CF91A2B887180E6670835B30`
SHA512 | `7E2D6893FDB5410DE9ECC5DE0AE15164BEA7B1C528A90F224F7ADF55200870E5C0385557682A883AF59C53096FC0AD6208CC2A60316DF8A396589EE9FB6CD12F`
SSDEEP | `768:n7bDiVME6tBz5s3NHhBX+ZpK76k7Q4+Sz8i75:HDiV2tBzyZhBEY1YSZ5`
PESHA1 | `6ECA061CE73ACE39C07AD61AD0C21174A867ACD1`
PE256 | `B51F0F8B04672E1E1E1BE7FAF8B563E858248A610055056405EB238DC5A7B242`

## Runtime Data

### Usage (stdout):
```cmhg
Windows App Certification Kit
(C) Microsoft Corporation. All rights reserved.

Welcome to Windows App Certification Kit.

This kit will help validate application compliance with Windows App Certification Kit requirements.
For best results please run this kit on a clean install of Windows. Also make sure all tests are run in the same session - reboots and/or log off will be recorded as failures.
Please ensure that you have run your application(s) at least once and dismissed license agreements and first-time prompts to avoid unnecessary failures while testing.
Please run 'appcert reset' before start of a new validation.

USAGE:

appcert.exe [ test | finalizereport | reset | querytestids] [options]

Verbs:

test                                     Executes the testing session.
finalizereport                           In case of any waiver instructions, you will need to exercise this option. The output of "test" will indicate if report finalization is required.
reset                                    Resets the testing process.
querytestids                             Prints list of test names and corresponding test ids for Microsoft Store Certification.

Options (test)
-packagefullname <packagefullname>       Specifies the installed package full name (Microsoft Store Apps only).
-appxpackagepath <path>                  Specifies the full path to the app package that will be tested (Microsoft Store Apps only).
-apptype <type>                          Specifies the application type. Can be either desktop or desktopdevice. Not needed for Store app.
-setuppath <path>                        Specifies the (required) setup executable or MSI full path.
-setupcommandline <commandline>          Specifies the (optional) setup command line.
-waittimeout <timeout>                   Specifies the (optional) install or uninstall wait timeout in seconds.
-appusage <usageType>                    Specifies the (optional) application usage type. Can be either peruser | permachine. Default value is permachine.
-reportoutputpath <name>                 Specifies the (required) report output full path and file name.
-testid [testid1,testid2,testid3, ...]   Specifies the (optional) list of comma separated test ids to execute during the test.

Options (finalizereport)
-reportfilepath <name>                   Specifies the full path (including file name) of the report that has to be finalized.

Examples:
appcert test -packagefullname microsoft.devx.appx.helloworld_1.0.0.0_neutral_NorthAmerica_ac4zc6fex2zjp -reportoutputpath c:\Output\MyReport.xml
appcert test -appxpackagepath C:\Input\myapp_helloworld.msix -reportoutputpath C:\Output\MyReport.xml
appcert test -appxpackagepath C:\Input\myapp_helloworld.appx -reportoutputpath C:\Output\MyReport.xml
appcert test -testid [21,47,31] -packagefullname microsoft.devx.appx.helloworld_1.0.0.0_neutral_NorthAmerica_ac4zc6fex2zjp -reportoutputpath c:\Output\MyReport.xml
appcert test -apptype desktop -setuppath d:\cdrom\setup.exe -setupcommandline "-install -quiet" -waittimeout 900 -appusage permachine -reportoutputpath c:\Output\MyReport.xml
appcert test -apptype desktop -setuppath d:\cdrom\setup.exe  -appusage peruser -reportoutputpath c:\Output\MyReport.xml
appcert test -apptype desktopdevice -setuppath d:\cdrom\setup.exe -setupcommandline "-install -quiet" -waittimeout 900 -reportoutputpath c:\Output\MyReport.xml
appcert querytestids
appcert finalizereport -reportfilepath c:\Output\MyReport.xml
appcert reset

Return codes:
   0 = The verb executed successfully.
   1 = The verb executed successfully but needs report finalization.
  -1 = Invalid command line error occurred.
  -2 = Infrastructure error occurred.
  -3 = User initiated error occurred.
  -4 = App installation error occurred.
  -5 = App unpackaging error occurred.


```

### Loaded Modules:

Path |
-- |
C:\Program Files (x86)\Windows Kits\10\App Certification Kit\appcert.exe |
C:\Windows\System32\KERNEL32.dll |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\SYSTEM32\MSCOREE.DLL |
C:\Windows\SYSTEM32\ntdll.dll |


## Signature

* Status: Signature verified.
* Serial: `33000002CF6D2CC57CAA65A6D80000000002CF`
* Thumbprint: `1A221B3B4FEF088B17BA6704FD088DF192D9E0EF`
* Issuer: CN=Microsoft Code Signing PCA 2010, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Corporation, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: Logotest.exe
* Product Name: Windows App Certification Kit
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/73
* VirusTotal Link: https://www.virustotal.com/gui/file/1c94217acd0b918409170b3764bc3b5771c1c2de2dafcb09b5e7d9bff9c226b4/detection


## Possible Misuse

*The following table contains possible examples of `appcert.exe` being misused. While `appcert.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [index.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Indexes-Markdown/index.md) | - T1546.009 AppCert DLLs [CONTRIBUTE A TEST](https://atomicredteam.io/contributing) | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [windows-index.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Indexes-Markdown/windows-index.md) | - T1546.009 AppCert DLLs [CONTRIBUTE A TEST](https://atomicredteam.io/contributing) | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [matrix.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Matrices/matrix.md) | \| [Default Accounts](../../T1078.001/T1078.001.md) \| Component Object Model [CONTRIBUTE A TEST](https://atomicredteam.io/contributing) \| Add-ins [CONTRIBUTE A TEST](https://atomicredteam.io/contributing) \| AppCert DLLs [CONTRIBUTE A TEST](https://atomicredteam.io/contributing) \| [BITS Jobs](../../T1197/T1197.md) \| Brute Force [CONTRIBUTE A TEST](https://atomicredteam.io/contributing) \| Cloud Groups [CONTRIBUTE A TEST](https://atomicredteam.io/contributing) \| Internal Spearphishing [CONTRIBUTE A TEST](https://atomicredteam.io/contributing) \| [Archive via Utility](../../T1560.001/T1560.001.md) \| Exfiltration Over Bluetooth [CONTRIBUTE A TEST](https://atomicredteam.io/contributing) \| Communication Through Removable Media [CONTRIBUTE A TEST](https://atomicredteam.io/contributing) \| Data Encrypted for Impact [CONTRIBUTE A TEST](https://atomicredteam.io/contributing) \| | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [matrix.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Matrices/matrix.md) | \| Drive-by Compromise [CONTRIBUTE A TEST](https://atomicredteam.io/contributing) \| [Cron](../../T1053.003/T1053.003.md) \| AppCert DLLs [CONTRIBUTE A TEST](https://atomicredteam.io/contributing) \| [Application Shimming](../../T1546.011/T1546.011.md) \| Bootkit [CONTRIBUTE A TEST](https://atomicredteam.io/contributing) \| Cloud Instance Metadata API [CONTRIBUTE A TEST](https://atomicredteam.io/contributing) \| Cloud Service Dashboard [CONTRIBUTE A TEST](https://atomicredteam.io/contributing) \| [Pass the Hash](../../T1550.002/T1550.002.md) \| [Automated Collection](../../T1119/T1119.md) \| Exfiltration Over Other Network Medium [CONTRIBUTE A TEST](https://atomicredteam.io/contributing) \| DNS Calculation [CONTRIBUTE A TEST](https://atomicredteam.io/contributing) \| Defacement [CONTRIBUTE A TEST](https://atomicredteam.io/contributing) \| | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [windows-matrix.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Matrices/windows-matrix.md) | \| [Default Accounts](../../T1078.001/T1078.001.md) \| Component Object Model and Distributed COM [CONTRIBUTE A TEST](https://atomicredteam.io/contributing) \| AppCert DLLs [CONTRIBUTE A TEST](https://atomicredteam.io/contributing) \| AppCert DLLs [CONTRIBUTE A TEST](https://atomicredteam.io/contributing) \| [BITS Jobs](../../T1197/T1197.md) \| Cached Domain Credentials [CONTRIBUTE A TEST](https://atomicredteam.io/contributing) \| [Domain Account](../../T1087.002/T1087.002.md) \| Internal Spearphishing [CONTRIBUTE A TEST](https://atomicredteam.io/contributing) \| Archive via Library [CONTRIBUTE A TEST](https://atomicredteam.io/contributing) \| Exfiltration Over Asymmetric Encrypted Non-C2 Protocol [CONTRIBUTE A TEST](https://atomicredteam.io/contributing) \| Commonly Used Port [CONTRIBUTE A TEST](https://atomicredteam.io/contributing) \| [Data Destruction](../../T1485/T1485.md) \| | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [apis.md](https://github.com/redcanaryco/atomic-red-team/blob/master/docs/apis.md) | Hardware Additions, Command-Line Interface, AppCert DLLs, AppCert DLLs, Binary Padding, Brute Force, Browser Bookmark Discovery, Distributed Component Object Model, Clipboard Data, Data Encrypted, Connection Proxy | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)



MIT License. Copyright (c) 2020-2021 Strontic.


