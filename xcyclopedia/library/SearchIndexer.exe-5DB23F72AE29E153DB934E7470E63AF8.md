---
title: SearchIndexer.exe | Microsoft Windows Search Indexer
---

# SearchIndexer.exe 

* File Path: `C:\WINDOWS\system32\SearchIndexer.exe`
* Description: Microsoft Windows Search Indexer
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `5DB23F72AE29E153DB934E7470E63AF8`
SHA1 | `39914B9C4E177C7701CE8E34F2F918425EF72612`
SHA256 | `8ADF07E9A1511872E185FBE22914C2130C77AE7B2DEF2FE33DA5DE319470DF0E`
SHA384 | `6ADD74A4684E64005B9930A23BC6F70FE433647A736E8ED36D566FB72E6F5B50604A6AAD8980F0B2CADAE0B6A054681C`
SHA512 | `A6DF1384BD8FB15B011F33691344187360CCA27CF8EDB5C7B56B2667BF2DA075C25DCE8F209109C4393240B91E38F1575D76A072683A5A64C0B84D0A29EA99C0`
SSDEEP | `24576:njii3HccalYk+8etruJUAa9MGJ3vphTH:njiMfD8QuJUAalvph`

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
* Serial: `330000023241FB59996DCC4DFF000000000232`
* Thumbprint: `FF82BC38E1DA5E596DF374C53E3617F7EDA36B06`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: SearchIndexer.exe.mui
* Product Name: Windows Search
* Company Name: Microsoft Corporation
* File Version: 7.0.18362.1 (WinBuild.160101.0800)
* Product Version: 7.0.18362.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.


## Possible Misuse

*The following table contains possible examples of `SearchIndexer.exe` being misused. While `SearchIndexer.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_raw_disk_access_using_illegitimate_tools.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/sysmon/sysmon_raw_disk_access_using_illegitimate_tools.yml) | `            - '\searchindexer.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020 Strontic.


