---
title: sigcheck64.exe | File version and signature viewer
excerpt: What is sigcheck64.exe?
---

# sigcheck64.exe 

* File Path: `C:\SysinternalsSuite\sigcheck64.exe`
* Description: File version and signature viewer

## Hashes

Type | Hash
-- | --
MD5 | `B8CEB67F37D44F4AAA477F7C5CB6A6DB`
SHA1 | `2B772AAFE711483A2B9C87C277714DE321B570BE`
SHA256 | `BD841661B5E82840B61F078F3E5B420969A3A8EA1345615C6820B9FE89000038`
SHA384 | `8F7597D435ED26F29D7DCDA076986BF99380F629FE36CCDAA8A9FA4DBB497F625E25ECEA1B28D925BF0E54BF29A7E2B7`
SHA512 | `C7E4EC6C4BA52296D2A4B2A8409A502DAA7E17D2986C35D2C9293E13CE5D738DF75955714C5DE4208897A4B1CC650D124C7AD6A223640ABD950B0D2E80CEE2B4`
SSDEEP | `24576:kLvloGoFLBXCPbgLxnf0LNzjCMzGRlmbd4vyXujx:kCZFkz7zGObm6Xul`
IMP | `9E056220139688D3D2268604BFB7E4A6`
PESHA1 | `F02FCE9287197086B7592836120B6587E2CB9383`
PE256 | `B575A38362582C766B9B9B8EE8C0F223E0697ABABD6A2D0A610CADCAEDFB6CFC`

## Runtime Data

### Usage (stdout):
```cmhg

Sigcheck v2.80 - File version and signature viewer
Copyright (C) 2004-2020 Mark Russinovich
Sysinternals - www.sysinternals.com

usage: C:\SysinternalsSuite\sigcheck64.exe [-a][-h][-i][-e][-l][-n][[-s]|[-c|-ct]|[-m]][-q][-p <policy GUID>][-r][-u][-vt][-v[r][s]][-f catalog file] [-w file] <file or directory>
usage: C:\SysinternalsSuite\sigcheck64.exe -d [-c|-ct] [-w file] <file or directory>
usage: C:\SysinternalsSuite\sigcheck64.exe -o [-vt][-v[r]] [-w file] <C:\SysinternalsSuite\sigcheck64.exe csv file>
usage: C:\SysinternalsSuite\sigcheck64.exe -t[u][v] [-i] [-c|-ct] [-w file] <certificate store name|*>
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
C:\SysinternalsSuite\sigcheck64.exe |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\SYSTEM32\ntdll.dll |


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
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/68
* VirusTotal Link: https://www.virustotal.com/gui/file/bd841661b5e82840b61f078f3e5b420969a3a8ea1345615c6820b9fe89000038/detection/





MIT License. Copyright (c) 2020-2021 Strontic.


