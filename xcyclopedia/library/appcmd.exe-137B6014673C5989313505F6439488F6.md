---
title: appcmd.exe | Application Server Command Line Admin Tool
---

# appcmd.exe 

* File Path: `C:\windows\SysWOW64\inetsrv\appcmd.exe`
* Description: Application Server Command Line Admin Tool
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `137B6014673C5989313505F6439488F6`
SHA1 | `1D2B77A97476BD7ED583963D9908AA979A803020`
SHA256 | `CCD7E7635BD261815DFAC9AB6EDB52A9789C3275DB09EA86A964F0E395BDBA4A`
SHA384 | `4CA12D654FE0ABD277AC470CEB0A9CBCC5672AB630FEBF6ED49B53F16EC85313B86499C20683D767CE6FD36716B5F1C9`
SHA512 | `9578166A01E581922B3CA8297BDF0EC83C509A955CC353219243F7CB8B854D345F4F351766728DF822683F730F6904FDCE8CA6B458A7B83FEBF41C5F5EB8BE09`
SSDEEP | `3072:SG6KeyYBTpx2MJ1eEhyxiE8zB0we8lUvuDdpx7:CKdYZ2MJ1eEhyxiEOph`

## Runtime Data

### Usage (stdout):
```Batchfile
General purpose IIS command line administration tool.

APPCMD (command) (object-type) <identifier> </parameter1:value1 ...>

Supported object types:

  SITE      Administration of virtual sites
  APP       Administration of applications
  VDIR      Administration of virtual directories
  APPPOOL   Administration of application pools
  CONFIG    Administration of general configuration sections
  WP        Administration of worker processes
  REQUEST   Administration of HTTP requests
  MODULE    Administration of server modules
  BACKUP    Administration of server configuration backups
  TRACE     Working with failed request trace logs
  BINDING   Object for working with SSL bindings

(To list commands supported by each object use /?, e.g. 'appcmd.exe site /?')

General parameters:

/?               Display context-sensitive help message.

/text<:value>    Generate output in text format (default).
                 /text:* shows all object properties in detail view.
                 /text:<attribute> shows the value of the specified
                 attribute for each object.
/xml             Generate output in XML format.
                 Use this to produce output that can be sent to another
                 command running in /in mode.
/in or -         Read and operate on XML input from standard input.
                 Use this to operate on input produced by another
                 command running in /xml mode.
/config<:*>      Show configuration for displayed objects.
                 /config:* also includes inherited configuration.
/metadata        Show configuration metadata when displaying configuration.

/commit          Set config path where configuration changes are saved.
                 Can specify either a specific configuration path, "site",
                 "app", "parent", or "url" to save to the appropriate portion
                 of the path being edited by the command, "apphost", "webroot",
                 or "machine" for the corresponding configuration level.
/apphostconfig   Specify an alternate applicationHost.config file to edit.
/debug           Show debugging information for command execution.

Use "!" to escape parameters that have same names as the general parameters,
like "/!debug:value" to set a config property named "debug".

```

### Usage (stderr):
```Batchfile

```

### Child Processes:


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: appcmd.exe.mui
* Product Name: Internet Information Services
* Company Name: Microsoft Corporation
* File Version: 10.0.17763.1 (WinBuild.160101.0800)
* Product Version: 10.0.17763.1
* Language: Language Neutral
* Legal Copyright:  Microsoft Corporation. All rights reserved.

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Windows\SysWOW64\inetsrv\appcmd.exe](appcmd.exe-78A4CCBAB7D1524FADED0C0D2F65F85A.md) | 35

## Possible Misuse

*The following table contains possible examples of `appcmd.exe` being misused. While `appcmd.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_iss_module_install.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_iss_module_install.yml) | `            - '*\APPCMD.EXE install module /name:*'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1562.002.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1562.002/T1562.002.md) | C:\Windows\System32\inetsrv\appcmd.exe set config "#{website_name}" /section:httplogging /dontLog:true | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1562.002.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1562.002/T1562.002.md) | C:\Windows\System32\inetsrv\appcmd.exe set config "#{website_name}" /section:httplogging /dontLog:false | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)



MIT License. Copyright (c) 2020 Strontic.


