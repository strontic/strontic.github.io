---
title: btprobe.exe | btprobe
excerpt: What is btprobe.exe?
---

# btprobe.exe 

* File Path: `C:\Program Files\SplunkUniversalForwarder\bin\btprobe.exe`
* Description: btprobe

## Hashes

Type | Hash
-- | --
MD5 | `7139FFBCDF7604134C0D5D98EDB460C4`
SHA1 | `D7CC08D4E3BEB607221E1218C0249403BA0F64A3`
SHA256 | `6CE4CEA9CD722519A779B35E8FD57712A27657B4487B5C7BBCEA51C1E8005926`
SHA384 | `9B5BCF877C0A8A28950977758724AF62CAC7BA23B21576EFFD5D123FEFF3563001D5028B6F6118A901D4BD857597A8C6`
SHA512 | `80A8876EFF4FDE97F7F97EA43C89C50C62BCA8B48847EA9AA9E160CBBE90D2272DDAB39CD8457003D0C60D37D2A67B99BE9F290AFA4AC66429618344805CB8A0`
SSDEEP | `1536:SB6yBpRvPW6Nf0t8yIYEKF8ZPLwCoAgyX1fDA5H:SB6yBpRvPWI79YEKyi3AgypDuH`
IMP | `D7E7C7FB1023AE6F5D81B244992E7451`
PESHA1 | `A94D21F18132D304C6745FC025C1B0FA82635715`
PE256 | `2987F878DD91706ADD9796467D79DD3AAC47B33F41C5568C2AFDB1ECE9785E56`

## Runtime Data

### Usage (stderr):
```cmhg

MSG: -help unrecognized flag

There are 2 possible ways to invoke this tool:

	 1: btprobe [-h or --help] -d <btree directory> [-k <hex key OR ALL> | --file <filename>] [--salt <salt>] [--validate] [--reset] [--bytes <bytes>] [-r]
	 Queries the specified BTree for the given key or file.

	    -d        	 Directory that contains the btree index. (Required)

	    -k        	 Hex crc key or ALL to get all the keys.
	    --file    	 File to compute the crc from.
	    -r        	 Rebuild the btree .dat files (i.e., var/lib/splunk/fishbucket/splunk_private_db/ 
	      (One of -k and --file must be specified.

	    --validate  	 Validate the btree to look for errors.
	    --salt      	 Salt the crc if --file param is specified.
	    --reset     	 Reset the fishbucket for the given key or file in the btree.
	    --bytes     	 Number of bytes to read when calculating CRC (default 256).
	    --sourcetype	 Sourcetype to load configurations and check Indexed Extraction
	                	 and compute CRC accordingly.

	 2: btprobe [-h or --help] --compute-crc <filename> [--salt <salt>] [--bytes <bytes>]
	 Computes a crc from the specified file (using the given salt if any).

	 Examples:
	 btprobe -d /opt/splunk/var/lib/splunk/fishbucket/splunk_private_db  -k 0xe8d117ddba85e714 --validate
	 btprobe -d /opt/splunk/var/lib/splunk/fishbucket/splunk_private_db --file /var/log/inputfile --salt SOME_SALT
	 btprobe --compute-crc /var/log/inputfile --salt SOME_SALT


```

### Child Processes:
Un_E.exe

### Loaded Modules:

Path |
-- |
C:\Program Files\SplunkUniversalForwarder\bin\btprobe.exe |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\SYSTEM32\ntdll.dll |


## Signature

* Status: Signature verified.
* Serial: `014E132916D610BB301B22ABBD994616`
* Thumbprint: `B8B4F0D3FD0571E184DEBB76A1F6DB73F30FA233`
* Issuer: CN=DigiCert EV Code Signing CA (SHA2), OU=www.digicert.com, O=DigiCert Inc, C=US
* Subject: CN="Splunk, Inc.", O="Splunk, Inc.", L=San Francisco, S=California, C=US, SERIALNUMBER=4109614, OID.2.5.4.15=Private Organization, OID.1.3.6.1.4.1.311.60.2.1.2=Delaware, OID.1.3.6.1.4.1.311.60.2.1.3=US

## File Metadata

* Original Filename: btprobe.exe
* Product Name: splunk Application
* Company Name: Splunk Inc.
* File Version: 8.2.3
* Product Version: 8.2.3 (Build cd0848707637)
* Language: English (United States)
* Legal Copyright: Copyright (C) 2005-2021
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/73
* VirusTotal Link: https://www.virustotal.com/gui/file/6ce4cea9cd722519a779b35e8fd57712a27657b4487b5c7bbcea51c1e8005926/detection

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Program Files\SplunkUniversalForwarder\bin\classify.exe](classify.exe-184E1137D0C14E2A607C2F9236CC3362.md) | 79




MIT License. Copyright (c) 2020-2021 Strontic.


