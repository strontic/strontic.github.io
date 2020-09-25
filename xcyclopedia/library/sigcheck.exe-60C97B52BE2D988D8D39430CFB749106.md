---
title: sigcheck.exe | File version and signature viewer
excerpt: What is sigcheck.exe?
---

# sigcheck.exe 

* File Path: `C:\SysinternalsSuite\sigcheck.exe`
* Description: File version and signature viewer

## Hashes

Type | Hash
-- | --
MD5 | `60C97B52BE2D988D8D39430CFB749106`
SHA1 | `F1D5330D467E9F7950509F60B758453A86D7EED4`
SHA256 | `5141B3A6558EB65BD9EAA87ABAFF040920F6A0E1F6F1894DF7A14CA1254E99AB`
SHA384 | `BDF3C46EC5F640F7A24106ABCEE175C939114E220436852B3D0DDD810C37FF4E0F1C9DA07F0E801BADCFCA6E54FA4697`
SHA512 | `8D34349403EB613CD5421B08A1F303E53FF3343D38E866FCBB43FCD93E684A96F3E23B28C58740F928A6157A3424E0A877D53CADB2E05C079568DE9FF8253CE2`
SSDEEP | `24576:zTTPhNYE72RYmxvTND/v4MmYZqtYbdjSeP:DkRYmhTx/v4MstaR`
IMP | `1FA91A5B71B4C34C060FC289B51FAAEE`
PESHA1 | `FB652CC0D7EF87911E93A37083C4EC5B1CBE4857`
PE256 | `1513648611DFDB6D04309339E814903D6600AA5839637B6C3B91D7B23BC36C0F`

## Runtime Data

### Usage (stdout):
```cmhg

Sigcheck v2.80 - File version and signature viewer
Copyright (C) 2004-2020 Mark Russinovich
Sysinternals - www.sysinternals.com

usage: C:\SysinternalsSuite\sigcheck.exe [-a][-h][-i][-e][-l][-n][[-s]|[-c|-ct]|[-m]][-q][-p <policy GUID>][-r][-u][-vt][-v[r][s]][-f catalog file] [-w file] <file or directory>
usage: C:\SysinternalsSuite\sigcheck.exe -d [-c|-ct] [-w file] <file or directory>
usage: C:\SysinternalsSuite\sigcheck.exe -o [-vt][-v[r]] [-w file] <C:\SysinternalsSuite\sigcheck.exe csv file>
usage: C:\SysinternalsSuite\sigcheck.exe -t[u][v] [-i] [-c|-ct] [-w file] <certificate store name|*>
  -a      Show extended version information. The entropy measure reported
          is the bits per byte of information of the file's contents.
  -c      CSV output with comma delimiter
  -ct     CSV output with tab delimiter
          Specify -nobanner to avoid banner being output to CSV
  -d      Dump contents of a catalog file
  -e      Scan executable images only (regardless of their extension)
  -f      Look for signature in the specified catalog file
  -h      Show file hashes
  -i      Show catalog name and signing chain
  -l      Traverse symbolic links and directory junctions
  -m      Dump manifest
  -n      Only show file version number
  -o      Performs Virus Total lookups of hashes captured in a CSV
          file previously captured by Sigcheck when using the -h option.
          This usage is intended for scans of offline systems.
  -p      Verify signatures against the specified policy, represented by
          its GUID.
  -r      Disable check for certificate revocation
  -s      Recurse subdirectories
  -t[u][v] Dump contents of specified certificate store ('*' for all stores).
          Specify -tu to query the user store (machine store is the default).
          Append '-v' to have Sigcheck download the trusted Microsoft
          root certificate list and only output valid certificates not rooted to
          a certificate on that list. If the site is not accessible,
          authrootstl.cab or authroot.stl in the current directory are
          used instead, if present.
  -u      If VirusTotal check is enabled, show files that are unknown
          by VirusTotal or have non-zero detection, otherwise show only
          unsigned files.
  -v[rs]  Query VirusTotal (www.virustotal.com) for malware based on file hash.
          Add 'r' to open reports for files with non-zero detection. Files
          reported as not previously scanned will be uploaded to VirusTotal
          if the 's' option is specified. Note scan results may not be
          available for five or more minutes.
  -vt     Before using VirusTotal features, you must accept
          VirusTotal terms of service. See:

          https://www.virustotal.com/en/about/terms-of-service/

          If you haven't accepted the terms and you omit this
          option, you will be interactively prompted.
  -w      Writes the output to the specified file.
  -nobanner
          Do not display the startup banner and copyright message.


```

### Loaded Modules:

Path |
-- |
C:\SysinternalsSuite\sigcheck.exe |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\wow64.dll |
C:\Windows\System32\wow64cpu.dll |
C:\Windows\System32\wow64win.dll |


## Signature

* Status: Signature verified.
* Serial: `3300000187721772155940C709000000000187`
* Thumbprint: `2485A7AFA98E178CB8F30C9838346B514AEA4769`
* Issuer: CN=Microsoft Code Signing PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Corporation, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: sigcheck.exe
* Product Name: Sysinternals Sigcheck
* Company Name: Sysinternals - www.sysinternals.com
* File Version: 2.80
* Product Version: 2.80
* Language: English (United States)
* Legal Copyright: Copyright (C) 2004-2020 Mark Russinovich
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/70
* VirusTotal Link: https://www.virustotal.com/gui/file/5141b3a6558eb65bd9eaa87abaff040920f6a0e1f6f1894df7a14ca1254e99ab/detection/





MIT License. Copyright (c) 2020 Strontic.


