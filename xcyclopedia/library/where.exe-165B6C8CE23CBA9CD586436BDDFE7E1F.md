
# where.exe 
* File Path: `C:\Windows\system32\where.exe`
* Description: Where - Lists location of files
* Comments: 

## Hashes
Type | Hash
-- | --
MD5 | `165B6C8CE23CBA9CD586436BDDFE7E1F`
SHA1 | `C5FF297D69D20A77DC92EBE01150C9041C8B6156`
SHA256 | `F949863F5E351EEB5054F04F181FE582E98CB322100956ED938538523258440C`
SHA384 | `242CBF390B788CEA680D3172643D8A208C0A84E5F0A314B2E0CBCE46CE583E4E1AC764DD083071C6349D8D1AA4FE9655`
SHA415 | `CFAD1D59E417558676D19BDC3A008FE0914EFC8EEDBDB18A85B365E015A59B77445AE056C4FB9F1ED8A77DEEC23D4236F5071F7E7F6B9BA6BF6FEA437EF37611`
SSDEEP | `768:3sFY7n39v/JNSiyzIs6nSCO3VC28PjYJP3/dmsxXC1:ASyUjYJP3/dxy1`

## Runtime Data
### Usage (stdout):
```Batchfile

WHERE [/R dir] [/Q] [/F] [/T] pattern...

Description:
    Displays the location of files that match the search pattern.
    By default, the search is done along the current directory and
    in the paths specified by the PATH environment variable.

Parameter List:
    /R       Recursively searches and displays the files that match the
             given pattern starting from the specified directory.

    /Q       Returns only the exit code, without displaying the list
             of matched files. (Quiet mode)

    /F       Displays the matched filename in double quotes.

    /T       Displays the file size, last modified date and time for all
             matched files.

    pattern  Specifies the search pattern for the files to match.
             Wildcards * and ? can be used in the pattern. The
             "$env:pattern" and "path:pattern" formats can also be
             specified, where "env" is an environment variable and
             the search is done in the specified paths of the "env"
             environment variable. These formats should not be used
             with /R. The search is also done by appending the
             extensions of the PATHEXT variable to the pattern.

     /?      Displays this help message.

  NOTE: The tool returns an error level of 0 if the search is
        successful, of 1 if the search is unsuccessful and
        of 2 for failures or errors.

Examples:
    WHERE /?
    WHERE myfilename1 myfile????.*
    WHERE $windir:*.* 
    WHERE /R c:\windows *.exe *.dll *.bat  
    WHERE /Q ??.??? 
    WHERE "c:\windows;c:\windows\system32:*.dll"
    WHERE /F /T *.dll 

```

### Usage (stderr):
```Batchfile
ERROR: Invalid argument or option - '/h'.
Type "WHERE /?" for usage help.

```

### Child Processes:


## Signature

* Status: Signature verified.
* Serial: 33000000BCE120FDD27CC8EE930000000000BC
* Thumbprint: E85459B23C232DB3CB94C7A56D47678F58E8E51E
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: where.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.14393.0 (rs1_release.160715-1616)
* Product Version: 10.0.14393.0
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.


