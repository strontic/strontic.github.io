---
title: SQLDumper.exe | SQL External minidumper
excerpt: What is SQLDumper.exe?
---

# SQLDumper.exe 

* File Path: `C:\Program Files (x86)\Microsoft Office\root\vfs\ProgramFilesX86\Microsoft Analysis Services\AS OLEDB\140\SQLDumper.exe`
* Description: SQL External minidumper
* Comments: SQL


## Hashes

Type | Hash
-- | --
MD5 | `C067C31A60F4B3A73938FEB64ABFB5C1`
SHA1 | `8B9272C6E98F6C475D8A34C1DD30CEF89DE5080D`
SHA256 | `AFD1B4A9869265D070D2575FFF244BAB18CF7A72153D932D5330F74ED7D3F2C7`
SHA384 | `8EDAA6C38AE1DC19C0411F777A0C2E1E5677E86ADA0FB4A5A25AF73A289335A3634FFFA4C76F09D7F646E2E2E904EB86`
SHA512 | `317A0DE4E2DCCF10D5A7CE75C4949B17A29CC3DAEC3F0D4F7675C7F8EE9803227BBFCF4AD39946A82BECA4FF3D6ADC2AC376F720920C33C3E8590C8BA777B656`
SSDEEP | `3072:Ka/6LKiS4sgk4h2qYr/j4+yrSlEYmyom9fioF:36LKgsYh2q+/j4VsE`
IMP | `759486AB43CB52DF3577D6A2B8B7CECA`
PESHA1 | `6CA351E3F31A7A8AEA66FC29EAE3029255A0E1FA`
PE256 | `2809D5A54DF91EA70D96A86922BF5452CE50662344819B9D81F6B65DB5459C86`

## Runtime Data

### Child Processes:
conhost.exe

### Open Handles:

Path | Type
-- | --
(RW-)   C:\Users\user\Documents | File
(RW-)   C:\Windows | File
\BaseNamedObjects\NLS_CodePage_1252_3_2_0_0 | Section
\BaseNamedObjects\NLS_CodePage_437_3_2_0_0 | Section


### Loaded Modules:

Path |
-- |
C:\Program Files (x86)\Microsoft Office\root\vfs\ProgramFilesX86\Microsoft Analysis Services\AS OLEDB\140\SQLDumper.exe |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\wow64.dll |
C:\Windows\System32\wow64cpu.dll |
C:\Windows\System32\wow64win.dll |


## Signature

* Status: Signature verified.
* Serial: `33000001B1DDEDBA54E965B85F0001000001B1`
* Thumbprint: `9DC17888B5CFAD98B3CB35C1994E96227F061675`
* Issuer: CN=Microsoft Code Signing PCA, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Corporation, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: SqlDumper.exe
* Product Name: Microsoft SQL Server
* Company Name: Microsoft Corporation
* File Version: 2019.0150.1500.158 ((BI_Main).190506-1918)
* Product Version: 15.0.1500.158
* Language: English (United States)
* Legal Copyright: Microsoft. All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/72
* VirusTotal Link: https://www.virustotal.com/gui/file/afd1b4a9869265d070d2575fff244bab18cf7a72153d932d5330f74ed7d3f2c7/detection/


## Possible Misuse

*The following table contains possible examples of `SQLDumper.exe` being misused. While `SQLDumper.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Sqldumper.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OtherMSBinaries/Sqldumper.yml) | `Name: Sqldumper.exe`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Sqldumper.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OtherMSBinaries/Sqldumper.yml) | `- Command: sqldumper.exe 464 0 0x0110`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Sqldumper.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OtherMSBinaries/Sqldumper.yml) | `- Command: sqldumper.exe 540 0 0x01100:40`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Sqldumper.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OtherMSBinaries/Sqldumper.yml) | `- Path: C:\Program Files\Microsoft SQL Server\90\Shared\SQLDumper.exe`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Sqldumper.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OtherMSBinaries/Sqldumper.yml) | `- Path: C:\Program Files (x86)\Microsoft Office\root\vfs\ProgramFilesX86\Microsoft Analysis\AS OLEDB\140\SQLDumper.exe`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Sqldumper.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OtherMSBinaries/Sqldumper.yml) | `- Link: https://support.microsoft.com/en-us/help/917825/how-to-use-the-sqldumper-exe-utility-to-generate-a-dump-file-in-sql-se`{:.highlight .language-yaml} | 



MIT License. Copyright (c) 2020-2021 Strontic.


