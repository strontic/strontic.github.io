﻿---
title: chocolateyInstall.ps1 | 
excerpt: What is chocolateyInstall.ps1?
---

# chocolateyInstall.ps1 

* File Path: `C:\Program Files\WindowsPowerShell\Modules\Pester\3.4.0\chocolateyInstall.ps1`

## Hashes

Type | Hash
-- | --
MD5 | `561801F9741841E047E2514877BA05A7`
SHA1 | `013A7B468B830C37FA51518E56933ACE54889CCC`
SHA256 | `01A120D3E32F92F8E14671E93045EFB9F76BC0F49B5F0C20216A6634801BC088`
SHA384 | `DAA99A1D3F9E400415E2D90DC710BDDE95BD3FB77B0D50C08C6F9CAF10F1BD554A93F8A977B5CC1E9179D1043F9AC37F`
SHA512 | `7E1D277B624FD6CC4D91265619850CEDC03069E0ECA80A958B7B4BF83E8BFABD31787F77099DF4ADEF1627F0BB17B2F0DCD0BC6267FF8F8BEB54372C8511AABB`
SSDEEP | `48:55iZveCJggotvVzhWXpQHga7X3tMmS8Qy6Qq3V9QPqy/Nk10Qgl7sbQQ9ktnKIGJ:5YvJEHK+UL+9T98a7GjT`
PESHA1 | `013A7B468B830C37FA51518E56933ACE54889CCC`
PE256 | `01A120D3E32F92F8E14671E93045EFB9F76BC0F49B5F0C20216A6634801BC088`

## Runtime Data

### Usage (stderr):
```cmhg
Test-ModuleManifest : The specified module 'C:\Program Files\WindowsPowerShell\Modules\Pester\3.4.0\Tools\Pester.psd1' 
was not loaded because no valid module file was found in any module directory.
At C:\Program Files\WindowsPowerShell\Modules\Pester\3.4.0\chocolateyInstall.ps1:14 char:28
+ ... st        = Test-ModuleManifest -Path $manifestFile -WarningAction Ig ...
+                 ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
    + CategoryInfo          : ResourceUnavailable: (C:\Program File...ols\Pester.psd1:String) [Test-ModuleManifest], F 
   ileNotFoundException
    + FullyQualifiedErrorId : Modules_ModuleNotFound,Microsoft.PowerShell.Commands.TestModuleManifestCommand
 

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
(R-D)   C:\Windows\Microsoft.NET\assembly\GAC_MSIL\Microsoft.PowerShell.Commands.Management\v4.0_3.0.0.0__31bf3856ad364e35\Microsoft.PowerShell.Commands.Management.dll | File
(R-D)   C:\Windows\Microsoft.NET\assembly\GAC_MSIL\Microsoft.PowerShell.ConsoleHost\v4.0_3.0.0.0__31bf3856ad364e35\Microsoft.PowerShell.ConsoleHost.dll | File
(R-D)   C:\Windows\Microsoft.NET\assembly\GAC_MSIL\Microsoft.PowerShell.Security\v4.0_3.0.0.0__31bf3856ad364e35\Microsoft.PowerShell.Security.dll | File
(R-D)   C:\Windows\Microsoft.NET\assembly\GAC_MSIL\System.Configuration.Install\v4.0_4.0.0.0__b03f5f7f11d50a3a\System.Configuration.Install.dll | File
(R-D)   C:\Windows\Microsoft.NET\assembly\GAC_MSIL\System.Configuration\v4.0_4.0.0.0__b03f5f7f11d50a3a\System.Configuration.dll | File
(R-D)   C:\Windows\Microsoft.NET\assembly\GAC_MSIL\System.Core\v4.0_4.0.0.0__b77a5c561934e089\System.Core.dll | File
(R-D)   C:\Windows\Microsoft.NET\assembly\GAC_MSIL\System.DirectoryServices\v4.0_4.0.0.0__b03f5f7f11d50a3a\System.DirectoryServices.dll | File
(R-D)   C:\Windows\Microsoft.NET\assembly\GAC_MSIL\System.Management.Automation\v4.0_3.0.0.0__31bf3856ad364e35\System.Management.Automation.dll | File
(R-D)   C:\Windows\Microsoft.NET\assembly\GAC_MSIL\System.Management\v4.0_4.0.0.0__b03f5f7f11d50a3a\System.Management.dll | File
(R-D)   C:\Windows\Microsoft.NET\assembly\GAC_MSIL\System.Numerics\v4.0_4.0.0.0__b77a5c561934e089\System.Numerics.dll | File
(R-D)   C:\Windows\Microsoft.NET\assembly\GAC_MSIL\System.ServiceProcess\v4.0_4.0.0.0__b03f5f7f11d50a3a\System.ServiceProcess.dll | File
(R-D)   C:\Windows\Microsoft.NET\assembly\GAC_MSIL\System.Windows.Forms\v4.0_4.0.0.0__b77a5c561934e089\System.Windows.Forms.dll | File
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
\BaseNamedObjects\Cor_Private_IPCBlock_v4_8912 | Section
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
* VirusTotal Link: https://www.virustotal.com/gui/file/01a120d3e32f92f8e14671e93045efb9f76bc0f49b5f0c20216a6634801bc088/detection

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Program Files (x86)\WindowsPowerShell\Modules\Pester\3.4.0\chocolateyInstall.ps1](chocolateyInstall.ps1-561801F9741841E047E2514877BA05A7.md) | 100




MIT License. Copyright (c) 2020-2021 Strontic.


