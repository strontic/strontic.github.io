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
MD5 | `199FB882004AA262B83C602E9FEFCF80`
SHA1 | `6FF7A061E02679D02DFC1A33BEC0E3477D2CA52E`
SHA256 | `45BA2D837EFB9F90105D3F7570EF258102CCB0CBFB60FB38E4FD1D721A31AE3D`
SHA384 | `7CE9A63C047EC31747B42EB022D9A01851247CC2C5315AA984BBECA8720B6DCB3F937416ABC174784D981DDC5338D101`
SHA512 | `32F3421C657604E70B37DE91E53EAC6712408F8932740FB19EC28A268E3EA50E2702014415496B8D19FB22766173F8A1B0639E3F8C233A9975D552DE1373D70C`
SSDEEP | `12288:UkfYcpj5dIx472w8HtmV9wis/ZAQ8CQ+bAmt:LpQ+B/s/ZAQ8CHNt`
IMP | `A520143BD09BFCF2E90534256C4C53F1`
PESHA1 | `EA63CC367164F282BAAFF1F0CDC0E53D4DC91305`
PE256 | `6DE8EB7F29529B77FE2EA14CF4C2041072CDD49FC21436E8AB6DD472DBAC6FB8`

## Runtime Data

### Usage (stdout):
```cmhg
Plink: command-line connection utility
Release 0.76
Usage: plink [options] [user@]host [command]
       ("host" can also be a PuTTY saved session name)
Options:
  -V        print version information and exit
  -pgpfp    print PGP key fingerprints and exit
  -v        show verbose messages
  -load sessname  Load settings from saved session
  -ssh -telnet -rlogin -raw -serial
            force use of a particular protocol
  -ssh-connection
            force use of the bare ssh-connection protocol
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
  -1 -2     force use of particular SSH protocol version
  -4 -6     force use of IPv4 or IPv6
  -C        enable compression
  -i key    private key file for user authentication
  -noagent  disable use of Pageant
  -agent    enable use of Pageant
  -no-trivial-auth
            disconnect if SSH authentication succeeds trivially
  -noshare  disable use of connection sharing
  -share    enable use of connection sharing
  -hostkey keyid
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
  -logoverwrite
  -logappend
            control what happens when a log file already exists
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
* File Version: Release 0.76
* Product Version: Release 0.76
* Language: English (United Kingdom)
* Legal Copyright: Copyright  1997-2021 Simon Tatham.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/73
* VirusTotal Link: https://www.virustotal.com/gui/file/45ba2d837efb9f90105d3f7570ef258102ccb0cbfb60fb38e4fd1d721a31ae3d/detection


## Possible Misuse

*The following table contains possible examples of `plink.exe` being misused. While `plink.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_susp_plink_remote_forward.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/sysmon_susp_plink_remote_forward.yml) | `title: Suspicious Plink Remote Forwarding`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_susp_plink_remote_forward.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/sysmon_susp_plink_remote_forward.yml) | `description: Detects suspicious Plink tunnel remote forarding to a local port`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_susp_plink_remote_forward.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/sysmon_susp_plink_remote_forward.yml) | `- https://medium.com/@informationsecurity/remote-ssh-tunneling-with-plink-exe-7831072b3d7d`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_exfiltration_and_tunneling_tools_execution.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_exfiltration_and_tunneling_tools_execution.yml) | `- '\plink.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020-2021 Strontic.


