
# lodctr.exe 

* File Path: `C:\Windows\SysWOW64\lodctr.exe`
* Description: Load PerfMon Counters
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `D6F483494305B33B5AD931C00B687CC3`
SHA1 | `8FFC384315387F8BBCE2211785285578BB2AF387`
SHA256 | `E64C1CE04A6CE1CFB212C723564B1FAEE575DF75CB51C4E52FBE139BBEABAB92`
SHA384 | `F9FC4D2DEA5F1486F54EA6FEF02564D55B1E9D135F20749A85A235A15F1CD9765730C527189B06F354F37AD5BC1FE7B2`
SHA415 | `95AB79BFE487F88E79FFFE4A11402964F58C61CEA79567B844CB1D46367013CAB06501F0F5928B045769AADB1FD8A4D503DD4C2F4B2D6D0906A3130C330DE42C`
SSDEEP | `768:OmzMb5lM8ZI+u4ov9+nZDl8jBTKcKWi0Mof6NI3tQaQbuxU:mlM8Z3ur8Zyj9KWi0l6oQaQbux`

## Runtime Data

### Usage (stdout):
```Batchfile


LODCTR
    Updates registry values related to performance counters.

Usage:
    LODCTR <INI-FileName>
        INI-FileName is the name of the initialization file that contains
            the counter name definitions and explain text for an extensible
            counter DLL.

    LODCTR /S:<Backup-FileName>
        save the current perf registry strings and info to <Backup-FileName>

    LODCTR /R:<Backup-FileName>
        restore the perf registry strings and info using <Backup-FileName>

    LODCTR /R
        rebuild the perf registry strings and info from scratch based on the current
            registry settings and backup INI files.

    LODCTR /T:<Service-Name>
        set the performance counter service as trusted.

    LODCTR /E:<Service-Name>
        enable the performance counter service.

    LODCTR /D:<Service-Name>
        disable the performance counter service.

    LODCTR /Q

    LODCTR /Q:<Service-Name>
        query the performance counter service information, either query all or specified one.

    LODCTR /M:<Counter-Manifest>
        install Windows Vista performance counter provider definition XML file
            to system repository.

Note: any arguments with spaces in the names must be enclosed within
Double Quotation marks.

```

### Usage (stderr):
```Batchfile

```

### Child Processes:


## Signature

* Status: Signature verified.
* Serial: 33000000BCE120FDD27CC8EE930000000000BC
* Thumbprint: E85459B23C232DB3CB94C7A56D47678F58E8E51E
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: LODCTR.EXE.MUI
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.14393.0 (rs1_release.160715-1616)
* Product Version: 10.0.14393.0
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.

MIT License. Copyright (c) 2020 Strontic.


