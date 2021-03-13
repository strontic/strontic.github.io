---
title: Pester.bat | 
excerpt: What is Pester.bat?
---

# Pester.bat 

* File Path: `C:\Program Files\WindowsPowerShell\Modules\Pester\3.4.0\bin\Pester.bat`

## Hashes

Type | Hash
-- | --
MD5 | `AE50055B1CDF8855C89616473392C167`
SHA1 | `E20AF79E7EC1B2DBA3DF7600C46E9CA613DF1A3C`
SHA256 | `EB83A9D837CFE2F409CA3839B017E307A7A65782CB6A0AE0C50731C244DAD40E`
SHA384 | `7B6B417FCA9B0981222DFBA785E38AC6B3B684BEB1EFC852944ABCE0911621BA1A1B85D5EC6017A8ECE57768005ECF42`
SHA512 | `8585F6ED6A7B47BFE7DA93CCB167A811E0BD3BAF7AD9B1CFF561E6041923264B29DD19A3C8D45662DF5A617B6A33803DA8ED48C6436492B8FDD8B7384796762B`
SSDEEP | `12:GRJPDRyEybyhy9nqQIYAHpcJB/0wEi4HJ8DV93ir1oiZoQvd4iWDH11KNHaXR40p:2A9pBAUjwoV84iEKhaS0I7BoP`
PESHA1 | `E20AF79E7EC1B2DBA3DF7600C46E9CA613DF1A3C`
PE256 | `EB83A9D837CFE2F409CA3839B017E307A7A65782CB6A0AE0C50731C244DAD40E`

## Runtime Data

### Usage (stdout):
```cmhg
To run pester for tests, just call pester or runtests with no arguments

Example: pester

For Detailed help information, call pester help with a help topic. See
help topic about_Pester for a list of all topics at the end

Example: pester help about_Pester


```

### Usage (stderr):
```cmhg
Add-Type : (0) : 'c:\Users\user\AppData\Local\Temp\kvyg0beo\CSC3B
B6D16419E646B1AAD1A2662C27243.TMP' is not a valid Win32 resource file
(1) :     namespace Pester
At C:\Program 
Files\WindowsPowerShell\Modules\Pester\3.4.0\Functions\SetupTeardown.ps1:301 
char:1
+ & $SafeCommands['Add-Type'] -TypeDefinition @'
+ ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
    + CategoryInfo          : InvalidData: 
(Microsoft.Power...peCompilerError:AddTypeCompilerError) [Add-Type], Exception
    + FullyQualifiedErrorId : 
SOURCE_CODE_ERROR,Microsoft.PowerShell.Commands.AddTypeCommand
 
Add-Type : Cannot add type. Compilation errors occurred.
At C:\Program 
Files\WindowsPowerShell\Modules\Pester\3.4.0\Functions\SetupTeardown.ps1:301 
char:1
+ & $SafeCommands['Add-Type'] -TypeDefinition @'
+ ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
    + CategoryInfo          : InvalidData: (:) [Add-Type], 
InvalidOperationException
    + FullyQualifiedErrorId : 
COMPILER_ERRORS,Microsoft.PowerShell.Commands.AddTypeCommand
 
Invoke-Pester : A parameter cannot be found that matches parameter name 'help'.
At line:1 char:126
+ ... ster\3.4.0\bin\..\Pester.psm1';  & { Invoke-Pester -EnableExit -help}
+                                                                    ~~~~~
    + CategoryInfo          : InvalidArgument: (:) [Invoke-Pester], 
ParameterBindingException
    + FullyQualifiedErrorId : NamedParameterNotFound,Invoke-Pester
 

```

### Child Processes:
conhost.exe powershell.exe

### Open Handles:

Path | Type
-- | --
(RW-)   C:\Users\user | File
\BaseNamedObjects\C:\*ProgramData\*Microsoft\*Windows\*Caches\*{6AF0698E-D558-4F6E-9B3C-3716689AF493}.2.ver0x0000000000000002.db | Section
\BaseNamedObjects\C:\*ProgramData\*Microsoft\*Windows\*Caches\*{DDF571F2-BE98-426D-8288-1A9A39C3FDA2}.2.ver0x0000000000000002.db | Section
\BaseNamedObjects\C:\*ProgramData\*Microsoft\*Windows\*Caches\*cversions.2 | Section
\BaseNamedObjects\NLS_CodePage_1252_3_2_0_0 | Section
\BaseNamedObjects\NLS_CodePage_437_3_2_0_0 | Section


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
* VirusTotal Link: https://www.virustotal.com/gui/file/eb83a9d837cfe2f409ca3839b017e307a7a65782cb6a0ae0c50731c244dad40e/detection

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Program Files (x86)\WindowsPowerShell\Modules\Pester\3.4.0\bin\Pester.bat](Pester.bat-AE50055B1CDF8855C89616473392C167.md) | 100

## Possible Misuse

*The following table contains possible examples of `Pester.bat` being misused. While `Pester.bat` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [pester.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSScripts/pester.yml) | `Name: Pester.bat`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [pester.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSScripts/pester.yml) | `- Command:  Pester.bat [/help\|?\|-?\|/?] "$null; notepad"`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [pester.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSScripts/pester.yml) | `- Path: c:\Program Files\WindowsPowerShell\Modules\Pester\3.4.0\bin\Pester.bat`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [pester.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSScripts/pester.yml) | `- Path: c:\Program Files\WindowsPowerShell\Modules\Pester\*\bin\Pester.bat`{:.highlight .language-yaml} | 



MIT License. Copyright (c) 2020-2021 Strontic.


