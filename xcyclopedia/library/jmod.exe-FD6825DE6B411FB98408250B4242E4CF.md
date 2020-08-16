---
title: jmod.exe | OpenJDK Platform binary
---

# jmod.exe 

* File Path: `C:\Program Files\Amazon Corretto\jdk11.0.8_10\bin\jmod.exe`
* Description: OpenJDK Platform binary

## Hashes

Type | Hash
-- | --
MD5 | `FD6825DE6B411FB98408250B4242E4CF`
SHA1 | `D39578ADBDB36C952806B206E87CA5056CD0FED7`
SHA256 | `09D7B7F34D1C60E483FC1F6D956BB79D6EA1AACAE3D856EAAE8914CBDBB8703E`
SHA384 | `654CC1E1132CCE3D2520DC2AB2FC7AE242F0C92740FE42C38970B0D6C1A62B9E0B281F357639BBF0B963499438BB4578`
SHA512 | `8EDF34638F9D689642B183DF92E927A8F0903D5702C77C9A725E163C1A17C5AED57AF972CEF9E234362333AC08C215F35BF07737533BAD534D423866C57F6328`
SSDEEP | `384:7EbdNt3yyvpaAABbFOO5AdqK6jSCwhrSZrPDgf2hw:8O+b+FOO5PKgarS9PUf2hw`

## Runtime Data

### Usage (stdout):
```Batchfile
Usage: jmod (create|extract|list|describe|hash) <OPTIONS> <jmod-file>

Main operation modes:
  create    - Creates a new jmod archive
  extract   - Extracts all the files from the archive
  list      - Prints the names of all the entries
  describe  - Prints the module details
  hash      - Records hashes of tied modules.

 Option                              Description                           
 ------                              -----------                           
  -?, -h, --help                      Print this help message               
  --class-path <path>                 Application jar files|dir containing  
                                        classes                             
  --cmds <path>                       Location of native commands           
  --config <path>                     Location of user-editable config files
  --dir <path>                        Target directory for extract          
  --dry-run                           Dry run of hash mode                  
  --exclude <pattern-list>            Exclude files matching the supplied   
                                        comma separated pattern list, each  
                                        element using one the following     
                                        forms: <glob-pattern>, glob:<glob-  
                                        pattern> or regex:<regex-pattern>   
  --hash-modules <regex-pattern>      Compute and record hashes to tie a    
                                        packaged module with modules        
                                        matching the given <regex-pattern>  
                                        and depending upon it directly or   
                                        indirectly. The hashes are recorded 
                                        in the JMOD file being created, or a
                                        JMOD file or modular JAR on the     
                                        module path specified the jmod hash 
                                        command.                            
  --header-files <path>               Location of header files              
  --help-extra                        Print help on extra options           
  --legal-notices <path>              Location of legal notices             
  --libs <path>                       Location of native libraries          
  --main-class <String: class-name>   Main class                            
  --man-pages <path>                  Location of man pages                 
  --module-version <module-version>   Module version                        
  -p, --module-path <path>            Module path                           
  --target-platform <String: target-  Target platform                       
    platform>                                                               
  --version                           Version information                   
  @<filename>                         Read options from the specified file  

```

## Signature

* Status: Signature verified.
* Serial: `2F83C35B5136353D68CE9EB669FD1B0B`
* Thumbprint: `4BAD227329ADEF18F215B6475FB7948E1629B505`
* Issuer: CN=Symantec Class 3 SHA256 Code Signing CA, OU=Symantec Trust Network, O=Symantec Corporation, C=US
* Subject: CN=Amazon.com Services LLC, OU=Software Services, O=Amazon.com Services LLC, L=Seattle, S=Washington, C=US

## File Metadata

* Original Filename: jmod.exe
* Product Name: OpenJDK Platform 11
* Company Name: Amazon.com Inc.
* File Version: 11.0.8
* Product Version: 11.0.8
* Language: Language Neutral
* Legal Copyright: Copyright  2020

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Program Files\AdoptOpenJDK\jdk-11.0.8.10-hotspot\bin\jar.exe](jar.exe-B39F84FB8C26E73075627CF8A3E30B00.md) | 43
[C:\Program Files\AdoptOpenJDK\jdk-11.0.8.10-hotspot\bin\javap.exe](javap.exe-E53972D2FEB5711E552CE72695BF2572.md) | 38
[C:\Program Files\AdoptOpenJDK\jdk-11.0.8.10-hotspot\bin\jcmd.exe](jcmd.exe-B264E0660D3BF070AAD25F2F033B9436.md) | 50
[C:\Program Files\AdoptOpenJDK\jdk-11.0.8.10-hotspot\bin\jdeps.exe](jdeps.exe-A2D8568F6868C17A7A8C88B625FDB100.md) | 40
[C:\Program Files\AdoptOpenJDK\jdk-11.0.8.10-hotspot\bin\jfr.exe](jfr.exe-08F03ABD9FF453E929D3232120C51BD7.md) | 44
[C:\Program Files\AdoptOpenJDK\jdk-11.0.8.10-hotspot\bin\jimage.exe](jimage.exe-D25C31744405D6ACAA96E47DE6F8D837.md) | 41
[C:\Program Files\AdoptOpenJDK\jdk-11.0.8.10-hotspot\bin\jmod.exe](jmod.exe-66A78959DA40CE102F7BB09A8C73395A.md) | 54
[C:\Program Files\AdoptOpenJDK\jdk-11.0.8.10-hotspot\bin\jps.exe](jps.exe-8B98A486BF91B0F184B1C587BB2B680F.md) | 44
[C:\Program Files\AdoptOpenJDK\jdk-11.0.8.10-hotspot\bin\jstat.exe](jstat.exe-92DD217A9387CDFD9D0F65CACD5DE308.md) | 43
[C:\Program Files\AdoptOpenJDK\jdk-11.0.8.10-hotspot\bin\jstatd.exe](jstatd.exe-F51B29210060B0377FB4EA13AFD3FD9D.md) | 40
[C:\Program Files\AdoptOpenJDK\jdk-11.0.8.10-hotspot\bin\kinit.exe](kinit.exe-1D16A2748895E35498E4E22F15EB5AC0.md) | 36
[C:\Program Files\AdoptOpenJDK\jdk-11.0.8.10-hotspot\bin\klist.exe](klist.exe-9371A9AC3DC11410EA50EA8C21C83C89.md) | 41
[C:\Program Files\AdoptOpenJDK\jdk-11.0.8.10-hotspot\bin\ktab.exe](ktab.exe-C6FB113B79364970E2246CCFB40878D0.md) | 41
[C:\Program Files\AdoptOpenJDK\jdk-11.0.8.10-hotspot\bin\rmic.exe](rmic.exe-BBCF27C5346C3075D09DF7355AEBB582.md) | 46
[C:\Program Files\AdoptOpenJDK\jdk-11.0.8.10-hotspot\bin\rmid.exe](rmid.exe-D98CF348139BB44E4EFCA15FEA955F7C.md) | 49
[C:\Program Files\AdoptOpenJDK\jre-11.0.8.10-hotspot\bin\jfr.exe](jfr.exe-065E5E752266CD2FA6F1CF2564249B21.md) | 43
[C:\Program Files\AdoptOpenJDK\jre-11.0.8.10-hotspot\bin\kinit.exe](kinit.exe-17561E8FCB677496BC34D76B2F9BE380.md) | 38
[C:\Program Files\AdoptOpenJDK\jre-11.0.8.10-hotspot\bin\klist.exe](klist.exe-7D151D16C96009205B92251019F782AF.md) | 43
[C:\Program Files\AdoptOpenJDK\jre-11.0.8.10-hotspot\bin\ktab.exe](ktab.exe-F45CED87218ADC894C655258D1FC5C10.md) | 41
[C:\Program Files\AdoptOpenJDK\jre-11.0.8.10-hotspot\bin\rmid.exe](rmid.exe-62D6E0918BC131ABDB5F5A98A66346EF.md) | 49
[C:\Program Files\Amazon Corretto\jdk11.0.8_10\bin\jar.exe](jar.exe-90E9FDEDBD307AAD814B9B310EF9EEF6.md) | 63
[C:\Program Files\Amazon Corretto\jdk11.0.8_10\bin\javap.exe](javap.exe-5FDBAB868D53F447324D0CEC119EADF4.md) | 57
[C:\Program Files\Amazon Corretto\jdk11.0.8_10\bin\jcmd.exe](jcmd.exe-8B031007B293E1B238FE7040C1E78BA9.md) | 65
[C:\Program Files\Amazon Corretto\jdk11.0.8_10\bin\jdeps.exe](jdeps.exe-93A0053100DB342311A5461DC158F9C5.md) | 58
[C:\Program Files\Amazon Corretto\jdk11.0.8_10\bin\jfr.exe](jfr.exe-B33A8A8C02F57743444E9F96936783DE.md) | 63
[C:\Program Files\Amazon Corretto\jdk11.0.8_10\bin\jimage.exe](jimage.exe-52585947B2B10A2C41E370B60D85A837.md) | 58
[C:\Program Files\Amazon Corretto\jdk11.0.8_10\bin\jps.exe](jps.exe-EAB3A072CA16676197FF86E06CBA9F13.md) | 63
[C:\Program Files\Amazon Corretto\jdk11.0.8_10\bin\jstat.exe](jstat.exe-94511EDBA5FC73EF516B66FF0BBFF032.md) | 58
[C:\Program Files\Amazon Corretto\jdk11.0.8_10\bin\jstatd.exe](jstatd.exe-5B818E750FE168F05BFF9A30354DEF83.md) | 57
[C:\Program Files\Amazon Corretto\jdk11.0.8_10\bin\kinit.exe](kinit.exe-2E9727621161826FE230D5C529D4D57A.md) | 58
[C:\Program Files\Amazon Corretto\jdk11.0.8_10\bin\klist.exe](klist.exe-0114F130B4E2B2C847324EF3EE2231B1.md) | 57
[C:\Program Files\Amazon Corretto\jdk11.0.8_10\bin\ktab.exe](ktab.exe-F3797AE1D338EAA8C55B716127B2FE64.md) | 58
[C:\Program Files\Amazon Corretto\jdk11.0.8_10\bin\rmic.exe](rmic.exe-B0BE3B0798C023F1A21C4E066BAE9527.md) | 63
[C:\Program Files\Amazon Corretto\jdk11.0.8_10\bin\rmid.exe](rmid.exe-1D81A7BE447A5B0CF10B76D15B1C69BC.md) | 69




MIT License. Copyright (c) 2020 Strontic.


