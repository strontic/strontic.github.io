---
title: python3.exe | 
excerpt: What is python3.exe?
---

# python3.exe 

* File Path: `C:\Users\user\AppData\Local\Microsoft\WindowsApps\python3.exe`

## Hashes

Type | Hash
-- | --
MD5 | ``
SHA1 | ``
SHA256 | ``
SHA384 | ``
SHA512 | ``
SSDEEP | ``

## Runtime Data

### Usage (stderr):
```cmhg
Python was not found; run without arguments to install from the Microsoft Store, or disable this shortcut from Settings > Manage App Execution Aliases.

```

### Loaded Modules:

Path |
-- |
C:\Program Files\WindowsApps\Microsoft.DesktopAppInstaller_1.16.12663.0_x64__8wekyb3d8bbwe\AppInstallerPythonRedirector.exe |
C:\WINDOWS\System32\KERNEL32.DLL |
C:\WINDOWS\System32\KERNELBASE.dll |
C:\WINDOWS\SYSTEM32\ntdll.dll |


## Signature

* Status: Signature verified.
* Serial: `33000003F16206E3E7EFDA8ABE0000000003F1`
* Thumbprint: `5362FAEB842C236D05A729B7FAC85BAA1B68BDCA`
* Issuer: CN=Microsoft Code Signing PCA 2010, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Corporation, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: 
* Product Name: 
* Company Name: 
* File Version: 
* Product Version: 
* Language: 
* Legal Copyright: 

## File Scan

* VirusTotal Detections: Unknown

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Users\user\AppData\Local\Package Cache\{5821f5cd-f914-460c-ab51-4301814e1920}\python-3.10.0.exe](python-3.10.0.exe-8270BED86C14BFB1305900C4908BE63D.md) | 60

## Possible Misuse

*The following table contains possible examples of `python3.exe` being misused. While `python3.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_pypykatz_cred_dump_lsass_access.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_access/sysmon_pypykatz_cred_dump_lsass_access.yml) | `- 'python3*.dll+'   # Pypy requires python>=3.6`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1003.007.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1003.007/T1003.007.md) | PYTHON=$(which python \|\| which python3 \|\| which python2) | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1003.007.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1003.007/T1003.007.md) | (which python \|\| which python3 \|\| which python2) | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1037.004.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1037.004/T1037.004.md) | echo "python3 -c \"import os, base64;exec(base64.b64decode('aW1wb3J0IG9zCm9zLnBvcGVuKCdlY2hvIGF0b21pYyB0ZXN0IGZvciBtb2RpZnlpbmcgcmMuY29tbW9uID4gL3RtcC9UMTAzNy4wMDQucmMuY29tbW9uJykK'))\"" \| sudo tee -a /etc/rc.common | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1037.004.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1037.004/T1037.004.md) | echo "python3 -c \"import os, base64;exec(base64.b64decode('aW1wb3J0IG9zCm9zLnBvcGVuKCdlY2hvIGF0b21pYyB0ZXN0IGZvciBtb2RpZnlpbmcgcmMubG9jYWwgPiAvdG1wL1QxMDM3LjAwNC5yYy5sb2NhbCcpCgo='))\"" \| sudo tee -a /etc/rc.local | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1140.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1140/T1140.md) | ENCODED=$(python3 -c 'import base64;enc=base64.b64encode("#{message}".encode());print(enc.decode())') | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1140.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1140/T1140.md) | python3 -c "import base64;dec=base64.b64decode(\"$ENCODED\");print(dec.decode())" | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1140.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1140/T1140.md) | python3 -c "import base64 as d;dec=d.b64decode(\"$ENCODED\");print(dec.decode())" | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1140.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1140/T1140.md) | python3 -c "from base64 import b64decode;dec=b64decode(\"$ENCODED\");print(dec.decode())" | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1140.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1140/T1140.md) | python3 -c "from base64 import b64decode as d;dec=d(\"$ENCODED\");print(dec.decode())" | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1140.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1140/T1140.md) | echo $ENCODED \| python3 -c "import base64,sys;dec=base64.b64decode(sys.stdin.read());print(dec.decode())" | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1140.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1140/T1140.md) | echo $ENCODED > #{encoded_file} && python3 -c "import base64;dec=base64.b64decode(open('#{encoded_file}').read());print(dec.decode())" | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1140.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1140/T1140.md) | which python3 | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1543.002.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1543.002/T1543.002.md) | python3 -c "import os, base64;exec(base64.b64decode('aW1wb3J0IG9zCm9zLnBvcGVuKCdlY2hvIGF0b21pYyB0ZXN0IGZvciBDcmVhdGluZyBTeXN0ZW1kIFNlcnZpY2UgVDE1NDMuMDAyID4gL3RtcC9UMTU0My4wMDIuc3lzdGVtZC5zZXJ2aWNlLmNyZWF0aW9uJykK'))" | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1543.002.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1543.002/T1543.002.md) | echo "python3 -c \"import os, base64;exec(base64.b64decode('aW1wb3J0IG9zCm9zLnBvcGVuKCdlY2hvIGF0b21pYyB0ZXN0IGZvciBtb2RpZnlpbmcgYSBTeXN0ZW1kIFNlcnZpY2UgVDE1NDMuMDAyID4gL3RtcC9UMTU0My4wMDIuc3lzdGVtZC5zZXJ2aWNlLm1vZGlmaWNhdGlvbicpCg=='))\"" \| sudo tee -a /etc/init.d/T1543.002 | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[stockpile](https://github.com/mitre/stockpile) | [47abe1f5-55a5-46cc-8cad-506dac8ea6d9.yml](https://github.com/mitre/stockpile/blob/master/data/abilities/discovery/47abe1f5-55a5-46cc-8cad-506dac8ea6d9.yml) | `python3 scanner.py -i #{remote.host.ip}`{:.highlight .language-yaml} | [Apache-2.0](https://github.com/mitre/stockpile/blob/master/LICENSE)
[stockpile](https://github.com/mitre/stockpile) | [b18e8767-b7ea-41a3-8e80-baf65a5ddef5.yml](https://github.com/mitre/stockpile/blob/master/data/abilities/discovery/b18e8767-b7ea-41a3-8e80-baf65a5ddef5.yml) | `python3 --version;python2 --version;python --version`{:.highlight .language-yaml} | [Apache-2.0](https://github.com/mitre/stockpile/blob/master/LICENSE)
[stockpile](https://github.com/mitre/stockpile) | [b18e8767-b7ea-41a3-8e80-baf65a5ddef5.yml](https://github.com/mitre/stockpile/blob/master/data/abilities/discovery/b18e8767-b7ea-41a3-8e80-baf65a5ddef5.yml) | `python3 --version&python2 --version&python --version`{:.highlight .language-yaml} | [Apache-2.0](https://github.com/mitre/stockpile/blob/master/LICENSE)



MIT License. Copyright (c) 2020-2021 Strontic.


