---
title: gengal.exe | 
---

# gengal.exe 

* File Path: `C:\program files\LibreOffice\program\gengal.exe`

## Hashes

Type | Hash
-- | --
MD5 | `911C064973EDDB54FA22CA68C8704C8F`
SHA1 | `3E7CC36A65CA70726D84CF4D625BCDB178242F53`
SHA256 | `0DF282350F06E60261CB90298717DAEC581F355EAC5E39DF50201C2D364AA5ED`
SHA384 | `F36487CF45A55CCCF5E5E8D0C8AF9F874A356700003959CC86FE079128326E2EA897ED7ACFDA6211A4F1E217A39C7E04`
SHA512 | `7EB757AB452650A63E3EF13E9F610ABEB82937A5311EE28B77A800B91540FAE75177312AB10896D4F16343B92269C8002A5404311939F6FCE5AAB9A48A74A0A3`
SSDEEP | `1536:0qWEE6u+TWzKRy5d8nfUf6tWAPRE/CUN+e0Epk:eD3n83tnPR4C6+e0uk`

## Runtime Data

### Usage (stdout):
```Batchfile
Utility to generate LibreOffice gallery files

using: gengal --name <name> --path <dir> [ --destdir <path> ]
              [ files ... ]

options:
 --name <theme>		defines the user visible name of the created or updated theme.
 --path <dir>		defines directory where the gallery files are created
			or updated.
 --destdir <dir>	defines a path prefix to be removed from the paths
			stored in the gallery files. It is useful to create
			RPM packages using the BuildRoot feature.
 --relative-urls		flags that after removing the destdir, the URL should be a path relative to the gallery folder in the install
			primarily used for internal gallery generation at compile time.
			theme files.
 files			lists files to be added to the gallery. Absolute paths
			are required.

```

### Usage (stderr):
```Batchfile
Work on gallery ''
Existing themes: 0
Existing themes: 1
Using DestDir: 
Failed to import 'file:///%3F'

```

### Child Processes:
conhost.exe

### Open Handles:

Path | Type
-- | --
(R--)   C:\Program Files\LibreOffice\share\config\default name.sdv | File
(RW-)   C:\Program Files\LibreOffice\program\types.rdb | File
(RW-)   C:\Program Files\LibreOffice\program\types\offapi.rdb | File
(RW-)   C:\Program Files\LibreOffice\program\types\oovbaapi.rdb | File
(RW-)   C:\Users\user\Documents | File
(RW-)   C:\Windows\WinSxS\amd64_microsoft.windows.gdiplus_6595b64144ccf1df_1.1.19041.450_none_fae7a009761b0b44 | File
\BaseNamedObjects\NLS_CodePage_1252_3_2_0_0 | Section
\BaseNamedObjects\NLS_CodePage_437_3_2_0_0 | Section
\Sessions\1\BaseNamedObjects\windows_shell_global_counters | Section
\Sessions\1\BaseNamedObjects\windows_webcache_counters_{9B6AB5B3-91BC-4097-835C-EA2DEC95E9CC}_S-1-5-21-2047949552-857980807-821054962-504 | Section


### Loaded Modules:

Path |
-- |
C:\program files\LibreOffice\program\gengal.exe |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\SYSTEM32\ntdll.dll |


## Signature

* Status: Signature verified.
* Serial: `049F5EBAA6B29CF6C79003917374242E`
* Thumbprint: `059BD34C72E8BE4FB19A80877268097C87F7D487`
* Issuer: CN=Certum Code Signing CA SHA2, OU=Certum Certification Authority, O=Unizeto Technologies S.A., C=PL
* Subject: E=info@documentfoundation.org, C=DE, S=Berlin, L=Berlin, OU=LibreOffice Build Team, O=The Document Foundation, CN=The Document Foundation

## File Metadata

* Original Filename: gengal.exe
* Product Name: LibreOffice
* Company Name: The Document Foundation
* File Version: 7.0.0.3
* Product Version: 7.0.0.3
* Language: English (United States)
* Legal Copyright: Copyright  2000-2020 by LibreOffice contributors. All rights reserved.





MIT License. Copyright (c) 2020 Strontic.


