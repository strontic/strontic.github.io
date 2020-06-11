
# qappsrv.exe 

* File Path: `C:\WINDOWS\system32\qappsrv.exe`
* Description: Query Remote Desktop Session Host Server Utility
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `A1B5A921BAE0F96AE14900DFD5EEDC8A`
SHA1 | `F5B101F87E41C586414DCC8BCBA8517BA36983FC`
SHA256 | `04B00881C96B29833C5A7FF0296638ACD66494768D58CF7AE5F408C358B79F67`
SHA384 | `0D9DD2109A2555838568EB59CB8ACB0A3A17E1DD8B83982A591F1A5F991D59E209FAB065A2DC7C7876B547ABA5752E73`
SHA415 | `941B0A867E0817AF371F03D6826EAF91DE4203C89158E191D2238D21C83D87C3A3BA6F685FDAA21043D27FB8F91F6C5F0400F6C5FB1A788E08FDCE2223493FD4`
SSDEEP | `384:CU7HX5bP44grDMkiUHdE5z5XWjK8mpk5VGqqNJg2yJ5HPwe9KpaYbFWRaWK:CGp8rDMOHKMjK8uO5bqaYb4`

## Runtime Data

### Usage (stdout):
```Batchfile
Displays the available Remote Desktop Session Host servers on the network.

QUERY TERMSERVER [servername] [/DOMAIN:domain] [/ADDRESS] [/CONTINUE]

  servername      Identifies a Remote Desktop Session Host server.
  /DOMAIN:domain  Displays information for the specified domain (defaults 
                  to the current domain).
  /ADDRESS        Displays network and node addresses.
  /CONTINUE       Does not pause after each screen of information.


```

### Usage (stderr):
```Batchfile
Invalid parameter(s)
Displays the available Remote Desktop Session Host servers on the network.

QUERY TERMSERVER [servername] [/DOMAIN:domain] [/ADDRESS] [/CONTINUE]

  servername      Identifies a Remote Desktop Session Host server.
  /DOMAIN:domain  Displays information for the specified domain (defaults 
                  to the current domain).
  /ADDRESS        Displays network and node addresses.
  /CONTINUE       Does not pause after each screen of information.


```

### Child Processes:
conhost.exe

## Signature

* Status: Signature verified.
* Serial: 33000001C422B2F79B793DACB20000000001C4
* Thumbprint: AE9C1AE54763822EEC42474983D8B635116C8452
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: qappsrv.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.18362.1 (WinBuild.160101.0800)
* Product Version: 10.0.18362.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.

MIT License. Copyright (c) 2020 Strontic.


