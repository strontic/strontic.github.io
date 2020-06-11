
# systeminfo.exe 

* File Path: `C:\Windows\system32\systeminfo.exe`
* Description: Displays system information
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `AA2FEF178C8252E8669F1F2BCE0C65CB`
SHA1 | `288D7C995A90B7B304AA6469BC973F1899AA4036`
SHA256 | `C1C3436B2D55D7F7D75B9620A9FD0A911CD8573C67115AEBF25F474A69E61862`
SHA384 | `B981F2C856FAA9E47B9447C46B776560C4363E0210D846928A48606613CD709DD51035FE57749C194FCAF0D8675DCC14`
SHA415 | `0CB78CD5FCFF41C4078EE213752C7714BDBA73BDE26597F479A349C02E436CC6ABE8984B7E30D7B81D3F6D3B3F592CC99F631BDE63EE6ADDCA2614A816D44541`
SSDEEP | `1536:/+x+xzZF1P0lx1inDphilRoFza762mLhYnghUMOKa93JyRen3wCNxxA6zn4:Gwxdt/g2RBXLhYg1a/n3wexm6z4`

## Runtime Data

### Usage (stdout):
```Batchfile

SYSTEMINFO [/S system [/U username [/P [password]]]] [/FO format] [/NH]

Description:
    This tool displays operating system configuration information for
    a local or remote machine, including service pack levels.

Parameter List:
    /S      system           Specifies the remote system to connect to.

    /U      [domain\]user    Specifies the user context under which
                             the command should execute.

    /P      [password]       Specifies the password for the given
                             user context. Prompts for input if omitted.

    /FO     format           Specifies the format in which the output
                             is to be displayed.
                             Valid values: "TABLE", "LIST", "CSV".

    /NH                      Specifies that the "Column Header" should
                             not be displayed in the output.
                             Valid only for "TABLE" and "CSV" formats.

    /?                       Displays this help message.

Examples:
    SYSTEMINFO
    SYSTEMINFO /?
    SYSTEMINFO /S system
    SYSTEMINFO /S system /U user
    SYSTEMINFO /S system /U domain\user /P password /FO TABLE
    SYSTEMINFO /S system /FO LIST
    SYSTEMINFO /S system /FO CSV /NH

```

### Usage (stderr):
```Batchfile
ERROR: Invalid argument/option - '-help'.
Type "SYSTEMINFO /?" for usage.

```

### Child Processes:


## Signature

* Status: Signature verified.
* Serial: 33000000BCE120FDD27CC8EE930000000000BC
* Thumbprint: E85459B23C232DB3CB94C7A56D47678F58E8E51E
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: sysinfo.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.14393.0 (rs1_release.160715-1616)
* Product Version: 10.0.14393.0
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.

MIT License. Copyright (c) 2020 Strontic.


