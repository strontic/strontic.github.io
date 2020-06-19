
# TSTheme.exe 

* File Path: `C:\Windows\system32\TSTheme.exe`
* Description: TSTheme Server Module
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `A9A89CB1838373C365F2B8AF72B1F1C2`
SHA1 | `C3692CD348CC07AF87DF37C5F524D38CE739B1C3`
SHA256 | `5EDB8F164B5CACAEFC551E3D0EA0971E5DA1AB144AB66FE429BC7E5DCB2FCC3C`
SHA384 | `26791D376DDC7698C4A16A4CE56B72A2B140E9096E560F73132DBF2117E7C5C9ABEEC9F76909B576CE0BF40DE2BE8DBA`
SHA512 | `BF3C0C06D2D42D37D54FCAE71D80B418FA97F57C733013F242BA3F537671FDD628550A278EBD6C4BBD997865D46F3DECBB03A89A05FC971F496CF0C06645E9DC`
SSDEEP | `1536:gpRsBistJVwVmaHXfTnR6eOlleFPt/Afv2:gpRKlra3fkllmPqf+`

## Runtime Data

### Usage (stdout):
```Batchfile

```

### Usage (stderr):
```Batchfile

```

### Child Processes:


## Signature

* Status: Signature verified.
* Serial: `33000000BCE120FDD27CC8EE930000000000BC`
* Thumbprint: `E85459B23C232DB3CB94C7A56D47678F58E8E51E`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: TSThemeS.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.14393.0 (rs1_release.160715-1616)
* Product Version: 10.0.14393.0
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.


## Possible Misuse

*The following table contains possible examples of `TSTheme.exe` being misused. While this file is **not** malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_suspicious_remote_thread.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/sysmon/sysmon_suspicious_remote_thread.yml) | `            - '\tstheme.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020 Strontic.


