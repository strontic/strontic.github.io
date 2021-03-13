---
title: Build.bat | 
excerpt: What is Build.bat?
---

# Build.bat 

* File Path: `C:\Program Files\WindowsPowerShell\Modules\Pester\3.4.0\Build.bat`

## Hashes

Type | Hash
-- | --
MD5 | `FBA5E49A848A2EAAB7F51E2ADB48D63F`
SHA1 | `B4FEDB2F7522EB6EEA68EEA73A095EBA8E441926`
SHA256 | `5DDA94698370CAF157D4FD6E669B630F9A2AD529A9DCE75710AB64F85FFA34D3`
SHA384 | `650E818D67F22400EF3A970E1457D520007DE37F23FEC81229F48A186356F94755CF2E36EC2593263351A8792CEA101F`
SHA512 | `75DD51AD7FB370E6B49F6A7FEB854B9F50D971AB8D125CAB43F21788BABB665924A71468AEF98B8FE1B2D7253FFD02243779E13287371D955D453C40BF08DA63`
SSDEEP | `12:tR3yMb1b/Gup3yFFqnHWS585VEO8XIYAHpc+N86yFFqnHWI+98XIYAHpc+1:td3UQ3WFYHW9ch6WFYHWI2`
PESHA1 | `B4FEDB2F7522EB6EEA68EEA73A095EBA8E441926`
PE256 | `5DDA94698370CAF157D4FD6E669B630F9A2AD529A9DCE75710AB64F85FFA34D3`

## Runtime Data

### Usage (stderr):
```cmhg
The system cannot find the path specified.
dir : Cannot find path 'C:\Program Files\WindowsPowerShell\Modules\Pester\3.4.0\vendor\packages' because it does not 
exist.
At line:1 char:22
+ ...  = ([array](dir "C:\Program Files\WindowsPowerShell\Modules\Pester\3. ...
+                 ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
    + CategoryInfo          : ObjectNotFound: (C:\Program File...vendor\packages:String) [Get-ChildItem], ItemNotFound 
   Exception
    + FullyQualifiedErrorId : PathNotFound,Microsoft.PowerShell.Commands.GetChildItemCommand
 
Cannot index into a null array.
At line:1 char:1
+ $psakeDir = ([array](dir "C:\Program Files\WindowsPowerShell\Modules\ ...
+ ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
    + CategoryInfo          : InvalidOperation: (:) [], RuntimeException
    + FullyQualifiedErrorId : NullArray
 
. : The term '\tools\psake.ps1' is not recognized as the name of a cmdlet, function, script file, or operable program. 
Check the spelling of the name, or if a path was included, verify that the path is correct and try again.
At line:1 char:116
+ ... .0\vendor\packages\psake.*"))[-1]; .$psakeDir\tools\psake.ps1 build.p ...
+                                         ~~~~~~~~~~~~~~~~~~~~~~~~~
    + CategoryInfo          : ObjectNotFound: (\tools\psake.ps1:String) [], CommandNotFoundException
    + FullyQualifiedErrorId : CommandNotFoundException
 

```

### Loaded Modules:

Path |
-- |
C:\Windows\system32\cmd.exe |
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

* Original Filename: 
* Product Name: 
* Company Name: 
* File Version: 
* Product Version: 
* Language: 
* Legal Copyright: 

## File Scan

* VirusTotal Detections: 0/76
* VirusTotal Link: https://www.virustotal.com/gui/file/5dda94698370caf157d4fd6e669b630f9a2ad529a9dce75710ab64f85ffa34d3/detection

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Program Files (x86)\WindowsPowerShell\Modules\Pester\3.4.0\Build.bat](Build.bat-FBA5E49A848A2EAAB7F51E2ADB48D63F.md) | 100




MIT License. Copyright (c) 2020-2021 Strontic.


