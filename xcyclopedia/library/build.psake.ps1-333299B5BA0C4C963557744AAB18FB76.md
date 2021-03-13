---
title: build.psake.ps1 | 
excerpt: What is build.psake.ps1?
---

# build.psake.ps1 

* File Path: `C:\Program Files\WindowsPowerShell\Modules\Pester\3.4.0\build.psake.ps1`

## Hashes

Type | Hash
-- | --
MD5 | `333299B5BA0C4C963557744AAB18FB76`
SHA1 | `70DA7E6DF0664C0E791C32C31E14924B779A6938`
SHA256 | `E70CCCC09D7EE184321D7A1DBDCC4E770E7F05A4E7FE4A286185FDC3469138D9`
SHA384 | `CDDB4C7C0E3ED6ED2CC05B5EE362C377CE5D4B332B7D31A84F6389E002825CCBDEC8220756C7A790FA6E13023E5506C7`
SHA512 | `CEF4FF161E2EC21006FFDD4231979182B4A043D44A44AF6B3B6AEC244F96F9DB971F2B5B99C3E93E26B7FA31FDAD5B4DD7ADD4144CCC11C0B78BDDD7E4731EB6`
SSDEEP | `24:dUD/MRlhzsyAmPFaoAR9EQ/PSbUo9bNbUo9b5hlXgzOyaG8n8FSo888qZwFen9ii:dgMfhzV79ao3Q3SbUGVUG5hlXTwSyaFQ`
PESHA1 | `70DA7E6DF0664C0E791C32C31E14924B779A6938`
PE256 | `E70CCCC09D7EE184321D7A1DBDCC4E770E7F05A4E7FE4A286185FDC3469138D9`

## Runtime Data

### Usage (stderr):
```cmhg
The property 'use_exit_on_error' cannot be found on this object. Verify that the property exists and can be set.
At C:\Program Files\WindowsPowerShell\Modules\Pester\3.4.0\build.psake.ps1:1 char:1
+ $psake.use_exit_on_error = $true
+ ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
    + CategoryInfo          : InvalidOperation: (:) [], RuntimeException
    + FullyQualifiedErrorId : PropertyNotFound
 
properties : The term 'properties' is not recognized as the name of a cmdlet, function, script file, or operable 
program. Check the spelling of the name, or if a path was included, verify that the path is correct and try again.
At C:\Program Files\WindowsPowerShell\Modules\Pester\3.4.0\build.psake.ps1:2 char:1
+ properties {
+ ~~~~~~~~~~
    + CategoryInfo          : ObjectNotFound: (properties:String) [], CommandNotFoundException
    + FullyQualifiedErrorId : CommandNotFoundException
 
Task : The term 'Task' is not recognized as the name of a cmdlet, function, script file, or operable program. Check 
the spelling of the name, or if a path was included, verify that the path is correct and try again.
At C:\Program Files\WindowsPowerShell\Modules\Pester\3.4.0\build.psake.ps1:11 char:1
+ Task default -depends Test, Build
+ ~~~~
    + CategoryInfo          : ObjectNotFound: (Task:String) [], CommandNotFoundException
    + FullyQualifiedErrorId : CommandNotFoundException
 
Task : The term 'Task' is not recognized as the name of a cmdlet, function, script file, or operable program. Check 
the spelling of the name, or if a path was included, verify that the path is correct and try again.
At C:\Program Files\WindowsPowerShell\Modules\Pester\3.4.0\build.psake.ps1:12 char:1
+ Task Build -depends Package
+ ~~~~
    + CategoryInfo          : ObjectNotFound: (Task:String) [], CommandNotFoundException
    + FullyQualifiedErrorId : CommandNotFoundException
 

```

### Child Processes:
conhost.exe

### Open Handles:

Path | Type
-- | --
(R-D)   C:\Windows\Microsoft.NET\assembly\GAC_64\mscorlib\v4.0_4.0.0.0__b77a5c561934e089\mscorlib.dll | File
(R-D)   C:\Windows\Microsoft.NET\assembly\GAC_64\System.Data\v4.0_4.0.0.0__b77a5c561934e089\System.Data.dll | File
(R-D)   C:\Windows\Microsoft.NET\assembly\GAC_64\System.Transactions\v4.0_4.0.0.0__b77a5c561934e089\System.Transactions.dll | File
(R-D)   C:\Windows\Microsoft.NET\assembly\GAC_MSIL\Microsoft.Management.Infrastructure\v4.0_1.0.0.0__31bf3856ad364e35\Microsoft.Management.Infrastructure.dll | File
(R-D)   C:\Windows\Microsoft.NET\assembly\GAC_MSIL\Microsoft.PowerShell.ConsoleHost\v4.0_3.0.0.0__31bf3856ad364e35\Microsoft.PowerShell.ConsoleHost.dll | File
(R-D)   C:\Windows\Microsoft.NET\assembly\GAC_MSIL\Microsoft.PowerShell.Security\v4.0_3.0.0.0__31bf3856ad364e35\Microsoft.PowerShell.Security.dll | File
(R-D)   C:\Windows\Microsoft.NET\assembly\GAC_MSIL\System.Configuration\v4.0_4.0.0.0__b03f5f7f11d50a3a\System.Configuration.dll | File
(R-D)   C:\Windows\Microsoft.NET\assembly\GAC_MSIL\System.Core\v4.0_4.0.0.0__b77a5c561934e089\System.Core.dll | File
(R-D)   C:\Windows\Microsoft.NET\assembly\GAC_MSIL\System.DirectoryServices\v4.0_4.0.0.0__b03f5f7f11d50a3a\System.DirectoryServices.dll | File
(R-D)   C:\Windows\Microsoft.NET\assembly\GAC_MSIL\System.Management.Automation\v4.0_3.0.0.0__31bf3856ad364e35\System.Management.Automation.dll | File
(R-D)   C:\Windows\Microsoft.NET\assembly\GAC_MSIL\System.Management\v4.0_4.0.0.0__b03f5f7f11d50a3a\System.Management.dll | File
(R-D)   C:\Windows\Microsoft.NET\assembly\GAC_MSIL\System.Numerics\v4.0_4.0.0.0__b77a5c561934e089\System.Numerics.dll | File
(R-D)   C:\Windows\Microsoft.NET\assembly\GAC_MSIL\System.Xml\v4.0_4.0.0.0__b77a5c561934e089\System.XML.dll | File
(R-D)   C:\Windows\Microsoft.NET\assembly\GAC_MSIL\System\v4.0_4.0.0.0__b77a5c561934e089\System.dll | File
(R-D)   C:\Windows\System32\en-US\crypt32.dll.mui | File
(R-D)   C:\Windows\System32\en-US\winnlsres.dll.mui | File
(R-D)   C:\Windows\System32\WindowsPowerShell\v1.0\en-US\powershell.exe.mui | File
(RW-)   C:\Users\user | File
\...\Cor_SxSPublic_IPCBlock | Section
\BaseNamedObjects\__ComCatalogCache__ | Section
\BaseNamedObjects\C:\*ProgramData\*Microsoft\*Windows\*Caches\*{6AF0698E-D558-4F6E-9B3C-3716689AF493}.2.ver0x0000000000000002.db | Section
\BaseNamedObjects\C:\*ProgramData\*Microsoft\*Windows\*Caches\*{DDF571F2-BE98-426D-8288-1A9A39C3FDA2}.2.ver0x0000000000000002.db | Section
\BaseNamedObjects\C:\*ProgramData\*Microsoft\*Windows\*Caches\*cversions.2 | Section
\BaseNamedObjects\Cor_Private_IPCBlock_v4_1940 | Section
\BaseNamedObjects\NLS_CodePage_1252_3_2_0_0 | Section
\BaseNamedObjects\NLS_CodePage_437_3_2_0_0 | Section
\Sessions\1\BaseNamedObjects\windows_shell_global_counters | Section


### Loaded Modules:

Path |
-- |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\WindowsPowerShell\v1.0\powershell.exe |


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
* VirusTotal Link: https://www.virustotal.com/gui/file/e70cccc09d7ee184321d7a1dbdcc4e770e7f05a4e7fe4a286185fdc3469138d9/detection

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Program Files (x86)\WindowsPowerShell\Modules\Pester\3.4.0\build.psake.ps1](build.psake.ps1-333299B5BA0C4C963557744AAB18FB76.md) | 100




MIT License. Copyright (c) 2020-2021 Strontic.


