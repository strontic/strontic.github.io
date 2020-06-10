
# lodctr.exe 
* File Path: `C:\Windows\system32\lodctr.exe`
* Description: Load PerfMon Counters
* Comments: 

## Hashes
Type | Hash
-- | --
MD5 | `F4436EB15113D5872A1ED801FFF738CE`
SHA1 | `47CC7447F9165129E59F3D89F9F0E352D909A807`
SHA256 | `AEAE0D1EDC73E853A73FA9BC1A0836557E05910E777682D9B80E516B9C9E874D`
SHA384 | `FB66E330A7F2CDFC6DEA7340FB4F83CBEBF23ACB18402BFE15F048AFB8602D58E2408F9A164358F3DDDFCD8EBB68294D`
SHA415 | `88DB51E791A6BB065181DE42A87B727F34214D5359A1607B6136FADCB0CEAAC8CD0FDB34534611F260E8B42626371F3DD74A05551D145EBA5BFA3ED0C39D13B9`
SSDEEP | `768:R5tugiyl/yPYp8yaigwZXbLsWwPN9s9aJuQrt8bplMcpvX/QxQb10Bxk:sxyUiRjwg9azYlMcBPQxQbmBxk`

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


