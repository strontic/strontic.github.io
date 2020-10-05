---
title: plink.exe | Command-line SSH, Telnet, and Rlogin client
excerpt: What is plink.exe?
---

# plink.exe 

* File Path: `C:\Program Files\PuTTY\plink.exe`
* Description: Command-line SSH, Telnet, and Rlogin client

## Hashes

Type | Hash
-- | --
MD5 | `0D18ADE4C70E60716B16708FFB50C00F`
SHA1 | `2483CBB7F28DCA127FFBF66ECD3311D97FBFC5F2`
SHA256 | `FEB29E7CC97DE6950192E29F2EC117CD9B17A0095A4F68D059770A24379C3993`
SHA384 | `794708CE9EB3C48EFEFDDCB3EB3B9604BDAF6B1DB5AF08F82EAF9568B140B5FB0024B6E80F4B0BDA6B77F4E7EE87ADC3`
SHA512 | `FB747EDBB1259900D9F3E210729743B4A2979066A3E0A4FF6487069223C86B7807F6285D54F1A114788B400FD1E5ACAD6EF74010A84A32D947B0345D73A1E913`
SSDEEP | `12288:nsOlmdo5WwBjy668m3nwvsOVwLkkowZfgl8cHD:n/lzWwByT3wvdVw5rZYl82`
IMP | `87AECF008D87EC86EC8B00A2394B3E6C`
PESHA1 | `3944D290E13A505DA8AD4C2302090112B96559E2`
PE256 | `EB5964601FFA7BFB773AA5E00CED927754F744B98A50004CD947BEE5F954CB40`

## Runtime Data

### Usage (stdout):
```cmhg
Plink: command-line connection utility
Release 0.74
Usage: plink [options] [user@]host [command]
       ("host" can also be a PuTTY saved session name)
Options:
  -V        print version information and exit
  -pgpfp    print PGP key fingerprints and exit
  -v        show verbose messages
  -load sessname  Load settings from saved session
  -ssh -telnet -rlogin -raw -serial
            force use of a particular protocol
  -P port   connect to specified port
  -l user   connect with specified username
  -batch    disable all interactive prompts
  -proxycmd command
            use 'command' as local proxy
  -sercfg configuration-string (e.g. 19200,8,n,1,X)
            Specify the serial configuration (serial only)
The following options only apply to SSH connections:
  -pw passw login with specified password
  -D [listen-IP:]listen-port
            Dynamic SOCKS-based port forwarding
  -L [listen-IP:]listen-port:host:port
            Forward local port to remote address
  -R [listen-IP:]listen-port:host:port
            Forward remote port to local address
  -X -x     enable / disable X11 forwarding
  -A -a     enable / disable agent forwarding
  -t -T     enable / disable pty allocation
  -1 -2     force use of particular protocol version
  -4 -6     force use of IPv4 or IPv6
  -C        enable compression
  -i key    private key file for user authentication
  -noagent  disable use of Pageant
  -agent    enable use of Pageant
  -noshare  disable use of connection sharing
  -share    enable use of connection sharing
  -hostkey aa:bb:cc:...
            manually specify a host key (may be repeated)
  -sanitise-stderr, -sanitise-stdout, -no-sanitise-stderr, -no-sanitise-stdout
            do/don't strip control chars from standard output/error
  -no-antispoof   omit anti-spoofing prompt after authentication
  -m file   read remote command(s) from file
  -s        remote command is an SSH subsystem (SSH-2 only)
  -N        don't start a shell/command (SSH-2 only)
  -nc host:port
            open tunnel in place of session (SSH-2 only)
  -sshlog file
  -sshrawlog file
            log protocol details to a file
  -shareexists
            test whether a connection-sharing upstream exists

```

### Usage (stderr):
```cmhg
Unable to open connection:
Host does not exist
```

### Child Processes:
conhost.exe

### Open Handles:

Path | Type
-- | --
(RW-)   C:\Users\user\Documents | File
\BaseNamedObjects\NLS_CodePage_1252_3_2_0_0 | Section
\BaseNamedObjects\NLS_CodePage_437_3_2_0_0 | Section
\Sessions\1\BaseNamedObjects\windows_shell_global_counters | Section


### Loaded Modules:

Path |
-- |
C:\Program Files\PuTTY\plink.exe |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\SYSTEM32\ntdll.dll |


## Signature

* Status: Signature verified.
* Serial: `7C1118CBBADC95DA3752C46E47A27438`
* Thumbprint: `5B9E273CF11941FD8C6BE3F038C4797BBE884268`
* Issuer: CN=COMODO RSA Code Signing CA, O=COMODO CA Limited, L=Salford, S=Greater Manchester, C=GB
* Subject: CN=Simon Tatham, O=Simon Tatham, L=Cambridge, S=Cambridgeshire, C=GB

## File Metadata

* Original Filename: Plink
* Product Name: PuTTY suite
* Company Name: Simon Tatham
* File Version: Release 0.74
* Product Version: Release 0.74
* Language: English (United Kingdom)
* Legal Copyright: Copyright  1997-2020 Simon Tatham.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/70
* VirusTotal Link: https://www.virustotal.com/gui/file/feb29e7cc97de6950192e29f2ec117cd9b17a0095a4f68d059770a24379c3993/detection/


## Possible Misuse

*The following table contains possible examples of `plink.exe` being misused. While `plink.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_exfiltration_and_tunneling_tools_execution.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_exfiltration_and_tunneling_tools_execution.yml) | `- '\plink.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020 Strontic.


