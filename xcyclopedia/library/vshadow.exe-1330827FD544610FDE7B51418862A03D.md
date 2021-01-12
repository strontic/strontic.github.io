---
title: vshadow.exe | VShadow, Volume Shadow Copy Service (VSS) Sample Requestor
excerpt: What is vshadow.exe?
---

# vshadow.exe 

* File Path: `C:\Program Files (x86)\Windows Kits\10\bin\10.0.19041.0\x86\vshadow.exe`
* Description: VShadow, Volume Shadow Copy Service (VSS) Sample Requestor

## Hashes

Type | Hash
-- | --
MD5 | `1330827FD544610FDE7B51418862A03D`
SHA1 | `EA7780FCFE6E723B8ABCAF33CD19AA02631AE1F1`
SHA256 | `CA6DA10CEBF8FB80BEC9D501EAED55860FB7DAD7E3E4079D7BED8E6523C87142`
SHA384 | `894BF2E143DB11A0BBE0A248B2421D326E2C7E1528009577525D00D7EFF36F1D64642EEA1D3B49F5E9FC953CD5AF627B`
SHA512 | `50DC69850D16AF2EBFCB37890E43C3D98FD171F2B4F254005C82A91AA61559C07E11E4C03809F800654DD025A91310398D3573BBF2622F08AC4948E6FA3B06CF`
SSDEEP | `3072:z+HBczyRUIRK4MR5vuyvmCSsxPGpeQ++x2OHoDkX6P6K9tnrwdTaJfDRFAyk:z+/BCSC+peQ+Y2OhXK/nsdgfrAy`
IMP | `9558560CBFDB419535F9680927A961EB`
PESHA1 | `0B54713236A46DC9339A9D98D1B731781C68B506`
PE256 | `2B66B55DA479649F6BAE40BCED607E3FB6BC772F3958E60E2ACAA09D3BBAEB66`

## Runtime Data

### Usage (stdout):
```cmhg

VSHADOW.EXE 3.0 - Volume Shadow Copy sample client.
Copyright (C) 2005 Microsoft Corporation. All rights reserved.



ERROR: invalid parameter '--help'

Usage:
   VSHADOW [optional flags] [commands]

List of optional flags:
  -?                 - Displays the usage screen
  -p                 - Manages persistent shadow copies
  -nw                - Manages no-writer shadow copies
  -nar               - Creates shadow copies with no auto-recovery
  -tr                - Creates TxF-recovered shadow copies
  -ad                - Creates differential HW shadow copies
  -ap                - Creates plex HW shadow copies
  -scsf              - Creates Shadow Copies for Shared Folders (Client Accessible)
  -t={file.xml}      - Transportable shadow set. Generates also the backup components doc.
  -bc={file.xml}     - Generates the backup components doc for non-transportable shadow set.
  -wi={Writer Name}  - Verify that a writer/component is included
  -wx={Writer Name}  - Exclude a writer/component from set creation or restore
  -mask              - BreakSnapshotSetEx flag: Mask shadow copy luns from system on break.
  -rw                - BreakSnapshotSetEx flag: Make shadow copy luns read-write on break.
  -forcerevert       - BreakSnapshotSetEx flag: Complete operation only if all disk signatures revertable.
  -norevert          - BreakSnapshotSetEx flag: Do not revert disk signatures.
  -revertsig         - Revert to the original disk's signature during resync.
  -novolcheck        - Ignore volume check during resync. Unselected volumes will be overwritten.
  -script={file.cmd} - SETVAR script creation
  -exec={command}    - Custom command executed after shadow creation, import or between break and make-it-write
  -wait              - Wait before program termination or between shadow set break and make-it-write
  -tracing           - Runs VSHADOW.EXE with enhanced diagnostics


List of commands:
  {volume list}                   - Creates a shadow set on these volumes
  -ws                             - List writer status
  -wm                             - List writer summary metadata
  -wm2                            - List writer detailed metadata
  -wm3                            - List writer detailed metadata in raw XML format
  -q                              - List all shadow copies in the system
  -qx={SnapSetID}                 - List all shadow copies in this set
  -s={SnapID}                     - List the shadow copy with the given ID
  -da                             - Deletes all shadow copies in the system
  -do={volume}                    - Deletes the oldest shadow of the specified volume
  -dx={SnapSetID}                 - Deletes all shadow copies in this set
  -ds={SnapID}                    - Deletes this shadow copy
  -i={file.xml}                   - Transportable shadow copy import
  -b={SnapSetID}                  - Break the given shadow set into read-only volumes
  -bw={SnapSetID}                 - Break the shadow set into writable volumes
  -bex={SnapSetID}                - Break using BreakSnapshotSetEx and flags, see options for available flags
  -el={SnapID},dir                - Expose the shadow copy as a mount point
  -el={SnapID},drive              - Expose the shadow copy as a drive letter
  -er={SnapID},share              - Expose the shadow copy as a network share
  -er={SnapID},share,path         - Expose a child directory from the shadow copy as a share
  -r={file.xml}                   - Restore based on a previously-generated Backup Components document
  -rs={file.xml}                  - Simulated restore based on a previously-generated Backup Components doc
  -revert={SnapID}                - Revert a volume to the specified shadow copy
  -addresync={SnapID},drive       - Resync the given shadow copy to the specified volume
  -addresync={SnapID}             - Resync the given shadow copy to it's original volume
  -resync=bcd.xml                 - Perform Resync using the specified BCD


Examples:

 - Non-persistent shadow copy creation on C: and E:
     VSHADOW C: E:

 - Non-persistent shadow copy creation on a CSV named Volume1
     VSHADOW C:\ClusterStorage\Volume1

 - Persistent shadow copy creation on C: (with no writers)
     VSHADOW -p -nw C:

 - Transportable shadow copy creation on X:
     VSHADOW -t=file1.xml X:

 - Transportable shadow copy import
     VSHADOW -i=file1.xml

 - List all shadow copies in the system:
     VSHADOW -q

Please see the README.DOC file for more details.




```

### Loaded Modules:

Path |
-- |
C:\Program Files (x86)\Windows Kits\10\bin\10.0.19041.0\x86\vshadow.exe |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\wow64.dll |
C:\Windows\System32\wow64cpu.dll |
C:\Windows\System32\wow64win.dll |


## Signature

* Status: Signature verified.
* Serial: `33000002CF6D2CC57CAA65A6D80000000002CF`
* Thumbprint: `1A221B3B4FEF088B17BA6704FD088DF192D9E0EF`
* Issuer: CN=Microsoft Code Signing PCA 2010, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Corporation, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: vshadow.exe
* Product Name: VShadow
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: Unknown
* VirusTotal Link: n/a





MIT License. Copyright (c) 2020 Strontic.


